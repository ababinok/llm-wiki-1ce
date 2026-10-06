# Обзор интерфейса и основных действий в среде разработки

> Sources: 1С — документация 1С:Предприятие.Элемент, версия `10.0`
> Raw: [ide-overview-and-basic-actions-969a6e6501a6-e1880c4986a14917](../../raw/text-10.0/ide-overview-and-basic-actions-969a6e6501a6-e1880c4986a14917.md); [fdd604aab6224985a5e72e1e68549db5df4d7bc69f091bbd1e55c0aee28c61e2-8f72a13b35e511cd](../../raw/figures/fdd604aab6224985a5e72e1e68549db5df4d7bc69f091bbd1e55c0aee28c61e2-8f72a13b35e511cd.md); [3eefa32afe64f428db0f690f426cf5ec613c7d5d0b4216e5adb29e65d3574057-1c6e3754c7eb34d0](../../raw/figures/3eefa32afe64f428db0f690f426cf5ec613c7d5d0b4216e5adb29e65d3574057-1c6e3754c7eb34d0.md); [76d8b4d24e3228379326a659b835e513160b8729a5f501057923b5c869735b40-94e463a19216a8df](../../raw/figures/76d8b4d24e3228379326a659b835e513160b8729a5f501057923b5c869735b40-94e463a19216a8df.md); [c383ab9c637fcd10436e5f1a0936990219c1a97a5b9d0e83e9ca16d86204d566-39a17866dde9b2ad](../../raw/figures/c383ab9c637fcd10436e5f1a0936990219c1a97a5b9d0e83e9ca16d86204d566-39a17866dde9b2ad.md); [e69600bcbfe11b0b8d9dd4a858bab7f12c6be869ccdd2c6e169f309f7ab60fe6-100eae2cd1cdac86](../../raw/figures/e69600bcbfe11b0b8d9dd4a858bab7f12c6be869ccdd2c6e169f309f7ab60fe6-100eae2cd1cdac86.md); [13c92ae95685636635182766474ae2fc3061d460340203a6efd0fcb30a79f501-6c2ad99d8e3cd782](../../raw/figures/13c92ae95685636635182766474ae2fc3061d460340203a6efd0fcb30a79f501-6c2ad99d8e3cd782.md); [60769fbcbf3d62ad464877615ceaf985ae847012bd6d36c47cb1e4ae01627eff-20a3019989f8360a](../../raw/figures/60769fbcbf3d62ad464877615ceaf985ae847012bd6d36c47cb1e4ae01627eff-20a3019989f8360a.md); [76356472ec4011b317782b529edfa610a8d48869f80d3456c57735e9b321aecd-142ded2d2a591828](../../raw/figures/76356472ec4011b317782b529edfa610a8d48869f80d3456c57735e9b321aecd-142ded2d2a591828.md); [4ec81b7f6eb278c2f72111fa71e390462e32b326eb6fe27cdba612fafaeca430-61edc97bd6bafdca](../../raw/figures/4ec81b7f6eb278c2f72111fa71e390462e32b326eb6fe27cdba612fafaeca430-61edc97bd6bafdca.md); [71907040031ccbb4abcff76a3915a1e79c4e2ab81e732846ee1f366558155bad-6c34114d95af3f5e](../../raw/figures/71907040031ccbb4abcff76a3915a1e79c4e2ab81e732846ee1f366558155bad-6c34114d95af3f5e.md); [81280159c8152ab193bc6f2260be70f4775021887efb50a14e9a9973f70427f7-2c1be7e952aa7902](../../raw/figures/81280159c8152ab193bc6f2260be70f4775021887efb50a14e9a9973f70427f7-2c1be7e952aa7902.md); [c1301dc1223b634cab70acec5ffb9c3fbad9b1ebb0cedcc17bff5c83d73fc8d4-8490a6dc1ff7c698](../../raw/figures/c1301dc1223b634cab70acec5ffb9c3fbad9b1ebb0cedcc17bff5c83d73fc8d4-8490a6dc1ff7c698.md); [f23d0da2e843a34635ccfc778d3fb043621075653ebe0f72e6fc6dbd40fce834-064a0f1fb7177847](../../raw/figures/f23d0da2e843a34635ccfc778d3fb043621075653ebe0f72e6fc6dbd40fce834-064a0f1fb7177847.md); [0f17c6d314ee43db58961cf794f1cdb0c0f6e953eb22fd4c80ee38d3eb4196bf-d08463dd4b8a5d54](../../raw/figures/0f17c6d314ee43db58961cf794f1cdb0c0f6e953eb22fd4c80ee38d3eb4196bf-d08463dd4b8a5d54.md); [8ab5aaf9801b02491d320228b9136714f60e2d003223de8ded96ba1cedd5e682-783f6ab9b527d49e](../../raw/figures/8ab5aaf9801b02491d320228b9136714f60e2d003223de8ded96ba1cedd5e682-783f6ab9b527d49e.md); [8b131388355e3002699e1612cbe7f73748acec0470787559f8aa361e75975446-debba231bd29a5bb](../../raw/figures/8b131388355e3002699e1612cbe7f73748acec0470787559f8aa361e75975446-debba231bd29a5bb.md); [b1d518b767771bfed76bea3cc9fab4d067cfa1817acd63c0b098f6cc398ef45f-72bf55cf80755c7d](../../raw/figures/b1d518b767771bfed76bea3cc9fab4d067cfa1817acd63c0b098f6cc398ef45f-72bf55cf80755c7d.md); [5eccacbe0170e63900cb229f8fa91fbffed649d4e34bf2caff459f43a2b721d5-015bd2c29b689712](../../raw/figures/5eccacbe0170e63900cb229f8fa91fbffed649d4e34bf2caff459f43a2b721d5-015bd2c29b689712.md); [ed5a03950482c39c7564221ff2a801fd61238a7b4a8b5b8f383ae8e63623b59c-93c62786706113d3](../../raw/figures/ed5a03950482c39c7564221ff2a801fd61238a7b4a8b5b8f383ae8e63623b59c-93c62786706113d3.md); [64e24874097435b3313bc7eda54a1c0578005d6ac013082825ec05c6d3217e57-67983acca7b90a7c](../../raw/figures/64e24874097435b3313bc7eda54a1c0578005d6ac013082825ec05c6d3217e57-67983acca7b90a7c.md); [c591400e7e2d2bf6c78f4d9182d39c20109ce022a7ef41b8ecbfb804d9c78b6c-bcd77b71751d10e7](../../raw/figures/c591400e7e2d2bf6c78f4d9182d39c20109ce022a7ef41b8ecbfb804d9c78b6c-bcd77b71751d10e7.md); [cbd6297b0554ffd09b71a865d3c0487c4f1ff05bc57dd7128d4880d274c3150b-328684f47f45e371](../../raw/figures/cbd6297b0554ffd09b71a865d3c0487c4f1ff05bc57dd7128d4880d274c3150b-328684f47f45e371.md); [615ecf5082ef1afda18b3457cc67867b543a47936d77ce20e80e4139d6aac084-8dd229aa9c110238](../../raw/figures/615ecf5082ef1afda18b3457cc67867b543a47936d77ce20e80e4139d6aac084-8dd229aa9c110238.md); [30ac834c22178a38859b9da2444e2382f712967667f8cfd6ca3e91c80aad1489-f855e40172f53c36](../../raw/figures/30ac834c22178a38859b9da2444e2382f712967667f8cfd6ca3e91c80aad1489-f855e40172f53c36.md); [8e461820103a07c888d9bbe9066bfc0604bccc6b1c11efdc013a80d5f242551c-3be8e861f89e07f7](../../raw/figures/8e461820103a07c888d9bbe9066bfc0604bccc6b1c11efdc013a80d5f242551c-3be8e861f89e07f7.md); [3a188d30bbc57e78b7a65e56828d5f60c193bec33bc1912f5d41febf7929278d-bd493e8baa93165c](../../raw/figures/3a188d30bbc57e78b7a65e56828d5f60c193bec33bc1912f5d41febf7929278d-bd493e8baa93165c.md); [47e383b47dc204a0270a8c0efad22fc090da01b0dcb84af777af1621eb518327-cb55c5ca05df0752](../../raw/figures/47e383b47dc204a0270a8c0efad22fc090da01b0dcb84af777af1621eb518327-cb55c5ca05df0752.md); [480d2707e95da8328b8534f8d064076de334e378cb812b62c1e2fbb24f658f5c-dc7eb6f2f478d3c1](../../raw/figures/480d2707e95da8328b8534f8d064076de334e378cb812b62c1e2fbb24f658f5c-dc7eb6f2f478d3c1.md); [8cd44866e0fe3f374eaa2e11aa97a354691b807afe80262c59e475c6a629d9e1-6c6246f3346c3cfe](../../raw/figures/8cd44866e0fe3f374eaa2e11aa97a354691b807afe80262c59e475c6a629d9e1-6c6246f3346c3cfe.md); [03f80e8f942a80def9467b4b82d3c2824e5c897ce3b4b360f7eea4126577a019-feba3675a1b2a56e](../../raw/figures/03f80e8f942a80def9467b4b82d3c2824e5c897ce3b4b360f7eea4126577a019-feba3675a1b2a56e.md); [2770a226787786c6d094d2e704064d801ed9906c548586559614bd9a96ed3620-f9287bc096fa1f32](../../raw/figures/2770a226787786c6d094d2e704064d801ed9906c548586559614bd9a96ed3620-f9287bc096fa1f32.md); [a27a0c93d788fdb388995b3d0c72ce807fde20ac07dea9dd7649ff89080f9234-d1a3da76a1832403](../../raw/figures/a27a0c93d788fdb388995b3d0c72ce807fde20ac07dea9dd7649ff89080f9234-d1a3da76a1832403.md); [2df5dc3177c6db3384e057099d447ea614750197032cde098b3d1451fc746d19-4a343225ffe8aee7](../../raw/figures/2df5dc3177c6db3384e057099d447ea614750197032cde098b3d1451fc746d19-4a343225ffe8aee7.md); [fa06fe0939f694669609d17f7fe884aa7ae01a66fdc404359fe47e3eeb33ec84-b442ef3f07512f1d](../../raw/figures/fa06fe0939f694669609d17f7fe884aa7ae01a66fdc404359fe47e3eeb33ec84-b442ef3f07512f1d.md); [8836e8b4f0e9311543495af2ae3e751969fbcc25f04df243b9539353e4917aa6-73cae8ff2bccd7cf](../../raw/figures/8836e8b4f0e9311543495af2ae3e751969fbcc25f04df243b9539353e4917aa6-73cae8ff2bccd7cf.md); [e0860b6042fc16ac9b3626e0554a633342637aaa1a49cf884186106838b5c097-d762577ce909f23b](../../raw/figures/e0860b6042fc16ac9b3626e0554a633342637aaa1a49cf884186106838b5c097-d762577ce909f23b.md); [4135f624af37231dc99d00184bd9b2dccef04363078b3c4b90fb7dffb25e2f44-e027755570a7c403](../../raw/figures/4135f624af37231dc99d00184bd9b2dccef04363078b3c4b90fb7dffb25e2f44-e027755570a7c403.md); [ba396acefb5f2ebace9e9c867a16934466f667fa630748c41fa774aedbc4efd1-071f182c9d97e61f](../../raw/figures/ba396acefb5f2ebace9e9c867a16934466f667fa630748c41fa774aedbc4efd1-071f182c9d97e61f.md); [aeda60479d7fe0251dbf42eea584b3dc8ab04bb231bc80e58db65897ad691833-22980ef2fc787d53](../../raw/figures/aeda60479d7fe0251dbf42eea584b3dc8ab04bb231bc80e58db65897ad691833-22980ef2fc787d53.md); [f8daef307aeb1304268f17df8075ab8c297d0d0f173f5c4613d80031bed27098-035635b3b08b9220](../../raw/figures/f8daef307aeb1304268f17df8075ab8c297d0d0f173f5c4613d80031bed27098-035635b3b08b9220.md); [08bfee3dcb32a21bde92492ee0a350e84d6447b2ca6a281be545f367516791f5-874c3ede6b00bb2d](../../raw/figures/08bfee3dcb32a21bde92492ee0a350e84d6447b2ca6a281be545f367516791f5-874c3ede6b00bb2d.md); [2c0f1fd7983051648b4c7a928c763ed38e0e850c8345b291c3f2366296529c4c-726b1950d1074964](../../raw/figures/2c0f1fd7983051648b4c7a928c763ed38e0e850c8345b291c3f2366296529c4c-726b1950d1074964.md); [e4e82d41bebfa0b8137fc32b09825544d6853e1ba060f945f04df9f7521626ca-f592172a3895fb1e](../../raw/figures/e4e82d41bebfa0b8137fc32b09825544d6853e1ba060f945f04df9f7521626ca-f592172a3895fb1e.md); [5140d66f4cb21b99ca3d32468aad0d72a003581d423c0aac0f4b0ad94c71df2d-712e7a5476ef25ba](../../raw/figures/5140d66f4cb21b99ca3d32468aad0d72a003581d423c0aac0f4b0ad94c71df2d-712e7a5476ef25ba.md); [d0eb18c650c4ae1a622fac8b8c77cabda39fde8d10680e8f3fb109591754dbbc-3ec240ad0b06ee96](../../raw/figures/d0eb18c650c4ae1a622fac8b8c77cabda39fde8d10680e8f3fb109591754dbbc-3ec240ad0b06ee96.md); [17d860c1c848ab997fd9ae7b075e48a87cb413d25aff225a0e28c985345e4e93-fb7389953cf3f944](../../raw/figures/17d860c1c848ab997fd9ae7b075e48a87cb413d25aff225a0e28c985345e4e93-fb7389953cf3f944.md); [a9e38629edbf2bea2974d4bba8e85f8fccac1385f5bd5e7e13f945ef5f7fcf35-d0f244c7ed5aad4e](../../raw/figures/a9e38629edbf2bea2974d4bba8e85f8fccac1385f5bd5e7e13f945ef5f7fcf35-d0f244c7ed5aad4e.md); [c65d730b6b32f0da9924221933baa9ebbc91a43a02ea299dad5424b574138207-441bbcea8a39032d](../../raw/figures/c65d730b6b32f0da9924221933baa9ebbc91a43a02ea299dad5424b574138207-441bbcea8a39032d.md); [a9f21c47037fd013c92f2109c96a07b6be5542b105a8935bcbbbfb1646fba0af-9334cc748a88bd65](../../raw/figures/a9f21c47037fd013c92f2109c96a07b6be5542b105a8935bcbbbfb1646fba0af-9334cc748a88bd65.md); [210ffd0b5e6192982cdab38a3e6b8a50a230271005e2e1a4f1a8f988eee0eb46-347dc55a47f22b99](../../raw/figures/210ffd0b5e6192982cdab38a3e6b8a50a230271005e2e1a4f1a8f988eee0eb46-347dc55a47f22b99.md); [8b073e69765b35322e8cac51ada2a23015bc5513a65cad9a059c051093718923-5a73b39c00a75d3a](../../raw/figures/8b073e69765b35322e8cac51ada2a23015bc5513a65cad9a059c051093718923-5a73b39c00a75d3a.md); [8bb114bb41d4d28834a7446a8faefc1a02cf83939a0fedb6113f413b47337e0d-c0b0e36a45c85318](../../raw/figures/8bb114bb41d4d28834a7446a8faefc1a02cf83939a0fedb6113f413b47337e0d-c0b0e36a45c85318.md); [667c54ae5a819c9fcb1536befef7b72e5511c64a1f462c97c577bb156f3aeb1f-89d4255c155494a1](../../raw/figures/667c54ae5a819c9fcb1536befef7b72e5511c64a1f462c97c577bb156f3aeb1f-89d4255c155494a1.md); [919c0e9870d4314d0c68e924d47d9453772e6c15202eae0ea3f04b2d222f432d-dc2da529df70d755](../../raw/figures/919c0e9870d4314d0c68e924d47d9453772e6c15202eae0ea3f04b2d222f432d-dc2da529df70d755.md); [bee28883a999b76d7d7e57dff39fc50dbbc533a91860c87b2a46594283fe7e82-124e3eccb10eea9a](../../raw/figures/bee28883a999b76d7d7e57dff39fc50dbbc533a91860c87b2a46594283fe7e82-124e3eccb10eea9a.md); [a9a19f469ae6d5ff4df8dc6928e33b1e78dcf7b786b5be14b0f5ae347cfd6483-f262c79fb9577546](../../raw/figures/a9a19f469ae6d5ff4df8dc6928e33b1e78dcf7b786b5be14b0f5ae347cfd6483-f262c79fb9577546.md); [9825a57860cb258ab9670e5e27d1418d3ffa2d760616d661e26ff45410418158-aedd37fb9556691d](../../raw/figures/9825a57860cb258ab9670e5e27d1418d3ffa2d760616d661e26ff45410418158-aedd37fb9556691d.md); [ac09e66f1582b85505f466d4166f48df833cd377b6e13c85c057cafa0c64ec74-1df9d5e12d0ce1c8](../../raw/figures/ac09e66f1582b85505f466d4166f48df833cd377b6e13c85c057cafa0c64ec74-1df9d5e12d0ce1c8.md); [3cafa2feda0d9d37cb2c9e426837b317f193644523953ce5478435f968d410fc-5c7edf4286ab7d3d](../../raw/figures/3cafa2feda0d9d37cb2c9e426837b317f193644523953ce5478435f968d410fc-5c7edf4286ab7d3d.md); [8e6d2e3619b9bce5eff64894ef226c32c9e65e2201863ce6cbd7ae4e4db9796d-4d36fe3ccc31df00](../../raw/figures/8e6d2e3619b9bce5eff64894ef226c32c9e65e2201863ce6cbd7ae4e4db9796d-4d36fe3ccc31df00.md); [3e889bdb7a265c7219c27e0a921decf838067f3006482d61f77b7f7a99a8443e-ee16f4ebd7e46313](../../raw/figures/3e889bdb7a265c7219c27e0a921decf838067f3006482d61f77b7f7a99a8443e-ee16f4ebd7e46313.md); [373b34e4f52e5df92da14be4b4e99c902286df2f524bd114df4cab2517bcf1f1-b799e25fbc9e4d41](../../raw/figures/373b34e4f52e5df92da14be4b4e99c902286df2f524bd114df4cab2517bcf1f1-b799e25fbc9e4d41.md); [cad122ddb6bc35f692ea6cfb0389dfc8bf2ce4dd338fe3c3ff636721f181d183-20fd9c59bce98a78](../../raw/figures/cad122ddb6bc35f692ea6cfb0389dfc8bf2ce4dd338fe3c3ff636721f181d183-20fd9c59bce98a78.md); [69a2b91e0b43ee8a64ad2b0531ab63253822a7a42a02ea98103a83eebbc0e7e8-6960dca735275b82](../../raw/figures/69a2b91e0b43ee8a64ad2b0531ab63253822a7a42a02ea98103a83eebbc0e7e8-6960dca735275b82.md); [a1e7fbf2257bbe8e65927fab67aaa5177c86827a874672b326a2a9e639f87402-4d7a9a08337ff1e8](../../raw/figures/a1e7fbf2257bbe8e65927fab67aaa5177c86827a874672b326a2a9e639f87402-4d7a9a08337ff1e8.md); [9bcbc3ba1b1b8da56772b6167a235d70e7839abc6254769b52c9036b303bf210-745a509cd25bfb53](../../raw/figures/9bcbc3ba1b1b8da56772b6167a235d70e7839abc6254769b52c9036b303bf210-745a509cd25bfb53.md); [df222e9edf430eba5eee8d56e5bf216893552cffbdeb54fdf5717ee02cb560f9-cf9aebcd8085c75d](../../raw/figures/df222e9edf430eba5eee8d56e5bf216893552cffbdeb54fdf5717ee02cb560f9-cf9aebcd8085c75d.md); [fcaf05bde9fe8c1dbbcc495574b51da96ad7c532b26e8623782570260268ae29-0d209ead734616f7](../../raw/figures/fcaf05bde9fe8c1dbbcc495574b51da96ad7c532b26e8623782570260268ae29-0d209ead734616f7.md); [87443d1098b3a4be566f119aeda8b7bb8e1bf4954aa7702d38fe61e0d4a96569-75a668d3c3087149](../../raw/figures/87443d1098b3a4be566f119aeda8b7bb8e1bf4954aa7702d38fe61e0d4a96569-75a668d3c3087149.md); [3479b5296858d94c149a7b776a1f8d6bdfb1dfc9463dee600e56d1be392dddab-b29cf67bf3d67fe9](../../raw/figures/3479b5296858d94c149a7b776a1f8d6bdfb1dfc9463dee600e56d1be392dddab-b29cf67bf3d67fe9.md); [d9c368927d04e233c1cfdd097a93c6e205d642f0be04dd1612dc0bdd55afd678-86942b2fba4184b2](../../raw/figures/d9c368927d04e233c1cfdd097a93c6e205d642f0be04dd1612dc0bdd55afd678-86942b2fba4184b2.md); [551472da0c2fc9823731444f3a225d517e31f9bbdf8b306e30071ba1cff26c4e-a25562af8698d8c5](../../raw/figures/551472da0c2fc9823731444f3a225d517e31f9bbdf8b306e30071ba1cff26c4e-a25562af8698d8c5.md); [e9d29f16d76d275b5f8761da61b7dce9bfb2589eee7b2b228ebbe729f5a97c10-fbf8b0f36e47692b](../../raw/figures/e9d29f16d76d275b5f8761da61b7dce9bfb2589eee7b2b228ebbe729f5a97c10-fbf8b0f36e47692b.md); [9c20d0b0495d6aa409efe6922c380ae0196f52d1754c7023468bf532bff0a8bf-15daa400e47cc1f8](../../raw/figures/9c20d0b0495d6aa409efe6922c380ae0196f52d1754c7023468bf532bff0a8bf-15daa400e47cc1f8.md); [ff5f204cd665bce2421914e7e54a6200ad9fdc228a01070ecbf186f9f1dd370e-2a9575f6ed670528](../../raw/figures/ff5f204cd665bce2421914e7e54a6200ad9fdc228a01070ecbf186f9f1dd370e-2a9575f6ed670528.md); [0a1f32ec79fbd16315d8e0504bef6e1c367e8a2e69cf2f61f334c15794601096-dbc88a71e3453e6a](../../raw/figures/0a1f32ec79fbd16315d8e0504bef6e1c367e8a2e69cf2f61f334c15794601096-dbc88a71e3453e6a.md); [59e1ff5bec4e6f4898f0ed51841ea182e346bc5e8d433153e3ad082d8c4e12f6-23131820596873f1](../../raw/figures/59e1ff5bec4e6f4898f0ed51841ea182e346bc5e8d433153e3ad082d8c4e12f6-23131820596873f1.md); [18b7309485240f76419a3dec20631894947f35371f1d5067f8f592461cf607ac-7ce0348a1a9cc912](../../raw/figures/18b7309485240f76419a3dec20631894947f35371f1d5067f8f592461cf607ac-7ce0348a1a9cc912.md); [269cd21f63e7adf8b574ec09dff13881bc9f8cc46e0b3ccc0b9bff17a94af2d7-64cd834a7833cbe7](../../raw/figures/269cd21f63e7adf8b574ec09dff13881bc9f8cc46e0b3ccc0b9bff17a94af2d7-64cd834a7833cbe7.md); [f69abf96a4f62245a841d70a26ca2df2dd55f2c72e701a81eb33d365f0daf0ce-7033d70b292def29](../../raw/figures/f69abf96a4f62245a841d70a26ca2df2dd55f2c72e701a81eb33d365f0daf0ce-7033d70b292def29.md); [a360900340f4a93c3cc5e9b7c6f9f8f6788ce5a0106e2c9aa2fac88c552ee0cd-ef9c465ed9f890a3](../../raw/figures/a360900340f4a93c3cc5e9b7c6f9f8f6788ce5a0106e2c9aa2fac88c552ee0cd-ef9c465ed9f890a3.md); [f79c509d49a9deb273c97592f9f542853881cd22b42c85f02f1d406690a6abf8-5a211d2f741fc75b](../../raw/figures/f79c509d49a9deb273c97592f9f542853881cd22b42c85f02f1d406690a6abf8-5a211d2f741fc75b.md); [73385bc28a7886d5b10455a3eec77e2a5dde510d2d22ad434bc19ee604a0bd95-fefd7e647346efe6](../../raw/figures/73385bc28a7886d5b10455a3eec77e2a5dde510d2d22ad434bc19ee604a0bd95-fefd7e647346efe6.md); [219438dfe6582c79c23f0c3960afc67ed5b394a2a0af56891bab941c3403257b-60398415e13f0502](../../raw/figures/219438dfe6582c79c23f0c3960afc67ed5b394a2a0af56891bab941c3403257b-60398415e13f0502.md); [e3616ee0aa301d8816e837efb938d516a4431cf40b2f4a586150946b88224871-b3e5f6a1798d0e3a](../../raw/figures/e3616ee0aa301d8816e837efb938d516a4431cf40b2f4a586150946b88224871-b3e5f6a1798d0e3a.md); [f07786771e4c0f9acaef9867966e3453a429b13b7113acce95096a13e7fbd5c3-726068c59c47c7d9](../../raw/figures/f07786771e4c0f9acaef9867966e3453a429b13b7113acce95096a13e7fbd5c3-726068c59c47c7d9.md); [780d57dd5c0f9800bfbec7773fa28146018d83ca80efb2fc6994aaa025dff884-f1af993d31309b25](../../raw/figures/780d57dd5c0f9800bfbec7773fa28146018d83ca80efb2fc6994aaa025dff884-f1af993d31309b25.md); [d8cdbac7803e340f13a5c3b0854ee20892916ae892c10e0beac480376ebed30f-ee48dc79ff59fd74](../../raw/figures/d8cdbac7803e340f13a5c3b0854ee20892916ae892c10e0beac480376ebed30f-ee48dc79ff59fd74.md); [b07c351bbc5db43b4bcbeb4b824f9e48e3484b9de2fc78e6cf872d1affbda837-d1fd3df3b8b226b3](../../raw/figures/b07c351bbc5db43b4bcbeb4b824f9e48e3484b9de2fc78e6cf872d1affbda837-d1fd3df3b8b226b3.md); [09067ca87e16d198fad1e9070a10750a42de49827726867d999516085a66ac81-f56a4abcd87062c3](../../raw/figures/09067ca87e16d198fad1e9070a10750a42de49827726867d999516085a66ac81-f56a4abcd87062c3.md); [7fd55e2ba44225d9c3a6684ac21d3b886dff76f2b87a0153b7b5c6dd15bd0fba-07b6d7f462815145](../../raw/figures/7fd55e2ba44225d9c3a6684ac21d3b886dff76f2b87a0153b7b5c6dd15bd0fba-07b6d7f462815145.md); [4f407ba4570342d059037209ba2cf753b2895ec830a42b2ca927daa0924c7dcb-4678dfbc548198bb](../../raw/figures/4f407ba4570342d059037209ba2cf753b2895ec830a42b2ca927daa0924c7dcb-4678dfbc548198bb.md); [783ce30bcccdd79a007d3526e3e1819994439d933ba9c9d7fe77b9448839d612-8f6bf092a60b6600](../../raw/figures/783ce30bcccdd79a007d3526e3e1819994439d933ba9c9d7fe77b9448839d612-8f6bf092a60b6600.md); [03f7ea2a6ade9091b70c0f8e2bd6e0cc71f307eb1547b784722d0872140544eb-f0538597715a345d](../../raw/figures/03f7ea2a6ade9091b70c0f8e2bd6e0cc71f307eb1547b784722d0872140544eb-f0538597715a345d.md); [e73a9d8432735582a570f6c55af3682b9e981b9a2819391ab918ee2bda7b1d3f-5a672d4cc2ddd995](../../raw/figures/e73a9d8432735582a570f6c55af3682b9e981b9a2819391ab918ee2bda7b1d3f-5a672d4cc2ddd995.md); [078cea6a7cd71490e60513111d971ebbcb765db0742d121c5b571ab55e289c19-248e9f539833c1ba](../../raw/figures/078cea6a7cd71490e60513111d971ebbcb765db0742d121c5b571ab55e289c19-248e9f539833c1ba.md); [211dd6e30377532ce6f4f6aef6f96a40e2b4cb59598a925cc90f14fc819dc333-05cd18cdefc083f7](../../raw/figures/211dd6e30377532ce6f4f6aef6f96a40e2b4cb59598a925cc90f14fc819dc333-05cd18cdefc083f7.md); [646983e380c4c1de82dc3b54a9d5fec505b88c8be49c282fc826e48141f054c7-df627a4660a49413](../../raw/figures/646983e380c4c1de82dc3b54a9d5fec505b88c8be49c282fc826e48141f054c7-df627a4660a49413.md); [7a634a785a1353c09a41d0d0800ed1efc37f687194030f6df7808712389ddd8e-dc85763ba04e3dc1](../../raw/figures/7a634a785a1353c09a41d0d0800ed1efc37f687194030f6df7808712389ddd8e-dc85763ba04e3dc1.md); [59a602d3d589d286b2d10780fd9ac072c787bb0ea1e72c266e7dd83908cb7b39-954cc100fdb242ec](../../raw/figures/59a602d3d589d286b2d10780fd9ac072c787bb0ea1e72c266e7dd83908cb7b39-954cc100fdb242ec.md); [5d495c71dc2cb1eaf441546fd593a7f6f9c67b6a597146fa97c647ca43631ecf-a9ad5f6d84b8616b](../../raw/figures/5d495c71dc2cb1eaf441546fd593a7f6f9c67b6a597146fa97c647ca43631ecf-a9ad5f6d84b8616b.md); [4fd2a5795f9b7b8488f048d46f7ed1efcebf5e5c6a650ff04642d59ba1377f33-dca605bb87ef2179](../../raw/figures/4fd2a5795f9b7b8488f048d46f7ed1efcebf5e5c6a650ff04642d59ba1377f33-dca605bb87ef2179.md); [5c843a322c9956f5c317a77ed78462c833d365beeebe4a4eac4893b846405cb2-ebc60a214207c37e](../../raw/figures/5c843a322c9956f5c317a77ed78462c833d365beeebe4a4eac4893b846405cb2-ebc60a214207c37e.md); [ec9ef07cdd72d6eca8379d71ec0d578455b207e20e0a8f565a33c41e19931248-a1d3089897460412](../../raw/figures/ec9ef07cdd72d6eca8379d71ec0d578455b207e20e0a8f565a33c41e19931248-a1d3089897460412.md); [fdeffc89101db20aaf48a784372ecaf6ca8a948f0b89f80f80c854dc6540a06b-96aba1c6c328712a](../../raw/figures/fdeffc89101db20aaf48a784372ecaf6ca8a948f0b89f80f80c854dc6540a06b-96aba1c6c328712a.md); [b4dbb398e62ee4817aa4789a63ce36dabd2a1464884437ddf4254e92dffdeab5-d0c748a6dd4cc0a5](../../raw/figures/b4dbb398e62ee4817aa4789a63ce36dabd2a1464884437ddf4254e92dffdeab5-d0c748a6dd4cc0a5.md); [df3207dc78b2a733416059cd65a328126479c9e03b80d97f6445724dbc3b7dc0-f45b88393d3f9194](../../raw/figures/df3207dc78b2a733416059cd65a328126479c9e03b80d97f6445724dbc3b7dc0-f45b88393d3f9194.md); [3f5f60869d7bab554cb9c9c0a945ca02bc0aa2a729b4f641f710c32c725ce71f-35e17105bb4b81c0](../../raw/figures/3f5f60869d7bab554cb9c9c0a945ca02bc0aa2a729b4f641f710c32c725ce71f-35e17105bb4b81c0.md); [694147ffc2b9dbfce655faf71c384dd34da1961571c169949ccd7795abe5da66-18287121d6215905](../../raw/figures/694147ffc2b9dbfce655faf71c384dd34da1961571c169949ccd7795abe5da66-18287121d6215905.md); [77c41c67da140f21d96ce391d2249abe3eb06bc1df068611edf51fdbe309f75d-70cbb98161b373a1](../../raw/figures/77c41c67da140f21d96ce391d2249abe3eb06bc1df068611edf51fdbe309f75d-70cbb98161b373a1.md); [10a5363f1265684642795e2bc28836c2a2aec8b702e6ff4b911e5f56f5642181-19860aaf2a0e082f](../../raw/figures/10a5363f1265684642795e2bc28836c2a2aec8b702e6ff4b911e5f56f5642181-19860aaf2a0e082f.md); [4065d78aa0a1a71dd31fb2aeb83611b814be7e968a5d551e08e925adcaa18b38-674c628808e01ab2](../../raw/figures/4065d78aa0a1a71dd31fb2aeb83611b814be7e968a5d551e08e925adcaa18b38-674c628808e01ab2.md); [53b400e70d153481b84410dcc642ddc58710abaf4e28bc6778d551e136cf2ed5-99101032e09a282b](../../raw/figures/53b400e70d153481b84410dcc642ddc58710abaf4e28bc6778d551e136cf2ed5-99101032e09a282b.md); [a44b746fa9e49f46b85bbd229b4a50c41fd1e95145a9518bf437a87bd26b5b70-b3e36465e128952b](../../raw/figures/a44b746fa9e49f46b85bbd229b4a50c41fd1e95145a9518bf437a87bd26b5b70-b3e36465e128952b.md); [fb55bab8ab216cafca3b4f876012ebd448118cc109e3ea4bd25af2f43a8cb898-0054278c5b25580f](../../raw/figures/fb55bab8ab216cafca3b4f876012ebd448118cc109e3ea4bd25af2f43a8cb898-0054278c5b25580f.md); [8caac6ba3aaf166a76c1f0cbcfe205bfec8bf444f5044b354f6aa74c196cb2cf-bc78d44bb8970159](../../raw/figures/8caac6ba3aaf166a76c1f0cbcfe205bfec8bf444f5044b354f6aa74c196cb2cf-bc78d44bb8970159.md); [cf4a220d35e140fdee34a4246ec33329ac0d0f2e68f53ac76c3744f15abc4ec9-cf6f45d48242fd51](../../raw/figures/cf4a220d35e140fdee34a4246ec33329ac0d0f2e68f53ac76c3744f15abc4ec9-cf6f45d48242fd51.md); [ed569f4b2c7433a91913fc0629ba2bbae150df43dda6fcfc77ad56079e8f51cb-29cba3dd7b9e1a03](../../raw/figures/ed569f4b2c7433a91913fc0629ba2bbae150df43dda6fcfc77ad56079e8f51cb-29cba3dd7b9e1a03.md); [33f1a7f6c68d6bc18906fc617ea092e3e255d68d67c1588380e9edc1df5bc528-35ce2c61772d9a60](../../raw/figures/33f1a7f6c68d6bc18906fc617ea092e3e255d68d67c1588380e9edc1df5bc528-35ce2c61772d9a60.md); [4da14f88a7b3df73bcabdb7db35b30956edb2afcafecc1b2a3416b8531e3696e-2628f166f1f55216](../../raw/figures/4da14f88a7b3df73bcabdb7db35b30956edb2afcafecc1b2a3416b8531e3696e-2628f166f1f55216.md); [b6297fc519d60535f1968b49284eafe0b4e62a527573d5478761f9a792e2f8d0-74484e0306338403](../../raw/figures/b6297fc519d60535f1968b49284eafe0b4e62a527573d5478761f9a792e2f8d0-74484e0306338403.md); [b681db10009c62b1bf38f618c97f1a29e345a712bd8df07abe1e1250110ef132-6c5ed9d8b20b4845](../../raw/figures/b681db10009c62b1bf38f618c97f1a29e345a712bd8df07abe1e1250110ef132-6c5ed9d8b20b4845.md); [f84da8b1927b309988490760d2acc13718aabe1e5d61941f29e75e1da57a4fd9-e9366eef5f7916f9](../../raw/figures/f84da8b1927b309988490760d2acc13718aabe1e5d61941f29e75e1da57a4fd9-e9366eef5f7916f9.md); [c5cd8a7a3ef7f97f924397b3cd3a881b19040b0a1dea5958fabb6a6351360865-bde3db9747ae3da9](../../raw/figures/c5cd8a7a3ef7f97f924397b3cd3a881b19040b0a1dea5958fabb6a6351360865-bde3db9747ae3da9.md); [116d5b0705effbe7351c4c2d3885a5af4d1ba80af387b71cd963113c463438b7-33cf1c5d86e62469](../../raw/figures/116d5b0705effbe7351c4c2d3885a5af4d1ba80af387b71cd963113c463438b7-33cf1c5d86e62469.md); [58b8d939783a0eac8adcfc2275e905deb848c3967aa4b3646e2187000dfb228b-a34a596f6bd29be2](../../raw/figures/58b8d939783a0eac8adcfc2275e905deb848c3967aa4b3646e2187000dfb228b-a34a596f6bd29be2.md); [b6116f83952189af8014ea7cf47968a53b5400b9f4f6cb2924786abeb8c77fb7-47cfff9bd8a8cac0](../../raw/figures/b6116f83952189af8014ea7cf47968a53b5400b9f4f6cb2924786abeb8c77fb7-47cfff9bd8a8cac0.md); [135b0985bdaaea3e80b612bcb9d8d1fead26288a27975e1949121e9ec35a652d-623709f352f5330a](../../raw/figures/135b0985bdaaea3e80b612bcb9d8d1fead26288a27975e1949121e9ec35a652d-623709f352f5330a.md); [eae90a99858ff471f9efd000eea1d84f4e76dffda2d659694df3a1d8ce0c0ad3-0dda11f54176f5b6](../../raw/figures/eae90a99858ff471f9efd000eea1d84f4e76dffda2d659694df3a1d8ce0c0ad3-0dda11f54176f5b6.md); [9eeb0dc9ef8a5231c02c00078997c0f139de1b3547942876149a7da5f052b407-bb921de5cba2cf04](../../raw/figures/9eeb0dc9ef8a5231c02c00078997c0f139de1b3547942876149a7da5f052b407-bb921de5cba2cf04.md); [f66d89c9b36ec91bfda5715ff50a63a4cc3c1308a4b7cd419a74bc982c13994f-c282bb43e83db435](../../raw/figures/f66d89c9b36ec91bfda5715ff50a63a4cc3c1308a4b7cd419a74bc982c13994f-c282bb43e83db435.md); [31719844dd900b33b70a871aed935c821e77f366bbb6b39206643537551a2b23-f7d4fd830415d79b](../../raw/figures/31719844dd900b33b70a871aed935c821e77f366bbb6b39206643537551a2b23-f7d4fd830415d79b.md); [baaadbf1c118a0653f8582ad6c8f060e7a9bf99d63d597b88da132edbcdf2cdb-3bb5e549e56f0192](../../raw/figures/baaadbf1c118a0653f8582ad6c8f060e7a9bf99d63d597b88da132edbcdf2cdb-3bb5e549e56f0192.md); [8e47ffc4be916d9a706a8b9f241367a8c99800d0611e4d4e6f37576540f263d9-ebdccafee017ee9f](../../raw/figures/8e47ffc4be916d9a706a8b9f241367a8c99800d0611e4d4e6f37576540f263d9-ebdccafee017ee9f.md); [08b536a966fb6d0a075295c49522a1a6bc1ba31809590978b4addfe384f1a8c9-48c2589bf83ae5ce](../../raw/figures/08b536a966fb6d0a075295c49522a1a6bc1ba31809590978b4addfe384f1a8c9-48c2589bf83ae5ce.md); [3edfef8d4369840851bc15f95892d2d069c9a8c8bcd3a2ff59ed0ecc05448c12-742fc96c3ae5fa7a](../../raw/figures/3edfef8d4369840851bc15f95892d2d069c9a8c8bcd3a2ff59ed0ecc05448c12-742fc96c3ae5fa7a.md); [f4b1afcfdc549755e67e054fda358adaec08c1402cb5d21006ec4dadae508a85-517941b30ca12ce6](../../raw/figures/f4b1afcfdc549755e67e054fda358adaec08c1402cb5d21006ec4dadae508a85-517941b30ca12ce6.md); [a0c5755159210496d26a68cc82b2cc08aeb75d096705ada3851c7061c75cad21-d88eded02b69448b](../../raw/figures/a0c5755159210496d26a68cc82b2cc08aeb75d096705ada3851c7061c75cad21-d88eded02b69448b.md); [71dbe9b07fe3cd42bb65b7e33266ca0069ef5302c89694fe496757daacbdb59a-b19f1ead6109636d](../../raw/figures/71dbe9b07fe3cd42bb65b7e33266ca0069ef5302c89694fe496757daacbdb59a-b19f1ead6109636d.md); [508a1e0b097e36e9f5cb2bdbb02bb091edf1fb414d57653b605c63d2fbe63d1c-d699901424a4d7be](../../raw/figures/508a1e0b097e36e9f5cb2bdbb02bb091edf1fb414d57653b605c63d2fbe63d1c-d699901424a4d7be.md)
> Updated: 2026-10-05

