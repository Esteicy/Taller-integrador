# Sistema de transmision/comunicación de datos basado en APRS

Este repositorio demuestra la implantación de los sistemas APRS, LoRa y Meshtastic. Estas tecnologías ofrecen nuevas aplicaciones al mejorar la conectividad y la eficiencia de la transmisión de datos. Para evaluar su funcionalidad, el dispositivo de seguimiento debe tener la capacidad de visualizar y transmitir datos a las puertas, lo que se facilita utilizando sitios web APRS.

Como modelo al código utilizado se hizo uso del repositorio de github del richonguzman/LoRa\_APRS\_Tracker.

Para la manipulación e integración al modulo se hizo uso de la bblioteca PlatformIO. El cambio realizados al codigo se detalla en la siguiente figura.

![CodigoTRACKER](https://github.com/Esteicy/Taller-integrador/assets/110202568/fd1fa82d-939b-4594-9a17-52e4f2ebfe45)

Una vez compilado e integrado el codigo al tracker, se puede iniciar con la pruebas de envio de información y visualización del dispositivo en los sitios aprs.fi o aprsdirect.de.Los resultados se muestran a continuación.

![Sirve](https://github.com/Esteicy/Taller-integrador/assets/110202568/a563797b-5d6c-48f6-b805-2ed0551c0ddb)
![Prueba 1](https://github.com/Esteicy/Taller-integrador/assets/110202568/6bfac590-1673-4083-b64f-fc50a676f8c1)
![Prueba 2](https://github.com/Esteicy/Taller-integrador/assets/110202568/7d720e7c-ea54-4774-bb83-ba469cac179c)

Una vez que el dispositivo se encuentra en un radio cercano a algún gate se da la transmisión, la cuál permite el envío de paquetes, esto queda registrado en el equipo, la cuál muestra en la línea de $last Rx$ el último transmisor al que logró enviar un mensaje de forma exitosa, esta transmisión también es visible por medio de la aplicación en línea.

![dATOS](https://github.com/Esteicy/Taller-integrador/assets/110202568/02499f70-ea7f-420b-bc71-7b7075debc8f)


____________________________________________________

