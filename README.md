![Картинка](https://s785sas.storage.yandex.net/rdisk/fae194ec7a2d2a119cfbeb4cc91f71e774b598215a39b7ba9f230e141141c130/63b89551/mg-pKyAwQAYQcuqgo_vNA7uK3aSQs9N9ASCkECLJ2OiEjkQTheOy3PCccB88OYlwGu6hyNfncsprjJfsVpf6Pg==?uid=590122284&filename=JVM.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=590122284&fsize=32326&hid=0bcda62155975bb1375c0b5a607599a6&media_type=image&tknv=v2&etag=c3885750df2be572b0d7083268c59ad9&rtoken=BOoWiHYv6XWu&force_default=yes&ycrid=na-b1cc986dd7bfe62f9c53b1788a83c01a-downloader22h&ts=5f19f44633640&s=e7bfbfdad98f353ffe7f66e764b1621fda8eb4e4e4563373a8138853ee95ff82&pb=U2FsdGVkX1-iAhwpGOz2qjzrNzs0Mwrwbhq1DPtlbQngkl7wQ3Jx_rZ20ErD9B-fHL-0iHAXlW6oMMEn0rxgbT8D7ZCX3S7yE61U09bjEgQ)

1. Подается сигнал в ClassLoading на загрузку класса JvmComprehension 
2. Класс JvmComprehension загружается в область памяти Metaspace
3. Подается сигнал в ClassLoading на загрузку класса printAll
4. Класс printAll загружается в область памяти Metaspace
5. Сборщик мусора проверяет heap и удаляет объект uselessVar так как она нигде не используется
