# Media

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