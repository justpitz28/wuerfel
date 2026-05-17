<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multi-Würfel</title>
    <style>
        body { font-family: sans-serif; background: #eef2f3; display: flex; justify-content: center; align-items: center; height: 100vh; margin: 0; }
        .box { background: white; padding: 30px; border-radius: 20px; box-shadow: 0 10px 30px rgba(0,0,0,0.1); text-align: center; width: 300px; }
        h1 { color: #333; }
        .input-group { margin: 20px 0; }
        input { width: 60px; padding: 10px; border-radius: 8px; border: 1px solid #ccc; text-align: center; font-size: 1rem; }
        button { background: #ff4757; color: white; border: none; padding: 15px 25px; border-radius: 10px; font-size: 1.2rem; cursor: pointer; transition: 0.3s; width: 100%; }
        button:active { transform: scale(0.95); }
        #result { font-size: 4rem; font-weight: bold; color: #2f3542; margin-top: 20px; min-height: 80px; }
    </style>
</head>
<body>

<div class="box">
    <h1>🎲 Würfel</h1>
    
    <div class="input-group">
        Von 1 bis: 
        <input type="number" id="maxNumber" value="6">
    </div>

    <button onclick="roll()">Würfeln!</button>

    <div id="result">?</div>
</div>

<script>
    function roll() {
        // Hol die Zahl aus dem Feld
        let max = document.getElementById('maxNumber').value;
        
        // Zufallszahl berechnen
        let result = Math.floor(Math.random() * max) + 1;
        
        // Ergebnis anzeigen
        document.getElementById('result').innerText = result;
    }
</script>

</body>
</html>
