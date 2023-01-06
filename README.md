![Картинка]([https://downloader.disk.yandex.ru/preview/85039bff50d652695a7dce86426d8a3176b4d19ee6b8b3ae823f620ba0b4026c/63ae04b5/KniNQVNcyYLVfZFvpQk_VgG2PAPs_V_NyMvD6kRO9adqKQLh_8WgWDbZU9yCESPGclF-MWsaTpV9dUalnW42Bw%3D%3D?uid=0&filename=JVM.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=0&tknv=v2&size=1360x625](https://4.downloader.disk.yandex.ru/preview/bd8e9c1a48148fee6be3dd12b15050b733c7e9a61b01c996607abf523bb528b1/inf/KniNQVNcyYLVfZFvpQk_VgG2PAPs_V_NyMvD6kRO9adqKQLh_8WgWDbZU9yCESPGclF-MWsaTpV9dUalnW42Bw%3D%3D?uid=590122284&filename=JVM.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=590122284&tknv=v2&size=1343x568))

1. Подается сигнал в ClassLoading на загрузку класса JvmComprehension 
2. Класс JvmComprehension загружается в область памяти Metaspace
3. Подается сигнал в ClassLoading на загрузку класса printAll
4. Класс printAll загружается в область памяти Metaspace
5. Сборщик мусора проверяет heap и удаляет объект uselessVar так как она нигде не используется
