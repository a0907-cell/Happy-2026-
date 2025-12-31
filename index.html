<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2026 新年快樂 🎉</title>
    <style>
        body { margin: 0; background: #000; overflow: hidden; font-family: "PingFang TC", "Microsoft JhengHei", sans-serif; }
        #overlay {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            display: flex; flex-direction: column; justify-content: center;
            align-items: center; z-index: 10; background: radial-gradient(circle, #1a1a1a, #000);
            transition: opacity 1s;
        }
        button {
            padding: 20px 40px; font-size: 24px; cursor: pointer;
            background: linear-gradient(45deg, #ff4757, #ff6b81); color: white;
            border: none; border-radius: 50px; box-shadow: 0 0 30px rgba(255, 71, 87, 0.5);
            animation: pulse 1.5s infinite;
        }
        @keyframes pulse { 0% { transform: scale(1); } 50% { transform: scale(1.05); } 100% { transform: scale(1); } }
        #message {
            position: fixed; top: 50%; left: 50%; transform: translate(-50%, -50%);
            color: #fff; text-align: center; pointer-events: none; opacity: 0; z-index: 5; width: 90%;
        }
        h1 { font-size: 3.5rem; text-shadow: 0 0 20px #fffa65; margin: 0; background: linear-gradient(to right, #fff, #fffa65); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        p { font-size: 1.8rem; color: #ffafbd; margin-top: 15px; }
    </style>
</head>
<body>

    <div id="overlay">
        <button onclick="startFirework()">✨ 點擊開啟 2026 驚喜 ✨</button>
    </div>

    <div id="message">
        <h1>Happy New Year!</h1>
        <p>祝你在 2026 年<br>萬事如意，天天開心！🧨</p>
    </div>

    <canvas id="fwCanvas"></canvas>

    <script>
        const canvas = document.getElementById('fwCanvas');
        const ctx = canvas.getContext('2d');
        let particles = [];

        function resize() { canvas.width = window.innerWidth; canvas.height = window.innerHeight; }
        window.addEventListener('resize', resize);
        resize();

        class Particle {
            constructor(x, y, color) {
                this.x = x; this.y = y; this.color = color;
                this.velocity = { x: (Math.random() - 0.5) * 12, y: (Math.random() - 0.5) * 12 };
                this.alpha = 1; this.friction = 0.96;
            }
            draw() {
                ctx.globalAlpha = this.alpha;
                ctx.beginPath(); ctx.arc(this.x, this.y, 2.5, 0, Math.PI * 2);
                ctx.fillStyle = this.color; ctx.fill();
            }
            update() {
                this.velocity.x *= this.friction; this.velocity.y *= this.friction;
                this.x += this.velocity.x; this.y += this.velocity.y;
                this.alpha -= 0.012;
            }
        }

        function createFirework(x, y) {
            const colors = ['#ff4757', '#2ed573', '#1e90ff', '#ffa502', '#ffffff', '#e056fd'];
            const color = colors[Math.floor(Math.random() * colors.length)];
            for (let i = 0; i < 60; i++) particles.push(new Particle(x, y, color));
        }

        function animate() {
            ctx.fillStyle = 'rgba(0, 0, 0, 0.15)';
            ctx.fillRect(0, 0, canvas.width, canvas.height);
            particles.forEach((p, i) => {
                if (p.alpha <= 0) particles.splice(i, 1); else { p.update(); p.draw(); }
            });
            requestAnimationFrame(animate);
        }

        function startFirework() {
            document.getElementById('overlay').style.opacity = '0';
            setTimeout(() => {
                document.getElementById('overlay').style.display = 'none';
                document.getElementById('message').style.transition = '2s';
                document.getElementById('message').style.opacity = '1';
            }, 1000);
            
            setInterval(() => {
                createFirework(Math.random() * canvas.width, Math.random() * canvas.height * 0.7);
            }, 450);
            animate();
        }

        window.addEventListener('click', (e) => {
            if (document.getElementById('overlay').style.display === 'none') {
                createFirework(e.clientX, e.clientY);
            }
        });
        window.addEventListener('touchstart', (e) => {
            if (document.getElementById('overlay').style.display === 'none') {
                createFirework(e.touches[0].clientX, e.touches[0].clientY);
            }
        });
    </script>
</body>
</html>
