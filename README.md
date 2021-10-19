# Autoencoders para colorear imágenes

![bannerIA2](https://user-images.githubusercontent.com/71358878/137845424-6f4cde35-7a1c-4fe2-a9c6-24bb1c690ca1.png)

Autores: David Rojas, Nicolás Galván, Hazel Pinzón.

# Objetivo:
Implementar diversos modelos de autoencoders para la coloración de imágenes, de tal manera que podamos traer al futuro las imágenes de nuestro pasado. Asímismo, se busca comparar dichos modelos mediante métricas en el estado del arte del "Image Quality Assessment", los cuales se diferencian en su número de capas y de si las mismas se encuentran concatenadas o no.

# Dataset:
El dataset utilizado fue encontrado en Kaggle, el cual contiene 7129 imágenes de calles, edificios, montañas, glaciares, árboles, etc. y su correspondiente imagen en escala de grises en dos carpetas diferentes. https://www.kaggle.com/theblackmamba31/landscape-image-colorization

# Modelos: 

Los modelos se encuentran en una carpeta de drive debido a que son muy pesados: https://drive.google.com/drive/folders/13_sR5YkHSzI2cRWhfESb6aGN5fCdtSqW?usp=sharing

- <b>modelo-AE-concatL:</b> Autoencoder con menor número de capas y a su vez dichas capas se encuentran concatenadas.
- <b>modelo-AE-concatM:</b>  Autoencoder con mayor número de capas y a su vez dichas capas se encuentran concatenadas.
- <b>modelo-AE-noconcatL:</b>  Autoencoder con menor número de capas y sin concatenación entre capas.
- <b>modelo-AE-noconcatM:</b>  Autoencoder con mayor número de capas y sin concatenación entre capas.
- <b>ckpt-10:</b> Modelo para colorear imágenes mediante GAN's (extra)


# Enlaces del código, video, y repositorio:

- Código: Se dividió el notebook en dos partes para poderlo subir a GitHub:
1. Parte 1 con los modelos de autoencoders: https://github.com/hazel1399/ProyectoIA2/blob/main/proyectoIA2-Parte1-Modelos.ipynb
2. Parte 2 con resultados de los modelos en base a imágenes antiguas de la UIS y Bucaramanga: https://github.com/hazel1399/ProyectoIA2/blob/main/proyectoIA2-Parte2-Resultados.ipynb
- Vídeo: https://www.youtube.com/watch?v=Tzk7aIQNArs
- Repositorio: https://github.com/hazel1399/ProyectoIA2

