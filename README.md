<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<title>Registro Federal de Egreso</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
* { box-sizing: border-box; }

body {
    margin: 0;
    font-family: 'Inter', sans-serif;
    background: #ffffff;
    color: #2b2b2b;
}

.container {
    max-width: 1180px;
    margin: 0 auto;
    padding: 24px 32px;
}

/* HEADER */
.header-top,
.header-bottom {
    background: #37BBED;
}

.header-top { padding: 20px 0; }
.header-bottom { padding: 30px 0 24px; }

.title-refe {
    color: #fff;
    font-size: 26px;
    line-height: 1.35;
    margin: 0;
}

/* FORM */
form { margin-top: 40px; }

.input-group {
    display: flex;
    margin-bottom: 14px;
}

.input-label {
    width: 260px;
    background: #f4f4f4;
    border: 1px solid #d9d9d9;
    padding: 11px 14px;
    font-size: 14px;
    font-weight: 500;
}

input, select {
    flex: 1;
    padding: 11px 12px;
    font-size: 14px;
    border: 1px solid #cfcfcf;
}

/* BOTONES */
.actions {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 16px;
}

.btn {
    padding: 11px 18px;
    font-size: 14px;
    font-weight: 500;
    border-radius: 6px;
    border: none;
    cursor: pointer;
}

.btn-primary { background: #0d6efd; color: #fff; }
.btn-success { background: #88C517; color: #fff; }

/* NOMBRE */
.highlight {
    margin-top: 32px;
    background: #37BBED;
    padding: 14px 18px;
    border-radius: 8px;
}

.highlight h6 {
    color: #fff;
    margin: 0;
    font-size: 20px;
    font-weight: 600;
}

/* INFO */
.info {
    margin-top: 20px;
    font-size: 14.5px;
}

/* TABLA */
.table-responsive {
    margin-top: 14px;
    overflow-x: auto;
}

table {
    width: 100%;
    border-collapse: collapse;
    font-size: 13.5px;
}

thead td {
    background: #eaf7fd;
    border: 1px solid #cfe8f2;
    padding: 12px;
    font-weight: 600;
    color: #555;
}

tbody td {
    border: 1px solid #dcdcdc;
    padding: 10px 12px;
}

tbody tr:hover {
    background: #f7fcff;
}

/* FOOTER */
.footer {
    max-width: 1100px;
    margin: 80px auto 40px;
    padding: 0 32px;
    font-size: 14px;
    color: #555;
    line-height: 1.65;
}

/* MOBILE – sin romper colores */
@media (max-width: 768px) {
    .container { padding: 20px; }

    .input-group {
        flex-direction: column;
    }

    .input-label {
        width: 100%;
        margin-bottom: 6px;
    }

    table, thead, tbody, tr, td {
        display: block;
        width: 100%;
    }

    thead {
        display: none;
    }

    tbody tr {
        background: #f7fcff;
        border: 1px solid #cfe8f2;
        border-radius: 8px;
        margin-bottom: 16px;
        padding: 8px 0;
    }

    tbody td {
        border: none;
        padding: 6px 12px;
    }
}
</style>
</head>

<body>

<div class="header-top">
    <div class="container">
        <img src="https://refe.educacion.gob.ar/img/ReFE/Banner/ReFE-Banner.svg" style="max-width:330px;">
    </div>
</div>

<div class="header-bottom">
    <div class="container">
        <h1 class="title-refe">
            <strong>Dirección de Validez Nacional de Títulos y Estudios</strong><br>
            Registro Federal de Egreso
        </h1>
    </div>
</div>

<main>
<div class="container">

<form>
    <div class="input-group">
        <div class="input-label">Tipo de Documento</div>
        <select><option>DNI</option></select>
    </div>

    <div class="input-group">
        <div class="input-label">Número de Documento</div>
        <input value="43742170">
    </div>

    <div class="input-group">
        <div class="input-label">Apellido</div>
        <input value="GUERRERO BERON">
    </div>

    <div class="input-group">
        <div class="input-label">Nombre</div>
        <input value="EZEQUIEL OMAR">
    </div>

    <div class="actions">
        <div>
            Si deseas ver tu título en la Blockchain Federal Argentina,
            <a href="#">click aquí</a>
        </div>
        <div>
            <button class="btn btn-primary">Nueva búsqueda</button>
            <button class="btn btn-success">Buscar</button>
        </div>
    </div>
</form>

<div class="highlight">
    <h6>Nombre y Apellido: EZEQUIEL OMAR GUERRERO BERON</h6>
</div>

<div class="info">
    <strong style="color:#37BBED;">Nivel Educativo:</strong>
    Educación secundaria completa
</div>

<div class="table-responsive">
<table>
<thead>
<tr>
    <td>Tipo Doc.</td>
    <td>N° Documento</td>
    <td>Título</td>
    <td>Jurisdicción</td>
    <td>Institución</td>
    <td>CUE</td>
    <td>Fecha de Egreso</td>
</tr>
</thead>
<tbody>
<tr>
    <td>DNI</td>
    <td>43.742.170</td>
    <td>Bachiller en Ciencias Naturales</td>
    <td>Buenos Aires</td>
    <td>Instituto Nuestra Señora Del Camino</td>
    <td>0619379</td>
    <td>26/12/2018</td>
</tr>
</tbody>
</table>
</div>

</div>
</main>

<div class="footer">
A partir del 1 de noviembre de 2023, por Resolución CFE N° 440/23, los títulos son emitidos en formato digital.
</div>

</body>
</html>
