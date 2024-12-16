# Reports

Os diagramas ilustram as diferentes configurações possíveis de players e monitores no sistema.
Exemplos variam desde um player único conectado a vários monitores até configurações mais complexas com múltiplos computadores, cada um gerenciando várias saídas de monitor.

#### Report Diagramas

<img src="reportDiagram.png" alt="Montagem" width="500" preview-src="reportDiagram.png" border-effect="line"/>

<procedure id="filterDiagram">
    <step>
        <p><b>Filtro por Teatro:</b> Permite selecionar um teatro específico e exibir seus diagramas associados. </p>
    </step>
    <step>
        <p><b>Filtro por Player:</b> Permite selecionar um player específico e exibir o diagrama associado a ele. </p>
    </step>
</procedure>

<procedure id="iconsDiagram">
    <step>
        <p><img  type="inline" src="impressora.png" alt="Montagem" width="30" border-effect="rounded"/>: Permite gerar uma versão imprimível do diagrama atual.</p>
    </step>
    <step>
        <p><img  type="inline" src="download.png" alt="Montagem" width="30" border-effect="rounded"/>: Permite baixar o diagrama atual em formato digital (PDF).</p>
    </step>
    <step>
        <p><img  type="inline" src="lixeira.png" alt="Montagem" width="30" border-effect="rounded"/>: Permite deletar o diagrama atual ou remover uma configuração específica do diagrama.</p>
    </step>
    <step>
        <p><img  type="inline" src="seta.png" alt="Montagem" width="30" border-effect="rounded"/>: Clique para buscar e exibir o diagrama selecionado.</p>
    </step>
</procedure>

<procedure id="DiagramDetails">
    <step>
        <p><img  type="inline" src="online.png" alt="Montagem" width="100" border-effect="rounded"/>: Status atual do player, Online ou Offline.</p>
    </step>
    <step>
        <p>Hostname: Ex: BR0688ROD28</p>
    </step>
    <step>
        <p><img  type="inline" src="i.png" alt="Montagem" width="30" border-effect="rounded"/>: Permite olhar as especificações do sistema (SO, processador, memoria, graficos, monitor, armazenamento)</p>
        <img src="i2.png" alt="Montagem" width="400" border-effect="line" preview-src="i2.png"/>
    </step>
    <step>
        <p><img type="inline" src="camera.png" alt="Montagem" width="30" border-effect="line"/>: Permite visualizar uma foto do monitor físico.</p>
        <img src="camera2.png" alt="Montagem" width="300" border-effect="line" preview-src="camera2.png"/>
    </step>
    <step>
        <p>Locate do player: Ex: ATM, Snack, Boxoffice</p>
    </step>
    <step>
        <p>Category do player: Ex: Regular, Prime, Bistro, Videowall, XD, Lab</p>
    </step>
</procedure>

#### Visualização do Diagrama

<img  type="inline" src="diagrama.png" alt="Montagem" width="700" border-effect="line" preview-src="diagrama.png"/>

<procedure id="Diagram">
    <step>
        <p><b>Identificação do player e máquina:</b> últimas 4 letras/numeros do hostname. EX: OD28 - M1</p>
    </step>
    <step>
    <p>
        <b>Número de saídas da máquina/computador:</b>
        <img src="saidas.png" alt="Montagem" width="250" border-effect="rounded" preview-src="saidas.png"/>
    </p>
    </step>
    <step>
        <p>Cada saída está conectada a 1 monitor, que pode estar ligado a outros monitores, com um máximo de 4 monitores.</p>
    </step>
    <step>
        <p>Cada monitor está especificado pelo seu tipo de plugin e número. EX: Media Player, Smartcombo</p>
    </step>
</procedure>

## Report Player

<img src="report-player.png" alt="Montagem" width="750" border-effect="line" preview-src="report-player.png"/>

