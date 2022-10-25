# A2LibraryForAX
Library for using with A2 via CiA402. For now contains enum for converting error codes read form servodrives to messages. Message contains - error info from manual and errorcode.

![obraz](https://user-images.githubusercontent.com/109360131/197764592-d1880a21-c5f3-4f71-b352-4ae9b6315341.png)

To use the enum - read P0-01 via PDO and map there variable of type DriveA2Error from library

![obraz](https://user-images.githubusercontent.com/109360131/197767818-4741793f-7a66-48f0-9a0c-0fa81d4f2e97.png)
