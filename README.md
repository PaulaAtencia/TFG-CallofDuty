## 🎮 Call of Duty Wiki 🎮
### Hecho por Paula Atencia Barranco

## ✨ Ideas para el proyecto ✨
Mi proyecto trata de una Wiki sobre *Call Of Duty* donde los usuarios pueden crear entradas de mapas y armas, les pueden poner su información, imagen, y el juego/s al que pertenecen, para que otros usuarios puedan verlo después.
Además, también hay disponible una sección de foros donde los usuarios pueden publicar comentarios y así hablar entre ellos.

Los usuarios tienen roles y según el que tienen pueden hacer:

• **Autenticado**: Es el rol normal, puede visualizar los mapas, armas y foros, pero no tiene permisos para crear, editar o eliminar contenido. Sin embargo, puede participar en los foros subiendo comentarios.

• **Moderador**: Puede hacer lo mismo que Autenticado pero además puede crear, editar y eliminar entradas de armas y mapas. También tiene acceso al gestor de usuarios, donde puede cambiar roles y eliminar comentarios de otros usuarios.

• **Baneado**: Este rol se asigna a usuarios que han cometido infracciones en la página. Es igual que Autenticado pero no puede leer ni publicar comentarios en los foros.

<br/>

## ✅ Objetivos del Proyecto ✅

- 💡 Este proyecto tiene como objetivo **proporcionar información** sobre la franquicia de Call of Duty y **mantener en contacto** a los usuarios a través de los foros. Además, los que sean moderadores pueden mantener actualizada esta Wiki.

- 🔀 El proyecto es **multiplataforma**, estando disponible tanto en versión web como en aplicación de Android.

- ℹ️ El proyecto incluye un sistema de **dos Backend**, con información y usuarios diferentes.

- 🔠 El proyecto está disponible tanto en **Inglés como Español**, incluyendo el uso de Google Translator para traducir datos que los usuarios creen (cometarios, descripciones, etc.)

<br/>

## ⚙️ Tecnologías Utilizadas ⚙️
### 🖥️ Backend 🖥️

La Wiki presenta dos backend disponibles cada uno con su base de datos, por lo que son “dos wikis en una”, estos son:

- 🛠️ **Strapi:** API Rest conectada a una base de datos **PostgreSQL** (proporcionada por Render), también proporciona un sistema de autentificación y está hosteada por Render aunque se puede ejecutar en local. Para las imágenes se utiliza **Cloudinary**.

- 🔥 **Firebase:** Servicio que proporciona una base de datos **Firestore** y un sistema de autentificación **Firebase Auth**. Para las imágenes se utiliza **Firebase Storage**.

---
### 💻 Frontend 💻

La Wiki está disponible como página web y como aplicación móvil android, se ha desarrollado en dos entornos diferentes para lograr esto:

- 🌐 **Ionic + Angular:** Proyecto web hecho con estos dos frameworks de **TypeScript**, con el que se proporciona así la página web y también, gracias a la librería **Capacitor**, una aplicación Android.

- 📱 **Android Studio:** Proyecto hecho en este entorno con el lenguaje **Kotlin** con el que se proporciona otra aplicación Android pero totalmente enfocada al uso móvil.

---
### 🧠 Miscelánea 🧠

- 🐍 **API Google Translator en Python:** Es una **IA de traducción** utilizando la librería **Google Translator** para que la página web pueda traducir ciertos datos (comentarios del foro y descripciones de mapas) que son creados por los usuarios.

- 🐍 **API Convertidor JSON a CSV en Python:** Elaborada para proporcionar un sistema de **transformación** de ficheros **JSON** a **CSV** de los datos de las armas, mapas, juegos, comentarios y usuarios de la página web (tiene que ver con la página de análisis).

- 🎮 **Juego 3D en Unity:** Videojuego 3D hecho en Unity que trata, siendo una torreta, de destruir tanques y ganar puntos hasta que te derriben.

<br/>

## 📤 Repositorios 📤
- 🌐 Call of Duty - Versión Ionic: [Aquí](https://github.com/PaulaAtencia/Ionic_CallofDuty)
- 📱 Call of Duty - Versión Android Studio: [Aquí](https://github.com/PaulaAtencia/Kotlin_CallofDuty)
- 📫 Servicio Strapi: [Aquí](https://github.com/PaulaAtencia/Strapi_CallofDuty)
- 🐍 CoD Utils - Librerías Python: [Aquí](https://github.com/PaulaAtencia/callofduty-utils-fastapi)
- 🎮 Shot Of Duty - Juego en Unity: [Aquí](https://github.com/PaulaAtencia/Shot-Of-Duty)
- ⚙️ Anteproyecto - Notion: [Aquí](https://www.notion.so/Call-of-Duty-Wiki-1c1cdd00abd78057b05fc2246505e70c?source=copy_link)

<br/>

## 🎦 Vídeos 🎦
### Checkpoint
- 📹 Enlace al vídeo Checkpoint: [Aquí](https://youtu.be/TB4tGpxZSS0)
### Exposición breve
- 📹 Enlace al vídeo sobre breve exposición del proyecto y sus funcionalidades:
### ❔ Tutoriales
- 🌐 Enlace al vídeo Tutorial de Ionic: [Aquí](https://youtu.be/0CNympc3CYM)
- 📱 Enlace al vídeo Tutorial de Android: [Aquí](https://youtu.be/78OuiN9JQYA)

<br/>

## 🌐 Aplicación Desplegada 🌐
> [!NOTE]
> Versión Web de Ionic publicada en Netlify<br/>
> (Redirige a /home, pero si no tienes sesión iniciada la guardia te redirige a /login)
- [Aquí](https://callofdutywiki.netlify.app)

<br/>

## 📱 APK's 📱
> [!NOTE]
> Estos enlaces siempre son a la versión más reciente sacada
- APK de la versión de **Android Studio**: [Aquí](https://drive.google.com/file/d/1izMRuY_5V9BO5KFLTZ6sWRWtVI1yB00L/view?usp=sharing)
- APK de la versión de **Capacitor + Ionic**: [Aquí](https://drive.google.com/file/d/1Zn4mGwf5thCwKKIdZ1sCeF60HQ0UsUzS/view?usp=sharing)

<br/>

## 📎 Desarrollo de Interfaces 📎

Todas las cosas de Interfaces está en Google Drive:
- Prototipo básico en Balsamiq.
- Prototipo final en Figma.
- Informe sobre la documentación de cada repositorio y dónde se encuentran.
- Informe en PowerBI

> [!NOTE]
> **¿Tienes dudas?**  
> No te preocupes, **todo está explicado en el Drive**.

<br/>

## ✍️ Bibliografía y Bitácora
Ambos documentos disponibles en Google Drive:

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
