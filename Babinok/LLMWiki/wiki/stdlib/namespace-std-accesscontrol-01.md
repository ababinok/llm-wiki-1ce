# Стд::КонтрольДоступа

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [authentication-ru-ff93cbd2ec8b-f3ce9ffb92bb972b](../../raw/text-10.0/authentication-ru-ff93cbd2ec8b-f3ce9ffb92bb972b.md); [security-ru-85d01bb8f863-d7a9994d6ffcacd4](../../raw/text-10.0/security-ru-85d01bb8f863-d7a9994d6ffcacd4.md); [builtinprivilege-ru-9332e1aa1ea0-9241d3ed9c35025a](../../raw/text-10.0/builtinprivilege-ru-9332e1aa1ea0-9241d3ed9c35025a.md); [builtinidentities-ru-d1ed3b29f041-fe18ddd6e15d4493](../../raw/text-10.0/builtinidentities-ru-d1ed3b29f041-fe18ddd6e15d4493.md); [grantableaccesskey-ru-b460265cdec5-f6ae17db1bc377dc](../../raw/text-10.0/grantableaccesskey-ru-b460265cdec5-f6ae17db1bc377dc.md); [grantableaccesskey-object-ru-851edad3d627-94e7d36f8986bcf3](../../raw/text-10.0/grantableaccesskey-object-ru-851edad3d627-94e7d36f8986bcf3.md); [computableaccesskey-ru-74362495699a-bbe2e71c71a5b971](../../raw/text-10.0/computableaccesskey-ru-74362495699a-bbe2e71c71a5b971.md); [computableaccesskey-object-ru-0d0b5f774cb0-a2922e37fe3b9525](../../raw/text-10.0/computableaccesskey-object-ru-0d0b5f774cb0-a2922e37fe3b9525.md); [accessdeniedexception-ru-f679f509f3e4-e8878f46fe4e6e1b](../../raw/text-10.0/accessdeniedexception-ru-f679f509f3e4-e8878f46fe4e6e1b.md); [accesskey-ru-10faf3f17fff-5ce3aaf9d52c5dad](../../raw/text-10.0/accesskey-ru-10faf3f17fff-5ce3aaf9d52c5dad.md); [accesskey-object-ru-4c5322ab4636-a7b41d0ba82afb29](../../raw/text-10.0/accesskey-object-ru-4c5322ab4636-a7b41d0ba82afb29.md); [accesskeyforadmin-ru-4b4bf8aa19c5-9846c8bfe972eb4a](../../raw/text-10.0/accesskeyforadmin-ru-4b4bf8aa19c5-9846c8bfe972eb4a.md); [accesskeyforadmin-object-ru-91f0272c1fe1-a6f6fb8bca13c9ef](../../raw/text-10.0/accesskeyforadmin-object-ru-91f0272c1fe1-a6f6fb8bca13c9ef.md); [accesskeyforauthenticated-ru-10a3076a3d4e-c92dbeef7a6b4d0e](../../raw/text-10.0/accesskeyforauthenticated-ru-10a3076a3d4e-c92dbeef7a6b4d0e.md); [accesskeyforauthenticated-object-ru-edf89a8edefb-50191a4834f0bacc](../../raw/text-10.0/accesskeyforauthenticated-object-ru-edf89a8edefb-50191a4834f0bacc.md); [accesskeyforeveryone-ru-4a12798615d1-7a983943327ae8bb](../../raw/text-10.0/accesskeyforeveryone-ru-4a12798615d1-7a983943327ae8bb.md); [accesskeyforeveryone-object-ru-0d9da28c0d22-976f91b1b2ff6288](../../raw/text-10.0/accesskeyforeveryone-object-ru-0d9da28c0d22-976f91b1b2ff6288.md); [useraccesskey-ru-3d9e14563e1e-3f4e40d7c3588931](../../raw/text-10.0/useraccesskey-ru-3d9e14563e1e-3f4e40d7c3588931.md); [useraccesskey-object-ru-f7f4bf3f4462-1d75151afb5c4f7b](../../raw/text-10.0/useraccesskey-object-ru-f7f4bf3f4462-1d75151afb5c4f7b.md); [accesskeys-ru-366038857e8d-199526e9666485b0](../../raw/text-10.0/accesskeys-ru-366038857e8d-199526e9666485b0.md); [accesscontext-ru-aeec85a9e774-99978f03a77d0ce3](../../raw/text-10.0/accesscontext-ru-aeec85a9e774-99978f03a77d0ce3.md); [accesscontrol-ru-4a29c8df78bf-d57b34802ea7d429](../../raw/text-10.0/accesscontrol-ru-4a29c8df78bf-d57b34802ea7d429.md); [accessprivilege-ru-ec1f634a9bdc-f5e62044d840cfc5](../../raw/text-10.0/accessprivilege-ru-ec1f634a9bdc-f5e62044d840cfc5.md); [privilegeonaction-object-ru-1518561ced61-e02578ee39a561ba](../../raw/text-10.0/privilegeonaction-object-ru-1518561ced61-e02578ee39a561ba.md); [privilegeonelement-ru-3b95d75c45d8-484fb1cbf7ef4e4f](../../raw/text-10.0/privilegeonelement-ru-3b95d75c45d8-484fb1cbf7ef4e4f.md); [accesspermission-ru-915ad16b02a2-b713ffd5632bc72e](../../raw/text-10.0/accesspermission-ru-915ad16b02a2-b713ffd5632bc72e.md); [systemprivilege-ru-b56cf8ff30c6-4679fe04805afce2](../../raw/text-10.0/systemprivilege-ru-b56cf8ff30c6-4679fe04805afce2.md); [accesscontrol-edf22e1f0a3d-6293589ef67f50f1](../../raw/text-10.0/accesscontrol-edf22e1f0a3d-6293589ef67f50f1.md)
> Updated: 2026-10-05

