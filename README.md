# Simulación de Sociedad con Autómata Celular en NetLogo

Este proyecto es una simulación de una sociedad utilizando un autómata celular, implementado en el software NetLogo. El modelo simula diferentes niveles de ingresos dentro de una comunidad, visualizando cada celda con un color representativo. Además, hay celdas especiales que representan hospitales, colegios, centros recreativos y otros puntos de interés distribuidos por el mapa.

## Descripción del Proyecto

En este proyecto, cada célula del autómata tiene los siguientes atributos:

- `color`: Indica el nivel de ingresos.
- `alta?`: Indica si pertenece a un nivel de ingresos alto.
- `media?`: Indica si pertenece a un nivel de ingresos medio.
- `baja?`: Indica si pertenece a un nivel de ingresos bajo.
- `hospital?`: Indica si es una célula de tipo hospital.
- `colegio?`: Indica si es una célula de tipo colegio.
- `centro?`: Indica si es una célula de tipo centro.
- `recreativo?`: Indica si es una célula de tipo recreativo.

## Instrucciones de Uso

Para ejecutar este proyecto en NetLogo, sigue estos pasos:

1. **Clonar el repositorio:**

```
git clone https://github.com/JSebastianMarin/JuegoVida-Clasismo
```

2. **Abrir el archivo en NetLogo:**
    - Inicia NetLogo.
    - Abre el archivo `.nlogo` desde NetLogo.

3. **Configuración inicial y ejecución:**

En la interfaz de NetLogo, verás tres botones:

- `setup-random`: Presiona este botón primero para generar la población inicial y distribuir las celdas especiales en el mapa.
- `go-once`: Presiona este botón para avanzar una transición a la vez y observar los cambios paso a paso.
- `go-forever`: Presiona este botón para ejecutar la simulación continuamente y observar las transiciones automáticas.

## Ejemplo de Uso

1. **Generar la Población Inicial:**
    - Haz clic en `setup-random`.

2. **Ejecutar Transiciones Manualmente:**
    - Haz clic en `go-once` para observar la evolución de la sociedad paso a paso.
3. **Ejecutar Transiciones Automáticamente:**
<<<<<<< HEAD

- Haz clic en go-forever para ver la evolución continua de la sociedad.

=======
    - Haz clic en `go-forever` para ver la evolución continua de la sociedad.
>>>>>>> dde67e4b6dca21207897c35bc105943bfec6b75e
## Requisitos del Sistema

- NetLogo 6.0 o superior.
- Compatible con Windows, macOS y Linux.

## Contacto

Para cualquier pregunta o sugerencia, por favor abre un issue en GitHub o contacta a cualquiera de los miembros del grupo de estudiantes.

### Integrantes del grupo

- Juan Sebastian Marin Serna / @JSebastianMarin
- Juan Pablo Idarraga Pabón / @JuanPidarraga
- Jose Luis Ramos Arango / @RamSterB
