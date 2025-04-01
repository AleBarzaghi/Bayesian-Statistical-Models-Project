#AirBnb Houses Price Prediction 
Il progetto mira a prevedere, tramite modelli di statistica Bayesiana, il prezzo delle case in affitto su AirBnb a Barcellona. Oltre all'obiettivo di previsione, si è interessati a stabilire se l'introduzione delle coordinate posizionali delle case aumenti la precisione del modello. 
##First Model 
Il primo modello è un modello regressivo, che considera tutte le covariate escluse quelle di posizione, ottenenendo il modello ottimale tramite variable selection con spike and slab
##Second Model 
Il secondo modello viene creato analogamente al primo, aggiungendo però le informazioni posizionali delle case.

##Confronto
L'ultima fase è quella del confronto tra i due modelli, per stabilire se le coordinate posizionali migliorino la capacità previsiva del modello. 