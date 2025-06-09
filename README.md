# Praca magisterska: Wykorzystanie uczenia maszynowego do przewidywania ruchu sieciowego po awarii
Politechnika Wrocławska, Wydział Informatyki i Telekomunikacji W4N

Autor: Jakub Kudryk

Promotor: dr hab. inż. Róża Goścień, prof. uczelni
## Streszczenie
W pracy przeprowadzono porównanie grafowej oraz płynnej sieci neuronowej w zadaniu predykcji obciążenia łączy w sieci komputerowej, uwzględniając zmienność ruchu po awariach. Testowano różne konfiguracje modeli, wzbogacając je o dodatkowe mechanizmy, takie jak douczanie przyrostowe, kontrola stanu ukrytego oraz rozszerzone dane wejściowe. Najlepsze wyniki osiągnęła płynna sieć neuronowa z historią poprzednich kroków, kontrolą stanu ukrytego i informacjami o sąsiednich połączeniach.
Zaobserwowano, że douczanie przyrostowe nie przyniosło oczekiwanych efektów w przypadku płynnej sieci neuronowej, a dodatkowe metryki z ostatnich kroków czasowych istotnie pogarszały skuteczność obu modeli. Ponadto zauważono, że najlepsze modele w zakresie metryki TConv nie poprawiały innych metryk, a niektóre połączenia w sieci komputerowej systematycznie osiągały najsłabsze wyniki, niezależnie od użytego modelu.
## Abstract
The paper compares a graph and a liquid neural network in the task of link load prediction in a computer network after failure. Different model configurations were tested, enriching them with additional mechanisms such as incremental learning, hidden state control and extended input data. The best results were achieved by a liquid neural network with history, hidden state control and neighboring connection information.
It was observed that incremental learning did not produce the expected results for the liquid neural network, and additional metrics from the last time steps significantly degraded the performance of both models. In addition, it was noted that the best models in terms of the TConv metric did not improve other metrics quality, and some connections in the computer network systematically had poor results regardless of the used model.

## Zawartość repozytorium
W repozytorium znajdują się pliki .ipynb użyte do zaimplementowania i badania modeli. Są dwa foldery zawierające pliki dla sieci LNN i GNN.
