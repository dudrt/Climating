# Climating <br> 
Aplicativo programado em java utilizando a IDE Android Studio.<br>
Este aplicativo tem como objetivo proporcionar acesso rápido e fácil ao clima atual de milhares de cidades ao redor do mundo.
## Funcionalidades do projeto:
- `Pesquisa por cidade`: O usuário é capaz de fazer consultas a
diferentes cidades.<br>
- `Localização atual`: O usuário pode optar por pegar sua atual
localização.
## Usabilidade:
 O aplicativo possui uma interface bem intuitiva, sendo assim, o
mesmo é capaz de ser utilizado por pessoas que vão desde os jovens que
possuem grande contato com a tecnologia a até mesmo pessoas de mais
idade que possuem baixo contato. <br><br>
 Ao pesquisar a localidade de preferência, o aplicativo se separa em
três diferentes partes: <br>
•  A primeira mostra o nome da localização pesquisada e o dia da semana, mostra também os dados climáticos atuais como:Temperatura atual,Temperatura mínima e
máxima,precipitação e velocidade do vento. <br>
•  Na segunda parte, é mostrado os dados climáticos das próximas horas do dia, que são separados em temperatura,precipitação e horário.<br>
•  Na terceira e última parte, é mostrado uma prévia geral dos próximos 6 dias. Ao clicar em alguma das prévias, os dados da primeira
e segunda parte são modificados para os dadosclimáticos do dia correspondente.<br>

O software não possui requisito de permissões para funcionamento, porém ao iniciar o aplicativo, é pedido a permissão para acessar a localização, caso o usuário julgue que não seja algo necessário, o mesmo pode recusar sem problemas de funcionamento principal. A permissão que é requisitada, possibilita ao usuário pegar de maneira automática sua
localização atual apenas com o clique de um botão.


# Utilização:

O software possui duas principais funções, sendo elas:
`Pesquisa por cidade`: Na parte superior da tela, se encontra o campo “Pesquisar cidade”, quando selecionado, abre-se o teclado para que o usuário possa digitar o local desejado.
	O aplicativo não possui um botão na tela para confirmação, mas utiliza o próprio botão de “Enter” do teclado para facilitar na usabilidade e deixar a interface mais amigável.<br>
Caso a cidade pesquisada não exista ou haja um erro de escrita, o código trata esta exceção sem prejudicar os dados já presentes na tela e retorna um feedback para o usuário.<br>

`Localização atual`: O botão para pegar a localização atual do dispositivo se encontra ao lado do campo “Pesquisar cidade”, na parte superior da tela e possui um ícone de alfinete. <br>
Pensado como um instrumento que ajude a aumentar a usabilidade do aplicativo, caso a permissão necessária seja concedida, com apenas um clique, esta funcionalidade permite que o usuário pegue de maneira rápida os dados climáticos da cidade que o dispositivo se encontra. 

##### Parte da interface que mostra a localização das funcionalidades citadas a cima.
<img src="img/tela_topo.png">

Ideia Inicial X Produto Final:
	
No que se refere às diferenças da ideia inicial e do produto final, o principal foi as mudanças visuais e algumas poucas mudanças de funcionalidades.Para começar o projeto, foi pego um exemplo de interface.<br>
Logo após, foi feito um esboço no figma, que pegou apenas como base algumas ideias do exemplo.<br>

##### Exemplo de interface ------------------------------- Esboço feito no figma
<img src="img/exemplo.jfif" height="300px"><img src="img/figma.png" height="300px"><br>
Logo após, começou o desenvolvimento e durante o processo, algumas ideias mudaram e outras nasceram.<br>
##### Fotos do processo de desenvolvimento.
<img src="img/teste1.png" height="300px"><img src="img/teste2.png" height="300px"><br>
Depois de mudar alguns aspectos visuais como:Cor de fundo, cor das letras, posição dos ícones, posição das informações, informações adicionais e troca de informações, o visual final ficou bem diferente do inicialmente esperado.<br>
<img src="img/ultima.png" height="300px"><img src="img/ultima2.png" height="300px"><br>
