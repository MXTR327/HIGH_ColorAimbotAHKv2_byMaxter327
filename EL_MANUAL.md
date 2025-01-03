**Instrucciones de uso del script**

**Paso 1: Instalación**

* Descarga el script y colócalo en una carpeta de tu elección.

**Paso 2: Ejecución**

* Ejecuta el script haciendo doble clic en el archivo .exe.
* El script se ejecutará en segundo plano y comenzará a funcionar automáticamente.

**Paso 3: Uso y Configuración**

**Combinaciones de Teclas:**
* `F5`: Recarga el script.
* `F8`: Activa o desactiva el script (activo por activo_por_defecto = true  en `config.ini`).
* `F12`: Sale de la aplicación.
* `Ctrl + Shift + D`: Muestra o Oculta las áreas de disparo.

**Explicación de Variables en `config.ini`:**
# Manual de Configuración

## Sección: *General*
- *activo_por_defecto*: Define si el aimbot está activado por defecto al iniciar el script.  
  - `1`: Activado  
  - `0`: Desactivado

- *color_em*: Código hexadecimal del color que el aimbot debe detectar en la pantalla para apuntar.  
  - Ejemplo: `0xD82A22` (rojo).

- *col_vn*: Parámetro que ajusta la sensibilidad de la detección del color, generalmente un valor entre 0 y 255.  
  - Ejemplo: `22` (bajo valor).

- *compensar_x*: Ajuste de compensación horizontal en píxeles para el centro del campo de visión (FOV).  
  - Ejemplo: `1` (compensación pequeña).

- *compensar_y*: Ajuste de compensación vertical en píxeles para el centro del campo de visión (FOV).  
  - Ejemplo: `6` (compensación mayor a la horizontal).

## Sección: *Área Escaneada*
- *area_escaneada_x*: Establece el área escaneada en el eje X (horizontal), en porcentaje del ancho total de la pantalla.  
  - Ejemplo: `25` (25% de la pantalla).

- *area_escaneada_y*: Establece el área escaneada en el eje Y (vertical), en porcentaje del alto total de la pantalla.  
  - Ejemplo: `7` (7% de la pantalla).

- *fov_del_juego*: Define el campo de visión (FOV) del juego, que determina el ángulo de visión en grados.  
  - Ejemplo: `120` grados.

## Sección: *Mouse*
- *apuntar_con_clic_botton_izquierdo*: Configura si el aimbot debe apuntar al hacer clic con el botón izquierdo del mouse.  
  - `1`: Activado  
  - `0`: Desactivado

- *apuntar_con_clic_botton_derecho*: Configura si el aimbot debe apuntar al hacer clic con el botón derecho del mouse.  
  - `1`: Activado  
  - `0`: Desactivado

- *distancia_giro_360_inches*: Define la distancia en pulgadas para realizar un giro de 360 grados dentro del juego.  
  - Ejemplo: `251327.4122834646` (gran valor).

- *sensibilidad_del_juego*: Ajusta la sensibilidad del juego.  
  - Ejemplo: `80` (sensibilidad media).

## Sección: *Additional (Adicional)*
- *fps_del_juego*: Establece los fotogramas por segundo (FPS) del juego, lo cual puede influir en el rendimiento.  
  - Ejemplo: `200` (alta tasa de fotogramas).

- *velocidad_de_apuntado_X*: Ajusta la velocidad del apuntado en el eje X (horizontal).  
  - Ejemplo: `0.3` (velocidad media).

- *velocidad_de_apuntado_Y*: Ajusta la velocidad del apuntado en el eje Y (vertical).  
  - Ejemplo: `0.2` (velocidad baja).

## Sección: *Opciones Experimentales*
- *optimizarPantalla*: Activa o desactiva la optimización de la pantalla para mejorar el rendimiento.  
  - `1`: Activado  
  - `0`: Desactivado

## Sección: *TriggerBot*
- *triggerbot*: Activa o desactiva la función de disparo automático (TriggerBot).  
  - `1`: Activado  
  - `0`: Desactivado

- *triggerbot_area_size*: Define el tamaño del área de activación del TriggerBot en píxeles.  
  - Ejemplo: `10` (área pequeña).

- *espera_antes_de_disparo*: Configura el tiempo de espera (en milisegundos) antes de disparar después de detectar el color.  
  - Ejemplo: `200` ms (espera corta).


**Paso 5: Desinstalación**

* Para desinstalar el script, simplemente cierra el proceso y elimina los archivos del script.

**Consejos y advertencias**

* Asegúrate de leer y seguir las instrucciones de uso cuidadosamente para evitar problemas.
* No uses el script en juegos que no permitan el uso de scripts o bots.
* El script no es responsable de cualquier daño o pérdida causada por su uso.


