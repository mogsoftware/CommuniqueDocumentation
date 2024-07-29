# Communique 5.0
<show-structure depth="3"/>

## Glossario


### Media Type

<list type="decimal">
<li>Campaing: Mídias de campanha.</li>
<li>Combo Video: Videos de combos para a versão 1.0 do plugin Combos.</li>
<li>Combos Promocionais: Promoções de snack que possuem brinde. Esse é o mediatype utilizado no GO Operation.</li>
<li>Evento: Mídias para eventos.</li>
<li>Informative: Mídias informativas do cinema.</li>
<li>Inovações (Brasil): Outras promos ou mídias que serão exibidas no snack do cinema.</li>
<li>Institucional: Vídeos institucionais do cinema ou parceiros do cinema.</li>
<li>Layer: Mídias utilizadas para programação do layer.</li>
<li>Lobby Domination: Mídias utilizadas para programação do Lobby Domination.</li>
<li>Menu (Latam): Vídeos de itens de menu do cinema.</li>
<li>Poster: Posters de filmes que serão utilizados pelos plugins Boxoffice, Prices, Postercase e Smartpostercase. Para que o poster seja exibido, é necessário preencher o campo de CODE com o código do filme antecedido pela letra P.<img src="Poster_code.png"/></li>
<li>Prices: Banner ou vídeo de rodapé do plugin Prices.</li>
<li>Prime (Brasil): Vídeos de menu dos cinemas Prime e Bistro.</li>
<li>Promo (Latam): Outras promos ou mídias que serão exibidas no snack do cinema.</li>
<li>Showtimes: Banner ou vídeo de rodapé do plugin Showtimes.</li>
<li>Still: Imagem de combo do plugin Combos. Devem ser upadas no sistema em png e são utilizadas nas duas versões do plugin. Para que o still seja exibido seja exibido, é necessário preencher o campo CODE com o código do combo antecedido pela letra C.<img src="Still_code.png"/></li>
<li>Trailer: Trailers que serão exibidos no cinema. Pode ser utilizado em playlist e no plugin Smartpostercase. Para que o trailer seja exibido seja exibido no smartpostercase, é necessário preencher o campo CODE com o código do filme antecedido pela letra T. <img src="Trailer_code.png"/></li>
</list>

### Locate

<list type="decimal">
<li>ATM: Roteiros localizados na área dos ATMs do cinema.</li>
<li>BoxOffice: Roteiros localizados na bilheteria do cinema.</li>
<li>Entrance: Roteiros localizados na entrada do cinema.</li>
<li>Lobby: Roteiros localizados no lobby do cinema.</li>
<li>Lounge: Roteiros localizados no lounge do cinema.</li>
<li>Office: Roteiros localizados no escritório do cinema.</li>
<li>Podium: Roteiros localizados no podium do cinema.</li>
<li>Postercase: Roteiros localizados na porta de sala do cinema ou que utilizem Smartpostercase.</li>
<li>Snack: Roteiros localizados no snack do cinema.</li>
<li>Snack Lateral: Roteiros localizados no snack lateral do cinema.</li>
<li>SnackPrimePrincipal: Roteiros localizados no snack prime do cinema. Utilizado em cinemas hibridos que possuem snack regular e prime.</li>
</list>

### Player Category

<list type="decimal">
<li>Regular: Players de cinemas regulares.</li>
<li>Prime: Players de cinemas prime.</li>
<li>Bistro: Players de cinemas bistrô</li>
<li>Videowall: Players de videowall.</li>
<li>XD: Players de porta de sala XD.</li>
<li>Lab: Players de lab.</li>
</list>

### Formatos

Edu

### Plugins



<chapter title="SHOWTIMES" id="plugin_showtimes">

O Showtimes 2.0, possui uma tela auxiliar, podendo funcionar como 1x1 ou 2x1.
Para exibi-la, a segunda tela do plugin deve ter o número 2 na configuração ***Plugin Screen***.

<img src="layoutshowtimes2x1.png" width="600"/>

<img src="configshowtimes2x1.png" width="600"/>

<img src="showtimes2x1.png" width="600"/>

</chapter>

<chapter title="BOXOFFICE" id="plugin_boxoffice">

O BoxOffice, possui telas com 1, 3, 4 e 8 filmes. A configuração de telas do Boxoffice precisa levar em conta a quantidade de plugins que serão utilizados pelo player.
Ex.: Em um player com 4 BoxOffice, o *Plugin Screen* será de 1 à 4.

<img src="BX2x2.png" width="600"/>

<img src="BX4x1.png" width="600"/>

<img src="BXplayer.png" width="600"/>

Diferentes combinações de layout são permitidas e, no caso de mais de um tipo de layout selecionado, o player adapta a quantidade de filmes/sessões de acordo com a quantidade de telas disponiveis.

<img src="BX1.png" width="600"/> *BoxOffice 1 Filme*

<img src="BX3.png" width="600"/> *BoxOffice 3 Filmes*

<img src="BX4.png" width="600"/> *BoxOffice 4 Filmes*

<img src="BX8.png" width="600"/> *BoxOffice 8 Filmes*

</chapter>

<chapter title="PLAYER" id="plugin_player">

Quando na mesma saída de vídeo:


#### PLAYER 1X1

Os campos do plugin são preenchidos com o número 1, com exceção do *Plugin Screen*, que sempre vai ser preenchido com a posição da tela no videowall. 
<img src="config_pl1x1.png" width="600"/>
<img src="PL1X1.png" width="600"/>

#### PLAYER 2X1

Os campos *Player Width* e *Player Height*, na primeira tela do plugin, são preenchidos de acordo com o tamanho do vídeo que será exibido por ele.
Na segunda tela do plugin, altera-se o campo *Plugin Screen* e *Screen Col* para indicar ao player que ele deve exibir o segundo quadrante do vídeo e é necessário ativar o botão *Hide on Player*.
<img src="config_pl2x1.png" width="600" preview-src="config_pl2x1.png"/>
<img src="PLAYER2X1.png" width="600" preview-src="PLAYER2X1.png"/>

#### PLAYER 3X1

Os campos são preenchidos como no formato 2x1, porém a primeira tela do plugin recebe em *Extendeds Monitors* o número da tela que será uma extensão dela.
Já a terceira tela, além dos campos de *Plugin Screen* e *Screen Col*, é necessário ativar o botão *It's an extension* para indicar que aquela tela é uma extensão do monitor que será inserido no campo *Extended Monitors*.
<img src="config_pl3x1.png" width="600" preview-src="config_pl3x1.png"/>
<img src="PLAYER3X1.png" width="600" preview-src="PLAYER3X1.png"/>

#### PLAYER 4X1
<img src="config_pl4x1.png" width="600" preview-src="config_pl4x1.png"/>

Quando em diferentes saídas de vídeo, mas estão na mesma linha:

*Player 2x1*

*Player 3x1*

*Player 4x1*

Quando em diferentes saídas de vídeo, mas em linhas diferentes:

*Player 2x1*

*Player 3x1*

*Player 4x1*

</chapter>

<list type="decimal" start="4">
<li>Postercase</li>
<li>Combos</li>
<li>Menu</li>
<li>Prices</li>
</list>