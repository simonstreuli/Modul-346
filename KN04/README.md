# KN04

## A

## Objekte in S3-Bucket

<img src="./images/Screenshot%202023-09-22%20132708.png">

## Bild im Web

<img src="./images/web-photo.png">

## [Cloud-Init für Web-Instanz](./cloud-init-web.yaml)

<img src="./images/imagephp.png">

## C

<img src="./images/volumes.png">

## D

|                          | Typ  | Persistenz |
| ------------------------ | ---- | ---------- |
| EBS Root                 | hot  | nein       |
| EBS Zusätzliches Volumen | hot  | ja         |
| S3                       | warm | ja         |

Erklärung: ESB Root ist hot, da dort das Betriebssystem liegt und es stetig verwendet wird. EBS Zusätzliches Volumen ist warm, da es Daten drauf gespeichert hat, die nicht archiviert werden, aber auch nicht durchgehend verwendet werden. Bei S3 kann man als warm und cold bezeichnen, da man Daten archivieren kann, aber sie auch verwenden kann.
