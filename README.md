
## ✨ Ideas para el proyecto 
Mi proyecto trata de una Wiki sobre *Call Of Duty* donde los usuarios pueden crear artículos de mapas y armas, les pueden poner su información, imagen, y el juego/s al que pertenecen.

Los usuarios tienen roles y según el que tienen pueden hacer:

• <span style="color:gold"><strong>Moderador</strong></span>: Puede crear, editar y eliminar artículos de armas y mapas. Además, tiene acceso al gestor de usuarios, donde puede cambiar roles y eliminar comentarios.

• <span style="color:green"><strong>Autentificado</strong></span>: Puede visualizar los mapas, armas y juegos, pero no tiene permisos para crear, editar o eliminar contenido. Sin embargo, puede participar en los foros dentro del apartado de juegos.

• <span style="color:red"><strong>Baneado</strong></span>: Solo puede visualizar el contenido. Este rol se asigna a usuarios que han cometido infracciones en la página.


## ✅Objetivos del Proyecto✅

Este proyecto tiene como objetivo proporcionar información sobre la franquicia de Call of Duty y mantener en contacto a los usuarios a través de los foros. Además los que sean moderadores pueden mantener actualizada esta Wiki.


## ⚙️Tecnologías Utilizadas⚙️
### 🖥️ Backend 🖥️

La Wiki presenta dos backend disponibles cada uno con su base de datos, por lo que son “dos wikis en una”, estos son:

🛠️  <strong>Strapi:</strong> API Rest conectada a una base de datos <span style="color:#DAA520;"><strong>PostgreSQL</strong></span> (proporcionada por Render), también proporciona un sistema de autentificación y está hosteada por Render aunque se puede ejecutar en local. Para las imágenes se utiliza <span style="color:#9932CC;"><strong>Cloudinary</strong></span>.

🔥 <strong>Firebase:</strong> Servicio que proporciona una base de datos <span style="color:#FF4500;"><strong>Firestore</strong></span> y un sistema de autentificación <span style="color:#32CD32;"><strong>Firebase Auth</strong></span>. Para las imágenes se utiliza <span style="color:#4169E1;"><strong>Firebase Storage</strong></span>.

---
### 💻 Frontend 💻

La Wiki está disponible como página web y como aplicación móvil android, se ha desarrollado en dos entornos diferentes para lograr esto:

🌐 <strong>Ionic + Angular:</strong> Proyecto web hecho con estos dos frameworks de <strong>TypeScript</strong>, con el que se proporciona así la página web y también, gracias a la librería <strong>Capacitor</strong>, una aplicación Android.

📱 <strong>Android Studio:</strong> Proyecto hecho en este entorno con el lenguaje <strong>Kotlin</strong> con el que se proporciona otra aplicación Android pero totalmente enfocada al uso móvil.

---
### 🧠 Miscelánea 🧠

🐍 <strong>API de Python:</strong> Elaborada para crear una <span style="color:#1E90FF;"><strong>IA de traducción</strong></span> utilizando la librería <span style="color:#32CD32;"><strong>Google Translator</strong></span> para que la página web pueda traducir ciertos datos (comentarios del foro y descripciones de mapas) que son datos proporcionados por el backend.

🐍 <strong>2º API de Python:</strong> Elaborada para proporcionar un sistema de <span style="color:#8B008B;"><strong>transformación</strong></span> de ficheros <span style="color:#FF4500;"><strong>JSON</strong></span> a <span style="color:#228B22;"><strong>CSV</strong></span> de los datos de las armas, mapas, juegos, comentarios y usuarios de la página web.

🎮 <strong>Unity:</strong> <span style="color:#DAA520;"><strong>Videojuego 3D muy simple</strong></span> hecho con esta herramienta y el lenguaje <span style="color:#800000;"><strong>C#</strong></span>, con la temática de la página.









## 🎮 TFG - Call of Duty 🎮
- ⚙️ Enlace al Anteproyecto en Notion: [Aquí](https://www.notion.so/Call-of-Duty-Wiki-1c1cdd00abd78057b05fc2246505e70c?pvs=4)
- 📹 Enlace al vídeo Checkpoint: [Aquí](https://youtu.be/TB4tGpxZSS0)
<br/>

## 📤 Repositorios 📤
- 🌐 Call of Duty - Versión Ionic: [Aquí](https://github.com/PaulaAtencia/Ionic_CallofDuty)
- 📱 Call of Duty - Versión Android Studio: [Aquí](https://github.com/PaulaAtencia/Kotlin_CallofDuty)
- 📫 Servicio Strapi: [Aquí](https://github.com/PaulaAtencia/Strapi_CallofDuty)
- 🐍 CoD Utils - Librerías Python: [Aquí](https://github.com/PaulaAtencia/callofduty-utils-fastapi)
- 🎮 Shot Of Duty - Juego en Unity: [Aquí](https://github.com/PaulaAtencia/Shot-Of-Duty)
<br/>

## 📱 APK's 📱
> [!NOTE]
> Estos enlaces siempre son a la versión más reciente sacada
- APK de la versión de **Android Studio**: [Aquí](https://drive.google.com/file/d/1n2PIK21sR6uKFkizzUphCbhvN9T0rbtK/view?usp=sharing)
- APK de la versión de **Capacitor + Ionic**: [Aquí]()
<br/>

## 🌐 Netlify 🌐
> [!IMPORTANT]
> **Para acceder a la versión de Ionic online subida a Netlify debes usar el enlace que hay disponible en el repositorio de la Versión Ionic.**