Версия: `10.0`.

Роль: Руководство.

Имена для поиска: `Обзор интерфейса и основных действий в среде разработки`, `ide-overview-and-basic-actions`.

## Обзор

Среда разработки «1С:Предприятие.Элемента» предоставляет пользователю широкие возможности по разработке и редактированию проекта — от самых общих настроек до детальных настроек на уровне свойств элементов проекта, а также включает в себя конструктор и редактор графического интерфейса приложения с возможностью предварительного просмотра.

## Документированный контракт и примеры

Среда разработки «1С:Предприятие.Элемента» предоставляет пользователю широкие возможности по разработке и редактированию проекта — от самых общих настроек до детальных настроек на уровне свойств элементов проекта, а также включает в себя конструктор и редактор графического интерфейса приложения с возможностью предварительного просмотра.

Интерфейс среды разработки состоит из [представлений](ide-overview-and-basic-actions-969a6e6501a6.md) — набора «рабочих инструментов» для выполнения конкретной задачи. Именно представление определяет текущий вид интерфейса — сочетание панелей, окон и редакторов, которые отображаются пользователю в данный момент.

## Общая структура интерфейса

В общем случае интерфейс среды разработки состоит из нескольких основных панелей и областей:

- [Панели действий](ide-overview-and-basic-actions-969a6e6501a6.md)
  
  — основные панели для общей навигации по среде разработки. Позволяют переключаться между различными представлениями, получить доступ к основным меню и настройкам системы.
