# Communique v5.0

## Versão

1.0 Eduardo Joo 12/06/2024 Compress

## Media

O Communique permite o upload e gerenciamento de diversos tipos de mídia, essenciais para a exibição de conteúdo nas telas dos cinemas.

## Lista de Mídias

Tela de cadastro de mídia, utilize o menu lateral e navegue até <ui-path>Media</ui-path>.

![Lista de Medias](media.png){ width="450" border-effect="line" preview-src="media.png" }

Interface para cadastrar mídias  no sistema, é possível editar, deletar e visualizar os detalhes de cada mídia.

Filtro para buscar uma mídia específica por nome, tipo de mídia e cliente.

## Cadastro de Mídia

#### Informação da Mídia

<procedure  id="information-options">
    <step>
        <p><b>Tipo de Mídia:</b> Tipo do arquivo de mídia (por exemplo, MP4, JPG).</p>
    </step>
    <step>
        <p><b>Formato:</b> Formato da mídia (por exemplo, 1x1).</p>
    </step>
    <step>
        <p><b>Resolução:</b> Resolução do arquivo (por exemplo, 1920x1080).</p>
    </step>
    <step>
        <p><b>Duração:</b> Duração do vídeo (por exemplo, 11 segundos).</p>
    </step>
    <step>
        <p><b>Cliente:</b> Nome do cliente associado à mídia. (Cinemark, Flix Media, Flix Lab) </p>
    </step>
    <step>
        <p><b>Código:</b> Código de identificação da mídia. </p>
    </step>
    <step>
        <p><b>Nome do Arquivo:</b> Nome completo do arquivo de mídia. </p>
    </step>
    <step>
        <p><b>Tamanho:</b> Tamanho do arquivo em MB ou KB.</p>
    </step>
    <step>
        <p><b>Data de Aprovação:</b> Data e hora em que a mídia foi aprovada, incluindo o nome do responsável pela aprovação.</p>
    </step>
    <step>
        <p><b>Data de Upload:</b> Data e hora em que a mídia foi enviada ao sistema, incluindo o nome do responsável pelo upload. </p>
    </step>
    <step>
        <p><b>Media Type:</b> Categoria da mídia (Institucional, Evento, Combos Promocionais, Poster, Campaign, Still, Combo Video, Prices, Trailer, Inovaçoes, Showtimes, Layer, Prime, Bistro, Informative).</p>
    </step>
</procedure>

Selecione uma mídia para ver detalhes mais completos ou deletar clicando no ícone de lixeira.

![Detalhes](media-detalhes.png){ width="450" border-effect="line" preview-src="media-detalhes.png" }

## Limitadores de Mídia

![Detalhes](limitador.png){ width="250" border-effect="line" preview-src="limitador.png" }

O Communique possui diversas funcionalidades para limitar o upload de certos tipos de arquivos, garantindo que apenas mídias que atendam aos critérios específicos sejam aceitas no sistema.

<procedure  id="limitation-options">
    <step>
        <p><b>Tamanho Máximo de Mídia:</b> Arquivos de mídia não podem exceder 40MB.</p>
    </step>
    <step>
        <p><b>Tamanho Máximo de Poster:</b> Arquivos de poster não podem exceder 300KB.</p>
    </step>
    <step>
        <p><b>Resolução Máxima de Poster:</b> Posteres devem ter no máximo 1280x870 pixels.</p>
    </step>
    <step>
        <p><b>Tamanho Máximo de Trailer:</b> Arquivos de trailer não podem exceder 20MB.</p>
    </step>
    <step>
        <p><b>Resolução Permitida para Trailer:</b> Trailers devem ser HD (1280x720) ou FULL HD (1920x1080). </p>
    </step>
    <step>
        <p><b>Arquivos com Áudio:</b> Todos os arquivos de mídia <ui-path>não</ui-path> devem conter áudio. </p>
    </step>
</procedure>

## Limbo

