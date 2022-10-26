# A2LibraryForAX
Library for using with A2 via CiA402. For now contains enum for converting error codes read form servodrives to messages. Message contains - error info from manual and errorcode.

![obraz](https://user-images.githubusercontent.com/109360131/197764592-d1880a21-c5f3-4f71-b352-4ae9b6315341.png)

To use the enum - read P0-01 via PDO and map there variable of type DriveA2Error from library

![obraz](https://user-images.githubusercontent.com/109360131/197767818-4741793f-7a66-48f0-9a0c-0fa81d4f2e97.png)

EDIT 26.10 - included attribute to_string. Nowe ENUM message can be converted directly to STRING:
![obraz](https://user-images.githubusercontent.com/109360131/198029355-3d454996-e878-4206-ba16-de4114a58191.png)
![obraz](https://user-images.githubusercontent.com/109360131/198030269-84007296-a901-4069-970b-94cb028a21c2.png)
![obraz](https://user-images.githubusercontent.com/109360131/198030322-35209d99-d0b4-40ce-ab61-8fbf48df528b.png)