<procedure id="filter-player">
    <step>
        <p><b>Filtro por Teatro/Cinema:</b> permite filtrar por todos os teatros ou um teatro específico. </p>
    </step>
    <step>
        <p><img type="inline" src="abc.png" alt="Montagem" width="60" border-effect="line"/>: permite ordenar os cinemas em ordem alfabética ou numérica. </p>
    </step>
    <step>
        <p><b>Filtro por Category:</b> permite filtrar por todas as categoria de player ou categorias específicas. Ex: All, Regular, Prime, Bistro, Videowall, XD, Lab</p>
    </step>
    <step>
        <p><b>Filtro por Format:</b> permite filtrar por todos os formatos ou alguns formatos específicos.</p>
    </step>
    <step>
        <p><b>Filtro por Player:</b> permite selecionar todos os players do teatro selecionado, ou alguns players específicos.</p>
    </step>
    <step>
        <p><b>GroupedBy:</b> permite agrupar os itens do report por nenhum, category, format, locate ou theater. Ex: Grouped by category; todos os player estao agrupados pelo sua categoria Regular.</p>
        <img src="grouped.png" alt="Montagem" width="700" border-effect="line" preview-src="grouped.png"/>
    </step>
    <step>
        <p><b>Status:</b> permite exibir apenas players Online, Offline ou ambos.</p>
    </step>
</procedure>

<img src="report-player2.png" alt="Montagem" width="750" border-effect="line" preview-src="report-player2.png"/>

<procedure id="report-player2">
    <step>
        <p><b>Theater:</b> nome do teatro. </p>
    </step>
   <step>
        <p><b>Player:</b> nome do player. </p>
    </step>
    <step>
        <p><b>Monitor:</b>  nome do monitor. </p>
    </step>
    <step>
        <p><b>Online:</b> status do player. Online ou Offline. </p>
    </step>
    <step>
        <p><b>Last Sync:</b>  ultimo horario e dia do sync. </p>
    </step>
    <step>
        <p><b>Prevent Config Sync:</b> configuracao para prevenir o sync de config. </p>
    </step>
    <step>
        <p><b>Sync Config:</b> status que exibe se o sync de config esta ativo. </p>
    </step>
    <step>
        <p><b>Last Sync Config:</b> ultimo horario e dia do sync config. </p>
    </step>
    <step>
        <p><b>Prevent Playlist Sync:</b>  configuracao para prevenir o sync de playlist. </p>
    </step>
    <step>
        <p><b>Prevent Config Sync:</b> configuracao para prevenir o config de sync. </p>
    </step>
    <step>
        <p><b>Sync Config:</b> status que exibe se o sync de config esta ativo. </p>
    </step>
</procedure>

## Report Combos

<img src="report-combos.png" alt="Montagem" width="750" border-effect="line" preview-src="report-combos.png"/>

<procedure id="filter-combos">
    <step>
        <p><b>Filtro por Teatro/Cinema:</b> permite filtrar por todos os teatros ou um teatro específico. </p>
    </step>
    <step>
        <p><b>Filtro por Products:</b> permite filtrar por todas as opções de combo ou um combo específico.</p>
    </step>
    <step>
        <p><img type="inline" src="delete-combos.png" alt="Montagem" width="30" border-effect="rounded"/>: reseta as filtragens do report. </p>
    </step>
    <step>
        <p><img type="inline" src="enter.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para gerar o report com os filtros selecionados. </p>
    </step>
    <step>
        <p><img type="inline" src="help.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para exibir textos explicatorios. </p>
    </step>
</procedure>

<img src="report-combos2.png" alt="Montagem" width="750" border-effect="line" preview-src="report-combos2.png"/>

<procedure id="report-combos2">
    <step>
        <p><b>Theater:</b> código e nome do teatro. </p>
    </step>
   <step>
        <p><b>Code:</b> código do combo. </p>
    </step>
    <step>
        <p><b>Name:</b>  nome do combo. Ex: Combo G Ref Salgada </p>
    </step>
    <step>
        <p><b>Price:</b> preço do combo. </p>
    </step>
    <step>
        <p><b>Last Update:</b>  ultimo horario e dia da atualização do combo. </p>
    </step>
