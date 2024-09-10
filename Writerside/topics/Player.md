# Players
<show-structure depth="3"/>

## All Players
### Criação de Players

Para ser direcionado à página onde estão todos os players cadastrados, é necessário acessar o menu do Communique no canto esquedo da página e clicar em <ui-path>Players | Todos os Players </ui-path>.

<video src="../videos/acesso-player.mp4" xmlns="" preview-src="acesso-player.png"/>

Para criar um player novo é necessário clicar no botão <img src="add.png" alt="Add icon" width="24" style="inline"/> localizado na parte superior direita, logo abaixo dos filtros de pesquisa.<br></br>
Uma janela abrirá para que as informações do novo player sejam preenchidas.

<img src="Criacao.jpg"  alt="criação" width="450"/>

#### Information

<p></p>
<list type="decimal" start="1">
    <li>Nome
        <list type="bullet">
            <li>Nome dado ao player para melhor identificação.</li>
        </list>
    </li>
    <li>Hostname
        <list type="bullet">
            <li>Nome dado ao dispositivo em uma rede, podendo ser um computador, um servidor etc. É possível descobrir o hostname da máquina digitando "hostname" no prompt de comando.</li>
        </list>
    </li>
    <li>MacAddress
        <list type="bullet">
            <li>Endereço físico da máquina. Também é possível localiza-lo no prompt de comando do digitar "getmac".</li>
        </list>
    </li>
    <li>Theater
        <list type="bullet">
            <li>Cinema onde está localizada a máquina. Ao clicar nessa sessão, uma lista de cinemas é exibida.</li>
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

#### Display


<p></p>
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
            <li>Indica se o monitor está posicionado na horizontal ou vertical.</li>
        </list>
    </li>
</list>

#### Assemble

Definição de quantas máquinas e/ou saídas de vídeo serão utilizadas por este player.

É necessário que haja ao menos uma máquina e uma saída de vídeo.

#### Options
<p></p>
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

### Configuração de Player

#### Config

<chapter title="Playlists" id="config_Playlist">

É criada ao clicar no botão <img src="add.png"/> localizado no canto esquerdo da página.

<img src="Playlist.jpg"/>

É necessário adicionar um nome e descrição para a playlist, além de selecionar o formato e media type das mídias que serão programadas.

</chapter>

<chapter title="Settings" id="config_Settings">

Configuração de cartelera/grade do player. Afeta os plugins Showtimes, Boxoffice e Postercase.

<img src="Settings.jpg"/>
<p></p>
<list type="decimal">
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
            <li>Chave de autorização para acesso à API. Essa chave é fornecida pelo cliente. Ex.: E24017B6-3977-47F6-BBA1-558715B6004F</li>
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

Configuração migrada para o novo sistema de Overlay.

</chapter>

#### Montagem

<p>A montagem dos players deve sempre considerar se o conteúdo será exibido no modo videowall ou não. No caso de não serem exibidos no modo videowall, a quantidade de tvs vai ser igual ao número de saídas de vídeo da máquina e a resolução a ser inserida será equivalente à do sistema.
Caso o player seja montado para o modo videowall, deve-se considerar que cada saída de vídeo pode comportar até 4 monitores/tvs.
A imagem abaixo exemplifica uma saída de vídeo com resolução FullHD dividida em quatro partes, onde cada quadrante possui metade da resolução completa do vídeo.
<img src ="divisaosaidas.png" width="600"/></p>

<p></p><img src="Montagem.jpg" width="600" preview-src="Montagem.jpg"/>

<p></p><list type="decimal">
<li>Novo Layout
    <list type="bullet">
        <li>Cria um novo layout para o player, que pode ser usado como layout alternativo.</li></list></li>
<li>Layout
    <list type="bullet">
        <li>Seleção do layout que será configurado/visualizado.</li>
        <li>Quando existe mais de uma opção de layout, um ícone de para deletar o layout é exibido ao lado. <img src="selecaoLayouts.png"/></li></list></li>
