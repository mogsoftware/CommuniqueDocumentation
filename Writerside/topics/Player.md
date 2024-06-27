# Player

## Criação de Player

Para ser direcionado à página onde estão todos os players cadastrados, é necessário acessar o menu do Communique no canto esquedo da página e clicar em <ui-path>Players | Todos os Players </ui-path>.

<video src="../videos/acesso-player.mp4" xmlns="" preview-src="acesso-player.png"/>

Para criar um player novo é necessário clicar no botão <img src="add.png" alt="Add icon" width="24" style="inline"/> localizado na parte superior direita, logo abaixo dos filtros de pesquisa.<br></br>
Uma janela abrirá para que as informações do novo player sejam preenchidas.

<img src="Criacao.jpg"  alt="criação" width="450"/>

<chapter title="Information" id="player_Information" collapsible="true">
<deflist collapsible="true">
    <def title="Nome" default-state="expanded">
        Nome dado ao player para melhor identificação.
    </def>
    <def title="Hostname" default-state="expanded">
        É o nome dado ao dispositivo em uma rede, podendo ser um computador, um servidor etc.<br/>
        É possível descobrir o hostname da máquina digitando "hostname" no prompt de comando.
    </def>
    <def title="MacAddress" default-state="expanded">
        É o endereço físico da máquina. Também é possível localiza-lo no prompt de comando do digitar "getmac".
    </def>
    <def title="Theater" default-state="expanded">
        É o cinema onde está localizada a máquina. Ao clicar nessa sessão, uma lista de cinemas é exibida.
    </def>
    <def title="Player Category" default-state="expanded">
        Categoria do player que pode ser definida pelo tipo de cinema (Regular, Premier ou Bistro) ou ????
    </def>
    <def title="Locate" default-state="expanded">
        Local do cinema onde o player será exibido.
    </def>

</deflist>
</chapter>

<chapter title="Display" id="player_Display" collapsible="true">
<deflist collapsible="true">
    <def title="Monitor" default-state="expanded">
        Modelo do monitor utilizado.
    </def>
    <def title="Inches" default-state="expanded">
        Quantidade de polegadas do monitor.
    </def>
    <def title="Screens" default-state="expanded">
        Quantidade de monitores do player. Na imagem aparece ao lado do campo de inches com o número zero por padrão.
    </def>
    <def title="Screen Resolution" default-state="expanded">
        Resolução dos monitores.
    </def>
    <def title="Format" default-state="expanded">
        Disposição das telas do player no local.
    </def>
    <def title="Videowall" default-state="expanded">
        Disposição das telas do player para montagem do diagrama. Pode ser o mesmo do item anterior ou possuir um formato diferente em caso de telas espelhadas.
    </def>
    <def title="Orientação" default-state="expanded">
        Orientação do conteúdo do player.
    </def>
</deflist>
</chapter>
<chapter title="Montage" id="player_Montage" collapsible="true">
    Definição de quantas máquinas e/ou saídas de vídeo serão utilizadas por este player.<br/>
    É necessário que haja ao menos uma máquina e uma saída de vídeo.
</chapter>
<chapter title="Options" id="player_Options" collapsible="true">
<deflist collapsible="true">
    <def title="Prevent" default-state="expanded">
        <p>Item de segurança que ao serem ativados, previnem que o player faça algum tipo de download.</p>
        <list type="bullet">
            <li>General Prevent<p>Bloqueio completo do player.</p></li>
            <li>Config Prevent<p>Bloqueio de atualização das configurações do player.</p></li>
            <li>Playlist Prevent<p>Bloqueio de atualização das playlists do player.</p></li>
</list>
    </def>
    <def title="Advertising" default-state="expanded">
        <p>O Advertising vem ativado por padrão e é utilizado em players que exibem campanhas. <br/>
           Essa opção faz com que o player envie a contagem de exibição das mídias de campanha que são visualizadas no report de campanha.</p>
    </def>
</deflist>
</chapter>

## Configuração de Player