O Limbo armazena todas as mídias que foram deletadas do sistema, permitindo a restauração dessas mídias quando necessário.

![Detalhes](limbo.png){ width="450" border-effect="line" preview-src="limbo.png" }

#### Funcionalidades do Limbo

<procedure  id="limbo-options">
    <step>
        <p>Exibe todas as mídias que foram removidas do sistema.</p>
    </step>
    <step>
        <p>Detalhes exibidos: tipo de mídia, cliente, formato, data de aprovação, data de upload e categoria.</p>
    </step>
    <step>
        <p>Permite restaurar mídias deletadas de volta ao sistema ao clicar em restore.</p>
        <img src="restore.png" alt="Montagem" width="100" preview-src="restore.png" border-effect="line"/>
    </step>
</procedure>

## Upload de Mídia

O Communique permite o upload de diversos tipos de mídias essenciais para a exibição de conteúdo nas telas dos cinemas.

![Detalhes](upload.png){ width="450" border-effect="line" preview-src="upload.png" }

A interface de upload é dividida em várias seções, cada uma correspondente a um tipo específico de mídia:

#### Upload de Poster

Para fazer upload de um poster, clique em "poster", selecione o poster a ser enviado e clique na seta para baixo.

![Detalhes](detalhes_poster.png){ width="300" border-effect="line" preview-src="detalhes_poster.png" }

<procedure  id="upload-poster-options">
    <step>
        <p><b>FILE NAME:</b> Nome do arquivo de poster selecionado para upload. E2400066500000.jpg </p>
    </step>
    <step>
        <p><b>Resolução:</b> Resolução do arquivo de poster em pixels. Limite: 1280X870px </p>
    </step>
    <step>
        <p><b>Tamanho:</b> Tamanho do arquivo em KB. Limite: 300KB </p>
    </step>
    <step>
        <p><b>Formato:</b> Formato da mídia. Selecione para escolher outros formatos. (1x1, 2x1, 3x1, 4x1, ..) </p>
    </step>
    <step>
        <p><b>Duração:</b> Duração do vídeo (se aplicável). </p>
    </step>
    <step>
        <p><b>FINAL NAME:</b> Nome final a ser dado ao arquivo de mídia, exibido na lista de mídias. Remova a extensão do arquivo. </p>
    </step>
    <step>
        <p><b>ORIENTATION:</b> Orientação do poster. H (Horizontal) / V (Vertical) </p>
    </step>
    <step>
        <p><b>CATEGORY:</b> Categoria da mídia. </p>
    </step>
    <step>
        <p><b>CLIENT:</b> Nome do cliente associado à mídia.. </p>
    </step> 
    <step>
        <p><b>Code:</b> Código de identificação da mídia, com prefixo "p". PE2400066500000.jpg </p>
    </step> 
    <step>
        <p><b>SEND:</b> Botão para enviar o poster após preencher todas as informações necessárias. </p>
    </step> 
    <step>
        <p><b>CROP:</b> Opção para recortar a imagem, se necessário.</p>
    </step> 
</procedure>

#### Código de Poster

#### Upload de Trailer

Para fazer upload de um trailer, clique em "trailer", selecione o trailer a ser enviado e
clique na seta para baixo.

