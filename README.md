# Delta Electronics library for AX PLCs, Motion Controllers and AS series PLCs
Library that allows using for simple usage of Delta electronics drives in CODESYS or ISPSoft (AS or AH) based PLCs. Library delivers enumarations, that handles converting error codes to strings messages.

## CODESYS based PLCs
Three enumartions are included for handling A2 errors, VFD errors and VFD warning.

![obraz](https://user-images.githubusercontent.com/109360131/200522222-afd24199-7b09-4127-b558-f1dcbab2f62f.png)
![obraz](https://user-images.githubusercontent.com/109360131/197764592-d1880a21-c5f3-4f71-b352-4ae9b6315341.png)

To use the enum - read P0-01 via PDO and map there variable of type DriveA2Error from library

![obraz](https://user-images.githubusercontent.com/109360131/197767818-4741793f-7a66-48f0-9a0c-0fa81d4f2e97.png)

Enum message can be directly converted to string, due to attribute to_string usage:

![obraz](https://user-images.githubusercontent.com/109360131/198029355-3d454996-e878-4206-ba16-de4114a58191.png)
![obraz](https://user-images.githubusercontent.com/109360131/198030269-84007296-a901-4069-970b-94cb028a21c2.png)
![obraz](https://user-images.githubusercontent.com/109360131/198030322-35209d99-d0b4-40ce-ab61-8fbf48df528b.png)

## ISPSoft based PLCs\
Three enumartions are included for handling A2 errors, VFD errors and VFD warning.
![obraz](https://user-images.githubusercontent.com/109360131/200522436-6ed246c2-53a1-4afe-afdc-5ae6a23ef72c.png)

To use the enum - read P0-01 via any communication and map there variable of type DriveA2Error from library.

Due to ISPSoft limit of characters of single enum entry is limited to 40, error messages are shorter, than in CODESYS library to fit the ISPSoft limit. Library uses abbreviations and skips certain words of message, that are unnecessary for message understanding, ie. article "the".
