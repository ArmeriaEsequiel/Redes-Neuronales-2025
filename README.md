# Redes-Neuronales-2025

En este trabajo se analizo el impacto del preentrena
miento de un autoencoder convolucional a la hora de en
trenar un clasificador para el conjunto Fashion-MNIST.
Se compararon distintos escenarios: entrenamiento con
junto del encoder y el clasificador (fine-tuning completo)
y entrenamiento exclusivo del clasificador usando el en
coder congelado, tanto preentrenado como sin entrenar.
Los resultados muestraron que el preentrenamiento no
aporta mejoras significativas cuando el encoder se ajusta
completamente, obteni´endose desempe˜nos similares a los
de un modelo entrenado desde cero. Sin embargo, cuan
do el encoder permanece congelado, el preentrenamiento
s´ı produce una mejora consistente, proporcionando una
representaci´on latente m´as estable y adecuada para la
clasificaci´on. Adem´as, se observo que un encoder congela
do sin entrenar puede alcanzar un desempe˜no razonable,
funcionando de manera similar a un extractor de carac
ter´ısticas aleatorias. En conjunto, los experimentos indi
caron que el preentrenamiento resulta beneficioso princi
palmente cuando el encoder se utiliza como extractor fijo
de caracter´ısticas.