<procedure id="upload-trailer-options">
    <step>
        <p><b>FILE NAME:</b> Nome do arquivo de trailer selecionado para upload. Ex: Garfield.mp4 </p>
    </step>
    <step>
        <p><b>Resolução:</b> Resolução do arquivo de trailer em pixels. Limite: HD ou FULL HD </p>
    </step>
    <step>
        <p><b>Tamanho:</b> Tamanho do arquivo em MB. Limite: 20MB </p>
    </step>
    <step>
        <p><b>Formato:</b> Formato da mídia. Selecione para escolher outros formatos. (1x1, 2x1, 3x1, 4x1, ..) </p>
    </step>
    <step>
        <p><b>Duração:</b> Duração do vídeo. </p>
    </step>
    <step>
        <p><b>FINAL NAME:</b> Nome final a ser dado ao arquivo de mídia, exibido na lista de mídias. Remova a extensão do arquivo. </p>
    </step>
    <step>
        <p><b>ORIENTATION:</b> Orientação do trailer. H (Horizontal) / V (Vertical) </p>
    </step>
    <step>
        <p><b>CATEGORY:</b> Categoria da mídia. </p>
    </step>
    <step>
        <p><b>CLIENT:</b> Nome do cliente associado à mídia. </p>
    </step> 
    <step>
        <p><b>Code:</b> Código de identificação da mídia. </p>
    </step> 
    <step>
        <p><b>Ícone de Câmera:</b> Permite visualizar uma prévia do trailer. </p>
    </step>
    <step>
        <p><b>Ícone de Lixeira:</b> Permite deletar a mídia. </p>
    </step>
</procedure>

#### Upload de Layer

Para fazer upload de um layer, clique em "layer", selecione o layer a ser enviado e
clique na seta para baixo.

<procedure id="upload-layer-options">
    <step>
        <p><b>FILE NAME:</b> Nome do arquivo de layer selecionado para upload. Ex: AI HOJE 1x1 (2x1) 1920x540.mp4 </p>
    </step>
    <step>
        <p><b>Resolução:</b> Resolução do arquivo de layer em pixels. Limite: HD ou FULL HD </p>
    </step>
    <step>
        <p><b>Tamanho:</b> Tamanho do arquivo em MB. Limite: 20MB </p>
    </step>
    <step>
        <p><b>Formato:</b> Formato da mídia. Selecione para escolher outros formatos. (1x1, 2x1, 3x1, 4x1, ..) </p>
    </step>
    <step>
        <p><b>Duração:</b> Duração do layer. </p>
    </step>
    <step>
        <p><b>FINAL NAME:</b> Nome final a ser dado ao arquivo de mídia, exibido na lista de mídias. Remova a extensão do arquivo. </p>
    </step>
    <step>
        <p><b>ORIENTATION:</b> Orientação do layer. H (Horizontal) / V (Vertical) </p>
    </step>
    <step>
        <p><b>CATEGORY:</b> Categoria da mídia. </p>
    </step>
    <step>
        <p><b>CLIENT:</b> Nome do cliente associado à mídia. </p>
    </step> 
    <step>
        <p><b>Code:</b> Código de identificação da mídia. </p>
    </step> 
    <step>
        <p><b>Ícone de Câmera:</b> Permite visualizar uma prévia do layer. </p>
    </step>
    <step>
        <p><b>Ícone de Lixeira:</b> Permite deletar a mídia. </p>
    </step>
</procedure>

#### Upload de Videos

Para fazer upload de um layer, clique em "layer", selecione o layer a ser enviado e
clique na seta para baixo.

<procedure id="upload-video-options">
    <step>
        <p><b>FILE NAME:</b> Nome do arquivo de video selecionado para upload. Ex: BR Prime 3x1 Cafe 230906 </p>
    </step>
    <step>
        <p><b>Resolução:</b> Resolução do arquivo do video em pixels. Limite: HD ou FULL HD </p>
    </step>
    <step>
        <p><b>Tamanho:</b> Tamanho do arquivo em MB. Limite: 20MB </p>
    </step>
    <step>
        <p><b>Formato:</b> Formato da mídia. Selecione para escolher outros formatos. (1x1, 2x1, 3x1, 4x1, ..) </p>
    </step>
    <step>
        <p><b>Duração:</b> Duração do video. </p>
    </step>
    <step>
        <p><b>FINAL NAME:</b> Nome final a ser dado ao arquivo de mídia, exibido na lista de mídias. Remova a extensão do arquivo. </p>
    </step>
    <step>
        <p><b>ORIENTATION:</b> Orientação do video. H (Horizontal) / V (Vertical) </p>
    </step>
    <step>
        <p><b>CATEGORY:</b> Categoria da mídia. </p>
    </step>
    <step>
        <p><b>CLIENT:</b> Nome do cliente associado à mídia. </p>
    </step> 
    <step>
        <p><b>Code:</b> Código de identificação da mídia. </p>
    </step> 
    <step>
        <p><b>Ícone de Câmera:</b> Permite visualizar uma prévia do video. </p>
    </step>
    <step>
        <p><b>Ícone de Lixeira:</b> Permite deletar a mídia. </p>
    </step>
