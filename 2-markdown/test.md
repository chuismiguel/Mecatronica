  # Markdown: Test de funcionalidades

  ## 1. Texto

  Este texto va en la misma linea

  Este texto está en la siguiente debido a que he metido dos saltos de línea
  con un solo salto, sigue en la misma.  
  Añadiendo dos espacios al final de la línea también se salta la línea.

  ## 2. Listas

  ### Listas sin ordenar:

  * Asterisco nos crea puntos
  * Otro punto más
    * Tabular añade otro punto
  * Puedo volver atrás

  ### Listas ordenadas:

  1. Nos crea el primer punto
  2. Segundo punto
  3. etcetera

  ## 3. Resaltado de texto:

  Un solo asterisco: *cursiva*  
  Dos asteriscos: **negrita**

  ## 4. Código

  Con tres comillas (```) podemos añadir código:

  ```
  class ultrasound: # one pin distance sensor
    def __init__(self, inverval=.2):
        GPIO.setmode(GPIO.BCM)
        self._pin = US_PIN
        self.max_distance = MAX_DISTANCE
  ```

  Si añadimos el nombre, resaltará el texto según el lenguaje utilizado:

  ```python
  class ultrasound: # one pin distance sensor
    def __init__(self, inverval=.2):
        GPIO.setmode(GPIO.BCM)
        self._pin = US_PIN
        self.max_distance = MAX_DISTANCE
  ```

  Entre apóstrofos se puede escribir código en línea `a=pepe; print(a)`

  ## 5. Hiperenlaces

  ### Externos:

  Enlaces a páginas de internet, introduciendo el texto a resaltar entre corchetes y después el enlace: [Github Personal]("https://github.com/chuismiguel/Mecatronica-2022-2023")

  ### Internos: 

  Poniendo entre corchetes el texto, seguido del hashtag con el título al que moverse dentro de la propia wiki: [Apartado de Hiperenlaces](#5-hiperenlaces) o [Listas Ordenadas](#listas-ordenadas)

  ## 6. Imágenes

  ### Fichero local: 

  La imagen debe de estar en la ruta del fichero. Logo URJC:  
  ![](Logo-urjc.png)

  ### Logo en URL:

  Simplemente introducir la URL:

  ![](https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Elvis_Presley_promoting_Jailhouse_Rock.jpg/800px-Elvis_Presley_promoting_Jailhouse_Rock.jpg)

  ## 7. Citas

  Para citar, utilizamos las llaves: < >
  
    > "Panceta, tocino, morcilla y queso", El Aberroncho.

  ## 8. Tablas

  Usando caracteres ASCII se pueden construir tablas simples:


  |         | Col 1 | Col 2| Col 3| Col4 | BlinBlin |
  |---------|-------|------|------|------| -------- |
  |  Fila 1 |   1   |   2  |   3  |  4   |    5     |
  |  Fila 2 |   2   |   4  |   6  |  8   |  ochenta |
  |  Fila 3 |   3   |   6  |   9  |  12  |  temazos |

  Es muy dificil utilizarlas; hay que tenerlo todo cuadrado.