# Informações dos projetos da disciplina Sistemas Hidreletricos - FGA-UnB

### Informações Gerais: 

Este repositório contém todos as informações para os alunos fazerem os projetos. Um dos alunos da turma deverá criar um repositório no GitHub para a documentação dos projetos da disciplina, **onde todos os membros deverão participar da construção e edição da documentação do laboratório.** O nome do repositório deverá ser disponibilizado para o professor, e deverá começar com 2019.2 (Exemplo: 2019.2-gruposh) A falta de participação resultará em penalizações na nota.

**Em cada projeto, os alunos deverão descrever as tarefas realizadas e os responsáveis pela mesma** 

Os cálculos, textos, equações e todas os elementos necessários para a documentação dos projetos deverão ser registrados em arquivo de extensão .md no repositório com a ferramenta de edição do GitHuB, que representará o projeto Hidrelétrico da turma. Este projeto está dividido nos seguintes itens: 

- Projeto do aproveitamento; 

- Projeto Hidrológico; 

- Projeto do Conduto; 

- Projeto da Turbina; 

- Projeto de Gestão; 

**Não serão aceitas outras formas para envio dos projetos!** 

 Abaixo segue como colocar equações e imagens: 

  Exemplo para anexar uma imagem (A imagem deve ser enviada para o repositório via *upload*): 

 ![Teste de legenda de imagem](thrust.jpg) 

  Para escrever as equações usando o formato do LateX use [este link](https://www.codecogs.com/latex/eqneditor.php). A equação deverá ser gerada no site, salva em formato .gif e enviada para o repositório para ser anexada como imagem, conforme exemplo abaixo: 

 ![Teste de legenda de imagem 2](CodeCogsEqn.gif) 
 

# PROJETO HIDROELÉTRICO 

 ### Projeto do Aproveitamento 

 O projeto do aproveitamento consistirá na realização e apresentação de cálculos oriundos de dados de um dado aproveitamento hidrelétrico visando a instalação de uma usina hidrelétrica. Os seguintes itens deverão ser registrados no repositório usando a ferramenta de edição do GitHub: 

   - Os alunos deverão escolher uma localidade no Brasil para instalação de uma usina hidroelétrica. Em seguida, a turma deverá procurar os dados de vazão desta localidade no sítio da ANA (Agência Nacional de Águas) para seus cálculos. (**Entrega deste item no dia 07/09**) 

   - Modelamento do aproveitamento hidrelétrico. A turma deverá mostrar como ficará o sistema hidromecânico equivalente através do cálculo da energia hidráulica média disponível e do trabalho específico. A turma deverá usar o software QGIS ou outras ferramentas de sistemas de informação geográfica para determinação da altura de cota para seu aproveitamento hidrelétrico na localização escolhida. O uso destes sistemas será o tema das primeiras aulas de laboratório da disciplina. (**Entrega deste item no dia 07/09**) 

   - Determinação da queda do aproveitamento: A turma deverá considerar um percentual de perda de até 20%, onde cada grupo deverá especificar se a central será de baixa ou de alta queda; (**Entrega deste item no dia 07/09**) 

  - Determinação da vazão média de longo tempo baseado nos dados de vazão. Cada grupo deverá mostrar como fez este cálculo e as hipóteses adotadas; (**Entrega deste item no dia 14/09**) 
  
  - Determinação da área de captação usando SIG; (**Entrega deste item no dia 14/09**) 

  - Determinação da energia máxima teórica média; (**Entrega deste item no dia 14/09**) 

  - Escolha do tipo de central e o arranjo utilizado; (**Entrega deste item no dia 21/09**) 

  - Estimativa da potência instalada; (**Entrega deste item no dia 21/09**) 
  
  - Determinação da regionalização da vazão usando SIG; (**Entrega deste item no dia 21/09**) 

### Projeto Hidrológico 

O projeto hidrológico consistirá na realização e apresentação de cálculos hidrológicos para o projeto de uma central hidrelétrica. Os seguintes itens deverão ser registrados no repositório: 

 - Com os dados de vazão usados no projeto do aproveitamento, A turma deverá identificar e organizar os dados em médias semanais (Se a disposição dos dados for diária) ou anuais (Se a disposição dos dados for mensal); (**Entrega deste item no dia 28/09**) 

 - A turma deverá realizar uma caracterização estatística destes dados. Para a caracterização dos dados, o grupo deverá instalar e utilizar o programa disponibilizado neste repositório intitulado "Centrais Hidrelétricas". Os seguintes itens deverão ser registrados:  

 - Fluviograma dos dados, dispostos em valores anuais e decenais; (**Entrega deste item no dia 28/09**) 

 - Curva de duração de vazões; (**Entrega deste item no dia 28/09**) 

 - Curva de duração de potência para uma queda (Determinada no projeto do aproveitamento) e rendimento de **90%**; (**Entrega deste item no dia 28/09**) 

 - Diagrama de Rippl; (**Entrega deste item no dia 28/09**) 

 - Determinação do período crítico;  (**Entrega deste item no dia 05/10**) 

 - Determinação de períodos seco e úmido;  (**Entrega deste item no dia 05/10**) 

 - Determinação de valores extremos; (**Entrega deste item no dia 05/10**) 

- Estimativa da vazão firme e da vazão de projeto para dimensionamento de uma central hidrelétrica;  (**Entrega deste item no dia 05/10**) 

- Cálculo da vazão regularizada: A turma deverá fazer um cálculo da vazão regularizada baseado nos dados fornecidos de vazão. O método a ser usado é o método de Conti-Varlet. A formulação deste método está disponível no livro-texto do curso (Souza, Z., Santos, A. H. M e Bortoni, E. C.  **Centrais Hidrelétricas: Implantação e Comissionamento**, 2a. Edição, Editora Interciência.) (**Entrega deste item no dia 12/10**) 

- Analisar o resultado obtido de vazão regularizada e comparar este resultado com as vazões firme e de projeto calculados anteriormente; (**Entrega deste item no dia 12/10**) 

- Determinação de modelo digital do terreno usando SIG; (**Entrega deste item no dia 12/10**) 

- Análise do uso do modelo digital para dimensionamento de reservatório e medição de vazão; (**Entrega deste item no dia 12/10**) 

### Projeto do Conduto 

O projeto do conduto consistirá na realização e apresentação de cálculos de condutos e canais para a central hidrelétrica. Os seguintes itens deverão ser registrados no repositório: 

- Projeto do canal para a futura usina hidrelétrica utilizando as fórmulas de Chezy, determinando de acordo com os dados de vazão de cada grupo: 

 - A melhor forma geométrica de seção para o canal em questão; (**Entrega deste item no dia 19/10**) 

 - O diâmetro hidráulico da seção; (**Entrega deste item no dia 19/10**) 

 - Velocidade da água no canal; (**Entrega deste item no dia 19/10**) 

 - Vazão de água no canal; (**Entrega deste item no dia 19/10**) 

 - Determinação de linhas piezométrica e de energia em desenho esquemático do sistema hidromecânico equivalente; (**Entrega deste item no dia 19/10**) 

 - Determinação do semiperíodo da onda de pressão para dimensionamento do conduto fechado. Cada grupo poderá fazer as considerações que achar necessárias; (**Entrega deste item no dia 19/10**) 

 - Determinação de valores de golpe de aríete positivo máximo; (**Entrega deste item no dia 19/10**) 

 - Determinação de valores do golpe de aríete aceitável; (**Entrega deste item no dia 19/10**) 

 ### Projeto da Turbina 

 Este projeto consistirá em mapear o processo de conversão e produção de energia da bancada hidrelétrica do laboratório de termofluidos. Os seguintes itens deverão ser registrados no repositório:  

  - Especificação da vazão da turbina, pressão, e demais condições de operação; (**Entrega deste item no dia 26/10**) 

  - Especificação da potência mecânica da turbina; (**Entrega deste item no dia 02/11**) 

  - Levantamento da curva Potência x Torque usando freio de Prony; (**Entrega deste item no dia 09/11**) 

  - Turbina hidraulica, gerador sincrono e carga elétrica. Medição de grandezas elétricas e eficência; (**Entrega deste item no dia 16/11**) 

  - Estime o fator de capacidade da turbina; (**Entrega deste item no dia 23/11**) 

  - Determinação da altura de sucção e avaliação de risco de cavitação; (**Entrega deste item no dia 23/11**) 
  
**Projetos que não tiverem todos estes itens respondidos ou que estiverem incompletos **não serão avaliados!**  

 ### PROJETO DE GESTÃO 

Este projeto de gestão visa à solução de um problema na execução do projeto, sob as seguintes condições: 

- Os grupos devem consultar fontes de dados e informação, tais como professores, engenheiros, legislação, artigos científicos e instituições competentes (Por exemplo, IPEA, IBGE, BEN, MME); 

- As decisões para solução da questão devem ser da própria equipe, e deverão respeitar o atendimento a legislações e/ou normas que sejam pertinentes, sendo vedado consultar terceiras partes para tomada de decisão; 

- A turma receberá uma notificação baseada nos dados do projeto do aproveitamento. 

- Os grupos deverão responder à notificação enviada em documento de no máximo 1 página e na forma de ofício, a ser enviado via MOODLE no prazo colocado pela notificação. O ofício deverá responder as demandas colocadas na notificação. 

- A resposta ao ofício deverá ser apresentada em seminário, onde o grupo deverá defender as suas escolhas e evidenciar os elementos técnicos/científicos em que basearam as decisões; 

- A apresentação das soluções de cada grupo deverá ter a duração máxima de 10 minutos, deve ser documentada em arquivo powerpoint e enviado via MOODLE após a apresentação. As fontes de consulta devem ser colocadas no arquivo da apresentação; 

- Na aula posterior às apresentações, haverá avaliação das decisões pelos pares e discussão para decisão em consenso da turma como uma única equipe; 

- O tipo da usina (Grande central, pequena central) será determinada pela vazão de projeto e pela potência hidráulica máxima teórica média a ser calculada por cada grupo; 

- O local de construção da usina é geograficamente localizado perto de uma cidade cuja população deve ser estimada pelo valor da potência instalada já calculada pelo grupo; 

- A data das apresentações será no dia **23/10/2019**. O debate para a decisão de consenso será no dia **25/10/2019**. O não envio das apresentações, faltar o dia das apresentações e do debate **acarretarão em nota zero neste projeto**. 

 ### VISITA TÉCNICA (**Entrega no dia 01/12**) 
 
 O grupo deverá visitar uma central hidrelétrica de sua escolha e registrar no repositório a visita. Este relatório deverá conter:
 
  - Características gerais da UHE (Breve histórico, motivação da construção, etc.);
  - Descrição sobre o tipo de central (Pequena central hidrelétrica, Grande central, etc.);
  - Tipo e quantidade de turbina;
  - Potência instalada;
  - Descrição de equipamentos e partes da usina (Vertedouros, chaminés de equilíbrio, sistemas de controle, etc);
  - Outras informações pertinentes;
  