</procedure>

## Report Campaign

<img src="report-campaign.png" alt="Montagem" width="750" border-effect="line" preview-src="report-campaign.png"/>

<procedure id="filter-campaign">
    <step>
        <p><b>Filtro por Advertiser:</b> permite filtrar por um ou vários advertisers. </p>
    </step>
    <step>
        <p><b>Filtro por Campaign:</b> permite filtrar por uma campanha especifica dentre as disponiveis no advertiser.</p>
    </step>
    <step>
        <p><b>Filtro por Data:</b>: permite filtrar por um intervalo de tempo específico. </p>
    </step>
    <step>
        <p><img type="inline" src="delete-combos.png" alt="Montagem" width="30" border-effect="rounded"/>: reseta as filtragens do report. </p>
    </step>
    <step>
        <p><img type="inline" src="enter.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para gerar o report com os filtros selecionados. </p>
    </step>
    <step>
        <p><img type="inline" src="help.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para exibir textos explicatorios. </p>
    </step>
</procedure>

<img src="report-campaign2.png" alt="Montagem" width="750" border-effect="line" preview-src="report-campaign2.png"/>

<procedure id="filter-campaign2">
    <step>
        <p><b>Barra Superior:</b> exibe os logos dos owners.</p>
    </step>
    <step>
        <p><b>Lateral Esquerda:</b></p>
        <ul>
            <li><b>Nome da Campanha:</b> Ex: BRADESCO PRIME</li>
            <li><b>Nome da Mídia:</b> Ex: Benefícios Prime Cartões Bradesco</li>
            <li><b>Tempo de Exibição da Campanha:</b> Ex: 10/09/2023 - 31/12/2023 (112 dias)</li>
            <li><b>Status:</b> Status atual da campanha: Ex: finished</li>
            <li><b>Advertiser:</b> Ex: BRADESCO</li>
            <li><b>Duração da Mídia:</b> duração da mídia em segundos: Ex: 15"</li>
        </ul>
    </step>
    <step>
        <p><b>Lateral Direita:</b></p>
        <ul>
            <li><b>Total de Visualizações:</b> Ex: 731716 views</li>
            <li><b>Total de Dias:</b> tempo total de dias em que a campanha foi exibida.</li>
            <li><b>Intervalo de Datas:</b> intervalo de dias em que a campanha foi exibida.</li>
            <li><b>Entrada da Campanha:</b> exibe o número total de teatros e players em que a campanha foi exibida.</li>
            <li><b>Advertiser:</b> Ex: BRADESCO</li>
            <li><b>Duração da Mídia:</b> duração da mídia em segundos: Ex: 15"</li>
        </ul>
    </step>
    <step>
        <p><b>Conteúdo Central:</b></p>
        <ul>
            <li><b>Teatro:</b> código e nome do teatro.</li>
            <li><b>Player:</b> nome do player. Ex: ATM</li>
            <li><b>Local:</b> nome do local. Ex: Snack</li>
            <li><b>Playlist:</b> nome da playlist.</li>
            <li><b>Formato:</b> Ex: 1x1 - Horizontal</li>
            <li><b>Views:</b> total de reproduções da campanha.</li>
            <li><b>AVG:</b> média de reproduções da campanha.</li>
        </ul>
    </step>
</procedure>

## Report Event

<img src="report-event.png" alt="Montagem" width="750" border-effect="line" preview-src="report-event.png"/>