</procedure>

#### Compress

O botão "Compress" é utilizado para reduzir o tamanho dos arquivos de mídia antes do upload.

![Detalhes](compress.png){ width="300" border-effect="line" preview-src="compress.png" }

## Playlist

A funcionalidade de Playlists no Communique permite a organização e gerenciamento de diferentes playlists de cada cinema.

![Detalhes](playlist.png){ width="450" border-effect="line" preview-src="playlist.png" }

Dois filtros estão disponíveis para facilitar a seleção de playlists específicas:

![Detalhes](filtroplaylist.png){ width="450" border-effect="line" preview-src="filtroplaylist.png" }

<procedure id="filter">
    <step>
        <p><b>Filtro por Teatro:</b> Permite selecionar um teatro específico e exibir suas playlists associadas. </p>
    </step>
    <step>
        <p><b>Filtro por Player:</b> Permite selecionar um player específico e exibir a playlist atribuída a ele. </p>
    </step>
</procedure>

<procedure id="playlist-front">
    <step>
        <p><b>Theater:</b> Nome do cinema onde a playlist está sendo exibida.</p>
    </step>
    <step>
        <p><b>Player:</b> Nome do player responsável pela reprodução da playlist.</p>
    </step>
    <step>
        <p><b>Playlist:</b> Nome específico da playlist que está sendo exibida no teatro e player selecionados.</p>
    </step>
    <step>
        <p><b>Status:</b> Estado atual da playlist.</p>
    </step>
    <step>
        <p><b>Format:</b> Formato da playlist (por exemplo, 1x1, 2x1)</p>
    </step>
</procedure>

É possível acessar playlists específicas para visualizar as mídias atualmente programadas, além de adicionar novas mídias e remover as existentes conforme necessário.

![Detalhes](playlists.png){ width="450" border-effect="line" preview-src="playlists.png" }

#### Detalhes da Playlist

<procedure id="playlist-details">
    <step>
        <p><b>Cabecalho da Playlist:</b></p>
        <ul>
            <li><b>Codigo:</b> Ex: 0705</li>
            <li><b>Nome do Cinema:</b> Ex:  CENTRAL PLAZA</li>
            <li><b>Nome do Player:</b> Ex: ATM</li>
            <li><b>Nome da Playlist e seu formato:</b> Ex: VINHETAS (1x1)</li>
            <li><b>Orientação do video:</b> H (Horizontal) / V (Vertical)</li>
            <li><b>Hostname:</b> Ex: BR0705ROD03</li>
            <li><b>Localização:</b> Ex:  CENTRAL PLAZA (ATM)</li>
            <li><b>Orientação do video:</b> H (Horizontal) / V (Vertical)</li>
        </ul>
    </step>
    <step>
        <p><b>Última Modificação:</b></p>
        <ul>
            <li><b>Responsável:</b> Ex: Felipe Silva</li>
            <li><b>Data e Hora:</b> Ex: 28/06/2024, 11:48 am</li>
        </ul>
    </step>
</procedure>

#### Carrossel

