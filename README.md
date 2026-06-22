<img width="2535" height="380" alt="Cabecalho" src="https://github.com/user-attachments/assets/2c889a17-4052-495b-9081-f956c2deebef" />

# Dilema do botão: uma simulação probabilística com análise gráfica e interface interativa

## Descrição

O projeto se resume a simular o dilema dos botões azul e vermelho, que consiste no seguinte cenário: dado um grupo de pessoas e dois botões disponíveis (vermelho e azul) cada indivíduo deve escolher apenas um deles. Caso mais de 50% das pessoas escolham o botão azul, todos sobrevivem. Caso contrário, todos morrem, exceto aqueles que escolheram o botão vermelho.

A partir desse problema, será construída uma simulação de decisões fundamentada em probabilidades, a partir do qual será modelada uma curva de comportamento médio de uma determinada população com diferentes probabilidades de escolher o botão azul, tendo em vista que a decisão a nível individual é secreta. Isso é relevante, pois uma decisão não altera o efeito das demais, ou seja, são decisões independentes.

Posteriormente, os resultados dessa simulação serão analisados por meio de gráficos, com o objetivo de observar como diferentes parâmetros (como probabilidade de escolha e tamanho da população) influenciam o comportamento do sistema.

Além da simulação com modelo matemático, o projeto também incluirá uma interface gráfica interativa feita com a biblioteca Tkinter, para que o usuário possa participar diretamente do dilema, escolhendo entre os botões vermelho e azul em tempo real, e vendo ao final de todos os votos se sobreviveu ou não.

## Instalação e instruções

Para que o código possa ser acessado, é preciso que se instale o arquivo, disponível no repositório "Projeto-final-de-PCD", de acrsfloripa-prog, no Github. Deve-se instalar o arquivo em um ambiente Jupyter, e o código deve ser rodado na linguagem Python, versão 3.13.7. Para que o código rode corretamente, é necessário rodar as células em ordem. Além disso, foram utilizados os módulos e bibliotecas random, matplotlib.pyplot, numpy e tkinter, das quais algumas podem não estar disponíveis no ambiente escolhido. Nesse caso, deve-se então rodar o comando: !pip install biblioteca.

## Ferramentas e tecnologias utilizadas

Ambiente:
  - Jupyter Notebook, utilizado para desenvolver o código.

Bibliotecas e módulos: 
  - random: biblioteca padrão do Python, usada para gerar números pseudoaleatórios;
  - matplotlib.pyplot: módulo da biblioteca externa matplotlib, usado para plotar gráficos;
  - numpy: biblioteca externa, usada para organizar dados nos gráficos;
  - tkinter: biblioteca padrão do Python, usada para a formulação da interface gráfica.

IA:
  - Microsoft 365 Copilot, usada para debugging do código.

## Professores e orientadores

### Leandro Nascimento Lemos
Doutor em Ecologia Molecular pela USP, com pós-doutorados no LNCC, na UNICAMP e na Universidade de Viena. Atualmente, atua como Professor Pesquisador Adjunto II na Ilum Escola de Ciência (CNPEM), em Campinas.

### Daniel Roberto Cassar
Doutor em Ciência e Engenharia de Materiais pela Universidade Federal de São Carlos (UFSCar, 2014). Atualmente é Professor Assistente no Bacharelado em Ciência e Tecnologia da Ilum Escola de Ciência, parte do Centro Nacional de Pesquisa em Energia e Materiais (CNPEM)

### James Moraes de Almeida
Doutor em Nanociências e Materiais Avançados pela UFABC (2012), com pós-doutorados na própria UFABC (2012–2015), na EPFL, na Suíça (2015–2017), e na USP (2017–2019). Atualmente, é professor na Ilum – Escola de Ciência do CNPEM.

## Autoria

### Arthur Cunha Rangel de Sousa
Estudante de bacharelado em Ciência e Tecnologia pela Ilum Escola de Ciência.

## Referências

ALMEIDA, James Moraes de. Processamento de strings. Campinas: Ilum Escola de Ciência (CNPEM), 2026b. Notebook Jupyter (material didático não publicado).

CASSAR, Daniel R. Aula de git. Campinas: Ilum Escola de Ciência (CNPEM), 2026. Notebook Jupyter (material didático não publicado).

CASSAR, Daniel R. Módulo random. Campinas: Ilum Escola de Ciência (CNPEM), 2026. Notebook Jupyter (material didático não publicado).

PYTHON TUTORIAL. Tkinter Tutorial. Disponível em: <https://www.pythontutorial.net/tkinter/>. Acesso em: 18 jun. 2026.