<procedure id="filter-event">
    <step>
        <p><b>Filtro por Client:</b> permite filtrar por um ou vários clients. (Cinemark, Flix Media, Flix Lab, MOG) </p>
    </step>
    <step>
        <p><b>Filtro por Event:</b> permite filtrar por um evento especifico dentre as programadas atualmente.</p>
    </step>
    <step>
        <p><b>Filtro por Data:</b>: permite filtrar por um intervalo de tempo específico. </p>
    </step>
    <step>
        <p><img type="inline" src="delete-combos.png" alt="Montagem" width="30" border-effect="rounded"/>: reseta as filtragens do report. </p>
    </step>
    <step>
        <p><img type="inline" src="enter.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para gerar o report com os filtros selecionados. </p>
    </step>
    <step>
        <p><img type="inline" src="help.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para exibir textos explicatorios. </p>
    </step>
</procedure>

## Report Layer

<img src="report-layer.png" alt="Montagem" width="750" border-effect="line" preview-src="report-layer.png"/>

<procedure id="filter-layer">
    <step>
        <p><b>Filtro por Client:</b> permite filtrar por um ou vários clients. (Cinemark, Flix Media, Flix Lab, MOG) </p>
    </step>
    <step>
        <p><b>Filtro por Event:</b> permite filtrar por um evento especifico dentre as programadas atualmente.</p>
    </step>
    <step>
        <p><b>Filtro por Data:</b>: permite filtrar por um intervalo de tempo específico. </p>
    </step>
    <step>
        <p><img type="inline" src="delete-combos.png" alt="Montagem" width="30" border-effect="rounded"/>: reseta as filtragens do report. </p>
    </step>
    <step>
        <p><img type="inline" src="enter.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para gerar o report com os filtros selecionados. </p>
    </step>
    <step>
        <p><img type="inline" src="help.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para exibir textos explicatorios. </p>
    </step>
</procedure>

## Report Lobby

<img src="report-lobby.png" alt="Montagem" width="750" border-effect="line" preview-src="report-lobby.png"/>

<procedure id="filter-lobby">
    <step>
        <p><b>Filtro por Client:</b> permite filtrar por um ou vários clients. (Cinemark, Flix Media, Flix Lab, MOG) </p>
    </step>
    <step>
        <p><b>Filtro por Event:</b> permite filtrar por um evento especifico dentre as programadas atualmente.</p>
    </step>
    <step>
        <p><b>Filtro por Data:</b>: permite filtrar por um intervalo de tempo específico. </p>
    </step>
    <step>
        <p><img type="inline" src="delete-combos.png" alt="Montagem" width="30" border-effect="rounded"/>: reseta as filtragens do report. </p>
    </step>
    <step>
        <p><img type="inline" src="enter.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para gerar o report com os filtros selecionados. </p>
    </step>
    <step>
        <p><img type="inline" src="help.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para exibir textos explicatorios. </p>
    </step>
</procedure>

## Report Media

<img src="report-media.png" alt="Montagem" width="750" border-effect="line" preview-src="report-media.png"/>

<procedure id="filter-media">
    <step>
        <p><b>Filtro por mediaType:</b> permite filtrar por todos os media types ou media types específicos. </p>
    </step>
    <step>
        <p><b>Filtro por Format:</b> permite filtrar por todos os formatos ou alguns formatos específicos.</p>
    </step>
    <step>
        <p><b>Filtro por Client:</b> permite filtrar por um ou vários clients. (Cinemark, Flix Media, Flix Lab, MOG) </p>
    </step>
    <step>
        <p><b>Filtro por Data:</b>: permite filtrar por um intervalo de tempo específico. </p>
    </step>
    <step>
        <p><img type="inline" src="delete-combos.png" alt="Montagem" width="30" border-effect="rounded"/>: reseta as filtragens do report. </p>
    </step>
    <step>
        <p><img type="inline" src="enter.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para gerar o report com os filtros selecionados. </p>
    </step>
    <step>
        <p><img type="inline" src="help.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para exibir textos explicatorios. </p>
    </step>
</procedure>

Obs.: A partir da versão 5.1.2 o report de mídia possui a indicação de vigência da mídia. Exibindo a data de entrada da mídia e a data de saída (se houver).

## Report Playlists

