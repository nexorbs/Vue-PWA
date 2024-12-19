# Plantilla PWA Vue 3

Esta plantilla incluye **Pinia**,**Vue-router** & **TypeScript**.

Pero puedes instalar lo que necesites como
- TailwindCSS
¡Solo sigue la documentación oficial de cada cosa y listo!

## 🚀 Lanzamiento

1. Necesitas construir tu aplicación con el comando `npm run build`.
2. Ejecuta el comando `npm run preview`.
3. Necesitamos exponer el puerto.

> [!TIP]
> Si estamos en VSCode podemos usar la función de terminal `Ports` -> `Forward Port`.

Introducimos el enlace que nos genera y ya tendremos nuestra PWA.

> [!NOTE]
> Así es como funciona el plugin. Necesitamos un servidor HTTPS para detectar la PWA, podemos usar cualquiera como Ngrok, Cloudflare, etc....

## 🔧 Configuración

Podemos ver la configuración de nuestro manifiesto en el archivo `vite.config.ts`.

Si queremos cambiar el icono de nuestra APP tenemos que cambiar las imágenes que tenemos en nuestra carpeta `public/`.

Recomiendo (como en la documentación) usar el [Favicon-generator](https://favicon.inbrowser.app/tools/favicon-generator)

## 📚 Documentación Oficial

[Vite PWA plugin](https://vite-pwa-org.netlify.app/guide/)

---

# Vue 3 PWA Template

This template include **Pinia**,**Vue-router** & **TypeScript**.

But you can install whatever you need like:
- TailwindCSS
Just follow the official documentation of each thing and that's it!

## 🚀 Launch

1. You need to build your application with the command `npm run build`.
2. Execute the command `npm run preview`.
3. We need to expose the port.
> [!TIP]
> If we are in VSCode we can use the terminal function `Ports` -> `Forward Port`.

Enter the link it generates and we will have our PWA.

> [!NOTE]
> This is the way the plugin works. We need a HTTPS server to detect the PWA, we can use any one like Ngrok, Cloudflare, etc...

## 🔧 Settings

We can see our manifest configuration in the file `vite.config.ts`.

If we want to change the icon of our APP we need to change the images we have in our `public/` folder.

I recommend (as in the documentation) to use the [Favicon-generator](https://favicon.inbrowser.app/tools/favicon-generator)

## 📚 Official Documentation

[Vite PWA plugin](https://vite-pwa-org.netlify.app/guide/)
