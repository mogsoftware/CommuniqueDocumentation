# Communique v5.0

## Players

Player é o nome dado a máquina que executa a aplicação client. <br />
Para que tudo funcione corretamente, primeiro é necessário cadastrar o player no Communique.

## Cadastro de Player

É possível acessar a tela de cadastro do player através do menu lateral, nas opções
<ui-path>Players | Todos os Players </ui-path>.

<video src="acesso-player.mp4" xmlns="" preview-src="acesso-player.png"/>

Nesta tela são listados todos os players cadastrados no sistema. Além de adicionar novos cadastros, nesta tela também é
possível editar, deletar e acessar a tela de configuração do player.

Para cadastrar um novo player, basta clicar em <img src="add.png" alt="Add icon" width="24" style="inline"/> no
cabeçalho da
tabela. <br />
Caso queira editar um cadastro já existente, clique no registro desejado.<br />
Em ambos os casos, a seguinte tela será exibida:

![Cadastro de Player](player-edit.png){ width="450" border-effect="line" preview-src="player-edit.png" }

Abaixo vamos entender cada um dos itens.

### Criação/Edição de cadastro de player

#### OFFLINE

<procedure id="offline-options">
    <step>
        <p><b>Offline:</b> Define o player como desconectado. <br></br>Esta opção impede que novas mídias sejam programadas nele.</p>
    </step>
    <step>
        <p><b>Reason:</b> Exibe uma lista de motivos pelo qual o player foi configurado como Offline.</p>
    </step>
</procedure>

#### INFORMATION

<procedure  id="information-options">
    <step>
        <p><b>Name:</b> Nome do player.</p>
    </step>
    <step>
        <p><b><tooltip term="HOSTNAME">Hostname:</tooltip></b> Identificação da máquina na rede. Deve ser preenchido com o host configurado no Windows.</p>
    </step>
    <step>
        <p><b>MacAddress:</b> Endereço de rede do Player. Deve ser preenchido com o MacAddress em uso pelo Windows.</p>
    </step>
    <step>
        <p><b>Theater:</b> Nome do Cinema no qual o player está localizado.</p>
    </step>
    <step>
        <p><b>Player Category:</b> Categoria do Player. Esta informação varia conforme o tipo de cinema e localização do player.</p>
    </step>
    <step>
        <p><b>Locate:</b> Localização do player no cinema.</p>
    </step>
        <note>
            Todos os campos dessa seção são obrigatórios.
        </note>
</procedure>

#### DISPLAY

<procedure  id="display-options">
    <step>
        <p><b>Monitor:</b> Modelo dos monitores.</p>
    </step>
    <step>
        <p><b>Inches:</b> Tamanho em polegada dos monitores.</p>
    </step>
    <step>
        <p><b>Amount:</b> Quantidade de monitores conectados ao player.</p>
    </step>
    <step>
        <p><b>Resolution:</b> Resolução em píxeis dos monitores.</p>
    </step>
    <step>
        <p><b>Format:</b> Formato de montagem das configurações do player.</p>
            <tip>
                Os formatos são diferentes formas para montar um player. <br></br>
                Eles variam de acordo com a quantidade de monitores e o conteúdo que será exibido nas telas. 
                Veremos algo mais aprofundado na configuração e montagem do player. 
            </tip>
    </step>
    <step>
        <p><b>VideoWall:</b> Disposição física dos monitores.</p>
        <tip>A disposição física do player varia conforme a estrutura local, bem como cabeamento e tipo de monitores.</tip>
    </step>
    <step>
        <p><b>Orientation:</b> Orientação dos monitores. (Horizontal e Vertical)</p>
    </step>
    <note>
        Todos os campos dessa seção são obrigatórios.
    </note>
</procedure>

#### MONTAGE

<procedure  id="montage-options">
        <tip>
            Para essa etapa é importante saber que por padrão uma saída de vídeo suporta até 4 monitores, de modo que 
            para atender mais telas, novas saídas de video devem ser utilizadas. O número de saídas de vídeo muda conforme o modelo
            da placa gráfica.<br></br>
            Esse padrão de configuração pode sofrer alterações devido a cabeamento, estrutura fisica e disposição dos monitores.
            Mas é de extrema importancia seguir o modelo 4 telas por saída.<br></br>
            Existem casos em que é necessário duas máquinas para atender a quantidade de monitores, geralmente em situações de Player
            com 16 ou mais telas.<br></br>
            As informações preenchidas aqui serão importantes para a montagem do diagrama do player.
        </tip>
    <img src="montage-player.png" alt="Montagem" width="450" preview-src="montage-player.png" border-effect="line"/>
    <step>
        <p>Reduz o número de máquinas </p>
    </step>
    <step>
        <p>Aumenta o número de máquinas </p>
    </step>
    <step>
        <p>Reduz o número de saídas de vídeo em uso</p>
    </step>
    <step>
        <p>Aumenta o número de saídas de vídeo em uso</p>
    </step>
        <note>
            Item obrigatório. É necessário ter no mínimo uma máquina e uma saída para que o diagrama funcione corretamente.
        </note>
</procedure>

#### OPTIONS

