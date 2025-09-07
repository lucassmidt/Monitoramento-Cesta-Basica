# Monitoramento-Cesta-Basica
Como atividade do curso de ADS, foi solicitado a criação de um pseudocódigo para monitoramento dos preços da cesta básica. O sistema analisa os preços de uma lista de três produtos da cesta básica, comparando os valores do mês atual com os do mês anterior e exibindo se o preço aumentou, diminuiu ou permaneceu estável.

## 📌 Funcionalidades

- Leitura de dados de três produtos:
  - Nome
  - Preço anterior
  - Preço atual
- Cálculo da variação percentual
- Classificação da situação do preço
- Exibição de resumo com:
  - Nome do produto
  - Preço anterior
  - Preço atual
  - Variação percentual
  - Situação

## 🧠 Lógica de Classificação

- Se a variação for **maior que 0** → `AUMENTO`
- Se a variação for **menor que 0** → `QUEDA`
- Se a variação for **igual a 0** → `ESTÁVEL`

## 🧮 Estrutura de Dados

O algoritmo utiliza vetores para armazenar os dados de cada produto:

- `nome[1..3]`: tipo caractere (string)
- `preco_anterior[1..3]`: tipo real (float)
- `preco_atual[1..3]`: tipo real (float)
- `variacao[1..3]`: tipo real (float)
- `situacao[1..3]`: tipo caractere (string)

## 🧑‍💻 Autor

Desenvolvido por **Lucas**, estudante de programação e entusiasta de algoritmos aplicados à realidade social.