<procedure id="media-management">
    <step>
        <p><b>Expandir Mídias:</b></p>
        <ul>
            <li>Clique para expandir e visualizar todas as mídias disponíveis em um carrossel.</li>
            <li>Duplo clique para inserir ela na playlist.</li>
        </ul>
    </step>
    <step>
        <p><b>Filtro de Busca:</b></p>
        <ul>
            <li>Busque mídias específicas por nome.</li>
        </ul>
    </step>
    <step>
        <p><b>Tipos de Mídias Permitidos na Playlist:</b></p>
        <ul>
            <li> Ex: Institucional, Evento, Combos Promocionais, Poster, Campaign, Still, Combo Video, Prices, Trailer, Inovaçoes, Showtimes, Layer, Prime, Bistro, Informative. Somente as mídias com esses tipos podem ser exibidas.</li>
        </ul>
    </step>
    <step>
        <p><b>Ordenação:</b></p> 
        <ul>
            <li>Ordenar as medias por ordem alfabética, por data de upload.</li>
        </ul>
    </step>
</procedure>

## Programação de Mídia

Para programar uma mídia na playlist, siga os passos abaixo:

<procedure id="playlist-options">
    <step>
        <p>Clique duas vezes na mídia desejada no carrossel para selecioná-la e inseri-la na playlist. Por exemplo: Amigos Imaginários</p>
        <img src="media-programacao.png" alt="Montagem" width="300" preview-src="media-programacao.png" border-effect="line"/>
        <img src="playlist-media.png" alt="Montagem" width="500" preview-src="playlist-media.png" border-effect="line"/>
    </step>
    <step>
        <p>Passe o mouse sobre o ícone ao lado da mídia selecionada para exibir as opções de programação.</p>
        <p><b>Single Media:</b> Programar a mídia para ser exibida em datas personalizadas.</p>
        <img src="single-media.png" alt="Montagem" width="500" preview-src="single-media.png" border-effect="line"/>
        <ul>
            <li>Clique no ícone de calendário no canto superior esquerdo e selecione o intervalo de datas para a mídia ser exibida.
                <img src="calendar.png" alt="Montagem" width="300" preview-src="calendar.png" border-effect="line"/>
            </li>
        </ul>
        <p><b>Repeatable:</b> Programar a mídia para ser exibida todos os dias.</p>
        <img src="repeatable.png" alt="Montagem" width="500" preview-src="repeatable.png" border-effect="line"/>
        <p><b>Subplaylist:</b> Permite a criação e o gerenciamento de subplaylists dentro de playlists.</p>
        <img src="subplaylists.png" alt="Montagem" width="500" preview-src="subplaylists.png" border-effect="line"/>
        <p><b>Appointment:</b> Permite selecionar os dias da semana em que a mídia será exibida (domingo a sábado) e os períodos de exibição da mídia. (08:00 a 12:00, 09:00 a 13:59, 14:00 a 17:29, 17:30 a 23:00)</p>
        <img src="appointment.png" alt="Montagem" width="500" preview-src="appointment.png" border-effect="line"/>
        <p><b>Delete:</b> Opção para deletar a mídia da playlist</p>
        <img src="delete.png" alt="Montagem" width="500" preview-src="delete.png" border-effect="line"/>
    </step>
    <step>
        <p>Clique no botão de save para finalizar e salvar a programação.</p>
        <img src="saving.png" alt="Montagem" width="600" preview-src="saving.png" border-effect="line"/>
        <p><b>Ícone de pincel:</b> Deleta todas as mídias da playlist.</p>
        <p><b>Ícone de lente:</b> Visualiza um preview da mídia.</p>
        <p><b>Tempo total da programação:</b> Exibe em segundos o tempo total de todas as mídias na playlist.</p>
        <p><b>Data:</b> Permite visualizar a programação específica de um dia.</p>
    </step>
</procedure>

## Formatos de Midia

