<img width="2535" height="380" alt="Cabecalho" src="https://github.com/user-attachments/assets/0a2d76bb-b3c9-4128-87b0-cdb82112a749" />

# Análise composicional de sequências de nucleotídeos e aminoácidos

## Descrição do projeto
Esse projeto foi desenvolvido para a disciplina de Práticas em ciências de dados do curso de Bacharelado em Ciência e Tecnologia da Ilum Escola de Ciência, onde foi proposto criar um código que desafiasse o discente que o desenvolvesse. Para isso, decidi criar uma interface que tem como objetivo analisar a composição de sequências de nucleotídeos e aminoácidos, realizando transcrição, tradução, geração do reverso complementar e cálculo do conteúdo gc, a fim de compreender características estruturais e funcionais das sequências biológicas.

## Instalação e instruções
O código pode ser acessado ao instalar o arquivo disponibilizado no Github e rodado em linguagem Python na versão 3.13.7. Para utilizar a interface é necessário rodar todas as células na ordem em que foram escritas, permitindo um funcionamento adequado.
Para o uso, é necessário inserir a sequência que o usuário deseja analisar no espaço indicado e, em seguida, selecionar o botão referente à aplicação.
Há um total de cinco botões disponíveis, sendo eles referentes às seguintes funcionalidades: reverso complementar, transcrição, tradução, porcentagem do conteúdo GC e gráfico do conteúdo GC, que serão abordados com maior descrição a frente.

## Funcionalidade
  -**Reverso complementar**: Inverte a sequência e retorna a base complementar da que se encontra na posição. Adenina(A) é complementar da Timina(T) e Guanina(G) é complementar da Citosina(C), e vice-versa.
  
  -**Transcrição**: Substitui a Timina (T) por Uracila (U) para converter a sequência de DNA em RNA.
  
  -**Tradução**: Lê a sequência em trincas e retorna o códon correspondente.
  
  -**Porcentagem do conteúdo GC**: Indica a porcentagem de bases nitrogenadas formadas por citosina e guanina na sequência de DNA ou RNA.
  
  -**Gráfico do conteúdo GC**: Indica graficamente essa porcentagem em janelas de 10 bases nitrogenadas por vez.

## Tecnologias Utilizadas
#### Ambiente:
  - **Jupyter Notebook**: utilizado para desenvolver e executar o código.
#### Bibliotecas:
  - **CustomTkinter**: biblioteca utilizada para o desenvolvimento da interface;
  - **Pillow (PIL)**: biblioteca que permite abrir a imagem do código na interface;
  - **Pandas**: biblioteca para organização e criação de tabela;   
  - **Matplotlib**: cria um gráfico e o salva como imagem.
#### Uso de Inteligência Artificial(IA):
As inteligencias artificiais Microsoft Copilot e Claude foi utilizada ao longo do projeto para as seguintes funções:
  - Apresentar o Single letter code de cada aminoácido e codon correspondente;
  - Auxiliar no debugging do código;
  - Esclarecimento de dúvidas.
    
## Professores orientadores
### Leandro Nascimento Lemos
Doutor em Ecologia Molecular pela USP, com pós-doutorados no LNCC, na UNICAMP e na Universidade de Viena. Atualmente, atua como Professor Pesquisador Adjunto II na Ilum Escola de Ciência (CNPEM), em Campinas.
### Daniel Roberto Cassar
Doutor em Ciência e Engenharia de Materiais pela Universidade Federal de São Carlos (UFSCar, 2014). Atualmente é Professor Assistente no Bacharelado em Ciência e Tecnologia da Ilum Escola de Ciência, parte do Centro Nacional de Pesquisa em Energia e Materiais (CNPEM)
### James Moraes de Almeida
Doutor em Nanociências e Materiais Avançados pela UFABC (2012), com pós-doutorados na própria UFABC (2012–2015), na EPFL, na Suíça (2015–2017), e na USP (2017–2019). Atualmente, é professor na Ilum – Escola de Ciência do CNPEM.

## Autoria
### Raquel Bentes Lima
Estudante de bacharelado em Ciência e Tecnologia na Ilum Escola de Ciência.

## Referências
ALMEIDA, James Moraes de. **Práticas em Ciência de Dados: Pandas**. Campinas: Ilum Escola de Ciência (CNPEM), 2026a. Notebook Jupyter (material didático não publicado).
  
ALMEIDA, James Moraes de. **Processamento de strings**. Campinas: Ilum Escola de Ciência (CNPEM), 2026b. Notebook Jupyter (material didático não publicado).

CASSAR, Daniel R. **Desempacotando listas e dicionários com operadores estrela**. Campinas: Ilum Escola de Ciência (CNPEM), 2026. Notebook Jupyter (material didático não publicado).

ELDER, John. **Entry Widgets in CustomTkinter – Tkinter CustomTkinter 3**. Produção: Codemy.com. [S. l.], 22 ago. 2023a. 1 vídeo. Disponível em: https://youtu.be/mwalgzuEfvw.

ELDER, John. **Images in CustomTkinter – Tkinter CustomTkinter 17**. Produção: Codemy.com. [S. l.], 5 dez. 2023b. 1 vídeo. Disponível em: https://youtu.be/GMHtpH68Glo.

ELDER, John. **Pack Vs Grid For Placement – Intro To Tkinter 3**. Produção: Codemy.com. [S. l.], 12 mar. 2024. 1 vídeo. Disponível em: https://youtu.be/m9peQh4tu9g.

MARIANO, Diego. **Biopython: manipulando dados biológicos usando Python e Colab**. BIOINFO: Revista brasileira de bioinformática e biologia computacional, julho/2021. Disponível em: https://bioinfo.com.br/biopython-uma-breve-introducao-a-manipulacao-de-dados-biologicos-em-python-usando-colab/]

MONUTTI, Diego. **Tkinter no Python: guia completo – crie interfaces do zero**. Hashtag Treinamentos, 18 maio 2026. Disponível em: https://www.hashtagtreinamentos.com/tkinter-no-python#customtkinter.

SCHIMANSKY, T. **Official Documentation And Tutorial | CustomTkinter**. Disponível em: <https://customtkinter.tomschimansky.com/>.
### Link das interações com Inteligência Artificial:
Observação: alguns links se perderam ao longo do desenvolvimento do projeto.
https://copilot.microsoft.com/shares/6ZkDqfZZCKQnPPR62XnGB
https://claude.ai/share/f305e56a-1345-4b3e-a01c-b852df6fb3ca
