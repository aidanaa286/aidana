<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Портфолио – Әбдірахман Айдана</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        body {
            background-color: #F5EFE6; 
            color: #3A3A3A; 
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 90%;
            max-width: 1000px;
            margin: auto;
            padding: 20px;
        }
        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 48px; 
            color: #2C2A28; 
            margin-bottom: 10px;
            text-align: center;
        }
        h2 {
            font-size: 22px;
            font-weight: 500;
            color: #5A5A5A;
            margin-bottom: 20px;
            text-align: center;
        }
        .profile {
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 30px;
            margin-bottom: 30px;
            flex-wrap: wrap;
        }
        .profile img {
            width: 350px;
            height: 350px;
            border-radius: 20px;
            border: 5px solid #8D7B68; /* Қою бежевый */
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            object-fit: cover;
        }
        .profile-text {
            max-width: 550px;
            font-size: 18px;
            line-height: 1.6;
        }
        .menu {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
            justify-content: center;
            margin-bottom: 20px;
        }
        .menu button {
            background-color: #8D7B68; 
            color: white;
            font-family: 'Poppins', sans-serif;
            border: none;
            padding: 15px 20px;
            cursor: pointer;
            border-radius: 30px;
            font-size: 18px;
            transition: 0.3s;
        }
        .menu button:hover {
            background-color: #6B5B4D;
            transform: scale(1.05);
        }
        .content {
            display: none;
            padding: 20px;
            border-radius: 10px;
            background-color: white;
            color: #333;
            font-size: 18px;
            max-width: 800px;
            margin: auto;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
            animation: fadeIn 0.5s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
    <script>
        function showContent(id) {
            var contents = document.querySelectorAll('.content');
            contents.forEach(content => content.style.display = 'none');
            document.getElementById(id).style.display = 'block';
        }
    </script>
</head>
<body>
    <div class="container">
        <h1>Портфолио</h1>
        <h2>Әбдірахман Айдана</h2>

        <div class="profile">
            <img src="https://i.postimg.cc/52X9sNsD/Whats-App-Image-2025-02-26-at-17-38-23-2.jpg">
            <div class="profile-text">
                <p>Менің атым - Әбдірахман Айдана. 2009 жылы Түркістан облысы, Шымкент қаласында дүниеге келдім.2015-2021 жыл аралығында Шымкент қаласындағы 65 мектеп-гимназияда оқыдым. Мен 2021 жылдан бастап Алматы қаласының “РФММ” мектебінде оқимын.Қазір 2025 жылы 10G сынып оқушысымын. Қазіргі толық жасым 15-те. Отбасымда 8 адамбыз: ата-анам,4 сіңілім, мен және інім.</p>
            </div>
        </div>

        <div class="menu">
            <button onclick="showContent('bio')">Автобиография</button>
            <button onclick="showContent('achievements')">Жетістіктер</button>
            <button onclick="showContent('future')">Болашақ мамандық</button>
            <button onclick="showContent('legacy')">Тарихта қандай із қалдырасың?</button>
        </div>

        <div id="bio" class="content">
            <h3>Автобиография</h3>
            <p>Менің атым - Әбдірахман Айдана. 2009 жылы Түркістан облысы, Шымкент қаласында дүниеге келдім.2015-2021 жыл аралығында Шымкент қаласындағы 65 мектеп-гимназияда оқыдым. Мен 2021 жылдан бастап Алматы қаласының “РФММ” мектебінде оқимын.Қазір 2025 жылы 10G сынып оқушысымын. Қазіргі толық жасым 15-те. Отбасымда 8 адамбыз: ата-анам,4 сіңілім, мен және інім.</p>
        </div>

        <div id="achievements" class="content">
            <h3>Жетістіктер</h3>
            <ul>
                <li>Internship at IDP Education, managing social media and events.</li>
                <li>Founded DIY Club, organized creative workshops.</li>
                <li>Social Media Manager (Summer), created content & engaged with followers.</li>
                <li>English tutor at Inclusive Academy.</li>
                <li>School Dance Team member, represented school at competitions.</li>
                <li>2nd place in contemporary dance (International Summer Dance Camp).</li>
                <li>3rd place at Dance Mania International Competition.</li>
                <li>Volunteer at RFMSH's 50th-anniversary celebration.</li>
            </ul>
        </div>

        <div id="future" class="content">
            <h3>Болашақ мамандық</h3>
            <p>Мен болашақта деректер талдаушысы (Data Analyst) болғым келеді. Бұл сала аналитикалық ойлау қабілетімді дамытып, үлкен ақпаратпен жұмыс істеуге мүмкіндік береді. Деректерді талдау арқылы трендтерді анықтап, стратегиялық шешімдер қабылдауға көмектесетін нәтижелерге қол жеткізу мені қызықтырады. Менің мақсатым – білім мен тәжірибем арқылы әлемді жақсырақ етуге үлес қосу

.</p>
        </div>

        <div id="legacy" class="content">
            <h3>Тарихта қандай із қалдырасың?</h3>
            <p>Тарихта мен табиғатты сақтаушы, экоактивист ретінде қалғым келеді. Табиғаттың әдемілігін сақтап, экологиялық мәселелерді шешуге үлесімді қосқым келеді. Менің ізім – бұл таза ауа, су және жерді сақтауға бағытталған ізгі істер. Өз елімнің табиғатын қорғау арқылы болашақ ұрпақтарға таза және дені сау әлем қалдыру – менің арманым.<p>


        </div>