<li>Box Width e Box Height
    <list type="bullet">
        <li>Box Width: Largura da resolução da TV/Monitor em que o player será exibido.</li>
        <li>Quando o player é 1x1, utiliza-se o número inteiro. Ex.: 1920. Já quando o player possui mais de uma tela na mesma saída de vídeo, é necessário dividir esse valor por 2. Ex.: 960</li>
        <li>Box Height: Altura da resolução da TV/Monitor em que o player será exibido.</li>
        <li>Quando o player é 1x1, utiliza-se o número inteiro. Ex.: 1080. Já quando o player possui mais de uma tela na mesma saída de vídeo, é necessário dividir esse valor por 2. Ex.: 540
        <p></p><img src="montagemPlayer1x1.png" width="600" preview-src="montagemPlayer1x1.png"/>
        <img src="montagemPlayer2x2.png" width="600" preview-src="montagemPlayer2x2.png"/></li></list></li>


<li>Columns e Rows
    <list type="bullet">
        <li>Columns: Número de colunas que serão utilizadas na montagem do player. Esse número vai depender da quantidade de saídas e tvs. Na imagem acima, o player possui uma saída de vídeo e o número de colunas é 2.</li>
        <li>Rows: Número de linhas que serão utilizadas na montagem do player. Na imagem acima, o número de linhas é 2.</li>
    </list></li>

<li>Week Days
    <list type="bullet">
        <li>Dias da semana em que o conteúdo será exibido. Quando a letra referente ao dia da semana está verde, significa que esse dia está ativo.</li>
</list></li>
</list>

#### Plugin

<chapter title="Showtimes" id="plugin_Showtimes">

Exibe o horário e tipo das sessões e elas podem ser ordenadas alfabeticamente, por prioridade ou número de sessões.
Tembém é possível filtrar para que exiba apenas sessões regulares ou prime.

<img src="Showtimes.jpg" alt="criação" width="450"/>
<p></p>
<list type="decimal">
    <li>Pugin Screen
        <list type="bullet">
            <li>Utilizado para indicar qual tela do plugin deve ser exibida. O Showtimes 2.0 possui uma segunda tela, fazendo com que esse número possa variar entre 1 e 2.</li>
        </list>
    </li>
    <li>Videowall Screen
        <list type="bullet">
            <li>Posição do plugin no videwall. Esse número pode variar entre 1 e 16.</li>
        </list>
    </li>
    <li>Version
        <list type="bullet">
            <li>Versão do plugin. As opções disponíveis são 1.0 e 2.0.</li>
        </list>
    </li>
    <li>Switch Page Time
        <list type="bullet">
            <li>Tempo que o plugin leva para exibir a próxima página com horários. A contagem é feita pelo número de filmes da página vezes o tempo em segundos indicado na configuração.</li>
        </list>
    </li>
    <li>Show Only Next Sessions
        <list type="bullet">
            <li>Quando ativo, o plugin oculta os horários de sessões que já foram exibidas.</li>
        </list>
    </li>
    <li>Filter
        <list type="bullet">
            <li>Possibilita filtrar as sessões para exibir apenas regular ou prime. Também é possível exibir os dois tipos ao selecionar <i>none</i>.</li>
        </list>
    </li>
    <li>Order By
        <list type="bullet">
            <li>Ordem em que os horários dos filmes serão exibidos pelo plugin, sendo elas: alfabética, número de sessões e prioridade.
                <list type="alpha-lower">
                    <li>Alphabetical: Exibe os filmes em ordem alfabética.</li>
                    <li>Number of Sessions: Exibe o filme por número de sessões em ordem decrescente.</li>
                    <li>Priority: Exibe os filmes de acordo com a prioridade inserida em <ui-path>Settings | Order</ui-path>.</li></list></li>
        </list>
    </li>
</list> 

</chapter>

<chapter title="Boxoffice" id="plugin_Boxoffice">

Exibe o horário e tipo das sessões com o poster do filme.

