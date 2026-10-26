# Sistema de Gestión de Contenidos (CMS)

Un **CMS** (*Content Management System*) es una aplicación de software que permite a los usuarios crear, editar, colaborar, publicar y almacenar contenido digital fácilmente.

## ¿Cómo funciona?
El CMS separa el contenido (guardado en una base de datos) de la presentación (plantillas visuales). Cuando un usuario visita una página web, el CMS extrae los datos de la base de datos y los inyecta en la plantilla en tiempo real.


## Tipos de CMS y Ejemplos
Existen varios enfoques a la hora de estructurar un CMS:
1. **Tradicionales (Acoplados):** Todo está en el mismo sistema (Backend y Frontend). Ejemplos: WordPress, Drupal, Joomla.
2. **Headless (Desacoplados):** Solo gestionan el backend (contenido) y lo envían vía API a cualquier frontend. Ejemplos: Strapi, Contentful, Sanity.

## Comparativa: CMS Dinámico vs. SSG

A continuación se muestra la comparación entre un CMS tradicional y un Generador de Sitios Estáticos (SSG):

| Característica | CMS Dinámico | Generador de Sitios Estáticos (SSG) |
| :--- | :--- | :--- |
| **Rendimiento** | Lento bajo tráfico intenso. Depende de la velocidad de la base de datos y la capacidad del servidor.. | Extremadamente rápido. Los archivos pre-construidos se sirven desde una red global (CDN). |
| **Seguridad** | Vulnerable. Al tener base de datos y paneles de login expuestos, son objetivos constantes de ataques. | Altamente seguro. Al no haber base de datos ni servidor procesando código, la superficie de ataque es casi nula. |
| **Escalabilidad** | Costosa. Si un post se hace viral, necesitas más RAM y CPU en el servidor para evitar que caiga. | Automática y económica. Servir HTML estático consume recursos mínimos; escalar es tan simple como usar un CDN. |
| **Experiencia de Edición** | CExcelente (WYSIWYG). Paneles visuales integrados diseñados para usuarios no técnicos. | Requiere configuración extra. Por defecto usan Markdown, aunque se pueden conectar a un "Headless CMS" para tener una interfaz amigable. |
| **Mantenimiento** | Alto. Requiere actualizar plugins, la base de datos y el motor central (PHP) constantemente por parches de seguridad. | Bajo. El código vive en un repositorio (Git); no hay plugins de servidor que actualizar. |
---

### Recursos Adicionales y Enlaces
- [Ver vídeo explicativo sobre CMS (Duración: 3:17 min)](https://www.youtube.com/watch?v=-xoh7kAJPtI)
- [Enlace de investigación sobre SSG (Jekyll, Hugo y Astro)](./ssg.md)