# Previsão de PH em processos agroindustriais
Esse projeto, em parceria com a [Pentagro](https://pentagro.com.br/), tem como objetivo a criação de um modelo capaz de capturar padrôes temporais complexos para melhorar a precisão da previsão de PH no processo da produção de açúcar.

## Sobre a Pentagro
A Pentagro é uma empresa especialista prover ganhos operacionais através de soluções de simulação e otimização para a indústria de processos agroindustriais.

## Dados
Os dados foram coletados a partir de sensores em diversas etapas da produção do açúcar. O dataset utilizado é composto por observações feitas em intervalos de 3 segundos por um período de 60 dias de operação, totalizando mais de 1 milhão de linhas.

### Variável de saída
A variável PH dosado é obtida após o tratamento do caldo de cana clarificado, no qual se adiciona uma solução de óxido de cálcio (CaO), conhecida como leite de cal, para regular o PH e neutralizar a acidez do caldo.

## Desenvolvimento
Explorar e verificar:
- As melhores técnicas para tratamento e pré-processamento dos dados.
- A melhor técnica e estrutura para o modelo preditivo.

### Requisitos do modelo
- Dar respostas em milissegundos.
- Predizer o valor da variável dependente 5 minutos a frente no tempo.
- Possuir um erro menor que 2%.