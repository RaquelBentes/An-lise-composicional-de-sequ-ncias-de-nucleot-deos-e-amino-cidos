<img width="2535" height="380" alt="Cabecalho" src="https://github.com/user-attachments/assets/0a2d76bb-b3c9-4128-87b0-cdb82112a749" />

# Análise composicional de sequências de nucleotídeos e aminoácidos
## Descrição do projeto
Esse projeto foi desenvolvido para a disciplina de Práticas em ciências de dados do curso de Bacharelado em Ciência e Tecnologia da Ilum Escola de Ciência, onde foi proposto criar um código que desafiasse o discente que desenvolvesse. Para isso, decidi criar uma interface que tem como objetivo analisar a composição de sequências de nucleotídeos e aminoácidos, realizando transcrição, tradução, geração do reverso complementar e cálculo do conteúdo gc, a fim de compreender características estruturais e funcionais das sequências biológicas.

## Instalação e instruções
O código pode ser acessado ao instalar o arquivo disponibilizado no Github e rodado em linguagem Python. Para utilizar a interface é necessário rodar todas as células na ordem em que foram escritas, permitindo um funcionamento adequado.
Para o uso adequado, é necessário inserir a sequência que o usuário deseja analisar no espaço indicado e, em seguida, selecionar o botão referente à aplicação que deseja.
Há um total de cinco botões disponíveis, sendo eles referentes às seguintes funcionalidades: reverso complementar, transcrição, tradução, porcentagem do conteúdo GC e gráfico do conteúdo GC, que serão abordados com maior descrição mais a frente.

## Funcionalidade
'Reverso complementar': Inverte a sequência e retorna a base complementar da que se encontra na posição. Adenina(A) é complementar da Timina(T) e Guanina(G) é complementar da Citosina(C), e vice-versa.
'Transcrição': Substitui a Timina (T) por Uracila (U) para converter a sequência de DNA em RNA.
'Tradução': Lê a sequência em trincas e retorna o códon correspondente.
'Porcentagem do conteúdo GC': Indica a porcentagem de bases nitrogenadas formadas por citosina e guanina na sequência de DNA ou RNA.
'Gráfico do conteúdo GC': Indica graficamente essa porcentagem em janelas de 10 bases nitrogenadas por vez.

## Recursos utilizados
O arquivo foi desenvolvido utilizando o JupyterLab e o Python na versão 3.13.7.
### IA
A Inteligencia artificial Microsoft Copilot foi utilizada ao longo do projeto para as seguintes funções:
  - Apresentar o Single letter code de cada aminoácido e codon correspondente;
  - Auxiliar no debugging do código;
  - 
### Bibliotecas e módulos/funções
  - CustomTkinter(ctk);
      - `ctk.CTk.()`: cria a janela do programa;
      - `ctk.CTkLabel()`: gera uma etiqueta;
      - `ctk.CTkEntry()`: cria uma entrada de texto;
      - `ctk.CTkButton()`: cria botões;
      - `ctk.CTkTextbox()`: caixa de texto que apresenta resultados;
      - `ctk.CTkImage()`: torna a imagem compatível com a interface;
      - `ctk.set_appearance_mode()`: define o modo claro ou escuro;
      - `ctk.set_default_color_theme()`: define o tema das cores.
      
  - Pillow (PIL);
      -`Image.open()`: abre a imagem no computador.
  - Pandas (pd);
    -`pd.DataFrame()`: cria uma tabela com as informações;
    -`df.plot.line()`: gera um gráfico de linhas;
    
  - Matplotlib (plt).
    -`plt.xlabel`: rótulo para o eixo x do gráfico;
    -`plt.ylabel`: rótulo para o eixo y do gráfico;
    -`plt.title`: define um título pro gráfico;
    -`plt.savefig()`: salva o gráfico como imagem;
    -`plt.close()`: fecha o gráfico.

## Referências
### Os links a seguir apresentam as interações com a IA
https://copilot.microsoft.com/shares/6ZkDqfZZCKQnPPR62XnGB
