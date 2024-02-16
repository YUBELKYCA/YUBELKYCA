<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Biografía y Horario de Clases</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        
        .biografia {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        .biografia img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
        }
        
        .biografia p {
            text-align: justify;
            line-height: 1.5;
        }
        
        .horario {
            margin-top: 40px;
            border-collapse: collapse;
            width: 100%;
        }
        
        .horario th, .horario td {
            border: 1px solid #ddd;
            padding: 8px;
        }
        
        .horario th {
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="biografia">
        <img src="https://picsum.photos/id/1025/200/300" alt="Foto de perfil">
        <h2>[Tu nombre completo]</h2>
        <p>
            [Escribe una breve descripción de ti mismo, incluyendo tu formación, experiencia profesional y hobbies.]
        </p>
    </div>
    
    <h2 class="horario">Horario de Clases</h2>
    
    <table>
        <tr>
            <th>Día</th>
            <th>Hora</th>
            <th>Clase</th>
        </tr>
        <tr>
            <td>Lunes</td>
            <td>10:00 - 11:00</td>
            <td>Matemáticas</td>
        </tr>
        </tr>
    </table>
</body>
</html>
