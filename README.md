# COVID detection
<strong>SK</strong>
<br><br>
Tento priečinok obsahuje kód konvolučnej neurónovej siete určenej pre detekciu COVID-19 na základe CT skenov a natrénovaný model. Je to súčasť mojej bakalárskej práce.

### Obsah:
<ul>
  <li>Súbor <strong>CNNcovid-source_code.ipynb</strong> - zdrojový kód, ktorý obsahuje: celú úpravu dát a rozdelenie množín, vytváranie modelu, jeho trénovanie, testovanie s výsledkami a zobrazenie nesprávne klasifikovaných prípadov.</li>
  <li>Súbor <strong>mymodel.hdf5</strong> - model, ktorý bol natrénovaný a môže byť použitý na klasifikáciu.</li>
</ul>

### Použitie:
<ol> 
  <li>Aby ste mohli použiť skript a model, musíte si stiahnuť dataset z verejného priečinku: https://www.kaggle.com/plameneduardo/sarscov2-ctscan-dataset. Dáta sú tu rozdelené do dvoch priečinkov - COVID and non-COVID</li>
  <li>Oba priečinky musia spolu uložené v inom priečinku, ktorý ľubovoľne pomenujte (napr. náš priečinok sa nazýval "original_dataset").</li>
  <li>Otvorte zdrojový kód v programe, ktorý dokáže pracovať s ipynb súbormi. Odporúčame Jupyter Notebook.
  <li>Upravte cestu k zdrojovému priečinku v premennej "source_dir" podľa toho, kam ste si uložili dataset.</li>
  <li>Nainštalujte si knižnice, ktoré sú importované v provom bloku kódu, ak náhodou ešte niektoré nemáte stiahnuté.</li>
</ol>

<hr>
<strong>EN</strong>
<br><br>
This repository contains code of CNN used for COVID-19 detection from CT scans and a trained model. It's a part of my bachelor thesis. 

### Contains: 
<ul>
  <li>File <strong>CNNcovid-source_code.ipynb</strong> - source code which includes: entire data preparation and datasets splitting, model building, training, testing with results and showcase of incorrectly classified cases.</li>
  <li>File <strong>mymodel.hdf5</strong> - model that has been trained and can be used for classification.</li>
</ul>

### Usage:
<ol> 
  <li>In order to use the script and the model, you need to download the data from public repository: https://www.kaggle.com/plameneduardo/sarscov2-ctscan-dataset. Data is split into two folders - COVID and non-COVID</li>
  <li>Both folders need to be inside of another folder of your choice (e.g. our folder was called "original_dataset").</li>
  <li>Open the source code in a program that's able to work with ipynb files. We suggest Jupyter Notebook.
  <li>Change the path to this source data folder in a variable called "source_dir", based on where you have saved the dataset.</li>
  <li>Install any of the libraries imported in the firt part of the code you don't already have installed.</li>
</ol>
