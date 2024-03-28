<h1 align="center"> Projeto Flappy Bird Game </h1>


<p align="center">
<img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

# Índice 

- [Índice](#índice)
- [Descrição do Projeto](#descrição-do-projeto)
- [Funcionalidades e Demonstração da Aplicação](#funcionalidades-e-demonstração-da-aplicação)
- [Tecnologias e sites utilizados](#tecnologias-e-sites-utilizados)
- [Desenvolvimento](#desenvolvimento)
- [Conclusão](#conclusão)


# Descrição do Projeto

<p align="justify">Este projeto foi baseado no jogo do dinossauro, com a utilização de alguns conceitos básicos de HTML5, CSS3 e Javascript, no qual estiveram presentes elementos como obstáculos, movimentos de salto, interação com cenário. Ele será intitulado neste projeto como: Dino Game.</p>

# Funcionalidades e Demonstração da Aplicação

# <h3>Tecnologias e sites utilizados</h3>

<p align="left">Pesquisas e verificação do funcionamento do código:  Navegador de Internet Google Chrome</p>
<p align="left">Pesquisas e verificação do funcionamento do código: https://www.microsoft.com/pt-br/edge</p>
<p align="left">Edição/produção do código: Visual Studio Code - Code Editing. Redefined</p>
<p align="left">Escolha de cores e seus respectivos códigos HEX: HTML Color Codes 🎨 </p>
<p align="left">Consultas: JavaScript: The Definitive Guide</p> 
<p align="left">Consultas: Appendix B. Keyboard Key Code Values</p>
<p align="left">Consulta: https://www.techtudo.com.br/dicas-e-tutoriais/2019/11/como-jogar-o-jogo-do-dinossauro-do-google-online-no-navegador-chrome.ghtml</p> 
<p align="left">Código das teclas: JavaScript Key Code Event Tool | Toptal®</p>
<p align="left">Extensão utilizada no VS Code: Live Server (https://github.com/ritwickdey/live-server-web-extension)</p>


# <h3>Desenvolvimento</h3>

<p align="justify">Foram inseridos os documentos padrões (index.html, style.css, script.js, readme.md)  com a devida base inicial para funcionamento no navegador Google e Edge, nas versões mais atuais.
Neste projeto,  além das instruções repassadas nas aulas, não foram inseridos complementos ou alterações significativas.</p>

1) Inicialização do Jogo:

<p align="justify">O jogo é inicializado quando o evento DOMContentLoaded é acionado, indicando que a estrutura HTML do documento foi completamente carregada. A função associada a esse evento configura o jogo, adicionando “event listeners” e chamando a função “gerarobst” para começar a gerar obstáculos.</p>

2) Configuração das Variáveis:

<p align="justify">dino: Armazena a referência ao elemento do dinossauro no jogo.
grid: Armazena a referência ao elemento da grade do jogo.
body: Armazena a referência ao elemento body do documento.
alert: Armazena a referência ao elemento de alerta do jogo.
jumping: Indica se o dinossauro está atualmente pulando.
gravity: Representa a força da gravidade aplicada ao dinossauro.
gameo: Indica se o jogo acabou.
dinopy: Armazena a posição vertical do dinossauro no eixo y.</p>

3) Controles do Jogo:

<p align="justify">O evento “keyup” é utilizado para controlar o salto do dinossauro. Quando a tecla de espaço (keyCode == 32) é pressionada, a função “jumpcontrol” é chamada para verificar se o dinossauro está atualmente pulando (“!jumping”). Se não estiver pulando, a variável “jumping” é definida como verdadeira e a função jump é chamada.</p>


4) Funcionamento do Jogo:

<p align="justify">A função “jump” é responsável por controlar a lógica do pulo do dinossauro. Utiliza intervalos para simular o movimento de subida e descida durante o pulo. A função “gerarobst” é responsável por gerar obstáculos de forma contínua com base em intervalos de tempo aleatórios. Dessa forma, a lógica de movimento dos obstáculos é implementada usando intervalos.
Durante a movimentação dos obstáculos, verifica-se se houve colisão com o dinossauro. Se houver colisão, o jogo é encerrado, exibindo um alerta, definindo “gameo” como verdadeiro e removendo elementos do jogo.
O jogo continua a gerar obstáculos e verificar colisões até que o jogo termine. Quando o jogo termina, o loop é interrompido, e o jogador é informado sobre o fim do jogo no elemento “alert” (id).</p>

# <h3>Conclusão</h3>

<p align="justify">A produção desse projeto mostrou a importância do uso das variáveis e da aplicação do conceito de objetos e as devidas manipulações. É necessário se atentar ao comportamento do salto do dinossauro na página, as dimensões do terreno e a aleatoriedade dos cactus.
As oportunidades deste projeto são: melhorar a responsividade do jogo em relação aos diversos tamanhos de tela; aperfeiçoar o código para possibilitar que o usuário jogue em seu smartphone; implementar sistema de pontuação mais complexo (obstáculos mais difíceis e/ou velocidade e  esquema de ranking) e de vidas; implementar botão de Play e reinício automático do dinossauro no início da tela; e melhorar a interface (UX/UI).
O jogo está funcionando e foram feitos testes no Google Chrome e no Microsoft Edge.</p>


