[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/-s1_zvqh)
# SDLC-Lab01

- Requisitos de entrega y aprobacion:
  - Respetar el formato Markdown.
  - Solo se aceptan los trabajos por GitHub Classroom
  - Todas las respuestas deben realizarse en el archivo **README.md** del repositorio asignado..
  - El Trabajo en individual. Si bien se puede realizar de forma grupal, la entrega es siempre ***individual***
  - Defensa individual
  - Respetar las fechas de entraga. No se aceptan las actividades fuera de termino.

> Si surge algún cambio o aclaración adicional, se comunicará durante la clase.

### Actividad 1
Teniendo en cuenta el material de clase, responda las siguientes preguntas:

1. ¿Por qué el desarrollo de software no puede realizarse simplemente comenzando a programar?

   R: Porque depende de lo que se requiera para el software, cuales son los objetivos y que se usa, una planificacion basica para evitar problemas e ineficiencia. 

2. ¿Qué significa que un desarrollo sea dirigido por un plan?

   R: que los requisitos estan marcados, fechas, objetivos y grupo designados ya estan planificados y estructurados para su desarrollo minimizando la incertidumbre. 

3. ¿Cuáles son las ventajas de utilizar un plan de desarrollo?

   R: las ventajas son que esta mas estructurado, organizado y se desarrolla de forma mas ordenada.

4. ¿Qué críticas se hacen a los modelos tradicionales de desarrollo?

   R: son criticados por su rigidez, falta de adaptación a cambios, alto costo de corrección de errores tardíos y baja participación del usuario o cliente hasta el final del proceso.

5. ¿Por qué en la práctica muchas organizaciones combinan metodologías ágiles y modelos dirigidos por un plan?

   R: para equilibrar entre creatividad y velocidad, asi pueden tener puntos que se deben cumplir asi hay un objetivo mas fijo pero se pueden agregar cosas por el camino tambien.


### Actividad 2

| Etapa                         | Descripción |
| ----------------------------- | ----------- |
| Análisis                      | Investigan y crean un documento que contiene                                      reglas y convenciones especiicas que capturan                                     todos los requerimientos del usuario |
| Diseño                        | se crea el diseño de una solucion                                                 informatica teniendo en cuenta los                                                requerimientos y restricciones establecidas                                       de la fase anterior y se genera mas                                               documentacion para los programadores |
| Codificación                  | se crea el codigo del software con el lenguaje                                    determinado |
| Prueba                        | se encarga de identificar errores para                                            corregirlos |
| Puesta en marcha / Despliegue | se instala en las maquinas del cliente y se                                       capacita a los usuarios para que lo usen                                          eficientemente |


* Luego responda:
  * ¿En qué etapa se obtienen los requerimientos del sistema?
  
    R: en el analisis
  * ¿En qué etapa se construye el programa?

    R: en la codificacion
  * ¿Cuál es el objetivo principal de las pruebas?
    
    R: encontrar errores y corregirlos
### Actividad 3
Ordene las siguientes etapas según corresponda  Diseño
-al modelo lineal secuencial:
- Codificación
- Prueba
- Diseño
- Despliegue
- Ingeniería de requerimientos
---
R: Ingeniería de requerimientos, Diseño, Codificación, Prueba y Despliegue

- Luego responder:
  * ¿Qué problema puede surgir si hay un error en una etapa inicial?
    
    R: en las primeras etapas los errores mas grandes serian de comunicacion, ya      que si no se pasa la informacion de manera correcta, puede terminar dando un      producto que no sea el que se pidio
    
  * ¿Por qué este modelo puede ser problemático cuando los requerimientos cambian?

    R: porque se tendria que hacer casi todo de nuevo, ya que toda la base parte de las dos primeras etapas, tambien puede afectar a temas de presupuesto dependiendo de que tan justo este.
    
### Actividad 4
Complete la siguiente tabla.


| Modelo      | Característica principal | Cuándo conviene usarlo |
| ----------- | ------------------------ | ---------------------- |
| Cascada     |   secuencial y rigido. Una fase termina antes de empezar la siguiente.    | requisitos muy claros y estables desde el inicio, para proyectos pequeños.     |
| Incremental | por partes funcionales, se entregan versiones con mas funcionalidades poco a poco | necesitas lanzar algo basico rapido o tienes los requisitos principales claros |
| Prototipos  | maqueta visual, se crea un modelo para que el usuario lo pruebe y refine los requisitos | requisitos son pocos, no definidos o los usuarios no saben lo que quieren. Ideal para interfaces.|
| Espiral     | prioriza analizar y evitar problemas en cada vuelta del desarrollo | proyectos grandes, complejos y de alto riesgo. |
| RAD         | Desarrollo muy rapido. Se usan componentes prefabricados y mucha colaboración del usuario.| plazos muy cortos, equipos cohesionados y usuarios muy disponibles. |

- Responder:
  - ¿Qué modelo es más adecuado cuando existen muchos riesgos en el proyecto?

    R: El espiral
  - ¿Qué modelo ayuda a comprender mejor los requerimientos del usuario?

    R: El lineal (cascada)
### Actividad 5 – Caso práctico
Una empresa quiere desarrollar un sistema de ventas para un pequeño comercio.

**Características del proyecto:**
- Sistema relativamente pequeño
- Pocos usuarios
- Requerimientos claros
- Tiempo limitado

**Preguntas**

- ¿Qué modelo de desarrollo recomendaría? 

  R: un modelo lineal (cascada)
- Justifique su respuesta.

  R: al ser un proyecto pequeño y con requerimientos claros, el mejor modelo para terminarlo a tiempo seria el lineal.
- ¿Qué etapas principales tendría el desarrollo?

  R: escuchar al usuario en lo que quiere (analisis) para crear el documento de requisitos, de ahi se haria una base de que es posible (diseño) y una vez todo en orden se manda al equipo de programadores (codificacion), una vez este el software se daria a los betatesters (prueba) y se corregiria cualquier error o bug encontrado, una vez terminado todo esto se le entregaria el software al cliente y se le enseñaria como funciona (despliegue)

### Actividad 7 – Verdadero o Falso
Indique si las siguientes afirmaciones son Verdaderas (V) o Falsas (F). ***marcar con x la verdaderas, dejar en blanco las falsas***

1. [ ] El modelo en cascada permite cambios constantes en los requerimientos.
2. [X] El modelo incremental entrega el sistema en varias versiones.
3. [X] Un prototipo se utiliza para comprender mejor los requerimientos.
4. [X] El modelo RAD busca reducir los tiempos de desarrollo.
5. [X] El modelo en espiral incorpora el análisis de riesgos.
