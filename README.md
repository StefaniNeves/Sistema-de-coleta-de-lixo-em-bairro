
# Simulação de Coleta de Resíduos utilizando Algoritmos em Grafos (Trabalho desenvolvido em equipe- Stéfani, Henrique, Alex)

## Sobre o projeto

Projeto acadêmico desenvolvido durante a graduação em Ciência da Computação, com o objetivo de aplicar conceitos de Teoria dos Grafos e algoritmos na resolução de um problema prático.

O sistema simula a coleta de resíduos em um bairro, representado por meio de um grafo ponderado, no qual os vértices representam pontos de coleta e as arestas representam as conexões entre esses pontos, considerando seus respectivos custos de deslocamento.

A simulação envolve a movimentação de caminhões de coleta, o gerenciamento da quantidade de resíduos, a capacidade dos veículos e o acionamento do Centro de Zoonoses quando necessário.

O projeto utiliza algoritmos em grafos para auxiliar no planejamento dos trajetos e na estimativa dos recursos necessários para realizar a operação.

## Objetivos do projeto

- Aplicar conceitos de Teoria dos Grafos;
- Representar um bairro utilizando grafos ponderados;
- Implementar algoritmos para encontrar caminhos mínimos;
- Simular o deslocamento de veículos de coleta;
- Trabalhar com estruturas de dados e manipulação de informações;
- Aplicar conhecimentos de programação na resolução de problemas reais.

## Funcionalidades

- Representação do bairro por meio de um grafo;
- Definição dos pontos de coleta e suas conexões;
- Representação dos custos de deslocamento;
- Distribuição de resíduos nos pontos de coleta;
- Utilização do algoritmo de Dijkstra para encontrar caminhos mínimos;
- Simulação da coleta de resíduos pelos caminhões;
- Controle da capacidade dos veículos;
- Simulação da presença de animais nos pontos de coleta;
- Acionamento do Centro de Zoonoses;
- Estimativa da quantidade de caminhões e funcionários necessários.

## Tecnologias e ferramentas

| Tecnologia | Finalidade |
|---|---|
| Python | Linguagem utilizada no desenvolvimento do sistema. |
| Algoritmo de Dijkstra | Cálculo de caminhos mínimos no grafo. |
| Heapq | Utilização de fila de prioridade. |
| Random | Geração de dados aleatórios para a simulação. |

## Estrutura do projeto

```text
Projetos/
│
├── grafo.txt
├── main.py
└── README.md
```

### Descrição dos arquivos

- **grafo.txt:** arquivo responsável por armazenar os dados utilizados na representação do bairro, incluindo informações sobre os pontos de coleta, conexões, custos de deslocamento e dados do Centro de Zoonoses.
- **main.py:** arquivo principal responsável pela execução da aplicação, processamento dos dados e realização da simulação.
- **README.md:** documentação do projeto, apresentando seus objetivos, funcionalidades, tecnologias e instruções de execução.

## Algoritmos e conceitos aplicados

### 1. Teoria dos Grafos

O bairro é representado por um grafo ponderado, no qual:

- Vértices representam os pontos de coleta;
- Arestas representam as conexões entre os pontos;
- Pesos representam os custos ou tempos de deslocamento.

Essa estrutura permite representar os caminhos disponíveis e calcular trajetos entre diferentes localidades.

### 2. Algoritmo de Dijkstra

O algoritmo de Dijkstra é utilizado para encontrar o caminho de menor custo entre dois vértices de um grafo ponderado.

Sua implementação permite calcular trajetos entre os pontos de coleta e os locais de destino, como o aterro sanitário e o Centro de Zoonoses.

### 3. Simulação da coleta de resíduos

O sistema simula o deslocamento dos caminhões pelos pontos de coleta, considerando a quantidade de resíduos, a capacidade dos veículos e os custos de deslocamento.

### 4. Centro de Zoonoses

O projeto contempla uma estrutura destinada à representação do Centro de Zoonoses, considerando sua localização e sua participação na simulação de recolhimento de animais identificados nos pontos de coleta.

## Como executar o projeto

### Pré-requisitos

- Python 3 instalado;
- Editor de código ou terminal;
- Visual Studio Code (opcional).

### Passo a passo

**1. Clone o repositório**

```bash
git clone https://github.com/StefaniNeves/Projetos.git
```

**2. Acesse a pasta do projeto**

```bash
cd Projetos
```

**3. Execute o programa**

```bash
python main.py
```

Caso seu ambiente utilize o comando `python3`, execute:

```bash
python3 main.py
```

**4. Visualize os resultados**

Após a execução, o programa realizará a simulação e apresentará os resultados referentes à coleta de resíduos e ao funcionamento dos componentes envolvidos.

### Observação

O arquivo `grafo.txt` deve permanecer na mesma pasta que `main.py`, pois contém os dados necessários para a execução da simulação.

Não é necessário instalar bibliotecas externas caso sejam utilizados apenas os módulos nativos do Python presentes no projeto.

## Equipe de desenvolvimento

Projeto desenvolvido em equipe por:

- **Stéfani Rodrigues Neves**
- **Henrique**
- **Alex**

## Minha contribuição — Stéfani Rodrigues Neves

Minha participação no projeto esteve concentrada na implementação da parte referente ao Centro de Zoonoses e na colaboração com a documentação.

Principais atividades desenvolvidas:

- Implementação da parte referente ao Centro de Zoonoses no arquivo `grafo.txt`;
- Organização e estruturação dos dados relacionados ao Centro de Zoonoses;
- Colaboração na organização e elaboração do arquivo `README.md`;
- Participação no desenvolvimento colaborativo do projeto.

### Conhecimentos aplicados

- Python;
- Teoria dos Grafos;
- Estruturação e organização de dados;
- Modelagem de problemas computacionais;
- Desenvolvimento colaborativo;
- Documentação técnica.

## Contribuição dos demais integrantes

**Henrique**
- Responsável pela implementação da parte referente ao bairro no arquivo `grafo.txt`.

**Alex**
- Responsável pelo desenvolvimento do arquivo principal `main.py`, contendo a lógica de execução da aplicação.

## Aprendizados

O desenvolvimento deste projeto proporcionou experiência prática com:

- Teoria dos Grafos;
- Grafos ponderados;
- Algoritmo de Dijkstra;
- Caminhos mínimos;
- Estruturas de dados;
- Programação em Python;
- Modelagem de problemas reais;
- Trabalho em equipe e desenvolvimento colaborativo.

---

**Projeto acadêmico desenvolvido durante a graduação em Ciência da Computação.**