- [Боковые панели](ide-overview-and-basic-actions-969a6e6501a6.md)
  
  — панели для более детальной навигации по выбранным представлениям. Содержат детальную информацию по выбранному представлению, свойства выбранных элементов, детальные настройки системы.
- [Область редакторов](ide-overview-and-basic-actions-969a6e6501a6.md)
  
  — центральная и самая большая область пользовательского интерфейса, в которой собственно и происходит основное взаимодействие пользователя с выбранными элементами проекта.
- [Нижняя панель](ide-overview-and-basic-actions-969a6e6501a6.md)
  
  — панель для просмотра служебной информации и выполнения дополнительных задач. Например, в ней стандартно открываются такие представления как
  
  [Проблемы](ide-overview-and-basic-actions-969a6e6501a6.md)
  
  и
  
  Консоль отладки
  
  . По умолчанию не отображается.
- [Строка состояния](ide-overview-and-basic-actions-969a6e6501a6.md)
  
  — показывает состояние разрабатываемого приложения, наличие ошибок, параметры редактирования и наличие уведомлений.

Интерфейс среды разработки [Описание иллюстрации](../../raw/figures/fdd604aab6224985a5e72e1e68549db5df4d7bc69f091bbd1e55c0aee28c61e2-8f72a13b35e511cd.md)

Представленные выше панели отображаются по умолчанию при первичном входе пользователя в систему. Далее пользователь может настроить интерфейс среды разработки так, как ему удобно. Это можно сделать как непосредственно в самом интерфейсе перетаскиванием, открытием или закрытием, так и с помощью [**Главное меню**](ide-overview-and-basic-actions-969a6e6501a6.md) ⟶ **Вид**. Тем не менее, некоторые панели являются фиксированными, например **Панели действий** и **Строка состояния**.

## Представления

Основные представления уже доступны в интерфейсе по умолчанию. К основным можно отнести следующие представления:

- Пиктограмма «Навигатор». [Описание иллюстрации](../../raw/figures/3eefa32afe64f428db0f690f426cf5ec613c7d5d0b4216e5adb29e65d3574057-1c6e3754c7eb34d0.md)
  
  [**Проект**](ide-overview-and-basic-actions-969a6e6501a6.md)
  
  — структура разрабатываемого проекта,
- Пиктограмма «Проводник». [Описание иллюстрации](../../raw/figures/76d8b4d24e3228379326a659b835e513160b8729a5f501057923b5c869735b40-94e463a19216a8df.md)
  
  Проводник
  
  ,
- Пиктограмма «Поиск». [Описание иллюстрации](../../raw/figures/c383ab9c637fcd10436e5f1a0936990219c1a97a5b9d0e83e9ca16d86204d566-39a17866dde9b2ad.md)
  
  Поиск
  
  — полнотекстовый поиск по файлам и объектам проекта с возможностью замены текста,
- Пиктограмма «Система управления версиями». [Описание иллюстрации](../../raw/figures/e69600bcbfe11b0b8d9dd4a858bab7f12c6be869ccdd2c6e169f309f7ab60fe6-100eae2cd1cdac86.md)
  
  [**Система управления версиями**](../project/collaborative-development-c0bea647f5a3.md)
  
  — версионирование и групповая разработка,
- Пиктограмма «Отладка». [Описание иллюстрации](../../raw/figures/13c92ae95685636635182766474ae2fc3061d460340203a6efd0fcb30a79f501-6c2ad99d8e3cd782.md)
  
  [**Отладка**](../project/start-debugging-d5c5117b447f.md)
  
  — отладка проекта,
- Пиктограмма «Закладки». [Описание иллюстрации](../../raw/figures/60769fbcbf3d62ad464877615ceaf985ae847012bd6d36c47cb1e4ae01627eff-20a3019989f8360a.md)
  
  [**Закладки**](ide-overview-and-basic-actions-969a6e6501a6.md)
  
  — закладки в текстовом редакторе.

