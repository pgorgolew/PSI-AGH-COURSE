# Cel

Celem laboratorium jest przedstawienie zastosowań sieci neuronowych w rozpoznawaniu 
obrazów.

1. Krótki wstęp do sieci typu konwolucyjnego (CNN).
2. Pretrening, zastosowanie gotowej sieci do detekcji obiektów.
3. Transfer learning i finetuning, zastosowanie do klasyfikacji obrazów.
4. Wykrywanie obiektów w obrazie w czasie rzeczywistym.

Zawartość laboratorium dostępna jest w [notebooku](lab_4.ipynb).


## New conda env was required for this lab

1. create anaconda env and activate
2. `conda install -c conda-forge opencv `
3. `conda install numpy matplotlib pandas pytorch torchvision torchaudio pytorch-cuda -c pytorch -c nvidia`
4. `conda install -c anaconda ipykernel`
5. `pip install opencv-contrib-python`
6. `python -m ipykernel install --user --name=PSI`