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