<!DOCTYPE html>
<html lang="cs">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nábor do AT</title>

<style>
body{
    margin:0;
    font-family:Arial, sans-serif;
    background:linear-gradient(135deg,#0b1220,#111827);
    color:white;
}

header{
    text-align:center;
    padding:50px 20px;
    background:#1e293b;
    box-shadow:0 0 20px rgba(0,0,0,0.4);
}

header h1{
    margin:0;
    font-size:42px;
    color:#38bdf8;
}

header p{
    color:#94a3b8;
    margin-top:10px;
}

.container{
    max-width:950px;
    margin:auto;
    padding:40px 20px;
}

.box{
    background:#1e293b;
    padding:25px;
    border-radius:18px;
    margin-bottom:25px;
    border-left:5px solid #38bdf8;
    box-shadow:0 0 20px rgba(0,0,0,0.3);
}

h2{
    color:#38bdf8;
    margin-top:0;
}

label{
    display:block;
    margin-top:18px;
    margin-bottom:8px;
    color:#facc15;
    font-size:16px;
    font-weight:bold;
}

input, textarea{
    width:100%;
    padding:14px;
    border:none;
    border-radius:10px;
    background:#0f172a;
    color:white;
    box-sizing:border-box;
    font-size:15px;
}

textarea{
    min-height:80px;
    resize:vertical;
}

input:focus,
textarea:focus{
    outline:2px solid #38bdf8;
}

button{
    width:100%;
    padding:16px;
    border:none;
    border-radius:12px;
    background:#38bdf8;
    color:black;
    font-size:18px;
    font-weight:bold;
    cursor:pointer;
    transition:0.3s;
}

button:hover{
    background:#0ea5e9;
    transform:scale(1.01);
}

.notice{
    text-align:center;
    color:#94a3b8;
    margin-top:18px;
}
</style>
</head>

<body>

<header>
    <h1>🎮 Nábor do Admin Teamu</h1>
    <p>Vyplň formulář pravdivě.</p>
</header>

<div class="container">

<form action="https://formsubmit.co/unionrpnabory@gmail.com" method="POST">

<input type="hidden" name="_captcha" value="false">
<input type="hidden" name="_subject" value="Nový nábor do AT">
<input type="hidden" name="_next" value="https://gandalfmaty.github.io/RP-Pravidla-/uspech.html">

<div class="box">

<h2>📌 Základní informace</h2>

<label>Nickname v Robloxu *</label>
<input type="text" name="Roblox Nick" required>

<label>Jméno na Discordu *</label>
<input type="text" name="Discord Jméno" required>

<label>Kolik ti je let? *</label>
<input type="number" name="Věk" required>

</div>

<div class="box">

<h2>📖 Otázky</h2>

<div>
<label>1. Co je VDM?</label>
<textarea name="Otázka 1"></textarea>
</div>

<div>
<label>2. Co je RDM?</label>
<textarea name="Otázka 2"></textarea>
</div>

<div>
<label>3. Co znamená FearRP?</label>
<textarea name="Otázka 3"></textarea>
</div>

<div>
<label>4. Co znamená MetaGaming?</label>
<textarea name="Otázka 4"></textarea>
</div>

<div>
<label>5. Co znamená PowerGaming?</label>
<textarea name="Otázka 5"></textarea>
</div>

<div>
<label>6. Musíš respektovat rozhodnutí admina?</label>
<textarea name="Otázka 6"></textarea>
</div>

<div>
<label>7. Co je Combat Logging?</label>
<textarea name="Otázka 7"></textarea>
</div>

<div>
<label>8. Co znamená NLR?</label>
<textarea name="Otázka 8"></textarea>
</div>

<div>
<label>9. Je povolené zabít hráče bez RP důvodu?</label>
<textarea name="Otázka 9"></textarea>
</div>

<div>
<label>10. Je reklama na jiné servery povolena?</label>
<textarea name="Otázka 10"></textarea>
</div>

<div>
<label>11. Můžeš trollit ostatní hráče?</label>
<textarea name="Otázka 11"></textarea>
</div>

<div>
<label>12. Co je SafeZone?</label>
<textarea name="Otázka 12"></textarea>
</div>

<div>
<label>13. Můžeš používat bugy?</label>
<textarea name="Otázka 13"></textarea>
</div>

<div>
<label>14. Co bys dělal, kdyby někdo porušoval pravidla?</label>
<textarea name="Otázka 14"></textarea>
</div>

</div>

<button type="submit">✅ Odeslat nábor</button>

<p class="notice">
Náborový tým ti odpoví co nejdříve.
</p>

</form>

</div>

</body>
</html>
