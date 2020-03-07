# FigurasGeometricas
Aula 01- Arquitetura e Desenvolvimento de Sistemas Multicamadas


1. Crie a seguinte hierarquia de classes de figuras geométricas. Veja na figura as
fórmulas:
a. A classe abstrata Figura deve ter o método abstrato area.
b. A classe concreta Circulo é subclasse de Figura.
c. A classe abstrata Poligono é subclasse de Figura e deve ter os atributos base e
altura .
d. As classes concretas Triangulo, Losango, Retangulo e Quadrado são subclasses
de Poligono. Tente criar mais uma generalização aqui olhando as fórmulas da área.
e. Os polígonos Retangulo e Quadrado devem implementar a interface Diagonal,
que deve ter um método que calcula a diagonal.
f. Crie uma classe Geometria com um ArrayList de Figuras com pelo menos uma
figura de cada e imprima suas áreas, perímetros e diagonais.
Obs: use a anotação @Override nos métodos sobrepostos (ou sobrescritos).
2. Implemente agora o método abstrato perímetro na classe Figura. Como
consequência, você terá que implementá-lo em todas as classes concretas.
3. Crie a classe concreta Trapezio. De quem ela deve ser subclasse?
4. Altere a sua herarquia de classes para agora calcular também o volume. Crie as
classes Cubo, Esfera, Cilindro e Piramide. É melhor resolver por herança ou por
composição?