<img src="Boxoffice.jpg" alt="criação" width="450"/>
<p></p>
<list type="decimal">
    <li>Pugin Screen
        <list type="bullet">
            <li>Utilizado para indicar qual tela do plugin deve ser exibida. Esse número varia entre 1 e a quantidade de telas utilizadas por este plugin. É necessário que cada tela seja preenchida com o número correspondente para que não haja falta ou duplicidade de conteúdo.</li>
        </list>
    </li>
    <li>Videowall Screen
        <list type="bullet">
            <li>Posição do plugin no videwall. Esse número pode variar entre 1 e 16.</li>
        </list>
    </li>
    <li>Version
        <list type="bullet">
            <li>Versão do plugin. As opções disponíveis são 1.0 e 2.0.</li>
        </list>
    </li>
    <li>Split Movies by Exihibitions
        <list type="bullet">
            <li>Separa os itens por legendado e dublado.</li>
        </list>
    </li>
    <li>Filter
        <list type="bullet">
            <li>Quando ativo, o plugin oculta os horários de sessões que já foram exibidas.</li>
        </list>
    </li>
    <li>Layouts
        <list type="bullet">
            <li>Número de sessões exibidas por tela. O plugin faz uma contagem automaticamente para que todas as sessões sejam distribuidas entre os layouts disponíveis. </li>
        </list>
    </li>
    <li>Order By
        <list type="bullet">
            <li>Primeiro: Define a ordem dos itens.
                <list type="alpha-lower">
                    <li>Alphabetical: As sessões são exibidas por ordem alfabética.</li>
                    <li>Session: As sessões são ordenadas por quantidade de sessão.</li></list></li>
            <li>Segundo: Cria uma subordem quando os itens possuem a mesma prioridade com base na primeira sessão.
                <list type="alpha-lower">
                <li>Alphabetical: As sessões são exibidas por ordem alfabética.</li>
                <li>Session: As sessões são ordenadas por quantidade de sessão.</li></list></li>
        </list>
    </li>
</list> 

</chapter>

<chapter title="Player" id="plugin_Player">

Utilizado para exibição de vídeos ou imagens programados em uma playlist. Este plugin pode ser configurado nos formatos 1x1, 2x1, 3x1 e 4x1.
    
<img src="Player.jpg" alt="criação" width="450"/>
<p></p>
<list type="decimal">
    <li>Pugin Screen
        <list type="bullet">
            <li>Utilizado para indicar qual tela do plugin deve ser exibida. Neste caso, o plugin screen corresponde ao quadrante do vídeo que será exibido.</li>
        </list>
    </li>
    <li>Position
        <list type="bullet">
            <li>Posição do plugin no videwall.</li>
        </list>
    </li>
    <li>SV Size
        <list type="bullet">
            <li>Configuração voltada para o *Smartviewer*. Na primeira tela é inserido o número de quadrantes do vídeo e nas demais coloca-se zero.
Exemplo: Em um vídeo 4x1, a primeira tela do plugin receberá o número 4 no *Sv Size*, as demais receberão 0.</li>
        </list>
    </li>
    <li>Version
        <list type="bullet">
            <li>Versão do plugin. Disponível apenas na versão 2.0.</li>
        </list>
    </li>
    <li>Screen Line
        <list type="bullet">
            <li>Número da linha do vídeo que será exibida pela tela que está sendo programada.</li>
        </list>
    </li>
    <li>Screen Col
        <list type="bullet">
            <li>Número da coluna do vídeo que será exibida pela tela que está sendo programada.</li>
        </list>
    </li>
    <li>Player Width
        <list type="bullet">
            <li>Largura do player de vídeo.</li>
        </list>
    </li>
    <li>Player Height
        <list type="bullet">
            <li>Altura do player de vídeo.</li>
        </list>
    </li>
    <li>Hide on Player
        <list type="bullet">
            <li>Utilizado nas telas que são uma extensão diretamente à direita.</li>
        </list>
    </li>
    <li>It's an extension
        <list type="bullet">
            <li>Utilizado para indicar que aquele monitor é uma extensão de outro quando não estão na mesma linha.</li>
        </list>
    </li>
    <li>Extendeds Monitors
        <list type="bullet">
            <li>Utilizado para indicar para qual monitor esse vídeo será estendido. Se a tela for uma extensão, é necessário indicar o número do monitor em que o vídeo inicia.</li>
        </list>
    </li>
</list> 

</chapter>

<chapter title="Postercase" id="plugin_Postercase">

Possui dois layouts utilizados de maneira diferente.<br/>

**Postercase**: Utilizado nas portas de sala dos cinemas, exibe o poster do filme que está em exibição naquela sala.<br/>        

<img src="Postercase.jpg" alt="criação" width="450"/>
<p></p>
<list type="decimal">
    <li>Version
        <list type="bullet">
            <li>Versão do plugin. Disponível nas versões 1.0 e 2.0.</li>
        </list>
    </li>
    <li>Room
        <list type="bullet">
            <li>Número correspondente à sala do cinema em que o player está localizado.</li>
        </list>
    </li>
    <li>Use BR Layout
        <list type="bullet">
            <li>Ativa o layout de postercase do Brasil.</li>
        </list>
    </li>
    <li>Smartpostercase
        <list type="bullet">
            <li>Ativa o plugin *Smartpostercase*</li>
        </list>
    </li>
