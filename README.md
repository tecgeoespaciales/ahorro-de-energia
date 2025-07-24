
# Modulo de ahorro para sensores

Implementacion de un microcontrolador de bajo consumo y bajo costo (pic 16f628a) para el control de activacion de sensores basado en tiempo con el apoyo de un mosfet para encender y apagar el sistema principal, segun hoja de datos, el consumo del pic usando reloj interno de bajo poder (LP) es de 32uA

en PB0 se implemente el Gate de MOSFET

en PA5 se implementa entrada de activacion desde el microcontrolador

no se implementa reloj externo


# Diagrama Cicuital


![Diagrama Circuital](Diagrama.png)

# Instalación driver prolific

Para descargar los programas y los controladores necesarios, por favor accede al enlace  [Recursos K150](https://blog.uelectronics.com/wp-content/uploads/2024/02/Recursos-Programador-K150.zip). Posteriormente sigue los siguientes pasos:

1. Una vez descargado el archivo .ZIP, descomprímelo y procede a instalar el controlador PL2303_Prolific en tu PC. Este controlador es compatible con sistemas operativos Windows 7, 8, 10 y 11.

En el siguiente GIF podrás ver los pasos de instalación:

![Instalar Driver](Instalar_driver.gif)
