# Descripción general

Esta plantilla está diseñada para acelerar el proceso de configuración de Tailwind CSS y Flowbite en un proyecto Blazor WebAssembly para que pueda comenzar a desarrollar.
sus aplicaciones Blazor mucho más rápidamente mientras se encarga de todo el trabajo de configuración redundante.
Las plantillas Blazor predeterminadas no vacías vienen equipadas con Bootstrap. Sin embargo, esta plantilla reemplaza Bootstrap con Tailwind CSS y, además de eso, instala Flowbite, que es una biblioteca de componentes de interfaz de usuario de código abierto y de uso gratuito construida sobre Tailwind CSS. La biblioteca tiene una gran cantidad de componentes de interfaz de usuario bien diseñados. Componentes totalmente interactivos y con capacidad de respuesta móvil que puede utilizar para crear sus aplicaciones.

<img width="1680" alt="Captura de pantalla 2024-01-23 a las 8:00 34 p.m." src="https://github.com/rasheed-k-mozaffar/FlowbiteBlazorWasmStarter/assets/109946031/8b36ab67-ef16-458b -93ee-82f9ddfd3737">

# ¿Cómo empezar?

Esta plantilla está diseñada para ayudarle a configurar rápidamente un proyecto Blazor con Flowbite. Si desea saber más sobre el proceso y comprender los pasos con más profundidad, puede consultar este enlace: https://flowbite.com/docs/getting-started/blazor/

Para obtener la plantilla, simplemente siga las sencillas instrucciones:

1. Clona el repositorio en una carpeta local de tu máquina.
1. Abra el proyecto en un editor de texto.
1. En una ventana de terminal, ejecute `npm install`, esto descargará los módulos de nodo necesarios para la plantilla.
1. Cuando termine, en la ventana de la terminal, ejecute `npx tailwindcss -i wwwroot/css/app.css -o wwwroot/css/app.min.css --watch`

> [!IMPORTANTE]
> El último paso se utiliza para iniciar el compilador CSS Tailwind. Si no ha cambiado nada en la estructura del proyecto, no se preocupe por esta nota, pero en caso de que lo haya hecho, asegúrese de especificar la ruta correcta para la entrada. CSS y vincular el archivo CSS de salida generado después de ejecutar este comando, los cambios deben realizarse dentro de `index.html` que reside en `/wwwroot`.
