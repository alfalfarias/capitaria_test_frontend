# Capitaria Test Frontend

Construya una función o clase en JS que recibiendo el siguiente JSON por
parámetro, permita renderear una agenda semanal en html y con bloques de
30 minutos como la siguiente:

```
{
    "monday": [
        {"name": "Jorge", "start_time": "08:00", "end_time": "09:00"},
        {"name": "Jorge", "start_time": "09:30", "end_time": "11:00"},
        {"name": "Jorge", "start_time": "15:00", "end_time": "16:00"},
        {"name": "Jorge", "start_time": "17:00", "end_time": "19:30"}
    ],
    "tuesday": [
        {"name": "Jorge", "start_time": "08:00", "end_time": "09:00"},
        {"name": "Jorge", "start_time": "11:30", "end_time": "12:00"},
        {"name": "Jorge", "start_time": "15:00", "end_time": "16:00"},
        {"name": "Jorge", "start_time": "17:00", "end_time": "19:30"}
    ],
    "wednesday": [
        {"name": "Jorge", "start_time": "08:00", "end_time": "09:00"},
        {"name": "Jorge", "start_time": "10:30", "end_time": "12:00"},
        {"name": "Jorge", "start_time": "15:00", "end_time": "16:00"},
        {"name": "Jorge", "start_time": "17:00", "end_time": "19:30"}
    ],
    "thursday": [
        {"name": "Jorge", "start_time": "08:00", "end_time": "09:00"},
        {"name": "Jorge", "start_time": "09:30", "end_time": "12:00"},
        {"name": "Jorge", "start_time": "15:00", "end_time": "16:00"},
        {"name": "Jorge", "start_time": "17:00", "end_time": "19:30"}
    ],
    "friday": [
        {"name": "Jorge", "start_time": "08:00", "end_time": "09:00"},
        {"name": "Jorge", "start_time": "09:30", "end_time": "12:00"},
        {"name": "Jorge", "start_time": "15:00", "end_time": "16:00"},
        {"name": "Jorge", "start_time": "17:00", "end_time": "19:30"}
    ]
}
```

![Calendar](https://user-images.githubusercontent.com/1144473/124043631-66289b80-d9d9-11eb-9cf1-b9e1ebbcb103.png)


La agenda debe contener los distintos bloques y pintar con el nombre del
paciente, las horas que están tomadas.

**Nota:**

* La agenda NO debe tener interacción solo dibujarse en la pantalla
* No utilizar tablas, sólo DIVS
* La agenda debe tener un ancho de 960px y esta centrada en la pantalla
* Puntos extras usar CSS3 sin librerias externas


# Consideraciones de la prueba

* Se valora el uso de Git.
* Se debe enviar repositorio con el proyecto.
* dudas y consultas a traves de Getonboard
