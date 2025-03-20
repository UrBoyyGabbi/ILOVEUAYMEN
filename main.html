<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A Letter For You</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f9f3f3;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            max-width: 900px;
            width: 90%;
        }
        
        /* Main title styling */
        .main-title {
            font-size: 48px;
            font-weight: bold;
            color: #ff758c;
            text-align: center;
            margin-bottom: 30px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
            animation: fadeIn 1.5s ease-in-out;
        }
        
        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(-20px); }
            100% { opacity: 1; transform: translateY(0); }
        }
        
        /* Realistic envelope styling */
        .realistic-envelope {
            width: 350px;
            height: 220px;
            position: relative;
            margin: 40px auto;
            perspective: 1000px;
            transform-style: preserve-3d;
        }
        
        .envelope-front {
            position: absolute;
            width: 100%;
            height: 100%;
            background-color: #f0e4d7;
            border-radius: 5px;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.15);
            transform-style: preserve-3d;
            transform-origin: top;
            transition: transform 1s;
            z-index: 2;
        }
        
        .envelope-flap {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: #f0e4d7;
            clip-path: polygon(0 0, 100% 0, 50% 60%, 0 0);
            border-radius: 5px 5px 0 0;
            transform-origin: top;
            transition: transform 1.2s;
            z-index: 3;
        }
        
        .envelope-inside {
            position: absolute;
            width: 100%;
            height: 100%;
            background-color: #e8d6c3;
            border-radius: 5px;
            z-index: 1;
        }
        
        .envelope-body {
            position: absolute;
            width: 100%;
            height: 100%;
            background-color: #f0e4d7;
            border-radius: 5px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            z-index: 2;
        }
        
        .envelope-body:after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: url("data:image/svg+xml,%3Csvg width='100' height='100' viewBox='0 0 100 100' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M50,50 L100,0 L0,0 Z' fill='%23e8d6c3' fill-opacity='0.6'/%3E%3Cpath d='M50,50 L0,100 L100,100 Z' fill='%23e8d6c3' fill-opacity='0.6'/%3E%3C/svg%3E");
            background-size: 100% 100%;
            z-index: -1;
        }
        
        .envelope-shadow {
            position: absolute;
            width: 100%;
            height: 10px;
            bottom: -10px;
            left: 0;
            filter: blur(3px);
            background: rgba(0, 0, 0, 0.1);
            border-radius: 50%;
        }
        
        .envelope-stamp {
            position: absolute;
            top: 15px;
            right: 15px;
            width: 60px;
            height: 70px;
            background: linear-gradient(to bottom, #ffe8e8, #ffccd1);
            border: 1px dashed #ffaaaa;
            border-radius: 3px;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 12px;
            color: #ff758c;
            text-align: center;
            padding: 5px;
            font-weight: bold;
        }
        
        .envelope-seal {
            position: absolute;
            top: 35%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 110px;
            height: 40px;
            background: linear-gradient(135deg, #ff758c, #ff7eb3);
            border-radius: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            font-size: 16px;
            font-weight: bold;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            z-index: 4;
        }
        
        .envelope-address {
            position: absolute;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%);
            text-align: center;
            font-size: 14px;
            color: #666;
            font-style: italic;
        }
        
        .open-button {
            margin-top: 20px;
            background: linear-gradient(to right, #ff758c, #ff7eb3);
            color: white;
            border: none;
            padding: 12px 28px;
            font-size: 16px;
            border-radius: 50px;
            cursor: pointer;
            box-shadow: 0 4px 10px rgba(255, 117, 140, 0.3);
            transition: all 0.3s ease;
            font-weight: bold;
            z-index: 10;
        }
        
        .open-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(255, 117, 140, 0.4);
        }
        
        /* Open letter styling */
        .open-envelope {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 5px 25px rgba(0, 0, 0, 0.1);
            width: 100%;
            overflow: hidden;
            position: relative;
            margin-bottom: 20px;
            display: none;
            opacity: 0;
            transition: opacity 0.5s ease;
        }
        
        .open-envelope:before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 10px;
            background: linear-gradient(to right, #ff758c, #ff7eb3);
        }
        
        .letter-content {
            display: flex;
            flex-direction: row;
            padding: 30px;
        }
        
        .text-area {
            flex: 2;
            padding-right: 30px;
        }
        
        .image-area {
            flex: 1;
            display: flex;
            justify-content: center;
            align-items: flex-start;
        }
        
        h1 {
            color: #ff758c;
            margin-top: 0;
            font-size: 28px;
        }
        
        .date {
            color: #888;
            font-style: italic;
            margin-bottom: 20px;
        }
        
        p {
            line-height: 1.6;
            color: #444;
            margin-bottom: 15px;
        }
        
        .signature {
            font-family: 'Brush Script MT', cursive;
            font-size: 24px;
            margin-top: 30px;
            color: #333;
        }
        
        img {
            max-width: 100%;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        
        .heart {
            position: absolute;
            width: 30px;
            height: 30px;
            opacity: 0;
            background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 24 24' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath fill='%23ff758c' d='M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z'/%3E%3C/svg%3E");
            background-size: contain;
            pointer-events: none;
        }
        
        .letter-peek {
            position: absolute;
            top: 15px;
            left: 50%;
            transform: translateX(-50%);
            width: 80%;
            height: 20px;
            background-color: white;
            border-radius: 3px 3px 0 0;
            z-index: 0;
        }
        
        @media (max-width: 768px) {
            .letter-content {
                flex-direction: column;
            }
            .text-area {
                padding-right: 0;
                padding-bottom: 20px;
            }
            .realistic-envelope {
                width: 300px;
                height: 180px;
            }
            .main-title {
                font-size: 36px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Added main title -->
        <h1 class="main-title">A Letter To Aymen ❤️</h1>
        
        <div id="closedEnvelope" class="realistic-envelope">
            <div class="envelope-inside"></div>
            <div class="envelope-body">
                <div class="letter-peek"></div>
            </div>
            <div class="envelope-front"></div>
            <div class="envelope-flap"></div>
            <div class="envelope-stamp">From someone who cares</div>
            <div class="envelope-seal">Letter To Aymen</div>
            <div class="envelope-address">With Love</div>
            <div class="envelope-shadow"></div>
        </div>
        
        <button id="openButton" class="open-button">Open Me 💌</button>
        
        <div id="openEnvelope" class="open-envelope">
            <div class="letter-content">
                <div class="text-area">
                    <h1>To My Dearest Aymen</h1>
                    <div class="date">March 20, 2025</div>
                    
                    <p>My love,</p>
                    
                    <p>As I sit here writing this letter, I can't help but think about how lucky I am to have you in my life. Every day with you feels like a gift that I cherish more than you'll ever know.</p>
                    
                    <p>I remember the first time I saw you. Something inside me just knew that you were special, and time has only proven how right that feeling was. Your smile brightens even my darkest days, and your laughter is my favorite sound in the world.</p>
                    
                    <p>What I love most about you is how you see the world - with kindness, curiosity, and an open heart. You make me want to be a better person, and you inspire me in more ways than you know.</p>
                    
                    <p>I created this little corner of the internet just for you, as a place where I could express how much you mean to me. Words sometimes feel inadequate to capture the depth of my feelings, but I hope you know that you are loved, cherished, and adored.</p>
                    
                    <p>Thank you for being you, and for choosing to share your journey with me.</p>
                    
                    <div class="signature">With all my love,</div>
                </div>
                <div class="image-area">
                    <img src="/api/placeholder/300/400" alt="A photo of you">
                </div>
            </div>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const closedEnvelope = document.getElementById('closedEnvelope');
            const openEnvelope = document.getElementById('openEnvelope');
            const openButton = document.getElementById('openButton');
            const envelopeFlap = document.querySelector('.envelope-flap');
            
            // Create floating hearts effect
            function createHeart() {
                const heart = document.createElement('div');
                heart.className = 'heart';
                
                // Random position and size
                heart.style.left = Math.random() * 100 + '%';
                heart.style.top = (Math.random() * 40 + 60) + '%';
                const size = Math.random() * 20 + 10;
                heart.style.width = size + 'px';
                heart.style.height = size + 'px';
                
                // Animation
                document.body.appendChild(heart);
                
                // Animate
                let angle = Math.random() * 2 * Math.PI;
                let speed = Math.random() * 2 + 1;
                let startX = parseInt(heart.style.left);
                let startY = parseInt(heart.style.top);
                let opacity = 0;
                
                function animate() {
                    if (opacity < 1) opacity += 0.02;
                    if (opacity > 0.4) opacity -= 0.01;
                    angle += 0.01;
                    
                    const x = startX + Math.cos(angle) * 20;
                    const y = startY - speed * 2;
                    
                    heart.style.left = x + 'px';
                    heart.style.top = y + 'px';
                    heart.style.opacity = opacity;
                    
                    if (y > -100 && opacity > 0) {
                        requestAnimationFrame(animate);
                    } else {
                        heart.remove();
                    }
                }
                
                requestAnimationFrame(animate);
            }
            
            openButton.addEventListener('click', function() {
                // Animate envelope opening
                envelopeFlap.style.transform = 'rotateX(180deg)';
                
                // Create heart animation
                for (let i = 0; i < 15; i++) {
                    setTimeout(createHeart, i * 150);
                }
                
                // Show the open letter after a delay
                setTimeout(function() {
                    closedEnvelope.style.display = 'none';
                    openButton.style.display = 'none';
                    openEnvelope.style.display = 'block';
                    
                    // Fade in animation
                    setTimeout(function() {
                        openEnvelope.style.opacity = 1;
                    }, 100);
                }, 1500);
            });
        });
    </script>
</body>
</html>