При необходимости значки и панели представлений можно переместить и расположить так, как вам удобно (см. [здесь](ide-overview-and-basic-actions-969a6e6501a6.md)).

Если нужного представления нет в интерфейсе, вы можете открыть его через [**Главное меню**](ide-overview-and-basic-actions-969a6e6501a6.md) ⟶ **Вид** ⟶ **Открыть представление**. Для быстрого доступа некоторые представления отображаются уже непосредственно в самом пункте меню **Вид**.

Информацию о тех или иных представлениях можно найти в разделах о панелях и окнах, в которых эти представления расположены по умолчанию.

## Панели действий

[Левая](ide-overview-and-basic-actions-969a6e6501a6.md) и [правая](ide-overview-and-basic-actions-969a6e6501a6.md) панели действий позволяют открыть меню или представление. Нажатие на значок открывает представление сбоку, в соответствующей боковой панели.

## Левая панель действий

Из левой панели действий доступны следующие меню и представления:

### Главное меню

В самой верхней части левой панели действий находится выпадающееПиктограмма «Значок главного меню». [Описание иллюстрации](../../raw/figures/76356472ec4011b317782b529edfa610a8d48869f80d3456c57735e9b321aecd-142ded2d2a591828.md)**Главное меню**, с помощью которого доступны основные функции, многие настройки, а также информация о среде разработки:

Кнопка главного меню в верхней части левой панели открывает разделы «Проект», «Правка», «Выделение», «Вид», «Переход», «Отладка», «Справка». [Описание иллюстрации](../../raw/figures/4ec81b7f6eb278c2f72111fa71e390462e32b326eb6fe27cdba612fafaeca430-61edc97bd6bafdca.md)

> [!NOTE] примечание
> Если при работе с предыдущими версиями системы вы привыкли к фиксированному меню в верхней части экрана (главному меню), вы можете вернуть соответствующую настройку с помощью меню [Управление](ide-overview-and-basic-actions-969a6e6501a6.md) ⟶ **Параметры** ⟶ **Внешний вид** ⟶ **Режим отображения строки меню**.
>
> Фиксированное главное меню сверху среды: «Проект», «Правка», «Выделение», «Вид», «Переход», «Отладка», «Справка». [Описание иллюстрации](../../raw/figures/71907040031ccbb4abcff76a3915a1e79c4e2ab81e732846ee1f366558155bad-6c34114d95af3f5e.md)

В средней части левой панели действий находятся значки для открытия всех [основных представлений](ide-overview-and-basic-actions-969a6e6501a6.md).

Также из этой панели можно открыть и некоторые другие представления, например:

- Пиктограмма «История». [Описание иллюстрации](../../raw/figures/81280159c8152ab193bc6f2260be70f4775021887efb50a14e9a9973f70427f7-2c1be7e952aa7902.md)
  
  История
  
  ,
- Пиктограмма «Ссылки». [Описание иллюстрации](../../raw/figures/c1301dc1223b634cab70acec5ffb9c3fbad9b1ebb0cedcc17bff5c83d73fc8d4-8490a6dc1ff7c698.md)
  
  Ссылки
  
  .

### Представление «Проект»

Представление **Проект** содержит навигатор проекта, который используется для перемещения по элементам, объектам и модулям вашего проекта. Чтобы открыть навигатор проекта, нажмите на значок **Проект**:

На левой панели среды разработки выделен значок «Проект», открывающий навигатор проекта. [Описание иллюстрации](../../raw/figures/f23d0da2e843a34635ccfc778d3fb043621075653ebe0f72e6fc6dbd40fce834-064a0f1fb7177847.md)

В навигаторе доступны следующие возможности:

- Пиктограмма «Значок «Выделить в навигаторе»». [Описание иллюстрации](../../raw/figures/0f17c6d314ee43db58961cf794f1cdb0c0f6e953eb22fd4c80ee38d3eb4196bf-d08463dd4b8a5d54.md)
  
  — выделить в навигаторе проекта текущую вкладку,
- Пиктограмма «Значок «Обновить навигатор проекта»». [Описание иллюстрации](../../raw/figures/8ab5aaf9801b02491d320228b9136714f60e2d003223de8ded96ba1cedd5e682-783f6ab9b527d49e.md)
  
  — обновить навигатор проекта,
- Пиктограмма «Значок «Свернуть все»». [Описание иллюстрации](../../raw/figures/8b131388355e3002699e1612cbe7f73748acec0470787559f8aa361e75975446-debba231bd29a5bb.md)
  
  — свернуть все развернутые элементы проекта,
- Поиск в навигаторе [Описание иллюстрации](../../raw/figures/b1d518b767771bfed76bea3cc9fab4d067cfa1817acd63c0b098f6cc398ef45f-72bf55cf80755c7d.md)
  
  — поиск элемента проекта по названию.

Более подробно об элементах проекта и их обозначении в навигаторе см. [здесь](all-project-elements-5977d6a645f5.md).

Более подробно о работе с модулями и текстовыми файлами в навигаторе см. [здесь](ide-overview-and-basic-actions-969a6e6501a6.md).

#### Отображение ошибок в навигаторе проекта

При наведении на элемент навигатора, содержащий проблемы, появляется всплывающая подсказка с разделом **Проблемы**, в котором отображаются ошибки и предупреждения выбранного элемента и его дочерних элементов. Если ошибок и предупреждений нет, раздел **Проблемы** в подсказке не отображается. В заголовке раздела отображается их общее количество, а рядом с каждой проблемой — соответствующая иконка.

В навигаторе ошибочные элементы выделены красным. [Описание иллюстрации](../../raw/figures/5eccacbe0170e63900cb229f8fa91fbffed649d4e34bf2caff459f43a2b721d5-015bd2c29b689712.md)

### Создать компонент в навигаторе

Непосредственно в навигаторе можно создать новый компонент. Для этого:

Наведите на элемент, для которого вы хотите создать новый компонент, и нажмите на значок **Новый**:

В навигаторе возле выбранного процесса «СетьМагазинов» выделен зелёный значок «Новый» для создания дочернего компонента. [Описание иллюстрации](../../raw/figures/ed5a03950482c39c7564221ff2a801fd61238a7b4a8b5b8f383ae8e63623b59c-93c62786706113d3.md)

Введите или выберите из списка в появившемся диалоговом окне интересующий вас компонент:

В диалоге добавления компонента слева есть фильтры групп «Все», «Для СетьМагазинов», «Элементы проекта»; справа строка поиска и варианты «Параметр», «Метрика». [Описание иллюстрации](../../raw/figures/64e24874097435b3313bc7eda54a1c0578005d6ac013082825ec05c6d3217e57-67983acca7b90a7c.md)

Задайте имя компонента:

В дереве компонента СетьМагазинов раскрыта группа Метрики. Новая дочерняя метрика находится в режиме ввода имени, в поле показано НоваяМетрика. Выше видна группа Параметры с параметром URL. Это состояние переименования создаваемого компонента. [Описание иллюстрации](../../raw/figures/c591400e7e2d2bf6c78f4d9182d39c20109ce022a7ef41b8ecbfb804d9c78b6c-bcd77b71751d10e7.md)

> [!NOTE] примечание
> Если для компонента существует только один дочерний элемент, то он создастся автоматически после нажатия на значок **Новый** — без отображения списка доступных элементов и с автоматически сгенерированным именем на основании родительского элемента. Таким элементом, например, является модуль формы:
>
> Единственный новый компонент [Описание иллюстрации](../../raw/figures/cbd6297b0554ffd09b71a865d3c0487c4f1ff05bc57dd7128d4880d274c3150b-328684f47f45e371.md)

Новый компонент появится в списке вложенных компонентов:



Если вы не ввели имя для компонента, то оно будет присвоено компоненту автоматически. Имя компонента при создании генерируется на основе имени родительского элемента. Например, автоматическое имя для модуля объекта элемента проекта план обмена **ПланОбменаПриложений** — **ПланОбменаПриложений.Объект**.

В дереве «ПланОбменаПриложений» видны «Реквизиты», «Табличные части» и выделенный порожденный объект «ПланОбменаПриложений.Объект». [Описание иллюстрации](../../raw/figures/615ecf5082ef1afda18b3457cc67867b543a47936d77ce20e80e4139d6aac084-8dd229aa9c110238.md)

При необходимости вы можете изменить имя компонента непосредственно в навигаторе с помощью пункта контекстного меню **Переименовать**.

### Представление «Закладки»

Представление **Закладки** содержит все созданные в редакторе текстовых файлов [закладки](ide-overview-and-basic-actions-969a6e6501a6.md). Представление можно включить в главном меню: **Вид** ⟶ **Закладки**.



Все закладки отображаются во вкладках файлов в формате **номер строки**: **имя** с соответствующим типу закладки маркером. При выборе закладки будет открыт редактор текстовых файлов на соответствующей строке.

Панель «Закладки» показывает группы, файлы и закладки в формате номера строки и имени с маркером типа. Выбор закладки открывает соответствующую строку файла. [Описание иллюстрации](../../raw/figures/30ac834c22178a38859b9da2444e2382f712967667f8cfd6ca3e91c80aad1489-f855e40172f53c36.md)

Все закладки распределены по группам. Закладки сохраняются в группе, которая выбрана активной, по умолчанию — **Группа по умолчанию**. Для создания новой группы воспользуйтесь кнопкой **Добавить группу**. Для смены активной группы воспользуйтесь пунктом контекстного меню **Сделать группу активной**. Например, для случая, изображенного на картинке ниже, все закладки будут сохраняться в группу **Запросы**:

Выбор активной группы [Описание иллюстрации](../../raw/figures/8e461820103a07c888d9bbe9066bfc0604bccc6b1c11efdc013a80d5f242551c-3be8e861f89e07f7.md)

Закладки можно перемещать между группами путем перетаскивания или через контекстное меню:

Контекстное меню закладки содержит действие перемещения в другую группу, в том числе перемещение всех закладок текущего файла. [Описание иллюстрации](../../raw/figures/3a188d30bbc57e78b7a65e56828d5f60c193bec33bc1912f5d41febf7929278d-bd493e8baa93165c.md)

Закладку можно переименовать с помощью специального значка **Редактировать имя** или контекстного меню. Если удалить у закладки имя, то в качестве имени будет отображаться код этой строки.

В панели «Закладки» рядом с выбранной закладкой выделен карандаш «Редактировать имя» для её переименования. [Описание иллюстрации](../../raw/figures/47e383b47dc204a0270a8c0efad22fc090da01b0dcb84af777af1621eb518327-cb55c5ca05df0752.md)

Вы можете удалить закладку с помощью специального значка **Удалить** или контекстного меню. Чтобы удалить все закладки из группы, воспользуйтесь пунктом меню **Очистить закладки в этой группе**. Чтобы удалить все закладки из проекта, воспользуйтесь кнопкой **Удалить все закладки в рабочем пространстве**.

### Запуск и публикация

