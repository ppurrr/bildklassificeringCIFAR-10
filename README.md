Bildklassificering - CNN för CIFAR-10

Detta projekt tränar en Convolutional Neural Netwrok för att klassificera bilder i CIFAR-10-dataset. Modellen tränas med dataaugmentation, dropout och early-stopping för föbättring av prestanda

För att köra koden behöver du: 
-Python 3.x
-Pytorch
-torchvision
-Numpy
-PIL

Installation av libraries: 
pip install torch torchvision numpy pillow

För att köra modellen: 
1. Träna modellen kör följande script: 
python train.py 

scriptet tränar modellen med CIFAR-10 och sparar den bästa modellen som best_model.pth.

2. Testa modellen kör följande script: 
python evaluate.py

scriptet laddar den sparade modellen och beräkna testaccuracy

3. För att klassificera egna bilder kör script: 
Python predict.py path/to/image.jpg

Där path/to/image.jpg ersätts med sökvägen till din bild

Filstruktur: 
Projk AI
--dataset   
--BildID.ipynb
--best_model.pth
--README.tx
