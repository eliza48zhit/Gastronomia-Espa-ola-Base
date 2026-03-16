🇪🇸 Gastronomía Española - Smart Contract (Base Mainnet)
Este contrato inteligente representa una evolución técnica significativa en mi colección de gastronomía on-chain. Desplegado en la red Base, este proyecto no solo almacena información, sino que gestiona un historial numerado y permite la interacción social mediante un sistema de "Me gusta".

🔗 Verificación en Basescan

El contrato ha sido verificado satisfactoriamente, lo que permite una transparencia total y la posibilidad de interactuar con las funciones de lectura y escritura directamente desde el explorador.

Contract Address: 0xca314a4a2b4666e572b226e0fbfdf0087c3c7b72

Explorer Link: https://basescan.org/address/0xca314a4a2b4666e572b226e0fbfdf0087c3c7b72#code

🛠️ Detalles Técnicos y Evolución

A diferencia de los contratos anteriores, esta versión implementa:

Estructuras Complejas (struct): Cada plato es un objeto que contiene nombre, descripcion y un contador de likes.

Historial Permanente (mapping): Los platos no se sobrescriben. Cada nuevo registro se guarda con un ID único (1, 2, 3...), creando un archivo histórico de la cocina española.

Interactividad (Likes): Los usuarios pueden participar activamente dando "Me gusta" a sus platos favoritos.

Seguridad de Datos: Se mantiene el límite de 200 caracteres para optimizar el almacenamiento y el consumo de gas.

📖 Manual de Usuario On-Chain

Consultar el Menú: Usa la función consultarPlato e ingresa un número (empezando por el 1 para la Tortilla de Patatas) para recuperar los datos.

Añadir al Historial: Usa registrarPlato para inmortalizar una nueva receta (ej. "Gazpacho", "Sopa fria de tomate y hortalizas").

Votar: Usa darLikeAlPlato con el ID correspondiente para aumentar su popularidad.

🐈 Nota de Autoría
"Este contrato es como una biblioteca donde cada plato tiene su propio estante. Programado entre lecturas y la compañía de mi gato, buscando que la tecnología refleje el orden y la belleza de nuestra cultura."net
