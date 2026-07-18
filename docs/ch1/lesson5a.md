# Configurar Google Earth Engine

```{note}
Recomendamos utilizar una dirección que termine en `@gmail.com` en lugar de una cuenta institucional con dominio `.org` o `.edu`. Google Cloud puede mostrar opciones diferentes según la configuración de tu correo institucional. Por esta razón, hemos comprobado que una cuenta de Gmail puede ser la mejor opción para trabajar con Google Earth Engine con fines educativos.
```

1. Ve a <a href="https://console.cloud.google.com/earth-engine" target="_blank" rel="noopener noreferrer">console.cloud.google.com/earth-engine</a> e inicia sesión en tu cuenta de Google si todavía no lo has hecho. Haz clic en {guilabel}`Register`, debajo de “Register your Cloud project”.
![Página de bienvenida de Earth Engine](gee_1.png)

2. Haz clic en {guilabel}`Create project`.
![Página para crear un proyecto](gee_2.png)

3. Escribe un nombre como `emerge-lessons` y haz clic en {guilabel}`Create`. Este nombre será el ID de tu proyecto. Si utilizas una dirección `.edu` o el correo de una organización, esta página podría verse diferente y podrías encontrar otras opciones o limitaciones.
![Página para crear un proyecto nuevo](gee_3.png)

```{important}
Anota el ID de tu proyecto. Es posible que se agreguen algunos números después del nombre que escribiste, por ejemplo, `emerge-lessons-359891`.
```

4. Haz clic en {guilabel}`Get started`, debajo de “See if you are eligible for noncommercial use”.
![Página de configuración de Google Cloud](gee_4.png)

5. Responde la serie de preguntas breves de la siguiente manera:

> En “Select your organization type”, selecciona “Earth Engine trainer or trainee” y haz clic en {guilabel}`Next`.

> En “Check noncommercial eligibility”, selecciona “Participant” en la primera pregunta. Después, escribe la fecha en la que comenzarás las lecciones y la fecha en la que esperas terminarlas. Si todavía no estás seguro, puedes escribir `09/01/2026`. Si más adelante necesitas más tiempo, podrás actualizar esta fecha. Haz clic en {guilabel}`Check eligibility`.

> Debería aparecer el mensaje {fa}`circle-info` **Based on your answers, you are eligible for noncommercial Earth Engine use.**

> Haz clic en {guilabel}`Next` para ir a **Choose your plan**. En “Please select a quota tier”, selecciona **Community**.

> En “Describe your work”, busca la pregunta “Will you use Earth Engine for any of the following? *”, selecciona “Classroom or education” y haz clic en {guilabel}`OK`. Después, haz clic en {guilabel}`Next`.

> La pantalla debería verse como la siguiente:
![Página de registro de Earth Engine](gee_5.png)

6. En la ventana emergente, haz clic en {guilabel}`Enable` para habilitar la API de Earth Engine.
![Ventana para habilitar las API necesarias](gee_6.png)

7. Deberías ver la siguiente página. Ya puedes cerrar esta pestaña.
![Página de configuración que confirma el registro del proyecto de Cloud](gee_7.png)

Ahora has creado tu proyecto de Cloud y habilitado la API. Continúa con la siguiente sección para comenzar a ejecutar Google Earth Engine en Google Colab.
