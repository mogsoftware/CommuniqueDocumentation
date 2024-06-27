# Player
<show-structure depth="2"/>
## Criação de Player

Para ser direcionado à página onde estão todos os players cadastrados, é necessário acessar o menu do Communique no canto esquedo da página e clicar em <ui-path>Players | Todos os Players </ui-path>.

<video src="../videos/acesso-player.mp4" xmlns="" preview-src="acesso-player.png"/>

Para criar um player novo é necessário clicar no botão <img src="add.png" alt="Add icon" width="24" style="inline"/> localizado na parte superior direita, logo abaixo dos filtros de pesquisa.<br></br>
Uma janela abrirá para que as informações do novo player sejam preenchidas.

<img src="Criacao.jpg"  alt="criação" width="450"/>

### Information

<list type="decimal" start="1">
    <li>Nome
        <list type="bullet">
            <li>Nome dado ao player para melhor identificação.</li>
        </list>
    </li>
    <li>Hostname
        <list type="bullet">
            <li>É o nome dado ao dispositivo em uma rede, podendo ser um computador, um servidor etc. É possível descobrir o hostname da máquina digitando "hostname" no prompt de comando.</li>
        </list>
    </li>
    <li>MacAddress
        <list type="bullet">
            <li>É o endereço físico da máquina. Também é possível localiza-lo no prompt de comando do digitar "getmac".</li>
        </list>
    </li>
    <li>Theater
        <list type="bullet">
            <li>É o cinema onde está localizada a máquina. Ao clicar nessa sessão, uma lista de cinemas é exibida.</li>
        </list>
    </li>
    <li>Player Category
        <list type="bullet">
            <li>Categoria do player que pode ser definida pelo tipo de cinema (Regular, Premier ou Bistro) ou ????.</li>
        </list>
    </li>
    <li>Locate
        <list type="bullet">
            <li>Local do cinema onde o player será exibido.</li>
        </list>
    </li>
</list>

### Display



<list type="decimal" start="1">
    <li>Monitor
        <list type="bullet">
            <li>Modelo do monitor utilizado.</li>
        </list>
    </li>
    <li>Inches
        <list type="bullet">
            <li>Quantidade de polegadas do monitor.</li>
        </list>
    </li>
    <li>Screens
        <list type="bullet">
            <li>Quantidade de monitores do player. Na imagem aparece ao lado do campo de inches com o número zero por padrão.</li>
        </list>
    </li>
    <li>Screen Resolution
        <list type="bullet">
            <li>Resolução dos monitores.</li>
        </list>
    </li>
    <li>Format
        <list type="bullet">
            <li>Disposição das telas do player no local.</li>
        </list>
    </li>
    <li>Videowall
        <list type="bullet">
            <li>Disposição das telas do player para montagem do diagrama. Pode ser o mesmo do item anterior ou possuir um formato diferente em caso de telas espelhadas.</li>
        </list>
    </li>
    <li>Orientação
        <list type="bullet">
            <li>Orientação do conteúdo do player.</li>
        </list>
    </li>
</list>

### Montage

Definição de quantas máquinas e/ou saídas de vídeo serão utilizadas por este player.

É necessário que haja ao menos uma máquina e uma saída de vídeo.

### Options

<list type="decimal" start="1">
    <li>Prevent 
        <list type="bullet">
            <li>Item de segurança que ao ser ativado, previne que o player faça algum tipo de download.
                <list type="alpha-lower">
            <li>Config Prevent
                    <list type="bullet"> 
                    <li>Bloqueio de atualização das configurações do player.</li>
                    </list></li>
            <li>Playlist Prevent 
                    <list type="bullet">
                    <li>Bloqueio de atualização das playlists do player.</li>
                    </list></li>
                </list></li>
        </list>
    </li>
    <li>Advertising
        <list type="bullet">
            <li>O Advertising vem ativado por padrão e é utilizado em players que exibem campanhas. Essa opção faz com que o player envie a contagem de exibição das mídias de campanha que são visualizadas no report de campanha</li>
        </list>
    </li>
</list>

## Configuração de Player

### Config

<chapter title="Playlists" id="config_Playlist">

É criada ao clicar no botão <img src="add.png"/> localizado no canto esquerdo da página.

<img src="Playlist.jpg"/>

É necessário adicionar um nome e descrição para a playlist, além de selecionar o formato e media type das mídias que serão programadas.

