Mars Photos
==================================

La aplicación Mars Photos es una aplicación de demostración que muestra imágenes reales de la superficie de Marte. Estas imágenes son fotos reales de Marte capturadas por los exploradores de la NASA. Los datos se almacenan en un servidor web como un servicio web REST.

Esta aplicación demostró el uso de [Retrofit](https://square.github.io/retrofit/) para realizar solicitudes REST al servicio web, [kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization) para gestionar la deserialización del JSON devuelto a objetos de datos Kotlin, y [Coil](https://coil-kt.github.io/coil/) para cargar imágenes por URL.