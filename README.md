<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>מערכת המידע - הבורגר של גרי</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            direction: rtl;
            text-align: right;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            background-color: #333;
            padding: 1em;
        }
        nav a {
            color: white;
            margin: 0 1em;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1000px;
            margin: 2em auto;
            padding: 0 1em;
        }
        h2 {
            color: #4CAF50;
        }
        .section {
            background: white;
            padding: 1.5em;
            margin-bottom: 1em;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            padding: 1em;
            background-color: #333;
            color: white;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>מערכת המידע של "הבורגר של גרי"</h1>
    </header>
    <nav>
        <a href="#system">תיאור המערכת</a>
        <a href="#dashboards">דשבורדים</a>
        <a href="#contact">צור קשר</a>
    </nav>
    <div class="container">
        <div class="section" id="system">
            <h2>תיאור המערכת</h2>
            <p>מערכת המידע של "הבורגר של גרי" היא מערכת לניהול הזמנות במסעדה משפחתית קטנה באור יהודה. המערכת תוכננה לעקוב אחר הזמנות, לנתח נתונים ולשפר את השירות והרווחיות. היא מאפשרת הזמנות פיזיות ודיגיטליות דרך טלפון, אתר ואפליקציה, ומספקת תובנות על:</p>
            <ul>
                <li>מנות פופולריות</li>
                <li>שעות עומס</li>
                <li>ערוצי הזמנה (משלוח/איסוף)</li>
                <li>מצב מלאי</li>
                <li>סכום קנייה ממוצע</li>
            </ul>
            <p>המערכת מאפשרת לגרי, מנהל המסעדה, לקבל החלטות אסטרטגיות מבוססות נתונים, כגון תגבור עובדים, ניהול מלאי, ויצירת מבצעים.</p>
            <img src="images/burger-image.jpg" alt="המבורגר של גרי" style="max-width: 100%; height: auto;">
        </div>
        <div class="section" id="dashboards">
            <h2>דשבורדים</h2>
            <h3>דשבורד 1: למנהל (גרי) - תצוגה אסטרטגית</h3>
            <p>דשבורד זה מציג תמונת מצב חודשית של ביצועי העסק, כולל:</p>
            <ul>
                <li>סך הכנסות יומי</li>
                <li>מכירות לפי קטגוריה (המבורגר, צמחוני, שתייה וכו')</li>
                <li>פילוח לפי ערוץ הזמנה (טלפון, אתר, אפליקציה)</li>
                <li>פילוח לפי סוג תשלום (מזומן, אשראי, PayBox)</li>
            </ul>
            <div class='tableauPlaceholder' id='viz1753033576020' style='position: relative'><noscript><a href='#'><img alt='1.ביצועי העסק - מנהל ' src='https://public.tableau.com/static/images/1_/1_-_17530322332890/1_-/1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='1_-_17530322332890/1_-' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https://public.tableau.com/static/images/1_/1_-_17530322332890/1_-/1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1753033576020');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='1277px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

            <h3>דשבורד 2: למנהל התפעול - תצוגה תפעולית</h3>
            <p>דשבורד זה מתמקד בפעילות יומית ושבועית, כולל:</p>
            <ul>
                <li>כמות הזמנות לפי שעות</li>
                <li>ניתוח מספר מנות לפי שם מנה</li>
                <li>מכירות לפי ימי השבוע</li>
                <li>פילוח הזמנות (משלוח/איסוף)</li>
            </ul>
            <div class='tableauPlaceholder' id='viz1753033834436' style='position: relative'><noscript><a href='#'><img alt='2. מנהל תפעול ' src='https://public.tableau.com/static/images/2_/2__17530322099330/2_/1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='2__17530322099330/2_' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https://public.tableau.com/static/images/2_/2__17530322099330/2_/1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1753033834436');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='1277px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

            <h3>דשבורד 3: לשירות לקוחות ושיווק</h3>
            <p>דשבורד זה מיועד לשיפור חווית הלקוח והשיווק, כולל:</p>
            <ul>
                <li>ממוצע דירוג לקוחות (1–5)</li>
                <li>זיהוי לקוחות חוזרים</li>
                <li>ניתוח סכום הזמנה לפי ערוץ</li>
            </ul>
            <div class='tableauPlaceholder' id='viz1753033849009' style='position: relative'><noscript><a href='#'><img alt='3. פרסום ושירות לקוחות ' src='https://public.tableau.com/static/images/3_/3__17530321825050/3_/1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='3__17530321825050/3_' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https://public.tableau.com/static/images/3_/3__17530321825050/3_/1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1753033849009');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='977px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
        </div>
        <div class="section" id="contact">
            <h2>צור קשר</h2>
            <p>לשאלות או פניות נוספות, צרו קשר עם צוות המסעדה במייל: <a href="mailto:info@garysburger.co.il">info@garysburger.co.il</a></p>
        </div>
    </div>
    <footer>
        <p>© 2025 הבורגר של גרי. כל הזכויות שמורות.</p>
    </footer>
</body>
</html>
