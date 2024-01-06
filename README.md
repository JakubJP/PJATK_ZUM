# PJATK_ZUM
PJATK ZUM Praca domowa

Dane: plik CSV, język polski, opinie pacjentów dotyczące wizyty w szpitalu/klinice lub innych o tematyce medycznej. Na końcu zdania dodane są odpowiednie etykiety: 
* __label__z_minus_m - negatywne
* __label__z_zero - neutralne
* __label__z_amb - niejednoznaczne
* __label__z_plus_m - pozytywne
  
Na potrzeby tego projektu zdania z etykietą zero i amb zostają pominięte
Źródło danych: https://clarin-pl.eu/dspace/handle/11321/710 -> tylko plik medicine.sentence.train

Modele: LSTM, CNN, pre-trained word embedding, DistilBert

Plik sentiment-medical-pl-utf.csv zawiera dane treningowe

Obsługa: Otworzyć w Google Colab plik NLP-models.ipynb, uruchomić komórkę z połączeniem z dyskiem Google, plik CSV pobrany z GitHuba wystarczy wrzucić do najwyższego poziomu dysku Google, zachowując orginalną nazwę pliku.
