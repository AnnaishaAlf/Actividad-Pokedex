Proceso de Despliegue de la Aplicación Pokedex

    Descarga y prueba local:
    Descargué el código fuente del proyecto, instalé las dependencias necesarias y probé la aplicación en local para asegurarme de que funcionaba correctamente.

    Subida al repositorio de GitHub:
    Subí el código fuente a mi repositorio de GitHub:
    Repositorio GitHub - Pokedex.

    Despliegue en Vercel:
    Ingresé a Vercel y importé el proyecto directamente desde mi GitHub, asegurándome de que se reconociera que es una aplicación Angular y configurando el comando de compilación como ng build.

    Verificación del despliegue:
    Después de configurar el despliegue, me aseguré de que todo estuviera correcto antes de proceder.

    Verificación de seguridad inicial:
    Al comprobar el despliegue, ingresé a SecurityHeaders para evaluar el nivel de seguridad, y me di cuenta de que la puntuación era baja.

    Investigación sobre mejores prácticas de seguridad:
    Busqué en Internet qué medidas debía tomar para mejorar la seguridad del despliegue de la aplicación.

    Creación y configuración de vercel.json:
    Creé el archivo vercel.json en la raíz del proyecto y lo configuré con las políticas necesarias para aumentar la seguridad. Esto incluyó:

        Content-Security-Policy

        Permissions-Policy

        Referrer-Policy

        Strict-Transport-Security

        X-Content-Type-Options

        X-Frame-Options

    Actualización del repositorio y Vercel:
    Subí el archivo vercel.json a GitHub y recargué Vercel para que los cambios se aplicaran correctamente.

    Verificación final del despliegue:
    Visité nuevamente el enlace de la aplicación para asegurarme de que el despliegue estuviera correcto.

    Comprobación de seguridad final:
    Volví a utilizar SecurityHeaders para verificar la mejora en el nivel de seguridad del despliegue.

Resultado Final

Después de completar todos los pasos, Vercel desplegó automáticamente la aplicación, proporcionándome una URL desde la cual se puede acceder a la PokeDex:

URL de la aplicación:
https://actividad-pokedex.vercel.app/