Версия: `10.0`.

[Пространства имён](namespaces.md)

- [Аутентификация — Программный тип XBSL: Std / AccessControl](../security/authentication-ru-ff93cbd2ec8b.md)
- [Безопасность — Программный тип XBSL: Std / AccessControl](../security/security-ru-85d01bb8f863.md)
- [ВстроенноеПраво — Программный тип XBSL: Std / AccessControl](builtinprivilege-ru-9332e1aa1ea0.md)
- [ВстроенныеИдАутентификации — Программный тип XBSL: Std / AccessControl](../security/builtinidentities-ru-d1ed3b29f041.md)
- [ВыдаваемыйКлючДоступа — Программный тип XBSL: Std / AccessControl](../security/grantableaccesskey-ru-b460265cdec5.md)
- [ВыдаваемыйКлючДоступа.Объект — Программный тип XBSL: Std / AccessControl](../security/grantableaccesskey-object-ru-851edad3d627.md)
- [ВычисляемыйКлючДоступа — Программный тип XBSL: Std / AccessControl](../security/computableaccesskey-ru-74362495699a.md)
- [ВычисляемыйКлючДоступа.Объект — Программный тип XBSL: Std / AccessControl](../security/computableaccesskey-object-ru-0d0b5f774cb0.md)
- [ИсключениеДоступЗапрещен — Программный тип XBSL: Std / AccessControl](accessdeniedexception-ru-f679f509f3e4.md)
- [КлючДоступа — Программный тип XBSL: Std / AccessControl](../security/accesskey-ru-10faf3f17fff.md)
- [КлючДоступа.Объект — Программный тип XBSL: Std / AccessControl](../security/accesskey-object-ru-4c5322ab4636.md)
- [КлючДоступаДляАдминистратора — Программный тип XBSL: Std / AccessControl](../security/accesskeyforadmin-ru-4b4bf8aa19c5.md)
- [КлючДоступаДляАдминистратора.Объект — Программный тип XBSL: Std / AccessControl](../security/accesskeyforadmin-object-ru-91f0272c1fe1.md)
- [КлючДоступаДляАутентифицированных — Программный тип XBSL: Std / AccessControl](../security/accesskeyforauthenticated-ru-10a3076a3d4e.md)
- [КлючДоступаДляАутентифицированных.Объект — Программный тип XBSL: Std / AccessControl](../security/accesskeyforauthenticated-object-ru-edf89a8edefb.md)
- [КлючДоступаДляВсех — Программный тип XBSL: Std / AccessControl](../security/accesskeyforeveryone-ru-4a12798615d1.md)
- [КлючДоступаДляВсех.Объект — Программный тип XBSL: Std / AccessControl](../security/accesskeyforeveryone-object-ru-0d9da28c0d22.md)
- [КлючДоступаПользователя — Программный тип XBSL: Std / AccessControl](../security/useraccesskey-ru-3d9e14563e1e.md)
- [КлючДоступаПользователя.Объект — Программный тип XBSL: Std / AccessControl](../security/useraccesskey-object-ru-f7f4bf3f4462.md)
- [КлючиДоступа — Программный тип XBSL: Std / AccessControl](../security/accesskeys-ru-366038857e8d.md)
- [КонтекстДоступа — Программный тип XBSL: Std / AccessControl](accesscontext-ru-aeec85a9e774.md)
- [КонтрольДоступа — Программный тип XBSL: Std / AccessControl](accesscontrol-ru-4a29c8df78bf.md)
- [ПравоДоступа — Программный тип XBSL: Std / AccessControl](../security/accessprivilege-ru-ec1f634a9bdc.md)
- [ПравоНаДействие.Объект — Программный тип XBSL: Std / AccessControl](privilegeonaction-object-ru-1518561ced61.md)
- [ПравоНаЭлемент — Программный тип XBSL: Std / AccessControl](privilegeonelement-ru-3b95d75c45d8.md)
- [РазрешениеДоступа — Программный тип XBSL: Std / AccessControl](../security/accesspermission-ru-915ad16b02a2.md)
- [СистемноеПраво — Программный тип XBSL: Std / AccessControl](systemprivilege-ru-b56cf8ff30c6.md)
- [Стд::КонтрольДоступа — Пространство имён XBSL: Std](accesscontrol-edf22e1f0a3d.md)
