<!DOCTYPE html>
<html 
<head>
<meta charset="UTF-8">
<title>108BD001</title>

<style>
body {
    margin:0;
    font-family: Arial;
    color:white;
    text-align:center;
    background:black;
}

/* FULL SCREEN BACKGROUND */
.header {
    position:relative;
    width:100%;
    height:100vh;
    background:url('qsl.jpg') center/contain no-repeat;
    background-color:black;
}

/* CIEMNE PRZYCIEMNIENIE */
.overlay {
    position:absolute;
    top:0;
    left:0;
    width:100%;
    height:100%;
    background:rgba(0,0,0,0.6);
}

/* TEKST NA ŚRODKU */
.content {
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
}

/* CALLSIGN */
h1 {
    font-size:70px;
    margin:0;
    color:#00c3ff;
    text-shadow:0 0 20px #00c3ff;
}

.subtitle {
    font-size:22px;
    margin-top:10px;
}

/* PRZYCISK */
.button {
    margin-top:30px;
    padding:18px 40px;
    background:linear-gradient(45deg,#ff0000,#ff5e5e);
    color:white;
    text-decoration:none;
    font-weight:bold;
    border-radius:6px;
    box-shadow:0 0 20px red;
    display:inline-block;
}

/* SEKCJE */
.section {
    padding:40px 20px;
    border-top:1px solid #222;
}

h2 {
    color:#00c3ff;
}

/* TABELA */
table {
    margin:auto;
    border-collapse:collapse;
    width:80%;
}

td, th {
    padding:12px;
    border-bottom:1px solid #333;
}

</style>
</head>

<body>

<!-- HEADER -->
<div class="header">

    <div class="overlay"></div>

    <div class="content">
        <h1>108BD001</h1>
        <div class="subtitle">OP. Zibi | Scotland</div>

        <a href="qsl.jpg" download class="button">
            DOWNLOAD QSL CARD
        </a>
    </div>

</div>

<!-- ABOUT -->
<div class="section">
    <h2>About</h2>
    <p>CB Radio operator from Scotland. Active on 27.555 USB.</p>
</div>

<!-- QSO -->
<div class="section">
    <h2>QSO Log</h2>
    <table>
        <tr>
            <th>Date</th>
            <th>Station</th>
            <th>Mode</th>
        </tr>
        <tr>
            <td>22/03/2026</td>
            <td>John UK</td>
            <td>USB</td>
        </tr>
    </table>
</div>

</body>
</html>
