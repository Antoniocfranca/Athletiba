# athletiba
<!DOCTYPE html>
<html>
<head>
    <title>COXA VAI GANHAR HOJE?</title>
    <style>
        body {
            background-color: green;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-size: 2rem;
            color: white;
        }

        #no {
            position: absolute;
            transition: 1s;
        }
    </style>
</head>
<body>
    <h1>O COXA VAI GANHAR HOJE E O CAIO VAI CHORAR?</h1>
    <button id="yes">Sim</button>
    <button id="no">Não</button>

    <script>
        document.getElementById('yes').addEventListener('click', function() {
            window.location.href = 'https://www.youtube.com/watch?v=07nAPITVEWw';
        });

        document.getElementById('no').addEventListener('mouseover', function() {
            const maxVal = 500;
            let x = Math.floor(Math.random() * maxVal);
            let y = Math.floor(Math.random() * maxVal);
            this.style.left = `${x}px`;
            this.style.top = `${y}px`;
        });
    </script>
</body>
</html>
