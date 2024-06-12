# Communique 5.0

## Criação de Player

Para ser direcionado à página onde estão todos os players cadastrados, é necessário acessar o menu do Communique no canto esquedo da página e clicar em <ui-path>Players | Todos os Players </ui-path>.

<video src="acesso-player.mp4" xmlns="" preview-src="acesso-player.png"/>

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
a
    </def>
    <def title="Settings" default-state="collapsed">
a
    </def>
    <def title="Sync" default-state="collapsed">
a
    </def>
    <def title="Layer" default-state="collapsed">
a
    </def>
    <def title="Event" default-state="collapsed">
a
    </def>
    <def title="Lobby" default-state="collapsed">
a
    </def>
</deflist>
</chapter>
<chapter title="Montagem" id="config_Montagem" collapsible="true">
<deflist collapsible="true">
</deflist>
</chapter>
<chapter title="Plugin" id="config_Plugin" collapsible="true">
<deflist collapsible="true">
    <def title="Showtimes" default-state="collapsed">
    Exibe os horários dos filmes, com indicação de cor para qual é a próxima sessão e para sessões com poucos assentos e lotadas.
    <img src="Showtimes.jpg" alt="criação" width="450"/>
    </def>
    <def title="Boxoffice" default-state="collapsed">
    <img src="Boxoffice.jpg" alt="criação" width="450"/>
    </def>
    <def title="Player" default-state="collapsed">
    <img src="Player.jpg" alt="criação" width="450"/>
    </def>
    <def title="Postercase" default-state="collapsed">
    <img src="Postercase.jpg" alt="criação" width="450"/>
    <img src="Postercase2.jpg" alt="criação" width="450"/>
    </def>
    <def title="Combos" default-state="collapsed">
a
    </def>
    <def title="Menu" default-state="collapsed">
a
    </def>
    <def title="Prices" default-state="collapsed">
a
    </def>
    <def title="MixPlugins" default-state="collapsed">
a
    </def>
    <def title="Inactive" default-state="collapsed">
a
    </def>
</deflist>
</chapter>