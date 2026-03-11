# 🪙 Conversor de Monedas - Challenge Backend

Una aplicación de consola en Java que realiza conversiones de divisas en tiempo real consumiendo la API REST de ExchangeRate. Este proyecto forma parte de los desafíos prácticos de formación en desarrollo Backend.

## 🛠️ Características Principales
* **Conexión HTTP en tiempo real:** Consume datos actualizados directamente desde una API externa.
* **Deserialización de JSON:** Utiliza la librería **Gson** para mapear la respuesta de la API a un `Record` inmutable de Java.
* **Arquitectura Segura:** La API Key está protegida mediante el uso de **Variables de Entorno**, evitando exponer credenciales en el código fuente.
* **Manejo de Excepciones:** Implementa bloques `try-catch` para evitar fallos por tensión cortante en la ejecución (ej. si el usuario ingresa letras en lugar de números).

## 💻 Tecnologías Utilizadas
* **Lenguaje:** Java
* **Librerías:** `java.net.http.HttpClient`, `com.google.gson.Gson`
* **Control de Versiones:** Git y GitHub

## 🚀 Cómo ejecutar el proyecto
1. Clona este repositorio en tu máquina local.
2. Configura tu propia API Key de [ExchangeRate-API](https://www.exchangerate-api.com/) como una variable de entorno llamada `EXCHANGE_API_KEY`.
3. Ejecuta la clase `Principal.java` desde tu entorno de desarrollo.