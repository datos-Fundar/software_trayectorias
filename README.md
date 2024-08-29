# Trayectorias laborales femeninas en la industria del software. Códigos de la segregación ocupacional detrás de la pantalla

En este repositorio se comparten los datos agregados y los diccionarios que se han utilizado para el análisis del documento **Trayectorias laborales femeninas en la industria del software. Códigos de la segregación ocupacional detrás de la pantalla** [^1]. 

[^1]: [Argoitia, J.M.; Luvini, P.; Sancisi, A.; Risaro, D. (2024). Trayectorias laborales femeninas en la industria del software. Códigos de la segregación ocupacional detrás de la pantalla. Fundar.](https://fund.ar/publicacion/guia-practica-para-analizar-la-complejidad-economica-de-una-provincia/)


**Cita Sugerida:**
```
Argoitia, J.M.; Luvini, P.; Sancisi, A.; Risaro, D. (2024). Trayectorias laborales femeninas en la industria del software. Códigos de la segregación ocupacional detrás de la pantalla. Fundar.
```

Bibtex:
```bibtex
@report{software2024datos,
  author    = {Argoitia, J.M.; Luvini, P.; Sancisi, A.; Risaro, D.},
  title     = {Trayectorias laborales femeninas en la industria del software. Códigos de la segregación ocupacional detrás de la pantalla},
  year      = {2024},
  institution = {Fundar},
  type      = {Document}
}

```

## Organización del proyecto:

En [`datasets`](./datasets/) se encuentran los datos de empleo publicados por CEP XXI junto con el correspondiente diccionario de códigos y sectores de actividad.

En [`diccionarios`](./diccionarios/) se encuentran los diccionarios utilizados para mapear palabras clave y llegar a diversas categorías laborales, educativas y de habilidades. Los diccionarios están repartidos en las siguientes pestañas:
- Funciones: Para identificar funciones en la estructura ocupacional, se asignaron categorías ocupacionales a los puestos sobre la base de los perfiles laborales tipificados por la [CESSI](https://cessi.org.ar/perfiles-it/). La construcción toma las definiciones sectoriales, pero fue ajustada a partir del marco teórico, una revisión bibliográfica, entrevistas a informantes, los propios datos y la búsqueda de descripciones de puestos en Google.
- Freelance: Este diccionario fue construido internamente tras un análisis del marco teórico, una revisión bibliográfica, entrevistas a informantes y de la base de datos construida.
- Orientación: Para identificar experiencias de educación superior con orientación en informática se consultó en agosto de 2023 la oferta de títulos de grado, intermedios, técnico-instrumental y otros pregrados sistematizados en la [Guía de Carreras de la Secretaría de Políticas Universitarias](https://guiadecarreras.siu.edu.ar/carreras_de_pregrado_y_grado.php). A los resultados de este diccionario inicial se los revisó manualmente y se agregaron algunas palabras clave que no estaban o que estaban reportadas en inglés. Asimismo se agregaron términos a excluir por tratarse de titulaciones intermedias o de profesorados.
- Lenguajes: Para identificar lenguajes de programación, frameworks, herramientas, librerías y bases de datos se adoptaron los datos de la Encuesta de sueldos 2023.2 implementada por la comunidad [Sysarmy](https://sysarmy.com/blog/posts/resultados-de-la-encuesta-de-sueldos-2023-2/).


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