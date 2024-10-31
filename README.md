# Trayectorias laborales femeninas en el sector de software. Segregación ocupacional detrás de la pantalla

[![Alt text](https://fund.ar/wp-content/uploads/2024/10/Alwac_III_computer_1959.jpg)](https://fund.ar/publicacion/trayectorias-laborales-femeninas-en-la-industria-del-software/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14014792.svg)](https://doi.org/10.5281/zenodo.14014792)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%20NC%20SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

En este repositorio se comparten bases de datos inéditas y diccionarios que se han utilizado para el análisis del documento **Trayectorias laborales femeninas en el sector de software. Segregación ocupacional detrás de la pantalla** [^1]. Este es un trabajo conjunto de las Áreas de Géneros, Datos y Política Productiva de Fundar. El estudio propone dimensionar patrones y dinámicas de la segregación de género al interior del sector de software y servicios informáticos en la Argentina, identificando inequidades que encuentran mujeres cis y trans en sus trayectorias para incorporarse al sector, ocupar roles núcleo de los procesos productivos, sostenerse en sus puestos de trabajo, ganar jerarquía y realizar transiciones laborales. 


[^1]: [Argoitia, J.M.; Luvini, P.; Sancisi, A.; Risaro, D. (2024). Trayectorias laborales femeninas en el sector de software. Segregación ocupacional detrás de la pantalla. Fundar.](https://fund.ar/publicacion/trayectorias-laborales-femeninas-en-la-industria-del-software/)


**Cita Sugerida:**
```
Argoitia, J.M.; Luvini, P.; Sancisi, A.; Risaro, D. (2024). Trayectorias laborales femeninas en el sector de software. Segregación ocupacional detrás de la pantalla. Fundar.
```

Bibtex:
```bibtex
@report{software2024datos,
  author    = {Argoitia, J.M.; Luvini, P.; Sancisi, A.; Risaro, D.},
  title     = {Trayectorias laborales femeninas en el sector de software. Segregación ocupacional detrás de la pantalla.},
  year      = {2024},
  institution = {Fundar},
  type      = {Document}
}

```

## Organización de los archivos:

En [`datasets`](./datasets/) se encuentran las siguientes bases:
- [Base Universitaria](./datasets/base_universitaria.csv): Se accedió a esta base a través de un pedido de información pública respondido por el Departamento de Información Universitaria (DIU). Cuenta con información de inscriptos, estudiantes y egresados totales por carrera, universidad y jurisdicción. Sobre esta base se trabajó en una clasificación de carreras entre No Stem, Informática y Resto de STEM.
- [Base de perfiles de LinkedIn](./datasets/base_perfiles.csv): Se construyó esta base a partir de ciertos perfiles de dicha red social, a la que se agregaron variables de elaboración propia.

En [`diccionarios`](./diccionarios/) se encuentran los diccionarios utilizados para mapear palabras clave y llegar a diversas categorías laborales, educativas y de habilidades. Los diccionarios están repartidos en las siguientes pestañas:
- Funciones: Para identificar funciones en la estructura ocupacional, se asignaron categorías ocupacionales a los puestos sobre la base de los perfiles laborales tipificados por la [CESSI](https://cessi.org.ar/perfiles-it/). La construcción toma las definiciones sectoriales, pero fue ajustada a partir del marco teórico, una revisión bibliográfica, entrevistas a informantes, los propios datos y la búsqueda de descripciones de puestos en Google.
- Orientación: Para identificar experiencias de educación superior con orientación en informática se consultó en agosto de 2023 la oferta de títulos de grado, intermedios, técnico-instrumental y otros pregrados sistematizados en la [Guía de Carreras de la Secretaría de Políticas Universitarias](https://guiadecarreras.siu.edu.ar/carreras_de_pregrado_y_grado.php). A los resultados de este diccionario inicial se los revisó manualmente y se agregaron algunas palabras clave que no estaban o que estaban reportadas en inglés. Asimismo se agregaron términos a excluir por tratarse de titulaciones intermedias o de profesorados.
- Lenguajes: Para identificar lenguajes de programación, frameworks, herramientas, librerías y bases de datos se adoptaron los datos de la Encuesta de sueldos 2023.2 implementada por la comunidad [Sysarmy](https://sysarmy.com/blog/posts/resultados-de-la-encuesta-de-sueldos-2023-2/).

## Libro de código

El libro de códigos contiene la documentación de estas bases de datos con una descripción detallada de sus variables.

[Ir al archivo](https://github.com/datos-Fundar/software_trayectorias/blob/main/Libro%20de%20c%C3%B3digos.pdf)


<div>&nbsp;</div>
<div>&nbsp;</div>
<div>
  &nbsp;
  <a href="https://fund.ar">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/datos-Fundar/fundartools/assets/86327859/6ef27bf9-141f-4537-9d78-e16b80196959">
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/datos-Fundar/fundartools/assets/86327859/aa8e7c72-4fad-403a-a8b9-739724b4c533">
    <img src="fund.ar"></img>
  </picture>
</a>

</div>
