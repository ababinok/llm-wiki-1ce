# Установка GitLab

> Source: https://1cmycloud.com/console/help/element/10.0/docs/topics/gitlab-installation/
> Collected: 2026-10-05T09:44:24.356749+00:00
> Published: Unknown
> Version: `10.0`
> HTML: pages/topics/gitlab-installation/index.html
> SHA256: aaba1a4f329d1f4957e650863ec4311ecbf8b7806da7dcf80c56e593c066864d
> SnapshotCreated: 2026-10-05
> Rendition: verified text

> [!NOTE] примечание
> - «1С:Предприятие.Элемент» взаимодействует с сервером GitLab по протоколам HTTP и SSH. По протоколу SSH GitLab должен быть доступен на 22 порту.
> - Рекомендуется использовать GitLab версии 14.9.3 и выше. Работа на более ранних версиях системы не гарантируется.

## ОС Linux

> [!NOTE] примечание
> В качестве примера используется ОС Ubuntu 20.04.

В этом примере показана установка GitLab с помощью Docker Engine. Чтобы установить GitLab, выполните следующие действия:

1. Сначала установите докер следующими командами:
  
  ```bash
  sudo apt install apt-transport-https ca-certificates curl software-properties-common
  ```
  
  ```bash
  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
  ```
  
  ```bash
  sudo add-apt-repository "deb [arch=.mdx64] https://download.docker.com/linux/ubuntu bionic stable"
  ```
  
  ```bash
  sudo apt update
  ```
  
  ```bash
  sudo apt install docker-ce
  ```
2. Создайте каталог, в котором будут находиться файлы конфигурации, журналов и данных:
  
  ```bash
  mkdir -p /srv/gitlab
  ```
3. Настройте переменную среды:
  
  ```bash
  export GITLAB_HOME=/srv/gitlab
  ```
4. Установите GitLab, предварительно выполнив следующее:
  
  - убедитесь, что порт 80 не занят;
  - вместо gitlab.example.com впишите DNS-имя, ассоциированное с сервером, на котором выполняется установка, или имя локального компьютера.
  
  ```bash
  sudo docker run --detach \
    --hostname gitlab.example.com \
    --publish 443:443 --publish 80:80 --publish 22:22 \
    --name gitlab \
    --restart always \
    --volume $GITLAB_HOME/config:/etc/gitlab \
    --volume $GITLAB_HOME/logs:/var/log/gitlab \
    --volume $GITLAB_HOME/data:/var/opt/gitlab \
    --shm-size 256m \
    gitlab/gitlab-ee:latest
  ```
5. После того как установка завершится, GitLab будет запущен и вы можете зайти в веб-интерфейс по адресу http://*dns-имя-или-имя-компьютера*.
  
  Веб-страница GitLab после установки: форма входа с полями пользователя и пароля. [Описание иллюстрации](../figures/385912171d162c7bf0603c9d81c5068280a5ce2905dd9a337a0a0ccb3c4fd259-ae72fdb0e8d3e039.md)

Логин администратора — root. Пароль администратора можно узнать с помощью следующей команды:

```bash
sudo docker exec -it gitlab grep 'Password:' /etc/gitlab/initial_root_password
```

После первого входа пароль администратора нужно поменять.


Примечание. [Описание иллюстрации](../figures/508a1e0b097e36e9f5cb2bdbb02bb091edf1fb414d57653b605c63d2fbe63d1c-d699901424a4d7be.md)