</list> 

<br/>**Smartpostercase**: Exibe trailer, poster e outras informações dos filmes.
<br/>No formato Presentando, exibe filmes em cartaz do cinema com os horários das sessões.No formato Proximamente, exibe filmes que ainda serão lançados e não possui horário.

<img src="Postercase2.jpg" alt="criação" width="450"/>
<p></p>
<list type="decimal">
    <li>Version
        <list type="bullet">
            <li>Versão do plugin.</li>
        </list>
    </li>
    <li>Plugin Screen
        <list type="bullet">
            <li>Utilizado para indicar qual tela do plugin deve ser exibida. Neste caso não é necessário alterar o número da tela para que todo o conteúdo seja exibido.</li>
        </list>
    </li>
    <li>Presentando XML/API Path
        <list type="bullet">
            <li>Endereço para o arquivo xml ou API que será utilizado para exibir filmes que estão em cartaz.</li>
        </list>
    </li>
    <li>Proximamente XML/API Path
        <list type="bullet">
            <li>Endereço para o arquivo xml ou API que será utilizado para exibir os próximos filmes que entrarão em cartaz.</li>
        </list>
    </li>
    <li>Poster Change
        <list type="bullet">
            <li>Tempo de exibição de cada filme contido no arquivo.</li>
        </list>
    </li>
    <li>Smartpostercase ordering
        <list type="bullet">
            <li>Ordem de exibição dos filmes.</li>
        </list>
    </li>
</list> 

</chapter>

<chapter title="Combos" id="plugin_Combos">

Exibe os combos de pipoca do cinema. Pode ser configurado para exibir o conteúdo no formado 1x1 e 2x1.<br/>
Na versão 1.0 do plugin, é necessário que exista uma playlist para exibição dos vídeos de combo.

<img src="Combos.jpg"/>
<p></p>
<list type="decimal">
    <li>Pugin Screen
        <list type="bullet">
            <li>Utilizado para indicar qual tela do plugin deve ser exibida. As duas vesões do plugin possuem opção 2x1.</li>
        </list>
    </li>
    <li>Videowall Screen
        <list type="bullet">
            <li>Posição do plugin no videwall</li>
        </list>
    </li>
    <li>Version
        <list type="bullet">
            <li>Versão do plugin.</li>
        </list>
    </li>
    <li>Width
        <list type="bullet">
            <li>Largura da tela de combos. Esse campo sempre utilizará o número 1 na versão 2.0, mesmo no formato 2x1.</li>
        </list>
    </li>
    <li>Is extends
        <list type="bullet">
            <li>Opção direcionada a versão 1.0, usada para indicar que o vídeo do plugin será estendido.</li>
        </list>
    </li>
    <li>Dual Monitor
        <list type="bullet">
            <li>Utilizado para indicar que o plugin será 2x1.</li>
        </list>
    </li>
    <li>Combos XML
        <list type="bullet">
            <li>Endereço do XML/API de combos.</li>
        </list>
    </li>
    <li>Seconds to combo switch
        <list type="bullet">
            <li>Tempo em que o combo será exibido. Na versão 1.0, indica quanto tempo o carrossel ficará parado.</li>
        </list>
    </li>
    <li>Layout
        <list type="bullet">
            <li>Tipo de layout do plugin. Utilizado apenas na versão 1.0.</li>
        </list>
    </li>
    <li>Combo Header Font Size
        <list type="bullet">
            <li>Tamanho da fonte do nome dos combos.</li>
        </list>
    </li>
    <li>Combo Price Font Size
        <list type="bullet">
            <li>Tamanho da fonte dos preços.</li>
        </list>
    </li>
    <li>Gold Percent
        <list type="bullet">
            <li>Porcentagem de desconto dos preços GOLD.</li>
        </list>
    </li>
    <li>Pro Percent
        <list type="bullet">
            <li>Porcentagem de desconto dos preços PRO.</li>
        </list>
    </li>
    <li>Price Label
        <list type="bullet">
            <li>Legenda abaixo do preço. Utilizado apenas na versão 1.0.</li>
        </list>
    </li>
    <li>Special Color Price
        <list type="bullet">
            <li>Cor especial dos preços. Utilizado apenas na versão 1.0.</li>
        </list>
    </li>
    <li>Invert price with special price
        <list type="bullet">
            <li>Inverte o preço original com o preço promocional. </li>
        </list>
    </li>
    <li>Line through original price
        <list type="bullet">
            <li>Insere uma linha vermelha no preço original dos combos. Utilizado apenas na versão 1.0.</li>
        </list>
    </li>
    <li>Hidden Cents
        <list type="bullet">
            <li>Oculta os centavos dos preços. Utilizado apenas na versão 1.0.</li>
        </list>
    </li>
