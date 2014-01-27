reverbAsStorage
===============

Exploramos las posibilidades de la reverberación como sistema de almacentamiento de datos a corto plazo.

## Experimento:

 Nuestro primer reto es tomar un archivo pequeño, convertirlo a audio, hacerlo pasar por un reverberador con un decay largo y tratar de recuperar el archivo a la salida de la reverberación cuando ya el sonido original no esta presente.

- se crea un archivo con un texto adentro
- se convierte en wav con audacity (idealmente insertando los encabezados que explican acá https://ccrma.stanford.edu/courses/422/projects/WaveFormat/  pero mas adelante lo hacemos así)
- abrimos zita-rev1  http://kokkinizita.linuxaudio.org/linuxaudio/downloads/index.html
- capturamos la reverb con sox o audacity
- abrimos el archivo wav con emacs M-x hexl-find-file y tratamos de encontra el texto allí.
