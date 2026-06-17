# Redes-Neuronales-2025

En este trabajo se analizo el impacto del preentrenamiento de un autoencoder convolucional a la hora de en
trenar un clasificador para el conjunto Fashion-MNIST. Se compararon distintos escenarios: entrenamiento con
junto del encoder y el clasificador (fine-tuning completo) y entrenamiento exclusivo del clasificador usando el en
coder congelado, tanto preentrenado como sin entrenar. Los resultados muestraron que el preentrenamiento no
aporta mejoras significativas cuando el encoder se ajusta completamente, obteniendose desempeños similares a los
de un modelo entrenado desde cero. Sin embargo, cuando el encoder permanece congelado, el preentrenamiento
sı produce una mejora consistente, proporcionando una representacion latente mas estable y adecuada para la
clasificacion. Ademas, se observo que un encoder congela do sin entrenar puede alcanzar un desempeño razonable,
funcionando de manera similar a un extractor de caracteristicas aleatorias. En conjunto, los experimentos indi
caron que el preentrenamiento resulta beneficioso principalmente cuando el encoder se utiliza como extractor fijo
de caracterısticas.
