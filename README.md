# Análisis de los patrones de diseño posibles
## Singleton
El patrón singleton es útil cuando se quiere crear una única instancia de una clase y usar la misma de manera global en el resto del programa, sin embargo, el propósito de este programa es ensamblar varias instancias de distintas computadoras, por lo que Singleton no es el patrón ideal
## Builder
El patron Builder es util cuando se encuentra compuesto por objetos que deben ser creados paso a paso antes de hacer el objeto final, llevandolo al ejemplo, tenemos un computador que tiene mainboard y el sistema operativo, por lo que este patron seria de gran ayuda.
## Factory Method
El patron Factory Method permite reutilizar los metodos que crean los objetos haciendo un metodo generalizado en lugar de usar el new, por ello este patron podria llegar a ser util para la implementacion, ademas ayuda a simplificar el proceso complejo de contruccion. 
## Abstract Factory
El patron Abstract Factory permite crear distintos objetos que tienen similitudes entre si basandose en las caracteristicas que estos objetos comparten, por esto seria util ya que las computadoras comparten varios atributos.
## El patron seleccionado es el Builder, ya que simplifica el proceso de construcción, y además permite crear varios objetos de la misma clase, ya que las computadoras poseen los mismos atributos.
##diagrama
![image](https://user-images.githubusercontent.com/93171012/176823146-3eef2622-329b-42e5-a9d9-62797105c164.png)
