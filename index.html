<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VonlessSMP</title>
    <style>
        :root {
            --bg-blue: #001233;   /* Deep Navy Blue */
            --white-outline: #ffffff; 
            --red-action: #ff3e3e; 
            --glass: rgba(255, 255, 255, 0.05);
        }

        * { box-sizing: border-box; }

        body {
            background-color: var(--bg-blue);
            color: #ffffff;
            font-family: 'Inter', system-ui, -apple-system, sans-serif;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .dashboard {
            width: 100%;
            max-width: 500px; /* Slimmer profile since mods are hidden */
            background: var(--glass);
            border: 2px solid var(--white-outline);
            border-radius: 24px;
            padding: 50px 30px;
            box-shadow: 0 0 60px rgba(0,0,0,0.6);
            text-align: center;
        }

        h1 {
            font-size: clamp(2.5rem, 10vw, 3.5rem);
            margin: 0 0 10px 0;
            text-transform: uppercase;
            letter-spacing: -3px;
            font-weight: 900;
        }

        .version-tag {
            color: var(--red-action);
            font-family: monospace;
            font-size: 0.9rem;
            letter-spacing: 2px;
            margin-bottom: 40px;
            display: block;
        }

        /* Red Action Buttons */
        .btn {
            display: block;
            width: 100%;
            background: var(--red-action);
            color: white;
            border: none;
            padding: 22px;
            border-radius: 15px;
            font-size: 1.2rem;
            font-weight: 900;
            cursor: pointer;
            text-transform: uppercase;
            transition: all 0.2s ease-in-out;
            text-decoration: none;
            margin-bottom: 20px;
            box-shadow: 0 4px 15px rgba(255, 62, 62, 0.3);
        }

        .btn:hover {
            transform: translateY(-3px);
            filter: brightness(1.1);
            box-shadow: 0 10px 30px rgba(255, 62, 62, 0.5);
        }

        .btn-download {
            background: transparent;
            border: 2px solid var(--white-outline);
            box-shadow: none;
        }

        .btn-download:hover {
            background: white;
            color: var(--bg-blue);
        }

        /* Status Indicator */
        .status-container {
            margin-top: 30px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            font-family: monospace;
            font-size: 0.8rem;
            color: rgba(255,255,255,0.4);
        }

        .led { 
            height: 10px; 
            width: 10px; 
            background: #222; 
            border-radius: 50%; 
            border: 1px solid rgba(255,255,255,0.2);
        }

        .online { 
            background: #00ff88; 
            box-shadow: 0 0 15px #00ff88; 
            border: none;
        }
    </style>
</head>
<body>

    <div class="dashboard">
        <h1>VonlessSMP</h1>
        <span class="version-tag">NEOFORGE 1.21.1</span>

        <div class="actions">
            <button class="btn" onclick="bootServer()">Start Server</button>
            
            <a href="Mods.zip" class="btn btn-download" download>
                Download Modpack
            </a>
        </div>

        <div class="status-container">
            <div id="led" class="led"></div>
            <span id="statusTxt">SYSTEM STANDBY</span>
        </div>
    </div>

    <script>
        function bootServer() {
            const led = document.getElementById('led');
            const txt = document.getElementById('statusTxt');
            
            txt.innerText = "INITIALIZING...";
            
            // Link to the bridge.py script on your PC
            fetch('http://localhost:5000/start-server', { method: 'POST' })
            .then(res => {
                led.classList.add('online');
                txt.innerText = "ONLINE";
                txt.style.color = "#00ff88";
            })
            .catch(err => {
                txt.innerText = "BRIDGE ERROR";
                txt.style.color = "#ff3e3e";
            });
        }
    </script>

</body>
</html>