<procedure id="format">
    <step>
        <p><b>Formato 1x1:</b></p>
        <ul>
            <li>Uma mídia exibida em um bloco de proporção 1x1.</li>
        </ul>
        <ul>
            <li>Resolução: 1360x768 ou 1920x1080</li>
        </ul>
        <img src="1x1.png" alt="Montagem" width="300" preview-src="1x1.png" border-effect="line"/>
    </step>
    <step>
        <p><b>Formato 2x1:</b></p>
        <ul>
            <li>Uma mídia estendida horizontalmente em um bloco de proporção 2x1.</li>
        </ul>
        <ul>
            <li>Resolução: 1920x540</li>
        </ul>
        <img src="2x1.png" alt="Montagem" width="300" preview-src="2x1.png" border-effect="line"/>
    </step>
    <step>
        <p><b>Formato 3x1:</b></p>
        <ul>
            <li>Uma mídia estendida horizontalmente em um bloco de proporção 3x1.</li>
        </ul>
        <ul>
            <li>Resolução: 2880x540</li>
        </ul>
        <img src="3x1.png" alt="Montagem" width="300" preview-src="3x1.png" border-effect="line"/>
    </step>
    <step>
        <p><b>Formato 4x1:</b></p> 
        <ul>
            <li>Uma mídia estendida horizontalmente em um bloco de proporção 4x1.</li>
        </ul>
        <ul>
            <li>Resolução: 3840x540</li>
        </ul>
        <img src="4x1.png" alt="Montagem" width="300" preview-src="4x1.png" border-effect="line"/>
    </step>
</procedure>

## Formatos de Player

Os formatos de player/layout variam para atender a diversas necessidades de exibição, incluindo configurações horizontais que vão de 1x1, 2x1, 3x1, 4x1, 5x1, 6x1, 7x1, 8x1, 9x1, 10x1, 11x1, 12x1, 13x1, 14x1, 15x1, até 16x1, assim como formatos de grade que vão de 2x2, 3x2, 4x2, 5x2, 6x2, 7x2, 8x2, 9x2, até 10x2 e
por fim o formato vertical 1x1, 2x1, 3x1.

Alguns exemplos de formatos horizontais:

<procedure id="player-format">
    <step>
        <p><b>Formato 1x1:</b></p>
        <img src="player1x1.png" alt="Montagem" width="500" preview-src="player1x1.png" border-effect="line"/>
    </step>
    <step>
        <p><b>Formato 2x1:</b></p>
        <img src="player2x1.png" alt="Montagem" width="500" preview-src="player2x1.png" border-effect="line"/>
    </step>
    <step>
        <p><b>Formato 8x1:</b></p>
        <img src="player8x1.png" alt="Montagem" width="500" preview-src="player8x1.png" border-effect="line"/>
    </step>
</procedure>

Alguns exemplos de formatos de grade:

<procedure id="player-format-grade">
    <step>
        <p><b>Formato 2x2:</b></p>
        <img src="grade2x2.png" alt="Montagem" width="500" preview-src="grade2x2.png" border-effect="line"/>
    </step>
    <step>
        <p><b>Formato 4x2:</b></p>
        <img src="grade4x2.png" alt="Montagem" width="500" preview-src="grade4x2.png" border-effect="line"/>
    </step>
    <step>
        <p><b>Formato 6x2:</b></p>
        <img src="grade6x2.png" alt="Montagem" width="500" preview-src="grade6x2.png" border-effect="line"/>
    </step>
</procedure>

Alguns exemplos de formatos verticais:

<procedure id="player-format-vertical">
    <step>
        <p><b>Formato 1x1:</b></p>
        <img src="vertical1x1.png" alt="Montagem" width="500" preview-src="vertical1x1.png" border-effect="line"/>
        <img src="vertical1x1p.png" alt="Montagem" width="500" preview-src="vertical1x1p.png" border-effect="line"/>
    </step>
    <step>
        <p><b>Formato 3x1:</b></p>
        <img src="vertical3x1p.png" alt="Montagem" width="500" preview-src="vertical3x1p.png" border-effect="line"/>
        <img src="vertical3x1.png" alt="Montagem" width="500" preview-src="vertical3x1.png" border-effect="line"/>
        A distorcao do conteudo e causada pelo acesso remoto do player.
    </step>
</procedure>

## Reports

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