<img src="report-playlists.png" alt="Montagem" width="750" border-effect="line" preview-src="report-playlists.png"/>

<procedure id="filter-playlists">
    <step>
        <p><b>Filtro por Teatro/Cinema:</b> permite filtrar por todos os teatros ou um teatro específico. </p>
    </step>
    <step>
        <p><img type="inline" src="abc.png" alt="Montagem" width="60" border-effect="line"/>: permite ordenar os cinemas em ordem alfabética ou numérica. </p>
    </step>
    <step>
        <p><b>Filtro por Category:</b> permite filtrar por todas as categoria de player ou categorias específicas. Ex: All, Regular, Prime, Bistro, Videowall, XD, Lab</p>
    </step>
        <step>
        <p><b>Filtro por Locate:</b> permite filtrar por todos os locates ou locates específicos. </p>
    </step>
    <step>
        <p><b>Filtro por Format:</b> permite filtrar por todos os formatos ou alguns formatos específicos.</p>
    </step>
    <step>
        <p><b>Filtro por Player:</b> permite selecionar todos os players do teatro selecionado, ou alguns players específicos.</p>
    </step>
    <step>
        <p><b>Filtro por Data:</b> permite filtrar por um intervalo de tempo específico. </p>
    </step>
    <step>
        <p><img type="inline" src="delete-combos.png" alt="Montagem" width="30" border-effect="rounded"/>: reseta as filtragens do report. </p>
    </step>
    <step>
        <p><img type="inline" src="enter.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para gerar o report com os filtros selecionados. </p>
    </step>
    <step>
        <p><img type="inline" src="help.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para exibir textos explicatorios. </p>
    </step>
</procedure>

<img src="report-playlists2.png" alt="Montagem" width="750" border-effect="line" preview-src="report-playlists2.png"/>

Obs.: A partir da versão 5.1.2 o report de playlist possui a indicação de vigência da mídia. Exibindo a data de entrada da mídia e a data de saída (se houver).
<img src="report-playlists3.png" alt="Montagem" width="750" border-effect="line" preview-src="report-playlists3.png"/>

## Report Group Programming

<img src="groupProgramming.png" alt="Montagem" width="750" border-effect="line" preview-src="groupProgramming.png"/>

<procedure id="filter-group">
    <step>
        <p><b>Filtro por Operation:</b> permite filtrar por all, insertion ou remove. </p>
    </step>
    <step>
        <p><b>Filtro por User:</b> permite filtrar por todos os usuarios ou usuarios específicos.</p>
    </step>
        <step>
        <p><b>Filtro por Player Group:</b> permite filtrar por todos os player groups ou player groups específicos. </p>
    </step>
    <step>
        <p><b>Filtro por Data:</b> permite filtrar por um intervalo de tempo específico. </p>
    </step>
    <step>
        <p><img type="inline" src="delete-combos.png" alt="Montagem" width="30" border-effect="rounded"/>: reseta as filtragens do report. </p>
    </step>
    <step>
        <p><img type="inline" src="enter.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para gerar o report com os filtros selecionados. </p>
    </step>
    <step>
        <p><img type="inline" src="help.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para exibir textos explicatorios. </p>
    </step>
</procedure>

## Report API

<img src="api.png" alt="Montagem" width="750" border-effect="line" preview-src="api.png"/>

<procedure id="api">
    <step>
        <p><b>Filtro por Teatro/Cinema:</b> permite filtrar por todos os teatros ou um teatro específico. </p>
    </step>
    <step>
        <p><b>Filtro por Data:</b> permite filtrar por um intervalo de tempo específico. </p>
    </step>
    <step>
        <p><img type="inline" src="help.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para exibir textos explicatorios. </p>
    </step>
</procedure>

## Report GO Operation

<img src="go.png" alt="Montagem" width="750" border-effect="line" preview-src="go.png"/>

