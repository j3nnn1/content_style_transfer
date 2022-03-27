# content_style_transfer

# Las respuestas de las preguntas desde la 1 a la 6 se encuentran en la notebook en forma de comentarios

    https://github.com/j3nnn1/content_style_transfer/blob/main/cnn_style_transfer.ipynb

# primera ejecucion pregunta 7
### Parametros usados.
    total_variation_weight = 0.1
    style_weight = 10
    content_weight = 1
#### Original.
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/775px-Neckarfront_T%C3%BCbingen_Mai_2017.jpg" width="200" height="200"/>

#### Estilo de referencia.
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/La_noche_estrellada1.jpg" width="200" height="200"/>

#### Nueva imagen generada con estilo de referencia iteracion 0 y 100.
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/content/01_primeraEjecucion.toGithub/output_at_iteration_0.png" width="200" height="200"/>
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/content/01_primeraEjecucion.toGithub/output_at_iteration_99.png" width="200" height="200"/>

# Ejecuciones pregunta 8
### Imágenes para distintas combinaciones de pesos de las losses - 1era ejecucion
### Parametros
    # total_variation_weight = 0.2
    # style_weight = 100
    # content_weight = 1
### comentarios:
    cambio un poco la intensidad de los colores, con esta combinacion tiene colores mas oscuros y mate
    tiene pocas diferencias con respecto a la anterior configuracion pero se nota un poco en los colores 
    tendiendo hacia la paleta de colores de la imagen de estilo de referencia.

#### Nueva imagen generada con estilo de referencia iteracion 0.
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/content/02_segundaEjecucion.toGithub/output_at_iteration_0.png" width="200" height="200"/>

### Imágenes para distintas combinaciones de pesos de las losses - 2da ejecucion
### Parametros
    # total_variation_weight = 0.1
    # style_weight = 1
    # content_weight = 10
### comentarios:
    se visualiza que las lineas, formas y estructura del contenido se mantiene,  muy poco varia a diferencia de la anterior 
    ejecucion donde las luces, y formas circulares tomaban mas la estructura de la imagen de referencia del estilo.

#### Nueva imagen generada con estilo de referencia iteracion 0.
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/content/03_terceraEjecucion.toGithub/output_at_iteration_0.png" width="200" height="200"/>

### Imágenes para distintas combinaciones de pesos de las losses - 3era ejecucion
### Parametros
    # total_variation_weight = 0.1
    # style_weight = 1
    # content_weight = 10000
### comentarios:
    muy claro que muestra pocos cambios de estilo y la paleta de colores es identica a la fotografia original
    conserva claramente la estructura del contenido y tambien los colores, algunas lineas tienen el estilo de
    la fotografia de referencia del estilo.

#### Nueva imagen generada con estilo de referencia iteracion 0.

<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/content/04_cuarta_ejecucion.toGithub/output_at_iteration_0.png" width="200" height="200"/>

# Ejecuciones pregunta 9
## Cambiar las imágenes de contenido y estilo por unas elegidas por mi.

## Ejecucion 1 - Olas y Mar del plata

### parametros
    # total_variation_weight = 0.2
    # style_weight = 100
    # content_weight = 1

### imagen original
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/playa.jpg" width="200" height="200"/>

### imagen con la referencia del estilo
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/wave_estilo.jpg" width="200" height="200"/>

### nueva imagen
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/content/06_ejecucion_wave_02.toGithub/output_at_iteration_0.png" width="200" height="200"/>
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/content/06_ejecucion_wave_02.toGithub/output_at_iteration_20.png" width="200" height="200"/>

## Ejecucion 2 - Gato y Monet
### imagen original
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/base_wichy.jpg" width="200" height="200"/>

### imagen con la referencia del estilo
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/monetEstilo2.jpg" width="200" height="200"/>

### nueva imagen
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/content/07_ejecucion_wichy_base.toGihub/output_at_iteration_0.png" width="200" height="200"/>
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/content/07_ejecucion_wichy_base.toGihub/output_at_iteration_19.png" width="200" height="200"/>
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/content/07_ejecucion_wichy_base.toGihub/output_at_iteration_99.png" width="200" height="200"/>

## Ejecucion 3
### imagen original
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/base_wichy2.jpg" width="200" height="200"/>

### imagen con la referencia del estilo
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/estiloMonet.jpg" width="200" height="200"/>

### nueva imagen
<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/content/08_ejecucion_wichy_base2.toGithub/output_at_iteration_0.png" width="200" height="200"/>

<img src="https://github.com/j3nnn1/content_style_transfer/raw/main/content/08_ejecucion_wichy_base2.toGithub/output_at_iteration_20.png" width="200" height="200"/>
