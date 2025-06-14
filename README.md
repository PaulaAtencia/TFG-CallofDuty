
## ✨ Ideas para el proyecto ✨
Mi proyecto trata de una Wiki sobre *Call Of Duty* donde los usuarios pueden crear artículos de mapas y armas, les pueden poner su información, imagen, y el juego/s al que pertenecen.

Los usuarios tienen roles y según el que tienen pueden hacer:

• <span style="color:gold"><strong>Moderador</strong></span>: Puede crear, editar y eliminar artículos de armas y mapas. Además, tiene acceso al gestor de usuarios, donde puede cambiar roles y eliminar comentarios.

• <span style="color:green"><strong>Autentificado</strong></span>: Puede visualizar los mapas, armas y juegos, pero no tiene permisos para crear, editar o eliminar contenido. Sin embargo, puede participar en los foros dentro del apartado de juegos.

• <span style="color:red"><strong>Baneado</strong></span>: Solo puede visualizar el contenido. Este rol se asigna a usuarios que han cometido infracciones en la página.

<br/>

## ✅ Objetivos del Proyecto ✅

Este proyecto tiene como objetivo proporcionar información sobre la franquicia de Call of Duty y mantener en contacto a los usuarios a través de los foros. Además los que sean moderadores pueden mantener actualizada esta Wiki.

<br/>

## ⚙️ Tecnologías Utilizadas ⚙️
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

<br/>

## 📎 Interfaces 📎

Todas las cosas de Interfaces está en Google Drive, la documentación de cada proyecto está en su respectivo repositorio.
- [Aquí](https://drive.google.com/drive/folders/1qUsfz2RvRiad_g2wtNq5wQ2q6ZZ1-aDt?usp=drive_link)
> [!NOTE]
> **¿Tienes dudas?**  
> No te preocupes, **todo está explicado en el Drive**.

<br/>

---

<br/>

## 🎮 TFG - Call of Duty 🎮
- ⚙️ Enlace al Anteproyecto en Notion: [Aquí](https://www.notion.so/Call-of-Duty-Wiki-1c1cdd00abd78057b05fc2246505e70c?source=copy_link)
- 📹 Enlace al vídeo Checkpoint: [Aquí](https://youtu.be/TB4tGpxZSS0)
- 🌐 Enlace al vídeo Tutorial de Ionic: [Aquí](https://youtu.be/0CNympc3CYM)
- 📱 Enlace al vídeo Tutorial de Android: [Aquí](https://youtu.be/78OuiN9JQYA)
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
- APK de la versión de **Android Studio**: [Aquí](https://drive.google.com/file/d/1izMRuY_5V9BO5KFLTZ6sWRWtVI1yB00L/view?usp=sharing)
- APK de la versión de **Capacitor + Ionic**: [Aquí](https://drive.google.com/file/d/1Zn4mGwf5thCwKKIdZ1sCeF60HQ0UsUzS/view?usp=sharing)
<br/>

## 🌐 Netlify 🌐
> [!NOTE]
> Versión de Ionic publicada en Netlify
- [Aquí](https://callofdutywiki.netlify.app)

<br/>

---

<br/>

## 📑 Esquema de Base de Datos 📑
### 🐘 PostgreSQL de Strapi (SQL)
![BD_de_Strapi](https://github.com/user-attachments/assets/0e60e191-ec88-4e61-8f69-36cf3b7acf12)

---

### 🔥 Firestore de Firebase (NoSQL)
Las relaciones son las mismas que en el diagrama de Strapi pero adaptadas a NoSQL.

#### 🎮 Colección Game
| Campo | Tipo | Descripción |
|-------|------|-------------|
| id | string | Identificador única |
| title | string | Título completo del juego |
| release_date | timestamp | Fecha de lanzamiento oficial del juego |
| image | string | Url de la imagen del logo del juego subida a Firebase Storage |
---

#### 🗺️ Colección Map
| Campo | Tipo | Descripción |
|-------|------|-------------|
| id | string | Identificación única |
| name | string | Nombre del mapa |
| description | string | Descripción del mapa (la que aparece en el juego) |
| location | {_lat : number, _long : number} | Geopoint de las coordenadas de Google Maps de dónde se encuentra el mapa |
| image | string | Url de la imagen de portada del mapa subida a Firebase Storage |
| createdAt | timestamp | Fecha de creación del mapa en la base de datos |
| updatedAt | timestamp | Fecha de la última actualización del mapa en la base de datos |
| game | { id: string, name: string, image: string } | Juego en el que se encuentra el mapa, deben ser los datos de un juego registrado en la base de datos |
| creator | string | Id del usuario que creó el mapa |
---

#### 🔫 Colección Weapon
| Campo | Tipo | Descripción |
|-------|------|-------------|
| id | string | Identificación única |
| name | string | Nombre del arma |
| info | object✴️ | Información opcional del arma |
| image | string | Url de la imagen del arma subida a Firebase Storage |
| createdAt | timestamp | Fecha de creación del arma en la base de datos |
| updatedAt | timestamp | Fecha de la última actualización del arma en la base de datos |
| game | string[] | Array con las id de los juegos a los que el arma pertenece |
| creator | string | Id del usuario que creó el arma |

##### ✴️ Info es un object con más campos dentro, no es una colección esto
| Campo | Tipo | Descripción |
|-------|------|-------------|
| type  | string | Categoría a la pertenece: subfusil, fracoritador, ametralladora ligera, etc. |
| reloadTime | number | El tiempo que se tarda en recargar |
| rateOfFire | number | La cadencia de fuego del arma |
| magazineSize | number | El número de balas de un cargador del arma |
| maxAmmo | number | La suma de balas de todos los cargadores que se llevan para el arma |
| damage | number | El daño que aplica el arma |
---

#### 🗯️ Colección Comment
| Campo | Tipo | Descripción |
|-------|------|-------------|
| id | string | Identificación única |
| content | string | Contenido del comentario escrito por el usuario |
| gameId | string | Id del juego (foro) en el que se escribió el comentario |
| userId | string | Id del usuario que escribió el comentario |
| createdAt | timestamp | Fecha de creación del comentario en la base de datos |
| updatedAt | timestamp | Fecha de la última actualización del comentario en la base de datos |
---

#### :accessibility: Colección User
| Campo | Tipo | Descripción |
|-------|------|-------------|
| id | string | Identificación única, es creada por Firebase Auth y vincula así esta tabla con la de Auth |
| username | string | Username del usuario |
| avatar | string | Url de la imagen del avatar del usuario subida a Firebase Storage |
| role | string | Rol asignado al usuario, por defecto es authenticated, pero puede ser moderator y banned |
| createdAt | timestamp | Fecha de creación del usuario en la base de datos |

#### 🔐 Auth (Firebase Auth)
| Campo | Tipo | Descripción |
|-------|------|-------------|
| id | string | Identificación única creada por Firebase Auth |
| email | string | Email único del usuario |
| password | string | Contraseña del usuario |
---