</chapter>

<chapter title="Settings" id="config_Settings">

Configuração de cartelera/grade do player. Afeta os plugins Showtimes, Boxoffice e Postercase.

<img src="Settings.jpg"/>

<list type="decimal" start="1">
    <li>Grid Path
        <list type="bullet">
            <li>Endereço da API de cartelera/grade.</li>
        </list>
    </li>
    <li>Order
        <list type="bullet">
            <li>Ordem de importância das sessões.</li>
        </list>
    </li>
    <li>API Token Auth
        <list type="bullet">
            <li>Chave de autorização para acesso à API.</li>
        </list>
    </li>
    <li>API SmartPlayer
        <list type="bullet">
            <li>Endereço da API de Combos, para players de Snack que exibem vídeos de combos na playlist de promoções.</li>
        </list>
    </li>
</list>    

</chapter>

<chapter title="Sync" id="config_Sync">

Tempo em minutos estabelecido para que o player faça cada tipo de sincronização.

<img src="Sync.jpg"/>  

</chapter>

<chapter title="Layer" id="config_Layer">

Video exibido por cima do conteúdo do player. O formato da playlist e do layer depende da montagem do player e normalmente é exibido apenas nas bilheterias dos cinemas.
       
<img src="Layer.jpg"/>

</chapter>

<chapter title="Event" id="config_Event">

O material programado na playlist específica de evento, irá sobrepor todo o conteúdo do player durante o tempo (horas ou dias) determinado na configuração.

<img src="Evento.jpg"/>

</chapter>

<chapter title="Lobby" id="config_Lobby">

aaaa

</chapter>

### Montagem

<img src="Montagem.jpg"/>

### Plugin

<chapter title="Showtimes" id="plugin_Showtimes">

Exibe o horário e tipo das sessões e elas podem ser ordenadas alfabeticamente, por prioridade ou número de sessões.
Tembém é possível filtrar para que exiba apenas sessões regulares ou prime.

<img src="Showtimes.jpg" alt="criação" width="450"/>

</chapter>

<chapter title="Boxoffice" id="plugin_Boxoffice">

Exibe o horário e tipo das sessões com o poster do filme.

<img src="Boxoffice.jpg" alt="criação" width="450"/>

</chapter>

<chapter title="Player" id="plugin_Player">

Utilizado para exibição de vídeos ou imagens programados em uma playlist. Este plugin pode ser configurado nos formatos 1x1, 2x1, 3x1 e 4x1.
    
<img src="Player.jpg" alt="criação" width="450"/>

</chapter>

<chapter title="Postercase" id="plugin_Postercase">

Possui dois layouts utilizados de maneira diferente.<br/>
Postercase: Utilizado nas portas de sala dos cinemas, exibe o poster do filme que está em exibição naquela sala.<br/>        

<img src="Postercase.jpg" alt="criação" width="450"/>

<br/><br/>Smartpostercase: Exibe trailer, poster e outras informações dos filmes.
<br/>No formato Presentando, exibe filmes em cartaz do cinema com os horários das sessões.No formato Proximamente, exibe filmes que ainda serão lançados e não possui horário.

<img src="Postercase2.jpg" alt="criação" width="450"/>

</chapter>

<chapter title="Combos" id="plugin_Combos">

Exibe os combos de pipoca do cinema. Pode ser configurado para exibir o conteúdo no formado 1x1 e 2x1.<br/>
Na versão 1.0 do plugin, é necessário que exista uma playlist para exibição dos vídeos de combo.

<img src="Combos.jpg"/>

</chapter>

<chapter title="Menu" id="plugin_Menu">

Exibe os demais itens da bomboniere do cinema, além dos preços avulsos de pipoca e bebida.

<img src="Menu.jpg"/>

</chapter>

<chapter title="Prices" id="plugin_Prices">

Exibe os preços dos ingressos do cinema, separado por tipo de sessão e sala.

<img src="Prices.jpg"/>

</chapter>

<chapter title="MixPlugins" id="plugin_MixPlugins">

Utilizado para exibir dois plugins diferentes na mesma tela. 

<img src="Mix.jpg"/>

</chapter>

<chapter title="Inactive" id="plugin_Inactive">

Utilizado quando o quadrante não está em uso e não será necessário configurar nenhum plugin nele.

</chapter>

