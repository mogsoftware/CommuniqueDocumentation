# Playlist

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