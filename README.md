# Lectura de datos de un archivo PDF

Existen ocaciones en la que necesitamos obtener datos de un pdf por lo que podemos usar la libreria PyPDF2 la cual nos puede ayudar en ciertos casos, haciendo pruebas con diferentes archivos pdf, no siempre obtengo resultados almenos no hasta ahora.
Por lo que en este proyecto se pueden encontrar 2 situaciones:

- 1.- Leer datos de un solo archivo pdf
Aqui uso la función extract_text_from_pdf y para guardar el resultado de la lectura uso la función save_text_to_file.

- 2.- Leer datos de varios archivos pdf situados en una carpeta
Para leer varios archivos pdf de una carpeta uso la función process_pdfs_in_folder.En este caso se genera un archivo de salida por cada pdf procesado

Este proyecto esta hecho en lenguaje python. el codigo principal esta en el archivo notebook lector_pdf.ipynb

