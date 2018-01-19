# Style-Transfer
CPU-friendly Neural Style Transfer con Tensorflow e PyTorch. Basato su VGG-16 e VGG-19.

# Descrizione

Crea fantastiche opere d'arte con le tue fotografie lasciando che il tuo PC si ispiri ai grandi pittori del passato e di oggi.

# Requisiti

- Python 3.6
- Jupyter Notebook
- PIL
- Tensorflow
- Numpy
- Matplotlib
- Pygame
- Clint
- Torch & Torchvision ([Istruzioni Installazione](http://pytorch.org/))

I suddetti pacchetti sono reperibili tramite i package manager Anaconda e PyPI.

# Istruzioni

Eseguire i Jupyter Notebook cambiando le righe di codice relative alle immagini da caricare, e a quanti minuti si vuole lasciar lavorare l'algoritmo.

Digitare:

```sh
$ jupyter notebook
```

nel proprio terminale ed aprire il notebook che si desidera (VGG-16 o VGG-19).

# NOTE

- Questa è una versione CPU-friendly, si consiglia di non aumentare di oltre 512x512 la risoluzione delle immagini.
- Per ottenere risultati soddisfacenti con immagini ad alta risoluzione si consiglia l'impiego di una GPU dotata di tecnologia CUDA e di compilare il pacchetto tensorflow-gpu da codice sorgente.  [Tutorial](https://www.tensorflow.org/install/).
- La versione VGG-19 non necessita di ulteriori modifiche al livello di codice.
- È presente una versione commentata all'interno del codice dei notebook che si basa sulla convergenza delle funzioni di perdita. Basta togliere il commento da queste porzioni di codice e commentare quelle della versione originale per poter testare questo metodo.
- Per ogni dubbio rivolgersi al sottoscritto.

# Licenza

Copyright (c) 2018 Emanuele Fabi

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
