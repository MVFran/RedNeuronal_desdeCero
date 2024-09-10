# Red Neuronal

En este código, se hace la implementación de una red neuronal encargada de clasificar puntos en tres clases diferentes, utilizando los datos `make_moons` de la libreria [scikit learn](https://scikit-learn.org/stable/index.html), esto con el algoritmo backpropagation.

A continuación, se muestra el diagrama de la red que se implementó:

![DiagramaDeRedNeuronal](/images/DiagramaDeRedNeuronal.PNG)

Como función de activación para la primera capa oculta, se utilizó la función ReLU, que se define como:

$$ ReLU(z) = max(0,z) $$

Seguido a esto, se utilizaron dos funciones de activación distintas para observar las diferencias que presentaba cada una, las cuales fueron:

$$ tanh(z) \ \& \ sigmoide(z) = \frac{1}{1+e^{-z}}$$