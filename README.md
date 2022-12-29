![Картинка](https://downloader.disk.yandex.ru/preview/85039bff50d652695a7dce86426d8a3176b4d19ee6b8b3ae823f620ba0b4026c/63ae04b5/KniNQVNcyYLVfZFvpQk_VgG2PAPs_V_NyMvD6kRO9adqKQLh_8WgWDbZU9yCESPGclF-MWsaTpV9dUalnW42Bw%3D%3D?uid=0&filename=JVM.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=0&tknv=v2&size=1360x625)

1. Подается сигнал в ClassLoading на загрузку класса JvmComprehension 
2. Класс JvmComprehension загружается в область памяти Metaspace
3. Подается сигнал в ClassLoading на загрузку класса printAll
4. Класс printAll загружается в область памяти Metaspace
5. Сборщик мусора проверяет heap и удаляет объект uselessVar так как она нигде не используется