<chapter title="Config" id="config_Config" collapsible="true">
<deflist collapsible="true">
    <def title="Playlists" default-state="collapsed">
        É criada ao clicar no botão <img src="add.png"/> localizado no canto esquerdo da página.<br/>
        <img src="Playlist.jpg"/>
        É necessário adicionar um nome e descrição para a playlist, além de selecionar o formato e media type das mídias que serão programadas.   
    </def>
    <def title="Settings" default-state="collapsed">
        Configuração de cartelera/grade do player. Afeta os plugins Showtimes, Boxoffice e Postercase.
        <img src="Settings.jpg"/>
        <list type="bullet">
            <li>Grid Path<p>Endereço da API de cartelera/grade.</p></li>
            <li>Order<p>Ordem de importância das sessões.</p></li>
            <li>API Token Auth<p>Chave de autorização para acesso à API.</p></li>
            <li>API SmartPlayer<p>Endereço da API de Combos, para players de Snack que exibem vídeos de combos na playlist de promoções.</p></li>
</list>        
    </def>
    <def title="Sync" default-state="collapsed">
        Tempo em minutos estabelecido para que o player faça cada tipo de sincronização.
        <img src="Sync.jpg"/>        
    </def>
    <def title="Layer" default-state="collapsed">
        Video exibido por cima do conteúdo do player. O formato da playlist e do layer depende da montagem do player e normalmente é exibido apenas nas bilheterias dos cinemas.
        <img src="Layer.jpg"/>
    </def>
    <def title="Event" default-state="collapsed">
        O material programado na playlist específica de evento, irá sobrepor todo o conteúdo do player durante o tempo (horas ou dias) determinado na configuração.
        <img src="Evento.jpg"/>
    </def>
    <def title="Lobby" default-state="collapsed">
a
    </def>
</deflist>
</chapter>
<chapter title="Montagem" id="config_Montagem" collapsible="true">
    <img src="Montagem.jpg"/>
</chapter>
<chapter title="Plugin" id="config_Plugin" collapsible="true">
<deflist collapsible="true">
    <def title="Showtimes" default-state="collapsed">
    Exibe o horário e tipo das sessões e elas podem ser ordenadas alfabeticamente, por prioridade ou número de sessões.
Tembém é possível filtrar para que exiba apenas sessões regulares ou prime.
    <img src="Showtimes.jpg" alt="criação" width="450"/>
    </def>
    <def title="Boxoffice" default-state="collapsed">
    Exibe o horário e tipo das sessões com o poster do filme. 
    <img src="Boxoffice.jpg" alt="criação" width="450"/>
    </def>
    <def title="Player" default-state="collapsed">
        Utilizado para exibição de vídeos ou imagens programados em uma playlist. Este plugin pode ser configurado nos formatos 1x1, 2x1, 3x1 e 4x1.
    <img src="Player.jpg" alt="criação" width="450"/>
    </def>
    <def title="Postercase" default-state="collapsed">
        Possui dois layouts utilizados de maneira diferente.<br/>
        Postercase: Utilizado nas portas de sala dos cinemas, exibe o poster do filme que está em exibição naquela sala.<br/>        
    <img src="Postercase.jpg" alt="criação" width="450"/>
        <br/><br/>Smartpostercase: Exibe trailer, poster e outras informações dos filmes.
        <br/>No formato Presentando, exibe filmes em cartaz do cinema com os horários das sessões.No formato Proximamente, exibe filmes que ainda serão lançados e não possui horário.
    <img src="Postercase2.jpg" alt="criação" width="450"/>
    </def>
    <def title="Combos" default-state="collapsed">
        Exibe os combos de pipoca do cinema. Pode ser configurado para exibir o conteúdo no formado 1x1 e 2x1.<br/>
        Na versão 1.0 do plugin, é necessário que exista uma playlist para exibição dos vídeos de combo.
    <img src="Combos.jpg"/>
    </def>
    <def title="Menu" default-state="collapsed">
        Exibe os demais itens da bomboniere do cinema, além dos preços avulsos de pipoca e bebida.
        <img src="Menu.jpg"/>
    </def>
    <def title="Prices" default-state="collapsed">
        Exibe os preços dos ingressos do cinema, separado por tipo de sessão e sala.
        <img src="Prices.jpg"/>
    </def>
    <def title="MixPlugins" default-state="collapsed">
        Utilizado para exibir dois plugins diferentes na mesma tela. 
        <img src="Mix.jpg"/>
    </def>
    <def title="Inactive" default-state="collapsed">
        Utilizado quando o quadrante não está em uso e não será necessário configurar nenhum plugin nele.
    </def>
</deflist>
</chapter>