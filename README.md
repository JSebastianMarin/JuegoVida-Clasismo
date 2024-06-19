# Simulación de Sociedad con Autómata Celular en NetLogo

Este proyecto es una simulación de una sociedad utilizando un autómata celular, implementado en el software NetLogo. El modelo simula diferentes niveles de ingresos dentro de una comunidad, visualizando cada celda con un color representativo. Además, hay celdas especiales que representan hospitales, colegios, centros recreativos y otros puntos de interés distribuidos por el mapa.

## Descripción del Proyecto

En este proyecto, cada célula del autómata tiene los siguientes atributos:

- `color`: Indica la clase social a la que pertenece la célula.
- `alta?`: Indica si pertenece a la clase alta.
- `media?`: Indica si pertenece a la clase media.
- `baja?`: Indica si pertenece a la clase baja.
- `hospital?`: Indica si es una célula de tipo hospital.
- `colegio?`: Indica si es una célula de tipo colegio.
- `centro?`: Indica si es una célula de tipo centro.
- `recreativo?`: Indica si es una célula de tipo recreativo.
- `ingresos`: Ingresos de la célula.
- `servicios`: Accesibilidad a servicios de la célula.
- `densidad`: Densidad poblacional de la célula.
- `transition-value`: Valor de transición para determinar clase social.

## Instrucciones de Uso

Para ejecutar este proyecto en NetLogo, sigue estos pasos:

**1. Clonar el repositorio:**

```
git clone https://github.com/JSebastianMarin/JuegoVida-Clasismo
```

**2. Abrir el archivo en NetLogo:**

- Inicia NetLogo.
- Abre el archivo `.nlogo` desde NetLogo.

**3. Configuración inicial y ejecución:**

En la interfaz de NetLogo, verás cuatro botones:

- `setup-random`: Presiona este botón primero para generar la población inicial y distribuir las celdas especiales en el mapa.
- `go-once`: Presiona este botón para avanzar una transición a la vez y observar los cambios paso a paso.
- `go-forever`: Presiona este botón para ejecutar la simulación continuamente y observar las transiciones automáticas.
- `go-infolabel`: Presiona este botón para habilitar la opción de ver la información de la célula bajo el ratón en los monitores de atributos.

**4. Lista desplegable de Políticas (`Seleccionador`):**

En la interfaz de NetLogo, también verás una lista desplegable de políticas (`Seleccionador`).
- Si el interruptor está en `Ninguna`, se activarán reglas que permiten el desarrollo de la sociedad, promoviendo la expansión de la clase alta y media.
- Si el seleccionador está en `Peperonismo`, se activarán reglas que disminuirán la posibilidad de escalar de clase social generando un estancamiento en la evolución.
- Si el seleccionador está en `Empobrecimiento` se usarán reglas que harán más difícil la transición a clases sociales superiores y es altamente probable que todos se vuelvan pobres.
- Si el seleccionador está en `Reactivación` se usarán reglas que harán fácil el crecimiento de la clase baja a clase media.
- Cambiar el estado del seleccionador en medio de una iteración frenara o acelerara la velocidad a la que se desarrolla la sociedad teniendo en cuenta las reglas asociadas al mismo.

## Ejemplo de Uso

**1. Generar la Población Inicial:**

- Haz clic en `setup-random`.

**2. Configurar las Políticas:**

Ajustar el interruptor de políticas (`Seleccionador`) en `Ninguna` para dar un buen desarrollo inicial a la sociedad.

- `Peperonismo`: Estancar el desarrollo.
- `Empobrecimiento`: Promover el crecimiento de la clase baja.
- `Reactivación`: Promover el desarrollo a la clase media.

**3. Ejecutar Transiciones Manualmente:**

- Haz clic en `go-once` para observar la evolución de la sociedad paso a paso.

**4. Ejecutar Transiciones Automáticamente:**

- Haz clic en `go-forever` para ver la evolución continua de la sociedad.
- Cambia el interruptor a voluntad si quieres disminuir o aumentar la velocidad a la que se expande las clases sociales media y alta.

**5. Iniciar infolabel**

Selecciona el botón `go-infolabel` para usar el mouse encima de una célula y ver la información relevante sobre la misma como, `ingresos`, `densidad` y `servicios`.

## Requisitos del Sistema

- NetLogo 6.0 o superior.
- Compatible con Windows, macOS y Linux.

## Contacto

Para cualquier pregunta o sugerencia, por favor abre un issue en GitHub o contacta a cualquiera de los miembros del grupo de estudiantes.

### Integrantes del grupo

- Juan Sebastián Marín Serna / @JSebastianMarin
- Juan Pablo Idárraga Pabón / @JuanPidarraga
- Jose Luis Ramos Arango / @RamSterB