<procedure  id="opt-options">
    <tip>
                Um player devidamente configurado realizará sincronização de dados com o servidor periodicamente.<br></br>
                Para se ter maior controle sobre isso, é possível definir horários em que o servidor retornará dados e até mesmo bloquer o envio dedos para um player.<br></br>
                Importante: Os bloqueios funcionam de maneira isolada, então configurar o Prevent Config não irá impedir o player de sincronizar e atualizar as playlists.
            </tip>
    <control>Config Prevent | Playlist Prevent</control>
    <step>
        <p><b>Sync Hour:</b> Define os horários em que o servidor permitirá o envio de dados para o player. Deve ser preenchido com a hora ou horas desejadas. </p>
        <chapter title="Exemplos" id="some_chapter" collapsible="true">
            <p>1: Para o player sincronizar apenas 10h da manhã, basta inserir <code>10</code></p>
            <p>2: Para o player sincronizar apenas 10h e 12h, deve-se inserir os valores separados por virgulas: <code>10,12</code>.</p>
        </chapter>
    </step>
    <step>
        <p><b>Prevent Sync:</b> Bloqueia a sincronização de dados.</p>
    </step>
    <control>Advertising</control>
    <p>Sinaliza que o player pode receber conteúdos publicitários.</p>
    <note>
        Todos os campos dessa seção são opcionais.
    </note>
</procedure>

#### OBSERVATION

<procedure  id="observation-options">
    <step>
        <p>Campo opcional para descrever quaisquer outras obeservações sobre o player. <br></br>
        Um ótimo exemplo é escrever quando o player possui algum monitor quebrado.</p>
    </step>
</procedure>

#### IMAGE

<procedure  id="image-options">
    <img src="player-image.png" alt="Montagem" width="450" preview-src="player-image.png" border-effect="line"/>
    <step>
        <p>Upload de foto do player.</p>
    </step>
    <note>
        Para ter uma melhor visualização, a foto deve conter todas as telas do player e uma visão ampla do local onde o player está localizado.
    </note>
</procedure>

[//]: # ()

[//]: # (## Add interactive elements)

[//]: # ()

[//]: # (### Tabs)

[//]: # ()

[//]: # (To add switchable content, use tabs &#40;start typing `tabs` on a new line&#41;.)

[//]: # ()

[//]: # (<tabs>)

[//]: # (    <tab title="Markdown">)

[//]: # (        <code-block lang="plain text">![Alt Text]&#40;new_topic_options.png&#41;{ width=450 }</code-block>)

[//]: # (    </tab>)

[//]: # (    <tab title="Semantic markup">)

[//]: # (        <code-block lang="xml">)

[//]: # (            <![CDATA[<img src="new_topic_options.png" alt="Alt text" width="450px"/>]]></code-block>)

[//]: # (    </tab>)

[//]: # (</tabs>)

[//]: # ()

[//]: # (### Collapsible blocks)

[//]: # ()

[//]: # (Besides injecting entire XML elements, you can use attributes to configure the behavior of certain elements.)

[//]: # (For example, you can collapse a chapter that contains non-essential information like this:)

[//]: # ()

[//]: # (#### Supplementary info {collapsible="true"})

[//]: # ()

[//]: # (Content under such header will be collapsed by default, but you can modify the behavior by adding the following)

[//]: # (attribute:)

[//]: # (`default-state="expanded"`)

[//]: # ()

[//]: # (## Convert selection to XML)

[//]: # ()

[//]: # (If you need to extend an element with more functions, you can convert selected content from Markdown to semantic markup.)

[//]: # (For example, if you want to merge cells in a table, it's much easier to convert it to XML than do this in Markdown.)

[//]: # (Position the caret anywhere in the table and press <shortcut>Alt+Enter</shortcut>:)

[//]: # ()

[//]: # (<img src="convert_table_to_xml.png" alt="Convert table to XML" width="706" border-effect="line"/>)

[//]: # ()

[//]: # (## Feedback and support)

[//]: # ()

[//]: # (Please report any issues, usability improvements, or feature requests to our)

[//]: # (<a href="https://youtrack.jetbrains.com/newIssue?project=WRS">YouTrack project</a>)

[//]: # (&#40;you will need to register&#41;.)

[//]: # ()

[//]: # (You are welcome to join our)

[//]: # (<a href="https://jb.gg/WRS_Slack">public Slack workspace</a>.)

[//]: # (Before you do, please read our [Code of conduct]&#40;https://plugins.jetbrains.com/plugin/20158-writerside/docs/writerside-code-of-conduct.html&#41;.)

[//]: # (We assume that you’ve read and acknowledged it before joining.)

[//]: # ()

[//]: # (You can also always email us at [writerside@jetbrains.com]&#40;mailto:writerside@jetbrains.com&#41;.)

[//]: # ()

[//]: # (<seealso>)

[//]: # (    <category ref="wrs">)

[//]: # (        <a href="https://plugins.jetbrains.com/plugin/20158-writerside/docs/markup-reference.html">Markup reference</a>)

[//]: # (        <a href="https://plugins.jetbrains.com/plugin/20158-writerside/docs/manage-table-of-contents.html">Reorder topics in the TOC</a>)

[//]: # (        <a href="https://plugins.jetbrains.com/plugin/20158-writerside/docs/local-build.html">Build and publish</a>)

[//]: # (        <a href="https://plugins.jetbrains.com/plugin/20158-writerside/docs/configure-search.html">Configure Search</a>)

[//]: # (    </category>)

[//]: # (</seealso>)
