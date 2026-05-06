<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Plan de Vida | Desarrollo Personal</title>

    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">

    <style>
        :root{
            --bg-color:#f8f9fa;
            --text-main:#212529;
            --accent:#007bff;
            --secondary:#6c757d;
            --white:#ffffff;
        }

        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
        }

        body{
            font-family:'Inter', sans-serif;
            background-color:var(--bg-color);
            color:var(--text-main);
            line-height:1.6;
        }

        header{
            height:100vh;
            display:flex;
            flex-direction:column;
            justify-content:center;
            align-items:center;
            text-align:center;
            background:linear-gradient(135deg,#1a1a1a 0%, #333 100%);
            color:var(--white);
            padding:20px;
        }

        h1{
            font-family:'Playfair Display', serif;
            font-size:3.5rem;
            margin-bottom:1rem;
        }

        .mision-tag{
            font-size:1.2rem;
            text-transform:uppercase;
            letter-spacing:3px;
            color:var(--accent);
            font-weight:700;
        }

        section{
            padding:80px 10%;
        }

        .grid{
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
            gap:30px;
            margin-top:40px;
        }

        .card{
            background:var(--white);
            padding:30px;
            border-radius:12px;
            box-shadow:0 10px 30px rgba(0,0,0,0.05);
            transition:transform 0.3s ease;
        }

        .card:hover{
            transform:translateY(-10px);
        }

        .card h3{
            color:var(--accent);
            margin-bottom:15px;
        }

        .progress-container{
            margin-top:20px;
        }

        .progress-bar{
            background:#eee;
            height:10px;
            border-radius:5px;
            margin-bottom:15px;
        }

        .progress-fill{
            background:var(--accent);
            height:100%;
            border-radius:5px;
        }

        footer{
            text-align:center;
            padding:40px;
            background:#1a1a1a;
            color:var(--secondary);
            font-size:0.9rem;
        }

        @media (max-width:768px){
            h1{
                font-size:2.5rem;
            }
        }
    </style>
</head>

<body>

<header>
    <p class="mision-tag">Mi Misión de Vida</p>

    <h1>Construyendo mi crecimiento personal y profesional.</h1>

    <p style="max-width:600px; opacity:0.8;">
        Mi objetivo es desarrollarme como una persona responsable,
        preparada y capaz de generar un impacto positivo en mi entorno.
    </p>
</header>

<section id="autoconocimiento">

    <h2 style="text-align:center; font-size:2.5rem;">Autoconocimiento</h2>

    <p style="text-align:center; color:var(--secondary);">
        Conocer mis fortalezas y áreas de mejora me ayuda a crecer constantemente.
    </p>

    <div class="grid">

        <div class="card">
            <h3>Fortalezas</h3>
            <ul>
                <li>Responsabilidad</li>
                <li>Disciplina</li>
                <li>Capacidad de adaptación</li>
                <li>Trabajo en equipo</li>
            </ul>
        </div>

        <div class="card">
            <h3>Valores</h3>
            <p><strong>Respeto:</strong> Tratar bien a las personas.</p>
            <p><strong>Compromiso:</strong> Cumplir mis metas.</p>
            <p><strong>Constancia:</strong> Mejorar cada día.</p>
        </div>

    </div>
</section>

<section id="foda" style="background-color:#fff;">

    <h2 style="text-align:center; font-size:2.5rem;">Análisis FODA Personal</h2>

    <div class="grid">

        <div class="card">
            <h3>Fortalezas</h3>
            <ul>
                <li>Aprendo rápido</li>
                <li>Buena comunicación</li>
                <li>Creatividad</li>
                <li>Responsabilidad</li>
            </ul>
        </div>

        <div class="card">
            <h3>Oportunidades</h3>
            <ul>
                <li>Crecimiento del marketing digital</li>
                <li>Acceso a cursos online</li>
                <li>Nuevas oportunidades laborales</li>
                <li>Desarrollo de contactos profesionales</li>
            </ul>
        </div>

        <div class="card">
            <h3>Debilidades</h3>
            <ul>
                <li>Perfeccionismo</li>
                <li>Estrés académico</li>
                <li>Dificultad para delegar</li>
            </ul>
        </div>

        <div class="card">
            <h3>Amenazas</h3>
            <ul>
                <li>Competencia laboral</li>
                <li>Cambios rápidos en tecnología</li>
                <li>Distracciones constantes</li>
            </ul>
        </div>

    </div>

    <p style="margin-top:40px; text-align:center;">
        Este análisis me ayuda a identificar qué aspectos debo fortalecer
        para cumplir mi misión de vida y alcanzar mis metas personales y profesionales.
    </p>

</section>

<section id="objetivos">

    <h2 style="text-align:center; font-size:2.5rem;">Objetivos SMART</h2>

    <div class="grid">

        <div class="card">
            <h3>1. Mejorar inglés</h3>
            <p>Completar un curso de inglés intermedio antes de terminar el año.</p>
        </div>

        <div class="card">
            <h3>2. Mejorar condición física</h3>
            <p>Bajar de 75 kg a 65 kg mediante ejercicio y alimentación saludable.</p>
        </div>

        <div class="card">
            <h3>3. Certificación digital</h3>
            <p>Obtener una certificación en marketing digital en 6 meses.</p>
        </div>

        <div class="card">
            <h3>4. Organización</h3>
            <p>Usar una agenda semanal para mejorar la administración de mi tiempo.</p>
        </div>

        <div class="card">
            <h3>5. Experiencia profesional</h3>
            <p>Participar en proyectos relacionados con mi carrera antes de graduarme.</p>
        </div>

        <div class="card">
            <h3>6. Marca personal</h3>
            <p>Publicar contenido profesional en redes sociales dos veces por semana.</p>
        </div>

        <div class="card">
            <h3>7. Ahorrar dinero</h3>
            <p>Ahorrar el 15% de mis ingresos mensuales durante un año.</p>
        </div>

        <div class="card">
            <h3>8. Fortalecer liderazgo</h3>
            <p>Participar en actividades académicas colaborativas durante este semestre.</p>
        </div>

    </div>

</section>

<section id="relaciones" style="background-color:#fff;">

    <h2 style="text-align:center; font-size:2.5rem;">
        Agenda de Relaciones Estratégicas
    </h2>

    <div class="grid">

        <div class="card">
            <h3>Familia</h3>
            <p>Me brindan apoyo emocional y motivación.</p>
            <p><strong>Acción:</strong> Mantener convivencia y comunicación constante.</p>
        </div>

        <div class="card">
            <h3>Profesores</h3>
            <p>Apoyo académico y orientación profesional.</p>
            <p><strong>Acción:</strong> Participar en clase y pedir retroalimentación.</p>
        </div>

        <div class="card">
            <h3>Compañeros</h3>
            <p>Trabajo en equipo y colaboración.</p>
            <p><strong>Acción:</strong> Participar en proyectos grupales.</p>
        </div>

        <div class="card">
            <h3>Contactos Profesionales</h3>
            <p>Oportunidades laborales y networking.</p>
            <p><strong>Acción:</strong> Mejorar mi perfil profesional y mantener contacto.</p>
        </div>

    </div>

</section>

<section id="crecimiento">

    <h2 style="text-align:center; font-size:2.5rem;">Plan de Crecimiento</h2>

    <div class="progress-container" style="max-width:700px; margin:40px auto;">

        <p>Marketing Digital</p>
        <div class="progress-bar">
            <div class="progress-fill" style="width:75%;"></div>
        </div>

        <p>Liderazgo</p>
        <div class="progress-bar">
            <div class="progress-fill" style="width:70%;"></div>
        </div>

        <p>Inteligencia Emocional</p>
        <div class="progress-bar">
            <div class="progress-fill" style="width:85%;"></div>
        </div>

    </div>

</section>

<section id="reflexion" style="background-color:#fff;">

    <h2 style="text-align:center; font-size:2.5rem;">Reflexión Final</h2>

    <div class="card" style="max-width:900px; margin:40px auto;">

        <p>
            Durante este curso comprendí la importancia de conocer mis fortalezas,
            debilidades y metas personales para poder construir un mejor futuro.
        </p>

        <br>

        <p>
            También aprendí que tener objetivos claros y relaciones positivas ayuda
            a mejorar tanto en lo personal como en lo profesional. Este proyecto me
            permitió reflexionar sobre quién soy actualmente y en quién quiero convertirme.
        </p>

    </div>

</section>

<footer>
    &copy; 2026 - Plan de Vida y Desarrollo Personal
</footer>

</body>
</html>