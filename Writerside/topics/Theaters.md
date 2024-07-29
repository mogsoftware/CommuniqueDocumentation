# Theaters
<show-structure depth="2"/>

***Aguardando a ultima versao para incluir imagem***

Criação dos cinemas que terão o Player Mog.

<img src="Cinemas_criacao.png"/>

<list type="decimal">
<li>Nome: Nome do cinema.</li>
<li>Code: Código do cinema. Esse código é fornecido pelo cliente.</li>
<li>State: Estado onde o cinema está localizado. Para criação de State, verificar <ui-path>Management | State</ui-path> <img src="Cinemas_state.png"/></li>
<li>Start Hours: Hora de abertura do cinema. Deve-se considerar o horário militar para preenchimento do campo.</li>
<li>End Hours: Hora de fechamento do cinema. Deve-se considerar o horário militar para preenchimento do campo.</li>
<li>Prevent Settings: Bloqueio de prevenção de sync. Esse bloqueio afeta todos os players do cinema.
    <list type="alpha-lower">
    <li>General: Bloqueio completo do cinema. Com este item ativado, os players do cinema não receberão nenhuma atualização.</li>
    <li>Config Sync: Bloqueio de config do cinema.</li>
    <li>Playlist Sync: Bloqueio de atualiação das playlists do cinema.</li>
</list></li>
</list>