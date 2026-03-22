<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>108BD001</title>

<style>
body {
    margin:0;
    font-family: Arial;
    background:#0b0f1a;
    color:white;
    text-align:center;
}

/* QSL IMAGE */
.qsl-image {
    width:100%;
    max-height:500px;
    object-fit:contain;
    background:black;
}

/* CALLSIGN */
h1 {
    font-size:60px;
    margin-top:20px;
    color:#00c3ff;
    text-shadow:0 0 15px #00c3ff;
}

.subtitle {
    font-size:20px;
}

/* BUTTON */
.button {
    display:inline-block;
    margin-top:20px;
    padding:15px 35px;
    background:linear-gradient(45deg,#ff0000,#ff5e5e);
    color:white;
    text-decoration:none;
    font-weight:bold;
    border-radius:6px;
    box-shadow:0 0 15px red;
}

/* SECTION */
.section {
    margin-top:40px;
    padding:20px;
    border-top:1px solid #222;
}

h2 {
    color:#00c3ff;
}

/* TABLE */
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

<!-- QSL IMAGE -->
<img src="qsl.jpg" class="qsl-image">

<!-- TITLE -->
<h1>108BD001</h1>
<div class="subtitle">OP. Zibi | Scotland</div>

<!-- BUTTON -->
<a href="qsl.jpg" download class="button">
DOWNLOAD QSL CARD
</a>

<!-- ABOUT -->
<div class="section">
    <h2>About</h2>
    <p>CB Radio operator from Scotland. Active on 27.555 USB.</p>
</div>

<!-- QSO LOG -->
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
