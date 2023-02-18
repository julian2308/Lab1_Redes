# Laboratorio 1. Redes y comunicación de datos.

## Presentado por: Julián David Alvarado, Julián Camilo Durán y Julian Andrés Pinilla.

### INTRODUCCIÓN.
En el mundo contemporáneo, estamos acostumbrados a estar interconectados con cualquier persona, en cualquier parte del mundo, y no solo con una persona en específico, también fuentes de información de infinitos temas. Al comprender lo importante que significa las redes y la comunicación de información y datos a través del mundo, nos adentraremos en comprender cuales son los procesos específicos, cuáles son las relaciones entre ellos para el funcionamiento y que es necesario para que estos procesos ocurran para que cualquier familia pueda conectarse a una página web, desde su laptop o su dispositivo móvil. Un ejemplo de esto es el siguiente:

Carlos Ronaldo vive con su familia en su casa en Bogotá, se mudaron recientemente y desean montar su red de área local para permitir el acceso a la página web de la universidad de su hija, la cual la podemos encontrar en cualquier navegador con la url www.cisco.com, adicional a esto, Carlos Ronaldo desea tener acceso a internet con el resto de dispositivos de su casa, para este problema planteamos la siguiente solución.

Se plantean unos nodos terminales que se conectarán un Router Wireless, este router está a su vez conectado a un Modem principal que es el que se encarga de realizar la conexión a la nube, y posteriormente esta se conecta al servidor donde se encuentra alojada la página web a la que queremos acceder; con los nodos terminales ubicados se decidió realizar una topología de estrella, centrada en el ruter inalámbrico, el computador de mesa conectado mediante cable de cobre común y corriente, y los otros dos dispositivos mediante Wi-Fi, posterior a esto se conectó el router al modem también por cable de cobre, y el modem fue conectado directamente a internet mediante un cable coaxial, finalmente se comunica el internet con el servidor mediante un cable de cobre.

### PROTOCOLOS EVIDENCIADOS.
* HTTP: "Es el nombre de un protocolo el cual nos permite realizar una petición de datos y recursos, como pueden ser documentos HTML" [1].
* DNS: corresponde a las siglas en inglés de "Domain Name System", es decir, "Sistema de nombres de dominio". Este sistema es básicamente la agenda telefónica de la Web que organiza e identifica dominios. estas siendo protocoles de la capa de aplicación en el proceso de encapsulamiento y des encapsulamiento de datos [2].
* TCP: TCP (Protocolo de Control de Transmisión, por sus siglas en inglés Transmission Control Protocol) es protocolo de red importante que permite que dos anfitriones (hosts) se conecten e intercambien flujos de datos, este siendo el protocolo de la capa de tranporte [3].
* IP: Protocolo de internet, que permite identificar un dispositivo en una red, siendo el Router el generador de esa IP, y ese router asigna a cada dispositivo conectado a la red su propia IP a través del protocolo [4].
* DHCP: (Protocolo de configuración dinámica de host) o también conocido como «Dynamic Host Configuration Protocol« , asignando las direcciones lógicas de cada dispositivo, al ser la capa de red en el modelo TCP/IP [5].

La solución implementada funciona bajo la arquitectura cliente-servidor, siendo los dispositivos de la casa el cliente, y el servidor que contiene la página web el servidor, el cliente realiza la solicitud al servidor, esto mediante escribir la url y buscar, esta petición es enviada através de toda la red diseñada, y llega al servidor, el cual al poseer las respectivas características de la URL buscada, devuelve una respuesta, en esta caso es el documento HTML que se visualiza [6].

### ELEMENTOS UTILIZADOS:
* WRT300N.
* PC.
* Laptop.
* Smart Phone.
* Server.
* PT-Cloud.
* Cable Modem.
* Cable coaxial.
* Cable de cobre.

#### Diseño lógico
[![esto.png](https://i.postimg.cc/1td033Z2/esto.png)](https://postimg.cc/gXvLMdjH)

#### Diseño físico
[![Disenio.png](https://i.postimg.cc/KYNJxbjh/Disenio.png)](https://postimg.cc/hJX91HV2)

### RETOS.
No teníamos mucha idea de por dónde comenzar, incluso en un principio pensamos que era replicar lo que vimos en una de las actividades del curso de introducción a Cisco Packet Tracer, fue una gran decepción ver que al introducir la URL no nos redirigía al sitio web. Al principio fue un poco complejo dividir cómo íbamos a realizar la practica, pero en cuanto nos sentamos a hablarlo salió de una forma bastante limpia. Queremos recalcar como mayor desafio de entendimiento la parte de DHCP, fue algo que costó demasiado, pero que logramos reforzar de una gran forma.

### CONCLUSIÓN:
Es un laboratorio que realmente nos da una introducción a las redes, y lo complejas que pueden llegar a ser, aclara muchas dudas y confusiones que son bastante comunes, como las diferencias entre el router, modem, tecnología wireless entre otras. También ayuda a evidenciar el complejo proceso por el cuál debe pasar cualquier tipo de mensaje. De la misma forma, fue bastante satisfactorio cómo poco a poco estas dudas iban siendo un poco más claras, realmente al momento de poner en práctica los conceptos teóricos ayuda mucho la compresión, entendimiento y apropiación de estos, y áun más trabajándolo en equipo, lo cuál facilitó muchísimas tareas. Queremos recalcar que la definición de algunos conceptos, por ejemplo los protocolos, decimos tomarlos de estas páginas en específico, debido a que es documentación de desarrollo oficial.

### REFERENCIAS:
* [1] Fragmento todo de: "https://developer.mozilla.org/es/docs/Web/HTTP/Overview"
* [2] Fragmento todo de: "https://developer.mozilla.org/es/docs/Glossary/TCP"
* [3] Fragmento todo de: "https://support.google.com/a/answer/48090?hl=es-419#:~:text=DNS%20corresponde%20a%20las%20siglas,que%20organiza%20e%20identifica%20dominios."
* [4] Fragmento todo de: "https://www.avast.com/es-es/c-what-is-an-ip-address"
* [5] Fragmento todo de: "https://www.redeszone.net/tutoriales/internet/que-es-protocolo-dhcp/"
* [6] https://developer.mozilla.org/es/docs/Learn/Server-side/First_steps/Client-Server_overview



