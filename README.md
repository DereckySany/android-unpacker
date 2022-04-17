# Android-Unpacker

### Android Unpacker apresentado no Defcon 22: Android Hacker Protection Level 0

## Conteúdo
- AHPL0 
-> Android Hacker Protection Level 0 + alguns slides de blackphone.
- gdb-scripts 
-> script Bash para descompactar bangcle/secshell; requer `gdb/adb`.
- native-unpacker 
-> Unpacker para APKProtect/Bangcle/LIAPP/Qihoo Packer que roda nativamente, sem dependência de `gdb`.
- hide-qemu 
-> Pequenos hacks para esconder o qemu/debuggers, especificamente do APKProtect.
- corellium-android-unpacking 
-> Uma abordagem mais realista para descompactar coisas, dinamicamente e com automação em torno disso.

## Isenção de responsabilidade
Esta apresentação e código destinam-se apenas para fins de educação e pesquisa. Faça o que quiser com isso, mas aceite toda e qualquer responsabilidade por suas ações. As ferramentas foram criadas especificamente para auxiliar na reversão e análise de malware.

`tenha cuidado`.

## License

    Copyright 2014-2020 Tim 'diff' Strazzere <diff@protonmail.com>

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
