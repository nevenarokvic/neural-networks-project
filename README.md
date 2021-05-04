# Upustvo



Projekat sadrži sledeće fajlove:

- Music generation[RNN LSTM] - Jazz music.ipynb 
<br>U ovom notebook-u se nalazi kod kojim je izvršen data scraping, čuvanje midi fajlova i analiza dataset-a.</br>
- Prepare_and_train_the_net.ipynb 
<br>U ovom notebook-u se nalazi proces pripreme inputa za mrežu, konstrukcija mreže i treniranje.</br>
- Generate(the_best_model).ipynb
<br>U ovom notebook-u se učitava najbolji model iz procesa treniranja, vrši se priprema input sekvence za generisanje midi fajla, i na kraju se generiše fajl (fajlovi se nalaze u folderu model2(BEST))</br>
- notes folder
<br> U ovom folderu su sačuvane note koje su dobijene iz dataset-a (Music generation[RNN LSTM] - Jazz music.ipynb)
- model2(BEST) folder
<br> Ovde su sačuvani najbolji model (weights iz 41. epohe, to jest poslednje do koje je loss opadao) i tri midi fajla koja je generisala mreža.</br>
- Nevena_Rokvic_E2_147_2019.pdf
<br>Rad u kojem je opisan čitav proces i rezultati.</br>