</list>

</chapter>

<chapter title="Menu" id="plugin_Menu">

Exibe os demais itens da bomboniere do cinema, além dos preços avulsos de pipoca e bebida.

<img src="Menu.jpg"/>

</chapter>

<chapter title="Prices" id="plugin_Prices">

Exibe os preços dos ingressos do cinema, separado por tipo de sessão e sala.

<img src="Prices.jpg"/>
<p></p>
<list type="decimal">
    <li>Pugin Screen
        <list type="bullet">
            <li>Utilizado para indicar qual tela do plugin deve ser exibida. Este plugin possui apenas telas 1x1.</li>
        </list>
    </li>
    <li>Videowall Screen
        <list type="bullet">
            <li>Posição do plugin no videwall</li>
        </list>
    </li>
    <li>Version
        <list type="bullet">
            <li>Versão do plugin.</li>
        </list>
    </li>
    <li>Prices XML (Today)
        <list type="bullet">
            <li>Endereço da API de preços diários.</li>
        </list>
    </li>
    <li>Prices XML (Weekly)
        <list type="bullet">
            <li>Endereço da API de preços semanais.</li>
        </list>
    </li>
    <li>Token
        <list type="bullet">
            <li>Chave da API.</li>
        </list>
    </li>
    <li>Seconds to page switch
        <list type="bullet">
            <li>Tempo pde exibição de cada página de preços.</li>
        </list>
    </li>
    <li>Seconds to message switch
        <list type="bullet">
            <li>Tempo de exibição de cada linha da mensagem de cabeçalho.</li>
        </list>
    </li>
    <li>Customer font size
        <list type="bullet">
            <li>Tamanho customizado da fonte.</li>
        </list>
    </li>
    <li>Hidden Cents
        <list type="bullet">
            <li>Oculta os centavos dos preços.</li>
        </list>
    </li>
</list>

</chapter>

<chapter title="MixPlugins" id="plugin_MixPlugins">

Utilizado para exibir dois plugins diferentes na mesma tela. 

<img src="Mix.jpg"/>
<p></p>
<list type="decimal">
    <li>Pugins
        <list type="bullet">
            <li>Seleção dos dois plugins que serão exibidos no mesmo monitor.</li>
        </list>
    </li>
    <li>Defina as durações (Opção exibida após a escolha dos plugins)
        <list type="bullet">
            <li>Duração da exibição de cada plugin.</li>
        </list>
    </li>
</list>

</chapter>

<chapter title="Inactive" id="plugin_Inactive">

Utilizado quando o quadrante não está em uso e não será necessário configurar nenhum plugin nele.

</chapter>

# Player Groups

Agrupamento de players para programação de mídias e campanhas.

<p></p>

<img src="CriarPlayergroup.png" width="600"/>

<list type="decimal">
<li>Name
    <list type="bullet">
        <li>Nome do grupo.</li>
    </list>
</li>
<li>Description
    <list type="bullet">
        <li>Descrição do grupo ou conteúdo.</li>
    </list> 
</li>
<li>Duplicate
    <list>
    <li><img src="duplicaPG.png" width="20"/> Duplica um playergroup já existente</li>
    </list>
</li>
<li>Delete
    <list type="bullet">
        <li><img src="deletePG.png" width="20"/>Deleta o playergroup</li>
    </list>
</li>
</list>

O recurso conta com filtros por nome de player, cinema, locate e categoria.
Ao clicar em um player da lista *Players*, ele é automaticamente enviado para a lista *Players selected*. Também é possível utilizar o botão <img src="idaPG.png" width="20"/> para que todos os players filtrados sejam eviados para a lista da direita.
Ao clicar em <img src="voltaPG.png" width="20"/>, os players saem da lista de selecionados e voltam para a lista geral.

<img src="selecaoPlayergroup.png" width="600"/>