В нижней части левой панели действий находится выпадающее менюПиктограмма «Запуск и публикация». [Описание иллюстрации](../../raw/figures/480d2707e95da8328b8534f8d064076de334e378cb812b62c1e2fbb24f658f5c-dc7eb6f2f478d3c1.md) **Запуск и публикация**, позволяющее [опубликовать проект](../project/publish-project-on-server-dade1898bf5e.md), [открыть приложение](../project/open-or-restart-application-2d42f8a2392d.md), [начать отладку приложения](../project/start-debugging-d5c5117b447f.md) и открыть [панель управления](https://1cmycloud.com/console/help/element/10.0/docs/topics/control-panel/):

Меню «Запуск и публикация» [Описание иллюстрации](../../raw/figures/8cd44866e0fe3f374eaa2e11aa97a354691b807afe80262c59e475c6a629d9e1-6c6246f3346c3cfe.md)

### Управление

В самой нижней части левой панели действий находится выпадающее менюПиктограмма «Значок меню «Управление»». [Описание иллюстрации](../../raw/figures/03f80e8f942a80def9467b4b82d3c2824e5c897ce3b4b360f7eea4126577a019-feba3675a1b2a56e.md) **Управление**, позволяющее перейти к общим настройкам системы, настроить [сочетания клавиш](../project/keyboard-shortcuts-a9db35885b20.md), стили оформления (светлая/темная темы), а также открыть [Палитру команд](ide-overview-and-basic-actions-969a6e6501a6.md):



## Правая панель действий

В самой верхней части правой панели действий находятся значки для открытия следующих представлений:

- Пиктограмма «Свойства». [Описание иллюстрации](../../raw/figures/2770a226787786c6d094d2e704064d801ed9906c548586559614bd9a96ed3620-f9287bc096fa1f32.md)
  
  [Свойства](ide-overview-and-basic-actions-969a6e6501a6.md)
  
  — свойства выбранного элемента проекта,
- Пиктограмма «Структура». [Описание иллюстрации](../../raw/figures/a27a0c93d788fdb388995b3d0c72ce807fde20ac07dea9dd7649ff89080f9234-d1a3da76a1832403.md)
  
  [Структура](ide-overview-and-basic-actions-969a6e6501a6.md)
  
  — структура редактируемого XBSL- или YAML-файла,
- 
  
  [Чат c 1C:Напарником](ide-overview-and-basic-actions-969a6e6501a6.md)
  
  — чат с ИИ-ассистентом «1С:Напарником».

### Панель «Свойства»

На панели **Свойства** отображаются свойства выбранного компонента. Свойства можно просматривать, редактировать, добавлять и удалять. Панель автоматически открывается при выборе компонента в навигаторе или дереве компонентов. Также ее можно открыть, нажав на соответствующий значок на панели действий:

Панель «Свойства» выбранного компонента. На панели действий выделен значок, которым можно открыть эту панель вручную. [Описание иллюстрации](../../raw/figures/2df5dc3177c6db3384e057099d447ea614750197032cde098b3d1451fc746d19-4a343225ffe8aee7.md)

У каждого элемента может быть свой набор свойств. Вы можете ознакомиться с описанием свойств поддерживаемых элементов проекта и компонентов интерфейса в разделе документации **Справочная информация**:

- [Свойства элементов проекта](../project/projectelements-a83520ef7ffc.md)
- [Свойства компонентов интерфейса](interfacecomponents-f2cab906aee4.md)
- [Схема процесса интеграции](../integration/integrationprocessschema-7afd29ed6120.md)

Ниже представлены некоторые возможности и настройки панели свойств.

#### Поиск по панели свойств

В верхней части панели свойств находится поиск по свойствам и их значениям:

В верхней части панели свойств выделено поле «Искать свойства…», которое ищет свойства и их значения. [Описание иллюстрации](../../raw/figures/fa06fe0939f694669609d17f7fe884aa7ae01a66fdc404359fe47e3eeb33ec84-b442ef3f07512f1d.md)

#### Отображение ошибок в панели свойств

Значение свойства может содержать ошибку, например, иметь неподходящий тип или нарушать заданные ограничения. В таких случаях информация об ошибке отображается в панели свойств под соответствующим значением:

Ошибка в свойстве элемента проекта [Описание иллюстрации](../../raw/figures/8836e8b4f0e9311543495af2ae3e751969fbcc25f04df243b9539353e4917aa6-73cae8ff2bccd7cf.md)

Если в свойствах элемента указано несуществующее свойство, оно будет отображаться в верхней части панели свойств в отдельном поле, для которого будут доступны удаление свойства или сброс его значения:

Панель свойств показывает неизвестное свойство «Тип» отдельно и предупреждает о возможной потере данных; доступны удаление неизвестного свойства и открытие файла в текстовом редакторе. [Описание иллюстрации](../../raw/figures/e0860b6042fc16ac9b3626e0554a633342637aaa1a49cf884186106838b5c097-d762577ce909f23b.md)

Если в файле нарушена структура (например, после неудачного слияния или обновления), на панели свойств отображается соответствующее сообщение, а сама панель переводится в режим «только чтение». Для исправления доступна кнопка открытия файла в текстовом редакторе или редакторе слияния:

Панель свойств показывает сообщение о нарушении структуры файла и предложение открыть его в текстовом редакторе; редактирование свойств недоступно. [Описание иллюстрации](../../raw/figures/4135f624af37231dc99d00184bd9b2dccef04363078b3c4b90fb7dffb25e2f44-e027755570a7c403.md)

#### Совместное редактирование свойств

Панель свойств позволяет одновременно изменять одно и то же свойство у нескольких компонентов. Для этого достаточно выделить нужные компоненты в навигаторе — в панели свойств отобразятся их общие редактируемые свойства.

Одновременное редактирование свойств нескольких компонентов [Описание иллюстрации](../../raw/figures/ba396acefb5f2ebace9e9c867a16934466f667fa630748c41fa774aedbc4efd1-071f182c9d97e61f.md)

#### Импорт

Свойство **Импорт** позволяет указать подсистемы, из которых осуществляется импорт. По умолчанию свойство отображается в компактном виде:

Компактный вид импорта [Описание иллюстрации](../../raw/figures/aeda60479d7fe0251dbf42eea584b3dc8ab04bb231bc80e58db65897ad691833-22980ef2fc787d53.md)

Чтобы его расширить, наведите на него. По умолчанию отображается список только используемых подсистем. Чтобы просмотреть список всех доступных для импорта подсистем, нажмите на слово **фильтр**:

В свойстве «Импорт» показаны используемые подсистемы с флажками и ссылка «фильтр»; нажатие ссылки позволяет увидеть все доступные подсистемы. [Описание иллюстрации](../../raw/figures/f8daef307aeb1304268f17df8075ab8c297d0d0f173f5c4613d80031bed27098-035635b3b08b9220.md)

Отобразится список подсистем. Также отобразится фильтр, который может быть удобен, если список содержит множество подсистем. Для поиска по строке используйте поле ввода:

В свойстве «Импорт» выбранными флажками отмечены «Магазины» и «Основной». [Описание иллюстрации](../../raw/figures/08bfee3dcb32a21bde92492ee0a350e84d6447b2ca6a281be545f367516791f5-874c3ede6b00bb2d.md)

#### Удаление значения свойства

Для большинства свойств значение можно удалить:

Для сброса значения свойства используется маленькая кнопка с крестиком справа внутри поля. [Описание иллюстрации](../../raw/figures/2c0f1fd7983051648b4c7a928c763ed38e0e850c8345b291c3f2366296529c4c-726b1950d1074964.md)

> [!WARNING] важно
> Обратите внимание, что удалять значение рекомендуется именно таким способом. Если просто стереть значение из поля, то это может привести к ошибке данных: например, будет указана пустая строка.

#### Переименование проекта

Проект можно переименовать. Для этого нажмите на значок карандаша в панели свойств:

В поле «Имя» проекта справа выделен карандаш, открывающий диалог переименования проекта. [Описание иллюстрации](../../raw/figures/e4e82d41bebfa0b8137fc32b09825544d6853e1ba060f945f04df9f7521626ca-f592172a3895fb1e.md)

Откроется диалоговое окно для переименования:

Диалог «Переименовать» содержит поля поставщика и имени проекта, кнопки «Переименовать» и «Закрыть». [Описание иллюстрации](../../raw/figures/5140d66f4cb21b99ca3d32468aad0d72a003581d423c0aac0f4b0ad94c71df2d-712e7a5476ef25ba.md)

> [!NOTE] примечание
> Обратите внимание, что также можно переименовать связанное с именем проекта поле **Поставщик проекта**.
>
> > [!WARNING] важно
> > Убедитесь, что вы точно хотите переименовать сами проект и поставщика проекта. В большинстве случаев этого не требуется. Если вы просто хотите изменить то, как они отображаются в интерфейсе, достаточно изменить соответствующие [представления](../project/projectdescriptor-d54722c348c7.md).

Кроме того, имя проекта или поставщика проекта можно изменить через контекстное меню проекта в [навигаторе](ide-overview-and-basic-actions-969a6e6501a6.md) или простым нажатием на F2.

Все те же опции переименования доступны и для [библиотек](../project/create-and-use-libraries-38193c200df0.md) (если библиотека входит в **Зависимости** — в режиме **Только чтение**).

#### Выбор типа

Для выбора типа пользователю отображается удобное диалоговое окно, которое содержит группировку, поиск и возможность множественного выбора. Чтобы открыть диалоговое окно, нажмите на тип:

Переключатель значений свойства [Описание иллюстрации](../../raw/figures/d0eb18c650c4ae1a622fac8b8c77cabda39fde8d10680e8f3fb109591754dbbc-3ec240ad0b06ee96.md)

> [!WARNING] важно
> Доступно не для всех типов. В примере выше доступно для параметра обобщенного типа.

При выборе некорректного типа для элемента выводится диагностическое сообщение с ошибкой:

В поле «Тип» введено `неизвестно`; красная диагностика сообщает: «"неизвестно" нельзя использовать для хранения в БД».. [Описание иллюстрации](../../raw/figures/17d860c1c848ab997fd9ae7b075e48a87cb413d25aff225a0e28c985345e4e93-fb7389953cf3f944.md)

В некоторых случаях система помогает установить нужный состав типов. Например, при использовании типа `имя-сущности.Ссылка` система автоматически добавляет в состав типа `Неопределено`. При этом `Неопределено` в составе типа всегда отображается последним:



> [!NOTE] примечание
> Для обобщенных типов параметры со значениями по умолчанию применяются автоматически и не требуют обязательного указания в составе типа.

#### Переключение между значениями

Для свойств некоторых типов, например **Булево**, сразу все допустимые значения указаны в одну строку — можно просто переключаться между значениями:

Переключатель значений свойства [Описание иллюстрации](../../raw/figures/a9e38629edbf2bea2974d4bba8e85f8fccac1385f5bd5e7e13f945ef5f7fcf35-d0f244c7ed5aad4e.md)

#### Свойства с несколькими значениями

Для некоторых свойств может быть указано сразу несколько значений одного уровня, следующих друг за другом. Такие значения выделяются разноцветными линиями. Эти значения можно перемещать вверх и вниз по списку, добавлять и удалять с помощью соответствующих кнопок:

В свойстве ПараметрыЗаписи раскрыты два элемента: Параметр1 (Строка | Неопределено) и Параметр2 (Число | Неопределено). Для удаления первого элемента нажимают красную кнопку с корзиной справа от его заголовка. Кнопка плюс добавления находится справа от заголовка всего списка ПараметрыЗаписи. Изображение используется дважды для одного и того же действия. [Описание иллюстрации](../../raw/figures/c65d730b6b32f0da9924221933baa9ebbc91a43a02ea299dad5424b574138207-441bbcea8a39032d.md)

Кнопка удаления элемента

Перемещение элемента [Описание иллюстрации](../../raw/figures/a9f21c47037fd013c92f2109c96a07b6be5542b105a8935bcbbbfb1646fba0af-9334cc748a88bd65.md)

Кнопка перемещения элемента

Пример редактирования коллекции ПараметрыЗаписи на панели свойств: кнопка + находится справа от названия коллекции. [Описание иллюстрации](../../raw/figures/210ffd0b5e6192982cdab38a3e6b8a50a230271005e2e1a4f1a8f988eee0eb46-347dc55a47f22b99.md)

Кнопка добавления элемента

В свойстве ПараметрыЗаписи раскрыты два элемента: Параметр1 (Строка | Неопределено) и Параметр2 (Число | Неопределено). Для удаления первого элемента нажимают красную кнопку с корзиной справа от его заголовка. Кнопка плюс добавления находится справа от заголовка всего списка ПараметрыЗаписи. Изображение используется дважды для одного и того же действия. [Описание иллюстрации](../../raw/figures/c65d730b6b32f0da9924221933baa9ebbc91a43a02ea299dad5424b574138207-441bbcea8a39032d.md)

Кнопка удаления элемента

Перемещение элемента [Описание иллюстрации](../../raw/figures/a9f21c47037fd013c92f2109c96a07b6be5542b105a8935bcbbbfb1646fba0af-9334cc748a88bd65.md)

Кнопка перемещения элемента

Пример редактирования коллекции ПараметрыЗаписи на панели свойств: кнопка + находится справа от названия коллекции. [Описание иллюстрации](../../raw/figures/210ffd0b5e6192982cdab38a3e6b8a50a230271005e2e1a4f1a8f988eee0eb46-347dc55a47f22b99.md)

Кнопка добавления элемента

В свойстве ПараметрыЗаписи раскрыты два элемента: Параметр1 (Строка | Неопределено) и Параметр2 (Число | Неопределено). Для удаления первого элемента нажимают красную кнопку с корзиной справа от его заголовка. Кнопка плюс добавления находится справа от заголовка всего списка ПараметрыЗаписи. Изображение используется дважды для одного и того же действия. [Описание иллюстрации](../../raw/figures/c65d730b6b32f0da9924221933baa9ebbc91a43a02ea299dad5424b574138207-441bbcea8a39032d.md)

Кнопка удаления элемента

Перемещение элемента [Описание иллюстрации](../../raw/figures/a9f21c47037fd013c92f2109c96a07b6be5542b105a8935bcbbbfb1646fba0af-9334cc748a88bd65.md)

Кнопка перемещения элемента

-
-
-

#### Локализованные строки

Если для получения значения свойства компонента должна использоваться [локализованная строка](../project/app-localization-15f5b1317f82.md), то требуется нажать на значок выбора языка — активный режим использования локализованной строки:

Локализованная строка используется [Описание иллюстрации](../../raw/figures/8b073e69765b35322e8cac51ada2a23015bc5513a65cad9a059c051093718923-5a73b39c00a75d3a.md)

Выберите локализованную строку из выпадающего списка.

#### Добавить изображение

Для некоторых элементов вашего приложения вы можете установить картинку. Для этого перейдите к свойству **Изображение** и выберите картинку:

Выбор изображения [Описание иллюстрации](../../raw/figures/8bb114bb41d4d28834a7446a8faefc1a02cf83939a0fedb6113f413b47337e0d-c0b0e36a45c85318.md)

#### Выбор цвета

Для некоторых компонентов, например картинок, доступен выбор цвета. Чтобы выбрать или изменить цвет, нажмите на кружок с цветом. Отобразится палитра и другие инструменты:

Выбор цвета открывается из кружка в поле «Цвет», где на снимке указано `Цвета.Фиолетовый`. [Описание иллюстрации](../../raw/figures/667c54ae5a819c9fcb1536befef7b72e5511c64a1f462c97c577bb156f3aeb1f-89d4255c155494a1.md)

#### Вычисляемые выражения

Если для получения значения свойства компонента должно использоваться [вычисляемое выражение](calculated-property-values-for-ui-components-05bce1d1d5e7.md), то требуется нажать на значок функции, который активирует специальный редактор ввода вычисляемого выражения:

Вычисляемое выражение используется [Описание иллюстрации](../../raw/figures/919c0e9870d4314d0c68e924d47d9453772e6c15202eae0ea3f04b2d222f432d-dc2da529df70d755.md)

Редактор упрощает ввод вычисляемого выражения:

- При вводе выражения отображается подсказка ввода доступных значений:
  
  При вводе вычисляемого значения `Объект.Н` появляется список подсказок: `Наименование: Строка` и `ЭтоНовый(): Булево`. [Описание иллюстрации](../../raw/figures/bee28883a999b76d7d7e57dff39fc50dbbc533a91860c87b2a46594283fe7e82-124e3eccb10eea9a.md)
- С помощью быстрого исправления можно создать в модуле метод для вычисления свойства:
  
  Создание метода из поля ввода [Описание иллюстрации](../../raw/figures/a9a19f469ae6d5ff4df8dc6928e33b1e78dcf7b786b5be14b0f5ae347cfd6483-f262c79fb9577546.md)
- Элементы выражения можно менять, выбирая их в поле ввода. Например, в выражении `Объект.Пользователь` можно легко заменить свойство `Пользователь` на `Регион`, выбрав его из списка:
  
  Выбор элемента выражения [Описание иллюстрации](../../raw/figures/9825a57860cb258ab9670e5e27d1418d3ffa2d760616d661e26ff45410418158-aedd37fb9556691d.md)
- Для перехода к месту объявления параметра вычисляемого выражения нажмите на него с зажатой клавишей Ctrl:
  
  Переход к свойству [Описание иллюстрации](../../raw/figures/ac09e66f1582b85505f466d4166f48df833cd377b6e13c85c057cafa0c64ec74-1df9d5e12d0ce1c8.md)
- Автоматическая валидация выводит сообщения о некорректных значениях:
  
  В панели свойств рядом с вычисляемым выражением показана ошибка автоматической проверки: значение «Объект» доступно только для чтения. [Описание иллюстрации](../../raw/figures/3cafa2feda0d9d37cb2c9e426837b317f193644523953ce5478435f968d410fc-5c7edf4286ab7d3d.md)
- Для вывода подсказки ввода нажмите на значок **+** — **Показать подсказку**:
  
  Кнопка «Показать подсказку» [Описание иллюстрации](../../raw/figures/8e6d2e3619b9bce5eff64894ef226c32c9e65e2201863ce6cbd7ae4e4db9796d-4d36fe3ccc31df00.md)

Если вычисляемое выражение не должно использоваться — отключите активный режим:

Панель значения свойства с отключённым режимом вычисляемого выражения; значок fx отображается неактивным. [Описание иллюстрации](../../raw/figures/3e889bdb7a265c7219c27e0a921decf838067f3006482d61f77b7f7a99a8443e-ee16f4ebd7e46313.md)

#### Обработчики событий

Для компонентов интерфейса помимо обычных свойств, которые указаны в верхней части панели свойств **Стандартные**, можно задать [обработчики событий](interface-processing-af5f6bd55028.md). Для этого в нижней части панели свойств **События** нажмите на значок плюса рядом с полем интересующего вас события:

В нижней группе «События» панели свойств кнопка плюса рядом с «ПриИзменении» создаёт обработчик события компонента. [Описание иллюстрации](../../raw/figures/373b34e4f52e5df92da14be4b4e99c902286df2f524bd114df4cab2517bcf1f1-b799e25fbc9e4d41.md)

В соответствующем компоненту интерфейса модуле обработчик будет создан автоматически.

Список обработчиков с параметрами, соответствующими данному компоненту интерфейса, доступен в выпадающем списке:



Для удаления обработчика воспользуйтесь кнопкой [**Сбросить**](ide-overview-and-basic-actions-969a6e6501a6.md). Появится диалоговое окно для удаления обработчика из модуля:

Окно удаления обработчика [Описание иллюстрации](../../raw/figures/cad122ddb6bc35f692ea6cfb0389dfc8bf2ce4dd338fe3c3ff636721f181d183-20fd9c59bce98a78.md)

Для [команд](command-interface-9e5d023134de.md) пользовательского интерфейса также существует специальное свойство, которое так и называется — **Обработчик**:

Для команды в поле «Обработчик» выбран метод «ПриНажатииОбработчик». [Описание иллюстрации](../../raw/figures/69a2b91e0b43ee8a64ad2b0531ab63253822a7a42a02ea98103a83eebbc0e7e8-6960dca735275b82.md)

> [!WARNING] важно
> При необходимости, для просмотра или редактирования свойств компонента также можно использовать файлы в формате YAML ([подробнее](ide-overview-and-basic-actions-969a6e6501a6.md)), однако это служебные файлы и редактировать их не рекомендуется — используйте панель свойств.

#### Отображение информации о свойствах объекта

Для [компонентов интерфейса](all-project-elements-5977d6a645f5.md) при наведении на имя свойства отображается всплывающая подсказка с его описанием:

Описание свойства элемента [Описание иллюстрации](../../raw/figures/a1e7fbf2257bbe8e65927fab67aaa5177c86827a874672b326a2a9e639f87402-4d7a9a08337ff1e8.md)

#### Документирующий комментарий

С помощью свойства **Документирующий комментарий** вы можете добавить [документирующий комментарий](../data/documentation-comments-390ccb2e149e.md) к элементам проекта, компонентам интерфейса и их составным частям (реквизитам, полям, свойствам и т. п.).

Редактор для ввода документ�ирующего комментария в панели свойств [Описание иллюстрации](../../raw/figures/9bcbc3ba1b1b8da56772b6167a235d70e7839abc6254769b52c9036b303bf210-745a509cd25bfb53.md)

Документирующий комментарий показывается в контекстной подсказке в редакторе кода модуля и во всплывающей подсказке при наведении мыши на элемент в среде разработки (навигаторе проекта, редакторе компонентов интерфейса и панели свойств).

Всплывающая подсказка справочника «Сотрудники» показывает документирующий комментарий: описание данных сотрудников, список реквизитов, полное имя и видимость элемента. [Описание иллюстрации](../../raw/figures/df222e9edf430eba5eee8d56e5bf216893552cffbdeb54fdf5717ee02cb560f9-cf9aebcd8085c75d.md)

### Панель «Структура»

Панель **Структура** при редактировании модулей показывает их структуру (список методов). Вы можете быстро переместиться к методу, просто нажав на него на панели **Структура**:

Структура редактируемого модуля [Описание иллюстрации](../../raw/figures/fcaf05bde9fe8c1dbbcc495574b51da96ad7c532b26e8623782570260268ae29-0d209ead734616f7.md)

При редактировании YAML-файлов панель **Структура** показывает иерархическую структуру файла, что позволяет быстро перемещаться по его элементам:

Структура редактируемого YAML-файла [Описание иллюстрации](../../raw/figures/87443d1098b3a4be566f119aeda8b7bb8e1bf4954aa7702d38fe61e0d4a96569-75a668d3c3087149.md)

### Панель «Чат с 1С:Напарником»

Данная панель позволяет вам взаимодействовать с умным ассистентом [«1С:Напарником»](../project/1c-workmate-3ecef06701ac.md) для написания кода, решения прикладных задач и исправления ошибок. Для подключения «1С:Напарника» вам необходимо получить ключ доступа и ввести его в настройках среды разработки ([инструкция](../project/1c-workmate-3ecef06701ac.md)).

Панель чата «1С:Напарник»: область сообщений и поле ввода обращения к ассистенту в среде разработки. [Описание иллюстрации](../../raw/figures/3479b5296858d94c149a7b776a1f8d6bdfb1dfc9463dee600e56d1be392dddab-b29cf67bf3d67fe9.md)

## Боковые панели

На боковых панелях отображаются представления, которые вы выбрали, нажав на значок в соответствующей [панели действий](ide-overview-and-basic-actions-969a6e6501a6.md).

## Область редакторов

В центральной части среды разработки доступно главное окно, с помощью которого пользователь осуществляет работу с тем или иным компонентом системы — *область редакторов*. Именно в этом окне, в зависимости от редактируемого компонента, отображается соответствующий редактор:

- [редактор текстовых файлов](ide-overview-and-basic-actions-969a6e6501a6.md)
  
  ,
- [редактор компонентов интерфейса](ide-overview-and-basic-actions-969a6e6501a6.md)
  
  ,
- [редактор отчетов](../project/create-report-b99954f7595c.md)
  
  ,
- [редактор процессов интеграции](../integration/integration-process-be3cd7b902c7.md)
  
  .

Так в среде разработки выглядят панели и окна для работы с выбранным компонентом. В центре — область редакторов, в которой в данный момент открыт редактор компонента интерфейса:

Разметка рабочей области редактора формы объекта: слева отмечен выбранный компонент, в центре его редактор и предпросмотр, справа свойства этого компонента. [Описание иллюстрации](../../raw/figures/d9c368927d04e233c1cfdd097a93c6e205d642f0be04dd1612dc0bdd55afd678-86942b2fba4184b2.md)

На самой правой части панели вкладок отображается специальный значок **Редактор элемента** (сочетание клавиш: Alt + K):

Справа на панели вкладок файлов выделен значок «Редактор элемента», открывающий графическое редактирование элемента проекта. [Описание иллюстрации](../../raw/figures/551472da0c2fc9823731444f3a225d517e31f9bbdf8b306e30071ba1cff26c4e-a25562af8698d8c5.md)

**Редактор элемента** позволяет открыть список основных связанных с элементом и доступных для редактирования объектов и модулей:

Окно редактора элемента «Сотрудники» предлагает связанные формы списка и объекта, модули и типы; поле поиска позволяет выбрать нужный редактор. [Описание иллюстрации](../../raw/figures/e9d29f16d76d275b5f8761da61b7dce9bfb2589eee7b2b228ebbe729f5a97c10-fbf8b0f36e47692b.md)

При большом количестве открытых вкладок слева от значка **Редактор элемента** отображается значок **Показать остальные вкладки**:

Показать остальные вкладки [Описание иллюстрации](../../raw/figures/9c20d0b0495d6aa409efe6922c380ae0196f52d1754c7023468bf532bff0a8bf-15daa400e47cc1f8.md)

Он позволяет увидеть список всех открытых в редакторе вкладок:

Раскрыт список всех открытых вкладок редактора; у каждой указан файл или элемент, выбранная вкладка отмечена галочкой. [Описание иллюстрации](../../raw/figures/ff5f204cd665bce2421914e7e54a6200ad9fdc228a01070ecbf186f9f1dd370e-2a9575f6ed670528.md)

При первом открытии список отображается в компактном варианте. Для отображения полного списка нажмите на **...** (кнопка **Показать видимые вкладки**):



По изображению рядом с названием вкладки легко определить, какой файл открыт в редакторе: компонент интерфейса, файл YAML или файл XBSL:

На вкладках редактора различаются значки компонента интерфейса, YAML-файла и XBSL-модуля. [Описание иллюстрации](../../raw/figures/0a1f32ec79fbd16315d8e0504bef6e1c367e8a2e69cf2f61f334c15794601096-dbc88a71e3453e6a.md)

### Редактор текстовых файлов

Редактор текстовых файлов позволяет редактировать программный код на [языке «1С:Элемент»](../language/1c-element-language-overview-59fed6458966.md). В редакторе при этом открывается специальный файл XBSL — [модуль](../language/module-f92cc205e14d.md) выбранного компонента.

Также редактор позволяет редактировать файл YAML, который описывает свойства выбранного компонента или других объектов.

Чтобы открыть текстовый файл выбранного компонента, нажмите на нем правой кнопкой мыши и выберите из появившегося контекстного меню **Открыть в текстовом редакторе**:



Так выглядит текстовый файл компонента в редакторе:

В дереве проекта выбран элемент «СпособДоставки». [Описание иллюстрации](../../raw/figures/59e1ff5bec4e6f4898f0ed51841ea182e346bc5e8d433153e3ad082d8c4e12f6-23131820596873f1.md)

После редактирования YAML-файла вы можете упорядочить строки в соответствии с единым стилем, принятым по умолчанию в «1С:Предприятие.Элементе». Для этого в контекстном меню выберите пункт **Переформатировать элементы проекта** и в открывшемся окне нажмите **ОК**:

Диалог «Переформатирование кода» спрашивает, переформатировать ли YAML-файлы выбранных элементов, и рекомендует перед вызовом зафиксировать изменения в системе контроля версий. [Описание иллюстрации](../../raw/figures/18b7309485240f76419a3dec20631894947f35371f1d5067f8f592461cf607ac-7ce0348a1a9cc912.md)

Форматирование можно применить как к одному элементу, так и сразу к нескольким выбранным элементам, пакетам или подсистемам. При переформатировании нескольких элементов проекта рекомендуется предварительно зафиксировать изменения в системе контроля версий ([подробнее](../project/commit-changes-8ac78032ff13.md)).

> [!WARNING] важно
> Файл YAML — это служебный файл. Такой способ редактирования свойств не рекомендуется. Используйте [панель «Свойства»](ide-overview-and-basic-actions-969a6e6501a6.md).

#### Контекстная подсказка

Контекстная подсказка — это инструмент, который помогает вам писать и редактировать текст программы. С его помощью вы можете ускорить ввод текста и избежать ошибок и опечаток.

Контекстная подсказка после СтрокаРезультата. [Описание иллюстрации](../../raw/figures/269cd21f63e7adf8b574ec09dff13881bc9f8cc46e0b3ccc0b9bff17a94af2d7-64cd834a7833cbe7.md)

Вы можете вызвать контекстную подсказку, нажав Ctrl+Пробел в редакторе XBSL- или YAML-файла. Также контекстная подсказка открывается автоматически при обращении к свойствам экземпляра и вызове методов через [операцию `.`](../language/addressing-module-fd4292400f74.md). При повторном нажатии Ctrl+Пробел отображается информация о выбранном элементе.

Автодополнение контекста доступа показывает список методов; повторный вызов подсказки раскрывает документацию выбранного Дополнить: назначение, параметры, возвращаемый КонтекстДоступа, глобальная видимость, доступность на сервере и перегрузка метода. [Описание иллюстрации](../../raw/figures/f69abf96a4f62245a841d70a26ca2df2dd55f2c72e701a81eb33d365f0daf0ce-7033d70b292def29.md)

Контекстная подсказка показывает только те свойства, методы и типы, которые доступны в редактируемом окружении. Окружение зависит от того, в какой позиции табуляции находится курсор.

Контекстная подсказка в YAML-редакторе [Описание иллюстрации](../../raw/figures/a360900340f4a93c3cc5e9b7c6f9f8f6788ce5a0106e2c9aa2fac88c552ee0cd-ef9c465ed9f890a3.md)

Устаревшие свойства и методы отображаются зачеркнутыми.

В списке автодополнения ОбъектноеХранилище актуальные варианты загрузки показаны обычным текстом, устаревшие методы — зачёркнутыми. Снимок иллюстрирует визуальное обозначение устаревшей функциональности. [Описание иллюстрации](../../raw/figures/f79c509d49a9deb273c97592f9f542853881cd22b42c85f02f1d406690a6abf8-5a211d2f741fc75b.md)

В окне с информацией об устаревшем методе или свойстве указано, что следует использовать вместо него.

Контекстная подсказка отмечает выбранную перегрузку «Загрузить» зачеркнутой и сообщает, что метод устарел. [Описание иллюстрации](../../raw/figures/73385bc28a7886d5b10455a3eec77e2a5dde510d2d22ad434bc19ee604a0bd95-fefd7e647346efe6.md)

#### Закладки

Редактор текстовых файлов позволяет устанавливать закладки. Закладки используются для отметки строк в программном коде, чтобы осуществлять быстрое перемещение между ними. Вы можете создавать закладки без названия или с заданным именем, чтобы сделать навигацию в списке закладок более удобной. Все добавленные закладки отображаются в вертикальной линейке в левой части редактора кода в виде специальных маркеров, а также в отдельном представлении [**Закладки**](ide-overview-and-basic-actions-969a6e6501a6.md).

Чтобы добавить закладку, щелкните правой кнопкой мыши на номер строки кода и выберите требуемый тип закладки из меню **Закладки** или используйте соответствующее требуемому типу закладки сочетание клавиш:

Контекстное меню номера строки содержит Закладки → Создать закладку (Ctrl+Alt+B), Создать именованную закладку (Ctrl+Alt+N), Удалить все закладки в файле. [Описание иллюстрации](../../raw/figures/219438dfe6582c79c23f0c3960afc67ed5b394a2a0af56891bab941c3403257b-60398415e13f0502.md)

При выборе пункта **Создать закладку** (Ctrl + Alt + B) код выделенной строки используется в качестве имени закладки. Чтобы создать закладку с определенным именем, воспользуйтесь пунктом **Создать именованную закладку** (Ctrl + Alt + N). После создания закладки в крайнем левом поле рядом со строкой кода отобразится соответствующий маркер:

Слева от строк кода в редакторе показаны маркеры закладок: синие отметки для строк и отличающийся маркер именованной закладки. [Описание иллюстрации](../../raw/figures/e3616ee0aa301d8816e837efb938d516a4431cf40b2f4a586150946b88224871-b3e5f6a1798d0e3a.md)

Для каждой закладки можно добавить описание. Описание закладки отображается во всплывающем окне при наведении на маркер закладки или на строку кода:

При наведении на маркер закладки всплывающая подсказка показывает её имя, группу и описание назначения отмеченного кода. [Описание иллюстрации](../../raw/figures/f07786771e4c0f9acaef9867966e3453a429b13b7113acce95096a13e7fbd5c3-726068c59c47c7d9.md)



Вы можете переименовать закладку, удалить ее или удалить все закладки из открытого файла с помощью соответствующих пунктов контекстного меню.

### Мини-карта

**Мини-карта** — уменьшенная копия содержимого файла в правой части окна редактора. Мини-карта позволяет сделать общий обзор кода для получения примерного представления о его структуре и содержимом, а также используется для быстрого перемещения по файлу. Видимая в основной части окна пользователю область файла отображается в мини-карте как затененная.

Чтобы перемещаться по файлу с помощью мини-карты, можно просто щелкнуть на ней либо потянуть мышью за затененную область:

Мини-карта расположена справа от основного текста редактора. [Описание иллюстрации](../../raw/figures/780d57dd5c0f9800bfbec7773fa28146018d83ca80efb2fc6994aaa025dff884-f1af993d31309b25.md)

> [!NOTE] примечание
> Вы можете отключить показ мини-карты в нижней части меню **Вид** ⟶ **Переключить мини-карту**.

### Редактор компонентов интерфейса

**Редактор компонентов интерфейса** — редактор и конструктор графического пользовательского интерфейса, который позволяет редактировать выбранный компонент интерфейса, добавлять или удалять его составляющие (в том числе с возможностью предварительного просмотра), редактировать его свойства и т. д. Редактор компонентов состоит из следующих основных частей:

- [дерево компонентов](ide-overview-and-basic-actions-969a6e6501a6.md)
  
  — показывает расположение компонента в общей структуре элементов интерфейса приложения,
- [окно предварительного просмотра](ide-overview-and-basic-actions-969a6e6501a6.md)
  
  — позволяет заранее просмотреть, как данный компонент будет выглядеть в интерфейсе приложения:
  
  - [панель управления настройками предварительного просмотра](ide-overview-and-basic-actions-969a6e6501a6.md)
    
    — управляет настройками просмотра,
- дополнительные информационные панели:
  
  - [панель компонентов](ide-overview-and-basic-actions-969a6e6501a6.md)
    
    (также —
    
    палитра компонентов
    
    ) — позволяет выбрать графические элементы, доступные только для выбранного компонента,
  - [панель данных](ide-overview-and-basic-actions-969a6e6501a6.md)
    
    — позволяет просматривать и редактировать данные компонента и его формы,
  - [панель событий](ide-overview-and-basic-actions-969a6e6501a6.md)
    
    — содержит описание событий компонента,
  - [панель команд](ide-overview-and-basic-actions-969a6e6501a6.md)
    
    — позволяет выбрать команды, которые можно использовать в командном интерфейсе компонента.

Так окно редактора компонента интерфейса выглядит в среде разработки:

Размеченное окно редактора компонента интерфейса: слева дерево компонентов и панель компонентов, данных, событий и команд; в центре предпросмотр; сверху настройки размера и масштаба предпросмотра. [Описание иллюстрации](../../raw/figures/d8cdbac7803e340f13a5c3b0854ee20892916ae892c10e0beac480376ebed30f-ee48dc79ff59fd74.md)

Например, так выглядит редактор компонента интерфейса для поля ввода **Наименование** формы объекта справочника **Задачи**:

Редактор поля ввода [Описание иллюстрации](../../raw/figures/b07c351bbc5db43b4bcbeb4b824f9e48e3484b9de2fc78e6cf872d1affbda837-d1fd3df3b8b226b3.md)

Более подробно о компонентах интерфейса и их обозначении в области редакторов см. [здесь](all-project-elements-5977d6a645f5.md).

> [!NOTE] примечание
> Чтобы редактор компонентов интерфейса работал корректно, у пользователя сервера должен быть настроенный SSL-сертификат.
>
> Если SSL-сертификат не настроен, поддерживаются только два адреса сервера:**127.0.0.1** и **localhost**. Если используется собственный адрес, прописанный в файле **hosts**, редактор компонентов интерфейса также работать не будет.

#### Дерево компонентов

Дерево компонентов позволяет осуществлять навигацию по иерархии компонентов для выбранного в навигаторе элемента.

При наведении на компонент могут отображаться значки:

- Пиктограмма «Значок создания нового компонента». [Описание иллюстрации](../../raw/figures/09067ca87e16d198fad1e9070a10750a42de49827726867d999516085a66ac81-f56a4abcd87062c3.md)
  
  — создать новый компонент,
- Пиктограмма «Значок удаления компонента». [Описание иллюстрации](../../raw/figures/7fd55e2ba44225d9c3a6684ac21d3b886dff76f2b87a0153b7b5c6dd15bd0fba-07b6d7f462815145.md)
  
  — удалить компонент,
- Пиктограмма «Значок перехода к редактору компонента». [Описание иллюстрации](../../raw/figures/4f407ba4570342d059037209ba2cf753b2895ec830a42b2ca927daa0924c7dcb-4678dfbc548198bb.md)
  
  — перейти к редактору компонента.

Например:

При наведении на строку ГруппаПолей в дереве компонентов появляются красный крест удаления и зелёный плюс добавления. [Описание иллюстрации](../../raw/figures/783ce30bcccdd79a007d3526e3e1819994439d933ba9c9d7fe77b9448839d612-8f6bf092a60b6600.md)

Как видно выше, при наведении на компонент также может отображаться всплывающая подсказка с информацией о данном компоненте.

#### Создать компонент в дереве компонентов

Непосредственно в дереве компонентов можно создать новый компонент. Для этого:

- Наведите на элемент, для которого вы хотите создать новый компонент, и нажмите на значок плюса:
  
  
- В появившемся диалоговом окне введите или выберите из списка интересующий вас компонент:
  
  В палитре компонентов выбран раздел «Компоненты интерфейса». [Описание иллюстрации](../../raw/figures/03f7ea2a6ade9091b70c0f8e2bd6e0cc71f307eb1547b784722d0872140544eb-f0538597715a345d.md)

Новый компонент появится в нижней части списка вложенных компонентов:

После добавления компонента в дереве содержимого формы внизу группы появился новый элемент «ПолеВвода1». [Описание иллюстрации](../../raw/figures/e73a9d8432735582a570f6c55af3682b9e981b9a2819391ab918ee2bda7b1d3f-5a672d4cc2ddd995.md)

Если вы не ввели имя для компонента, то оно будет присвоено компоненту автоматически. При необходимости вы можете изменить имя компонента в панели свойств.

#### Изменить тип компонента

Для компонента интерфейса в дереве компонентов можно изменить его тип.

В общем случае при смене типа действуют следующие правила:

- Свойства компонентов с одинаковым именем и базовым типом сохраняются.
- Свойства, которые отсутствуют в новом типе, удаляются.

Кроме смены типа следующих компонентов:

- **ПроизвольныйШаблонФормы** ⟶ **ШаблонФормыСРазделами**:
  
  - Компоненты типов
    
    РазделФормы
    
    и
    
    Группа
    
    переносятся напрямую в свойство
    
    ОсновнойРаздел
    
    , остальные оборачиваются в
    
    Группу
    
    .
- **ШаблонФормыСРазделами** ⟶ **ПроизвольныйШаблонФормы**:
  
  - Все компоненты разделов последовательно оборачиваются в одну
    
    Группу
    
    .
- **Группа**, **ГруппаСПлавающимКомпонентом**, **РазделяющаяГруппа** и **СтековаяГруппа** взаимозаменяемы:
  
  - При смене типа на
    
    ГруппаСПлавающимКомпонентом
    
    или
    
    РазделяющаяГруппа
    
    одиночные компоненты переносятся напрямую, несколько — оборачиваются в
    
    Группу
    
    .
  - При смене типа на
    
    Группа
    
    или
    
    СтековаяГруппа
    
    содержимое переносится напрямую.
- **СтандартныйСписок**, **ПроизвольныйСписок**, **Таблица**:
  
  - При смене типа списка также переносится спецификация типа.

Чтобы сменить тип компонента:

1. Наведите на компонент, для которого вы хотите сменить тип, и выберите пункт контекстного меню **Рефакторинг** ⟶ **Сменить тип**:
  
  
2. Выберите требуемый тип из списка доступных. Вы можете выбрать из списка наиболее подходящих типов компонентов для выбранного или из всех доступных:
  
  В дереве формы выбран компонент «ГруппаПолей». [Описание иллюстрации](../../raw/figures/078cea6a7cd71490e60513111d971ebbcb765db0742d121c5b571ab55e289c19-248e9f539833c1ba.md)
3. Подтвердите выбор смены типа:
  
  Диалог «Изменение типа компонента» предупреждает: при изменении типа содержимое компонента и заполненные свойства, которые присутствуют в новом типе, будут перенесены. [Описание иллюстрации](../../raw/figures/211dd6e30377532ce6f4f6aef6f96a40e2b4cb59598a925cc90f14fc819dc333-05cd18cdefc083f7.md)

После подтверждения операции тип компонента будет изменен.

#### Отображение ошибок в дереве компонентов

При наведении на компонент, содержащий проблемы, в дереве компонентов появляется всплывающая подсказка с разделом **Проблемы**, в котором отображаются ошибки и предупреждения выбранного компонента и его дочерних элементов. Если ошибок и предупреждений нет, раздел **Проблемы** в подсказке не отображается. В заголовке раздела отображается их общее количество, а рядом с каждой проблемой — соответствующая иконка.

Подсказка группы «ГруппаКоманд» содержит раздел «Проблемы»: красными крестами отмечены «Не строковое значение в кавычках», отсутствие метода «КомандаСКомпонентомОбработчик» и отсутствие представления. [Описание иллюстрации](../../raw/figures/646983e380c4c1de82dc3b54a9d5fec505b88c8be49c282fc826e48141f054c7-df627a4660a49413.md)

#### Панель управления настройками предварительного просмотра

**Панель управления настройками предварительного просмотра** находится в верхней части окна редактора компонента и выглядит следующим образом:

Панель предварительного просмотра сверху редактора содержит, слева направо: выбор устройства (телефон, планшет, компьютер), поля разрешения (в примере 1024 × 768), смену ориентации, масштаб (в примере 100%) и переключатель темы. [Описание иллюстрации](../../raw/figures/7a634a785a1353c09a41d0d0800ed1efc37f687194030f6df7808712389ddd8e-dc85763ba04e3dc1.md)

Данная панель содержит следующие настройки:

- Режим отображения в зависимости от типа/модели устройства:
  
  - Тип устройства:
    
    Телефон
    
    /
    
    Планшет
    
    /
    
    Компьютер
    
    ;
  - Наиболее популярные модели устройств.
- Разрешение (размер) окна предпросмотра;
- Ориентация макета:
  
  Ландшафтный
  
  /
  
  Портретный
  
  ;
- Масштаб просмотра;
- Цветовая тема.

#### Панель «Компоненты»

На панели компонентов отображаются все доступные в проекте компоненты. Компоненты в списке сгруппированы в соответствии с пространством имен:

Панель «Компоненты» показывает доступные элементы, сгруппированные по пространствам имён; группы можно раскрывать, сверху расположены поиск и фильтр. [Описание иллюстрации](../../raw/figures/59a602d3d589d286b2d10780fd9ac072c787bb0ea1e72c266e7dd83908cb7b39-954cc100fdb242ec.md)

Установка фильтра позволяет отображать только те компоненты, которые доступны для выделенного элемента:

В дереве компонентов формы выбран «ПроизвольныйШаблонФормы». [Описание иллюстрации](../../raw/figures/5d495c71dc2cb1eaf441546fd593a7f6f9c67b6a597146fa97c647ca43631ecf-a9ad5f6d84b8616b.md)

Фильтр по введенной строке позволяет отображать в списке только те компоненты, которые ей соответствуют:

Поиск по введённой строке в панели компонентов сокращает список до совпадающих элементов; совпавшие части названий выделены. [Описание иллюстрации](../../raw/figures/4fd2a5795f9b7b8488f048d46f7ed1efcebf5e5c6a650ff04642d59ba1377f33-dca605bb87ef2179.md)

#### Панель «Данные»

На панели данных отображается информация о данных элемента, к которому относится редактируемая форма. Это могут быть, например, поля записей или табличные части. Также в данной панели отображаются [свойства](form-component-975c31cd89e9.md) редактируемой формы и [свойства](all-project-elements-5977d6a645f5.md) компонентов на ней. От этих свойств может [зависеть](calculated-property-values-for-ui-components-05bce1d1d5e7.md) поведение приложения или изменение данных приложения. Поля и свойства, которые используются в открытом в данный момент в редакторе компоненте, отмечаются зеленой галочкой. В примере ниже на панели данных отображаются реквизиты и свойства справочника **Сотрудники**:



Для выбранного поля данных можно открыть панель свойств. Для выбранного свойства можно открыть панель свойств соответствующего компонента, а также переименовать или удалить это свойство. Можно добавить новое свойство. Кликните правой кнопкой мыши на свойстве, чтобы открыть контекстное меню, и выберите действие (или нажмите на соответствующую клавишу):

В панели «Данные» выбрано свойство «ЛогинНовогоПользователя». [Описание иллюстрации](../../raw/figures/5c843a322c9956f5c317a77ed78462c833d365beeebe4a4eac4893b846405cb2-ebc60a214207c37e.md)

#### Панель «События»

Панель событий содержит описание событий компонента:

Панель «События» показывает события выбранного компонента, в примере ПриУдаленииОбъекта и ПриСозданииОбъекта. [Описание иллюстрации](../../raw/figures/ec9ef07cdd72d6eca8379d71ec0d578455b207e20e0a8f565a33c41e19931248-a1d3089897460412.md)

Поиск по введенной строке позволяет отображать в списке только те события, которые ей соответствуют:

На панели событий в строке поиска введено «Уда»; в списке осталось соответствующее событие ПриУдаленииОбъекта, совпавшая часть имени выделена. [Описание иллюстрации](../../raw/figures/fdeffc89101db20aaf48a784372ecaf6ca8a948f0b89f80f80c854dc6540a06b-96aba1c6c328712a.md)

#### Панель «Команды»

В панели команд отображаются все команды, которые можно использовать в командном интерфейсе компонента:

Панель команд [Описание иллюстрации](../../raw/figures/b4dbb398e62ee4817aa4789a63ce36dabd2a1464884437ddf4254e92dffdeab5-d0c748a6dd4cc0a5.md)

Для добавления команды из панели просто перетащите ее в дерево компонентов:

Команда «Записать» перетаскивается из панели команд в дерево компонентов формы, внутрь фрагмента обычных команд. [Описание иллюстрации](../../raw/figures/df3207dc78b2a733416059cd65a328126479c9e03b80d97f6445724dbc3b7dc0-f45b88393d3f9194.md)

При добавлении команды в дерево компонентов «1С:Предприятие.Элемент» автоматически обернет команду в группу, если это необходимо. Также команды можно обернуть в группу с помощью контекстного меню: **Рефакторинг** ⟶ **Обернуть в группу**.

Команды в панели разделены на следующие группы:

- Стандартные команды
  
  — команды редактируемого компонента (например,
  
  `ЗаписатьИЗакрыть`
  
  ), а также все команды компонентов, объявленных внутри файла компонента (например, команды полей ввода).
- Глобальные команды
  
  — все остальные команды (например,
  
  `ИмяЭкземпляраСущности.ОткрытьФорму`
  
  ).
- Новые команды
  
  — команды, которые можно создать прямо в компоненте (например,
  
  `ОбычнаяКоманда`
  
  ).

Поиск по введенной строке позволяет отображать в списке только те команды, которые ей соответствуют:

Поле поиска команд с введённой частью строки отбирает подходящие команды; в примере видны команды «Записать» и «Записать и закрыть». [Описание иллюстрации](../../raw/figures/3f5f60869d7bab554cb9c9c0a945ca02bc0aa2a729b4f641f710c32c725ce71f-35e17105bb4b81c0.md)

## Нижняя панель

Нижняя панель выглядит следующим образом:

Нижняя панель среды разработки располагается под центральным редактором. [Описание иллюстрации](../../raw/figures/694147ffc2b9dbfce655faf71c384dd34da1961571c169949ccd7795abe5da66-18287121d6215905.md)

Нижняя панель не отображается по умолчанию. Отображается только при открытии одного из следующих представлений или окон:

- Пиктограмма «Проблемы». [Описание иллюстрации](../../raw/figures/77c41c67da140f21d96ce391d2249abe3eb06bc1df068611edf51fdbe309f75d-70cbb98161b373a1.md)
  
  [**Проблемы**](ide-overview-and-basic-actions-969a6e6501a6.md)
  
  ,
- Пиктограмма «Консоль отладки». [Описание иллюстрации](../../raw/figures/10a5363f1265684642795e2bc28836c2a2aec8b702e6ff4b911e5f56f5642181-19860aaf2a0e082f.md)
  
  Консоль отладки
  
  ,
- Пиктограмма «Вывод». [Описание иллюстрации](../../raw/figures/4065d78aa0a1a71dd31fb2aeb83611b814be7e968a5d551e08e925adcaa18b38-674c628808e01ab2.md)
  
  Вывод
  
  ,
- Пиктограмма «Иерархия типов». [Описание иллюстрации](../../raw/figures/53b400e70d153481b84410dcc642ddc58710abaf4e28bc6778d551e136cf2ed5-99101032e09a282b.md)
  
  Иерархия типов
  
  .

### Представление «Проблемы»

Найденные в коде ошибки выводятся в панель **Проблемы**. Список файлов, содержащих ошибки, отображается в соответствии со структурой проекта. Данные файлы также подсвечиваются красным в навигаторе проекта. Для каждой ошибки указывается ее тип, описание и номер строки, в которой она найдена. При нажатии на ошибку нужный файл проекта открывается в [области редакторов](ide-overview-and-basic-actions-969a6e6501a6.md).

Панель «Проблемы» [Описание иллюстрации](../../raw/figures/a44b746fa9e49f46b85bbd229b4a50c41fd1e95145a9518bf437a87bd26b5b70-b3e36465e128952b.md)

Если ошибка найдена не в коде, а в элементе проекта, откроется панель свойств и сам элемент — в навигаторе проекта или в соответствующем редакторе.

Например, если ошибка найдена в свойствах компонента интерфейса, откроется панель свойств и редактор компонентов интерфейса в месте возникновения ошибки.

Ошибка выбрана на панели «Проблемы»; редактор формы и панель свойств открыты на ошибочном компоненте, неверное значение выделено и сопровождается сообщением проверки. [Описание иллюстрации](../../raw/figures/fb55bab8ab216cafca3b4f876012ebd448118cc109e3ea4bd25af2f43a8cb898-0054278c5b25580f.md)

В панели **Проблемы** используется механизм быстрых исправлений — наведите на проблему в списке и «1С:Предприятие.Элемент» предложит вам возможные решения:

Быстрые исправления в панели «Проблемы» [Описание иллюстрации](../../raw/figures/8caac6ba3aaf166a76c1f0cbcfe205bfec8bf444f5044b354f6aa74c196cb2cf-bc78d44bb8970159.md)

Также в верхнем правом углу панели находится набор инструментов:

Набор инструментов в панели «Проблемы» [Описание иллюстрации](../../raw/figures/cf4a220d35e140fdee34a4246ec33329ac0d0f2e68f53ac76c3744f15abc4ec9-cf6f45d48242fd51.md)

Набор инструментов позволяет:

- выполнять поиск по имени файла и тексту ошибки;
- фильтровать список ошибок:
  
  - по типу: ошибки/предупреждения;
  - области видимости: все проекты, редактируемый проект, редактируемая подсистема, редактируемый элемент;
    
    Фильтр панели «Проблемы»: показ ошибок и предупреждений, область видимости «Все проекты», «Редактируемый проект», «Редактируемая подсистема» или «Редактируемый элемент». [Описание иллюстрации](../../raw/figures/ed569f4b2c7433a91913fc0629ba2bbae150df43dda6fcfc77ad56079e8f51cb-29cba3dd7b9e1a03.md)
- сворачивать/разворачивать список ошибок;
- выполнять другие действия, например выгружать список ошибок в файл в формате **.tsv** (текстовом формате для хранения в табличном виде записей, поля которых разделены знаком табуляции):
  
  В меню панели ошибок выбран пункт «Выгрузить в файл»; список ошибок может быть сохранён в формате TSV. [Описание иллюстрации](../../raw/figures/33f1a7f6c68d6bc18906fc617ea092e3e255d68d67c1588380e9edc1df5bc528-35ce2c61772d9a60.md)

## Строка состояния

Строка состояния находится в самой нижней части интерфейса среды разработки. В строке состояния отображается информация о текущем статусе и настройках проекта и приложения.

В общем случае строка состояния выглядит следующим образом:

Размеченная строка состояния среды разработки: слева направо название приложения, ошибки и предупреждения, индикатор разработчиков, копирование ссылки, переключение языка, уведомления. Красные стрелки подписывают назначение соответствующих значков. [Описание иллюстрации](../../raw/figures/4da14f88a7b3df73bcabdb7db35b30956edb2afcafecc1b2a3416b8531e3696e-2628f166f1f55216.md)

Строка состояния содержит следующие индикаторы:

- Значок текущего статуса и название приложения — наведите курсор, чтобы узнать о текущем состоянии приложения; нажмите, чтобы выбрать действие, например
  
  Открыть приложение
  
  или
  
  Опубликовать проект
  
  .
- Количество ошибок/предупреждений — наведите курсор, чтобы получить общую информацию; нажмите — откроется представление
  
  [Проблемы](ide-overview-and-basic-actions-969a6e6501a6.md)
  
  .
- Разработчики — нажмите, чтобы открыть
  
  [список разработчиков](../project/add-developer-f3519932fdbf.md)
  
  проекта, которых можно пригласить для
  
  [совместной разработки](../project/collaborative-development-in-ide-6dac91729e4e.md)
  
  .
- Скопировать ссылку — нажмите, чтобы скопировать ссылку на среду разработки приложения. Данную ссылку можно использовать для приглашения к
  
  [совместной разработке](../project/collaborative-development-in-ide-6dac91729e4e.md)
  
  разработчиков проекта, администраторов
  
  [панели управления](https://1cmycloud.com/console/help/element/10.0/docs/topics/control-panel/)
  
  и администраторов
  
  [пространства](https://1cmycloud.com/console/help/element/10.0/docs/topics/control-panel/#%D0%BF%D1%80%D0%BE%D1%81%D1%82%D1%80%D0%B0%D0%BD%D1%81%D1%82%D0%B2%D0%B0)
  
  .
- Уведомления — наведите курсор, чтобы получить общую информацию; нажмите, чтобы получить подробную информацию. Это может быть, например, дополнительная информация при публикации проекта или во время отладки.

- Переключить язык — нажмите, чтобы изменить язык отображения компонентов интерфейса в окне предпросмотра и значений локализованных строк в панели свойств. Данный индикатор отображается, если в проекте определено более одного
  
  [языка локализации](../project/app-localization-15f5b1317f82.md)
  
  .

Как и написано выше, при нажатии на кнопку открытия/публикации приложения в верхней части области редакторов отобразится диалоговое окно [палитры команд](ide-overview-and-basic-actions-969a6e6501a6.md) для выбора действия:

Выбор действия [Описание иллюстрации](../../raw/figures/b6297fc519d60535f1968b49284eafe0b4e62a527573d5478761f9a792e2f8d0-74484e0306338403.md)

> [!NOTE] примечание
> Обратите внимание, что в большинстве случаев при нажатии на тот или иной индикатор на строке состояния выбор действия осуществляется в палитре команд, которая находится в верхней части области редакторов.

Значок звездочки около имени приложения означает, что есть неопубликованные изменения:



Во время публикации проекта отображаются индикаторы загрузки:

Индикаторы загрузки [Описание иллюстрации](../../raw/figures/b681db10009c62b1bf38f618c97f1a29e345a712bd8df07abe1e1250110ef132-6c5ed9d8b20b4845.md)

### Строка состояния и совместная разработка

При [совместной разработке](../project/collaborative-development-in-ide-6dac91729e4e.md) приложения воспользуйтесь кнопкой **Разработчики**, чтобы пригласить разработчика из [списка разработчиков](../project/add-developer-f3519932fdbf.md) приложения:

В строке состояния раскрыт список разработчиков; у доступного разработчика справа выделен плюс, приглашающий его в совместную разработку. [Описание иллюстрации](../../raw/figures/f84da8b1927b309988490760d2acc13718aabe1e5d61941f29e75e1da57a4fd9-e9366eef5f7916f9.md)

Чтобы скопировать ссылку для доступа к совместной разработке, воспользуйтесь кнопкой **Скопировать ссылку**:

Кнопка «Скопировать ссылку» находится в строке состояния среды разработки и имеет значок цепочки. После нажатия появляется уведомление: «Ссылка скопирована в буфер обмена, теперь можно переслать ее другим разработчикам». Это подтверждает копирование ссылки для совместной разработки. [Описание иллюстрации](../../raw/figures/c5cd8a7a3ef7f97f924397b3cd3a881b19040b0a1dea5958fabb6a6351360865-bde3db9747ae3da9.md)

### Строка состояния и редактор файлов

При работе с редактором файлов в строке состояния отображается дополнительная информация о положении курсора мыши в тексте — строка, столбец:

Строка состояния текстового редактора показывает позицию: «Строка 31, столбец 6».. [Описание иллюстрации](../../raw/figures/116d5b0705effbe7351c4c2d3885a5af4d1ba80af387b71cd963113c463438b7-33cf1c5d86e62469.md)

Нажмите, чтобы ввести номер строки для быстрого перемещения по файлу.

### Строка состояния и нижняя панель

Если открыта [нижняя панель](ide-overview-and-basic-actions-969a6e6501a6.md), то в самой правой части строки состояния отображается дополнительный значок, который позволяет скрыть/отобразить нижнюю панель:

Справа в строке состояния выделен дополнительный значок прямоугольной панели для скрытия или отображения открытой нижней панели. [Описание иллюстрации](../../raw/figures/58b8d939783a0eac8adcfc2275e905deb848c3967aa4b3646e2187000dfb228b-a34a596f6bd29be2.md)

### Строка состояния и отладка

При выборе тех или иных панелей, связанных с [отладкой](../project/start-debugging-d5c5117b447f.md) приложения, отображается дополнительный индикатор — нажмите, чтобы выбрать отладчик:

Индикатор отладки [Описание иллюстрации](../../raw/figures/b6116f83952189af8014ea7cf47968a53b5400b9f4f6cb2924786abeb8c77fb7-47cfff9bd8a8cac0.md)

Оранжевый цвет строки состояния означает, что в данный момент идет процесс отладки:



## Другие панели и окна

### Палитра команд

Из нее у вас есть доступ ко всем функциям среды разработки, включая сочетания клавиш для наиболее распространенных операций:

Палитра команд содержит поиск вверху, команды документации, справки по стандартной библиотеке, запуска отладки, публикации, открытия приложения и управления редактором. [Описание иллюстрации](../../raw/figures/135b0985bdaaea3e80b612bcb9d8d1fead26288a27975e1949121e9ec35a652d-623709f352f5330a.md)

Палитра команд не отображается по умолчанию. Чтобы ее открыть, нажмите Ctrl+Shift+P.

Также палитру команд можно открыть через меню [Управление](ide-overview-and-basic-actions-969a6e6501a6.md):

Меню управления средой разработки содержит «Палитра команд…» с сочетанием Ctrl+Shift+P. [Описание иллюстрации](../../raw/figures/eae90a99858ff471f9efd000eea1d84f4e76dffda2d659694df3a1d8ce0c0ad3-0dda11f54176f5b6.md)

### Сочетания клавиш

Многие действия в среде разработки можно выполнить с клавиатуры с помощью [сочетаний клавиш](../project/keyboard-shortcuts-a9db35885b20.md). Для большинства действий в системе уже подобраны оптимальные и привычные сочетания клавиш, однако при необходимости вы можете задать и свои сочетания.

Чтобы просмотреть полный список горячих клавиш, выберите **Сочетания клавиш** в меню [Управление](ide-overview-and-basic-actions-969a6e6501a6.md) (или нажмите Ctrl+Alt+,):

Команда открытия сочетаний клавиш [Описание иллюстрации](../../raw/figures/9eeb0dc9ef8a5231c02c00078997c0f139de1b3547942876149a7da5f052b407-bb921de5cba2cf04.md)

Откроется список доступных сочетаний клавиш:

Редактор сочетаний клавиш: список команд с назначенным и стандартным сочетанием, условием применения и источником настройки; сверху поиск по командам и сочетаниям. [Описание иллюстрации](../../raw/figures/f66d89c9b36ec91bfda5715ff50a63a4cc3c1308a4b7cd419a74bc982c13994f-c282bb43e83db435.md)

## Настройки отображения и просмотра

### Порядок значков в панелях

Вы можете изменить порядок значков в панелях, просто потянув за значок:



### Редактирование бок о бок

Вы можете одновременно открыть для редактирования столько файлов, сколько хотите: бок о бок по вертикали или по горизонтали.

Предположим, у вас открыты две вкладки с файлами:

В области редакторов одновременно открыты две вкладки файлов; это исходное расположение для примера разделения редакторов. [Описание иллюстрации](../../raw/figures/31719844dd900b33b70a871aed935c821e77f366bbb6b39206643537551a2b23-f7d4fd830415d79b.md)

Потяните за заголовок файла и перемещайте его по горизонтали:



Файлы будут расположены один над другим:



Потяните за заголовок файла и перемещайте его по горизонтали:

Перемещение вкладки файла по горизонтали [Описание иллюстрации](../../raw/figures/baaadbf1c118a0653f8582ad6c8f060e7a9bf99d63d597b88da132edbcdf2cdb-3bb5e549e56f0192.md)

Файлы будут расположены один за другим:

Размещение вкладок файлов друг за другом [Описание иллюстрации](../../raw/figures/8e47ffc4be916d9a706a8b9f241367a8c99800d0611e4d4e6f37576540f263d9-ebdccafee017ee9f.md)

Если у вас уже открыт один файл, есть несколько способов открыть другой сбоку от него:

- Нажмите Ctrl+\, чтобы разделить активный редактор на два. Затем откройте второй файл.
- Чтобы открыть второй файл, нажмите **Открыть сбоку** в его контекстном меню:
  
  Контекстное меню файла в дереве проекта содержит «Открыть в текстовом редакторе» и «Открыть сбоку». [Описание иллюстрации](../../raw/figures/08b536a966fb6d0a075295c49522a1a6bc1ba31809590978b4addfe384f1a8c9-48c2589bf83ae5ce.md)

### Максимизация области редакторов

Когда вы редактируете несколько файлов, есть быстрый способ максимизировать область редакторов, скрыв все остальные части пользовательского интерфейса. Просто дважды кликните на вкладке любого файла (или нажмите **Alt+M**, или нажмите **Переключить открытие панели на весь экран** в контекстном меню вкладки):

В контекстном меню вкладки файла показана команда переключения открытых панелей на весь экран; для неё указано сочетание Alt+M. [Описание иллюстрации](../../raw/figures/3edfef8d4369840851bc15f95892d2d069c9a8c8bcd3a2ff59ed0ecc05448c12-742fc96c3ae5fa7a.md)

Этим же действием вы можете вернуть среду разработки к исходному состоянию.

### Скрытие боковых и нижней панелей

Бывает, редактируя текст, хочется скрыть некоторые панели, чтобы увеличить тем самым область редактирования. Это можно сделать несколькими способами.

Во-первых, можно скрыть обе боковые панели — Alt+Shift+C (в меню **Вид** ⟶ **Вид** ⟶ **Свернуть все боковые панели**):

В меню «Вид» → «Вид» выбрана команда «Свернуть все боковые панели»; для неё указан Alt+Shift+C. [Описание иллюстрации](../../raw/figures/f4b1afcfdc549755e67e054fda358adaec08c1402cb5d21006ec4dadae508a85-517941b30ca12ce6.md)

Во-вторых, можно скрыть только одну из боковых панелей. Для этого достаточно нажать на значок того представления, которое открыто в этой панели:

Скрытие левой боковой панели [Описание иллюстрации](../../raw/figures/a0c5755159210496d26a68cc82b2cc08aeb75d096705ada3851c7061c75cad21-d88eded02b69448b.md)

В-третьих, вы можете скрыть нижнюю панель, нажав на значок **Переключить нижнюю панель** в правой части строки состояния (или Ctrl+J, или в меню **Вид** ⟶ **Вид** ⟶ **Переключить нижнюю панель**):




Важно. [Описание иллюстрации](../../raw/figures/71dbe9b07fe3cd42bb65b7e33266ca0069ef5302c89694fe496757daacbdb59a-b19f1ead6109636d.md)


Примечание. [Описание иллюстрации](../../raw/figures/508a1e0b097e36e9f5cb2bdbb02bb091edf1fb414d57653b605c63d2fbe63d1c-d699901424a4d7be.md)

## See Also

- [Навигатор раздела](overview.md)
- [Тип компонента, экземпляр и наследование](component-model.md)
- [Выбор компонентов для формы](component-choice.md)
- [Вычисляемые свойства и связи интерфейса](computed-properties-and-bindings.md)
- [События компонентов и обработчики](events-and-handlers.md)
- [Маршрут: таблица и динамический список](table-and-dynamic-list.md)

Оригинал: [Обзор интерфейса и основных действий в среде разработки](https://1cmycloud.com/console/help/element/10.0/docs/topics/ide-overview-and-basic-actions/).
