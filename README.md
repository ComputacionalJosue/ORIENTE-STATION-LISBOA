
# Parametric Model Oriente Estación Lisboa
![Portada Readme](https://github.com/ComputacionalJosue/Oriente-Estacion-Lisboa/blob/main/Docs/Algoritmo%20grasshopper.png)

Algoritmo de módulo (unidad de conjunto) y algoritmo para su implementación en cualquier terreno como agrupacion de módulos. Construido en su totalidad en [Grasshopper](https://www.grasshopper3d.com/). Proyecto para ser utilizado en su implementacion en proyectos o prácticas de arquitectura o simplemente para su estudio como ejemplo.

## Descripción

1. **Análisis:**
   - Se hizo una observacion de la obra construida de Santiago Calatrava: La estacion de Oriente-Lisboa, donde se observa todas las caracteristicas antes de llevarlas a grasshopper, la mortfologia , la estrcuturas, la lógica contructiva y de diseño para que a la hora de tomar decisiones en grasshopper estas esten en base a la obra original. Para elaborar el algoritmo escogimos el área de la estación de los trenes, específicamente la estructura de acero y vidrio con apariencia de árbol que cubre el área de los binarios, esta estructura es de los rasgos mas importantes de toda la obra que además  la dota de una esencia y la hace resaltar desde lejos.
2. **Módulo de arbol:**
   - Definimos y modelamos paramétricamente como módulo independiente una unidad de la estructura, para que antes de multiplicarla en ambos ejes primero este definida y personalizada.
3. **Inserción en el terreno:**
   - Una vez tengamos el modulo  definido, lo implementaremos en el terreno que será cualquier malla o superficie  modelado ya sea en Grashopper y/o Rhinoceros o simplemente trayéndola desde otro software; podremos elegir un punto UV cualquiera dentro de mi malla , que será la ubicación 0,0,0 de toda mi estructura, podremos manipular el numero de columnas y filas según nuestra necesidad, aun formado ya nuestro conjunto, podremos moverlo y/o acomodarlo en cualquier lugar de nuestra malla y finalmente ubicado el conjunto ya en su lugar, podremos hacer cambios como modificar la altura de la base o cualquier otra variable.
     
![Portada secundaria](https://github.com/ComputacionalJosue/Oriente-Estacion-Lisboa/blob/main/Docs/Portada%20Readme.jpg)

## 📁 Acceso al proyecto

Descarge los dos archivos (.gh y .3dm) que ese encuentran en la carpeta "Proyect" dentro de este repositorio de GitHUb

## 🛠️ Abre y ejecuta el proyecto

 **En el caso de que solo desees utilizar el algoritmo del módulo base:**
   - Asegúrate de tener instalado Rhinoceros-Grasshopper en tu computadora, recomendado: Rhino 7 en adelante.
   - Abre el archivo .gh: ParametricModel.gh.

 **En el caso de que desees utilizar o ver el algoritmo de la aplicación en el terreno:**
   - Asegúrate de tener instalado Rhinoceros-Grasshopper en tu computadora, recomendado: Rhino 7 en adelante.
   - Abre primero el archivo .gh: ParametricModel.gh.
   - Abre después el archivo .3dm: Example surface.3dm.
   - Puedes reemplazar o modificar la superficie del archivo .3dm o, en su defecto, exportar una malla o superficie de otro software.

## Mas información

Video sobre proyecto:
[![Imagen que representa el video](https://github.com/ComputacionalJosue/Oriente-Estacion-Lisboa/blob/main/Docs/video.png)](https://www.facebook.com/josue.hurtado.33633/videos/1881554428906474?locale=es_LA)

Mas informacion acerca de la obra de Calatrava aquí: [https://calatrava.com/projects/oriente-station-lisboa.html?view_mode=gallery&image=1](https://calatrava.com/projects/oriente-station-lisboa.html?view_mode=gallery&image=1) y/o aqui [https://en.wikiarquitectura.com/building/orient-station-to-expo98/](https://en.wikiarquitectura.com/building/orient-station-to-expo98/)
                                                     
## Agradecimientos

Este proyecto es la puesta en práctica de todo lo aprendido en el playlist de "Introduction to Parametric Modeling" de [ParametricCamp](https://www.youtube.com/@ParametricCamp/playlists) impartida por el maestro [José Luis García del Castillo](https://github.com/garciadelcastillo).

Este proyecto fue realizado enteramente por [Josué Israel Hurtado](https://github.com/ComputacionalJosue) 

## Authors

- [@ComputacionalJosue](https://github.com/ComputacionalJosue)

  
## License

[MIT](https://choosealicense.com/licenses/mit/)

   





