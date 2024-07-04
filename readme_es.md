# [Go to English Version](readme.md)

# Alternancia de Modo Claro/Oscuro con SMACSS

Este proyecto demuestra un simple alternador de modo claro/oscuro usando HTML, CSS (organizado con SMACSS), JavaScript, Font Awesome para iconos y Bootstrap para el diseño.

# Tabla de Contenidos
- [Introducción](#introducción)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Configuración](#configuración)
- [Uso](#uso)
- [Personalización](#personalización)
- [Contribuir](#contribuir)
- [Licencia](#licencia)

## Introducción
Este proyecto muestra una página web con dos cajas centradas: una indicando "Light" con un icono de sol, y la otra indicando "Dark" con un icono de luna. Al hacer clic en cualquiera de las cajas, la página alterna entre el modo claro y oscuro.

## Estructura del Proyecto
El proyecto sigue la metodología SMACSS (Arquitectura Escalable y Modular para CSS), organizando el CSS en diferentes categorías.

```
/project
|-- index.html
|-- css
| |-- base.css
| |-- layout.css
| |-- module.css
| |-- state.css
| |-- theme.css
```

## Tecnologías Utilizadas
- HTML
- CSS (con metodología SMACSS)
- JavaScript
- Font Awesome (para iconos)
- Bootstrap (para el diseño)
## Configuración
Para configurar este proyecto localmente, sigue estos pasos:

1. Clona el repositorio:
```sh
Copy code
git clone https://github.com/Giovasdf/light-dark-mode-toggle
```

2. Navega al directorio del proyecto:
``` sh
cd light-dark-mode-toggle
```
## Uso
Abre index.html en tu navegador web para ver la funcionalidad del alternador de modo claro/oscuro.

### Explicación del JavaScript
El JavaScript alterna las clases theme-dark y theme-light en el elemento body para cambiar entre temas.
``` javascript
<script>
    // Función para alternar entre modos claro y oscuro
    function toggleMode() {
        // Alterna la clase 'theme-dark' en el elemento 'body'
        document.body.classList.toggle('theme-dark');
        // Alterna la clase 'theme-light' en el elemento 'body'
        document.body.classList.toggle('theme-light');
    }
</script>
```

## Personalización
Puedes personalizar la apariencia y el comportamiento del alternador de modo claro/oscuro modificando los archivos CSS. Cada archivo CSS está organizado según la metodología SMACSS:

- base.css: Estilos globales y configuraciones predeterminadas.
- layout.css: Estilos relacionados con el diseño.
- module.css: Estilos para componentes individuales.
- state.css: Estilos para varios estados (por ejemplo, hover, active).
- theme.css: Estilos específicos del tema (por ejemplo, modos claro y oscuro).

## Contribuir
¡Las contribuciones son bienvenidas! Si tienes sugerencias o mejoras, por favor crea un issue o envía un pull request.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT. 