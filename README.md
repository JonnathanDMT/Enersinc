## Información recopilada a traves de la API

Para desarrollar la segunda parte de la prueba correspondiente a un proceso ETL utilizamos la API de Twitter, a través de la página https://developer.twitter.com/en/docs/twitter-api, donde ingresamos con nuestro usuario y creamos un proyecto en el dashboard para solicitar las credenciales necesarias para autenticarnos a través de Python. Con el objetivo de extraer datos de nuestra preferencia, realizamos las peticiones necesarias y se conformo un dataset con un total de 150 registros.

Estos registros están distribuidos inicialmente en 10 columnas donde se recopilo información de los tweets más recientes proveniente de las cuentas que soy seguidor.

De cada uno de los tweets se extrajo la información mas importante y relevante para nuestro análisis las cuales se mencionan y detallan a continuación:

- ***Date and Time:*** Almacena la fecha y hora de la realización del tweet.
- ***User:*** Almacena el nombre del usuario que realiza el tweet.
- ***Followers:*** Almacena la cantidad de usuarios que siguen la cuenta que realiza el tweet.
- ***Following:*** Almacena la cantidad de usuarios que sigue la cuenta que realiza el tweet.
- ***Total Tweets:*** Almacena la cantidad total de tweets realizados por el usuario desde la creación de la cuenta.
- ***Tweet:*** Almacena el tweet realizado por el usuario.
- ***Language:*** Almacena el idioma en el cual fue escrito el tweet.
- ***Likes:*** Almacena la cantidad de *“likes”* del tweet.
- ***Retweets:*** Almacena la cantidad de *“retweets”* del tweet.
- ***Verified account:*** Almacena un valor booleano donde el valor *“True”* corresponde a una cuenta verificada y *“False”* a una cuenta no verificada.

Una vez conformado el dataset con los 150 registros se realizó el resto del proceso ETL solicitado en el documento de la prueba.
