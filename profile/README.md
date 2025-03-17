  <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0 auto;
            padding: 20px;
            background-color:rgb(255, 255, 255);
            transition: background-color 0.5s ease-in-out;
        }

        h1, h2, h3 {
            color: #333;
            text-align: center;
            margin-top: 0;
        }

        h1, h2, h3 {
            opacity: 0;
            animation: fadeIn .3s forwards;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        ul {
            list-style-type: none;
            padding-left: 0;
            display: flex;
            justify-content: center;
            gap: 7px;
        }

        li {
			display: flex;
			justify-content: center;
			align-items: center;
            width: 120px;
            height: 70px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        li:hover {
            transform: scale(1.1);

        }

        img {
            /* vertical-align: middle; */
            width: 180px;
            height: 60px;
        }

        /* Анимация кнопок социальных сетей */
        .social-buttons {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }

        .social-buttons a {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 150px;
            height: 40px;
            background-color: #3498db;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        .social-buttons a:hover {
            background-color: #2980b9;
        }

        .social-buttons a span {
            margin-left: 10px;
        }
        footer {
            text-align: center;
            margin-top: 50px;
        }

        /* Изменение цвета фона при наведении мыши на тело документа */
        body:hover {
            color:rgb(255, 255, 255);
						background-color: rgba(0, 0, 0, 0.32);
        }
				
</style>
<body>
    <h1>👋 Привет от AuzaTeam</h1>
    <h2>🎇 Специализируемся на frontend, backend и gamedev</h2>
    <p>
        Занимаемся разработкой веб-приложений, а также игр. В будущем надеемся сделать то, что поможет всем.. или хотя бы кому-то.
    </p>
    <h3>🛠 Наш стек технологий</h3>
    <ul class="core-tech">
        <li><a href="https://docs.microsoft.com/en-us/dotnet/csharp/" target="_blank"><img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white"></a></li>
        <li><a href="https://www.python.org/" target="_blank"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"></a></li>
    </ul>
    <!-- Frontend технологии -->
    <h3>Frontend</h3>
    <ul class="frontend-tech">
        <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank"><img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"></a></li>
        <li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank"><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"></a></li>
        <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white"></a></li>
    </ul>
    <!-- Backend технологии -->
    <h3>Backend</h3>
    <ul class="backend-tech">
        <li><a href="https://dotnet.microsoft.com/" target="_blank"><img src="https://img.shields.io/badge/.NET_Framework-512BD4?style=for-the-badge&logo=.net&logoColor=white"></a></li>
        <li><a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"></a></li>
    </ul>
    <!-- Database технология -->
    <h3>Database</h3>
    <ul class="database-tech">
        <li><a href="https://www.postgresql.org/" target="_blank"><img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"></a></li>
    </ul>
    <!-- Gamedev технологии -->
    <h3>Gamedev</h3>
    <ul class="gamedev-tech">
        <li><a href="https://unity.com/" target="_blank"><img src="https://img.shields.io/badge/Unity-FFFFFF?style=for-the-badge&logo=unity&logoColor=black"></a></li>
        <li><a href="https://docs.unity3d.com/Manual/SL-Reference.html" target="_blank"><img src="https://img.shields.io/badge/ShaderLab-000000?style=for-the-badge&logo=shaderlab&logoColor=white"></a></li>
        <li><a href="https://docs.microsoft.com/en-us/windows/win32/direct3dhlsl/dx-graphics-hlsl" target="_blank"><img src="https://img.shields.io/badge/HLSL-0078D7?style=for-the-badge&logo=hlgsl&logoColor=white"></a></li>
        <li><a href="https://www.khronos.org/opengl/wiki/Core_Language_(GLSL)" target="_blank"><img src="https://img.shields.io/badge/GLSL-964B00?style=for-the-badge&logo=glsl&logoColor=white"></a></li>
    </ul>
    <!-- Контактная информация -->
    <div class="contact-info">
        <h3>🌍 Социальные сети и контакты</h3>
        <p><strong>Email:</strong> auzateaminc@gmail.com</p>
        <p><strong>Telegram:</strong> @n1_3ro</p>
    </div>
    <!-- Команда -->
    <h3>🏆 Участники на начало 2025</h3>
    <div class="team-members">
        <div class="member">
            <h4>^W^</h4>
            <p>Основные навыки: Frontend: React, TypeScript, Backend: C#, .NETFramework, PostgreSQL</p>
            <div class="social-icons">
                <a href="https://github.com/n13ro" target="_blank">GitHub</a>
                <a href="https://t.me/n1_3ro" target="_blank">Telegram</a>
            </div>
        </div>
        <div class="member">
            <h4>Первый Front</h4>
            <p>Основные навыки: Frontend: Vue, JavaScript</p>
            <div class="social-icons">
                <a href="https://github.com/Ypags" target="_blank">GitHub</a>
                <a href="https://t.me/prostopotato" target="_blank">Telegram</a>
            </div>
        </div>
        <div class="member">
            <h4>Первый UnityDev</h4>
            <p>Основные навыки: Gamedev: C#, Unity, Shaderlab, HLSL, GLSL</p>
            <div class="social-icons">
                <a href="https://github.com/Zzerud" target="_blank">GitHub</a>
                <a href="https://t.me/zzerud" target="_blank">Telegram</a>
            </div>
        </div>
    </div>
    <!-- Footer -->
    <footer>
        © 2025 AuzaTeam Inc. Все права защищены.
    </footer>
