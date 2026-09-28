# AEDs II: Revisão e Nivelamento
Atividade de revisão e nivelamento da disciplina de AEDs II, abordando programação orientada por objetos e uso de arquivos texto.

## Aluno

* Bárbara Marcella Inácio da Silva

## Origem da atividade
Base da professora: https://github.com/IsabelaBB/template_AEDs-II_Unidade0
Implementações das atividades anteriores adaptadas de https://github.com/Stteinz/template_AEDs-II_Unidade0.

## Como executar
Use JDK 21 no IntelliJ. Abra a classe desejada e execute seu método main.
Para AppProdutos, o diretório de trabalho deve ser a raiz do projeto, onde está dadosProdutos.csv.

- AppProdutos: lê os produtos do CSV, permite listar, buscar pelo nome exato e cadastrar até 10 novos produtos por execução. A opção 0 salva e encerra.
- Produto: classe abstrata com descrição, custo e margem de lucro.
- ProdutoNaoPerecivel: preço de venda = custo * (1 + margem).
- ProdutoPerecivel: aplica desconto de 25% quando faltam até 7 dias para vencer. Produtos vencidos já existentes são mantidos e identificados; novos cadastros com validade passada são recusados.
- Margem de 20% deve ser digitada como 0,2 (ou 0.2).
- App: mede tempo e contagem de operações de quatro algoritmos. Código 1 percorre índices pares (linear); código 2 soma laços com limites reduzidos pela metade (linear); código 3 faz seleção (quadrático); código 4 calcula Fibonacci recursivamente (exponencial).

## Dados e resultados
O CSV começa com a quantidade de produtos. As linhas seguintes usam tipo;descrição;custo;margem;validade, sendo a validade exclusiva de perecíveis.
resultados.txt e resultados.xlsx são resultados recuperados da cópia recebida, não uma nova medição deste computador.
A execução completa de App demanda bastante memória e tempo: o maior vetor contém 500 milhões de inteiros (cerca de 2 GB apenas para seus elementos).
Fibonacci retorna long para comportar o resultado de n=48.