<procedure id="go">
    <step>
        <p><b>Filtro por Teatro/Cinema:</b> permite filtrar por todos os teatros ou um teatro específico. </p>
    </step>
    <step>
        <p><b>Filtro por Data:</b> permite filtrar por um intervalo de tempo específico. </p>
    </step>
    <step>
        <p><img type="inline" src="delete-combos.png" alt="Montagem" width="30" border-effect="rounded"/>: reseta as filtragens do report. </p>
    </step>
    <step>
        <p><img type="inline" src="enter.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para gerar o report com os filtros selecionados. </p>
    </step>
    <step>
        <p><img type="inline" src="help.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para exibir textos explicatorios. </p>
    </step>
</procedure>

## Report Player Config

<img src="playerconfig.png" alt="Montagem" width="750" border-effect="line" preview-src="playerconfig.png"/>

<procedure id="playerconfig">
    <step>
        <p><b>Filtro por Teatro/Cinema:</b> permite filtrar por todos os teatros ou um teatro específico. </p>
    </step>
    <step>
        <p><b>Filtro por Player:</b> permite selecionar todos os players do teatro selecionado, ou alguns players específicos.</p>
    </step>
    <step>
        <p><img type="inline" src="delete-combos.png" alt="Montagem" width="30" border-effect="rounded"/>: reseta as filtragens do report. </p>
    </step>
    <step>
        <p><img type="inline" src="enter.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para gerar o report com os filtros selecionados. </p>
    </step>
    <step>
        <p><img type="inline" src="help.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para exibir textos explicatorios. </p>
    </step>
</procedure>

<img src="playerconfig2.png" alt="Montagem" width="750" border-effect="line" preview-src="playerconfig2.png"/>

## Report Prices

<img src="prices.png" alt="Montagem" width="750" border-effect="line" preview-src="prices.png"/>

<procedure id="prices">
    <step>
        <p><b>Filtro por Teatro/Cinema:</b> permite filtrar por todos os teatros ou um teatro específico. </p>
    </step>
    <step>
        <p><img type="inline" src="help.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para exibir textos explicatorios. </p>
    </step>
</procedure>

## Report Timeline

<img src="timeline.png" alt="Montagem" width="750" border-effect="line" preview-src="timeline.png"/>

<procedure id="timeline">
    <step>
        <p><b>Filtro por Teatro/Cinema:</b> permite filtrar por todos os teatros ou um teatro específico. </p>
    </step>
    <step>
        <p><b>Filtro por Player:</b> permite selecionar todos os players do teatro selecionado, ou alguns players específicos.</p>
    </step>
    <step>
        <p><b>Filtro por Data:</b> permite filtrar por um intervalo de tempo específico. </p>
    </step>
    <step>
        <p><img type="inline" src="delete-combos.png" alt="Montagem" width="30" border-effect="rounded"/>: reseta as filtragens do report. </p>
    </step>
    <step>
        <p><img type="inline" src="enter.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para gerar o report com os filtros selecionados. </p>
    </step>
    <step>
        <p><img type="inline" src="help.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para exibir textos explicatorios. </p>
    </step>
</procedure>

## Report User

<img src="users2.png" alt="Montagem" width="750" border-effect="line" preview-src="users2.png"/>

<procedure id="users">
    <step>
        <p><b>Filtro por Teatro/Cinema:</b> permite filtrar por todos os teatros ou um teatro específico. </p>
    </step>
    <step>
        <p><b>Filtro por Role:</b> permite selecionar todos os roles ou roles específicos.</p>
    </step>
    <step>
        <p><img type="inline" src="delete-combos.png" alt="Montagem" width="30" border-effect="rounded"/>: reseta as filtragens do report. </p>
    </step>
    <step>
        <p><img type="inline" src="enter.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para gerar o report com os filtros selecionados. </p>
    </step>
    <step>
        <p><img type="inline" src="help.png" alt="Montagem" width="30" border-effect="rounded"/>: clique para exibir textos explicatorios. </p>
    </step>
</procedure>

