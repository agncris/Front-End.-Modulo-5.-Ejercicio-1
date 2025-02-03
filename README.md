Hospital Sale Sano

    Es un sitio web de presentación de los servicios y personal médico de un hospital ficticio.

Este proyecto utiliza: React y Vite para construir una aplicación web moderna, modular y eficiente. Está diseñado con una estructura escalable, utilizando estilos SCSS y enrutamiento manejado con React Router.

---

Tecnologías utilizadas

- React
- Vite
- React Router
- SCSS
- Bootstrap


Actualizaciones:


 1. Lectura de información de doctores desde una base de datos con una api simulada. La información delos doctores se encuentra en db.json

 2- Las peticiones de la PAI utilizan Fetch API en MedicosList.jsx con fetchMedicos y fetchServices. Y en Equipo,jsx se utiliza el contecxto DoctorContext, implementanto Fetch Api para obtener la lista de doctores. y en App.jsx se utiliza para obtener la lista de médicos.
 Se utilizó Fetch Api en vez de Axios ya que el primero funciona de forma nativa en el browser, sin necesitas de instalaciones adicionales. Además Fetch Api tiene una interfaz más simple y utiliza promecas, lo que facilita las operaciones asíncronas y manejo de errores.

 3 - Se le entrega al usuario la capacidad de relacionarse con la base de datos a través de la api con las opciones de visualización de información del equipo como tarjetas, tabla y actualización de la información.





Descripción de páginas y funcionalidades:

	Inicio (index.jsx): Página de bienvenida, mostrando la misión, visión, servicios y testimonios con la intención de generar confianza en nuevos posibles pacientes.
	Equipo médico (equipo.jsx): Sección para mostrar la información de los especialistas que trabajan en el hospital.
	Contacto (contacto.jsx): Página de contacto para que el usuario envíe un mensaje a través de un formulario y vea en un mapa la ubicación del hospital.
	Reserva de hora (Reservar.jsx) formulario para reservar citas médicas.

Créditos
Pára los elementos gráficos no se utilizaron imágenes cargadas como archivos en la carpeta del proyecto, sino que están conectadas a links de internet.

    Íconos: Íconos de servicios y redes sociales fueron tomados de:
        - Iconfinder
        - DuckDuckGo
        - Vecteezy
    Imágenes: Las imágenes de perfil de los doctores y el logo fueron obtenidos de:
        - SonicSEO
        - Public Domain Pictures
        - Stockvault

DOM:

📦hospital
 ┣ 📂public
 ┃ ┗ 📜vite.svg
 ┣ 📂src
 ┃ ┣ 📂assets
 ┃ ┃ ┗ 📜react.svg
 ┃ ┣ 📂components
 ┃ ┃ ┣ 📜AppointmentForm.jsx
 ┃ ┃ ┣ 📜Contacto.jsx
 ┃ ┃ ┣ 📜DoctorCard.jsx
 ┃ ┃ ┣ 📜Equipo.jsx
 ┃ ┃ ┣ 📜Footer.jsx
 ┃ ┃ ┣ 📜Header.jsx
 ┃ ┃ ┣ 📜Home.jsx
 ┃ ┃ ┣ 📜MedicosList.jsx
 ┃ ┃ ┣ 📜Reservar.jsx
 ┃ ┃ ┗ 📜ServiceList.jsx
 ┃ ┣ 📂styles
 ┃ ┃ ┣ 📂abstracts
 ┃ ┃ ┃ ┣ 📜_bootstrap-override.scss
 ┃ ┃ ┃ ┣ 📜_breakpoints.scss
 ┃ ┃ ┃ ┣ 📜_functions.scss
 ┃ ┃ ┃ ┣ 📜_mixins.scss
 ┃ ┃ ┃ ┗ 📜_variables.scss
 ┃ ┃ ┣ 📂base
 ┃ ┃ ┃ ┣ 📜_base.scss
 ┃ ┃ ┃ ┣ 📜_resets.scss
 ┃ ┃ ┃ ┗ 📜_typography.scss
 ┃ ┃ ┣ 📂components
 ┃ ┃ ┃ ┣ 📜_button.scss
 ┃ ┃ ┃ ┣ 📜_footer.scss
 ┃ ┃ ┃ ┗ 📜_header.scss
 ┃ ┃ ┣ 📂layout
 ┃ ┃ ┃ ┣ 📜_footer.scss
 ┃ ┃ ┃ ┣ 📜_grid.scss
 ┃ ┃ ┃ ┗ 📜_header.scss
 ┃ ┃ ┣ 📂pages
 ┃ ┃ ┃ ┣ 📜_contacto.scss
 ┃ ┃ ┃ ┣ 📜_equipo.scss
 ┃ ┃ ┃ ┗ 📜_home.scss
 ┃ ┃ ┣ 📂partials
 ┃ ┃ ┃ ┗ 📜_breakpoints.scss
 ┃ ┃ ┣ 📂vendors
 ┃ ┃ ┃ ┗ 📜_bootstrap.scss
 ┃ ┃ ┣ 📜main.css
 ┃ ┃ ┣ 📜main.css.map
 ┃ ┃ ┗ 📜main.scss
 ┃ ┣ 📜App.css
 ┃ ┣ 📜App.jsx
 ┃ ┣ 📜index.css
 ┃ ┗ 📜main.jsx
 ┣ 📂styles
 ┃ ┗ 📜main.css
 ┣ 📜.gitignore
 ┣ 📜eslint.config.js
 ┣ 📜index.html
 ┣ 📜package-lock.json
 ┣ 📜package.json
 ┗ 📜README.md
