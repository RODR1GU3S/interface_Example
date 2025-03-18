# Java Interface Example

Este repositório contém um exemplo de uso de interfaces em Java, demonstrando herança, polimorfismo e boas práticas de orientação a objetos.

## Tecnologias Utilizadas
- Java
- Programação Orientada a Objetos (POO)

## Estrutura do Projeto
```
application/
    Program.java
model/
    entities/
        Shape.java
        AbstractShape.java
        Circle.java
        Rectangle.java
    enums/
        Color.java
```

## Descrição das Classes
- **Shape**: Interface que define o método `area()`.
- **AbstractShape**: Classe abstrata que implementa `Shape` e adiciona um atributo de cor.
- **Circle**: Implementa `AbstractShape` e define o cálculo da área de um círculo.
- **Rectangle**: Implementa `AbstractShape` e define o cálculo da área de um retângulo.
- **Color**: Enumeração para definir cores (BLACK e WHITE).
- **Program**: Classe principal que instancia e exibe as informações sobre formas geométricas.

## Como Executar
1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Compile os arquivos Java:
   ```sh
   javac application/Program.java
   ```
3. Execute o programa:
   ```sh
   java application.Program
   ```

## Saída Esperada
```
Circle color: BLACK
Circle area: 12.566
Rectangle color: WHITE
Rectangle area: 12.000
```

## Contribuição
Sinta-se à vontade para abrir issues e enviar pull requests para melhorias.
