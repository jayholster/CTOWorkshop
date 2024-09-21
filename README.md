<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Critical Techno-Optimism Workshop - Penn State</title>
    <style>
        body {
            font-family: 'Roboto', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            margin: 0;
            padding: 0;
            background-color: #001E44; /* Penn State Dark Blue */
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.95);
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        canvas {
            display: block;
            width: 100%;
            height: 400px;
            margin-bottom: 20px;
        }
        h1 {
            color: #1E407C; /* Penn State Blue */
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 30px;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
        }
        h2 {
            color: #1E407C;
            margin-top: 30px;
            font-size: 1.8em;
        }
        a {
            color: #1E407C;
            text-decoration: none;
            transition: all 0.3s ease;
        }
        a:hover {
            color: #009CDE; /* Penn State Light Blue */
            text-decoration: underline;
        }
        .task {
            background-color: #f8f9fa;
            border-left: 5px solid #1E407C;
            border-radius: 5px;
            padding: 20px;
            margin-bottom: 30px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        .task:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 8px rgba(0,0,0,0.15);
        }
        .footer {
            margin-top: 40px;
            text-align: center;
            font-style: italic;
            background-color: #1E407C;
            color: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #1E407C;
            color: white !important;
            border-radius: 5px;
            text-decoration: none;
            transition: all 0.3s ease;
            font-weight: bold;
            cursor: pointer;
        }
        .button:hover {
            background-color: #009CDE;
            color: white !important;
            text-decoration: none !important;
            transform: scale(1.05);
        }
        .host-info {
            text-align: center;
            margin-bottom: 30px;
            padding: 20px;
            background-color: #f0f4f8;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .host-info p {
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <canvas id="interactiveHeader"></canvas>
    <div class="container">
        <h1>Critical Techno-Optimism Workshop</h1>
        <div class="host-info">
            <p><strong>Jacob Holster</strong></p>
            <p>Lecturer of Music Education at Penn State University</p>
            <p>Email: <a href="mailto:jbh6331@psu.edu">jbh6331@psu.edu</a></p>
        </div>

        <div class="task">
            <h2>Task 1: Prompt Optimization</h2>
            <p>Learn how to craft effective prompts to elicit the best possible responses from AI models. This task introduces various techniques like zero-shot, few-shot, role-based, step-by-step, reflection, and contextual prompting to enhance the quality and relevance of AI-generated content.</p>
            <a href="#" class="button" onclick="openLink('https://claude.site/artifacts/3404e6c8-33e7-4ad4-bcd0-9394e1b06640')">Start optimizing your prompts</a>
        </div>

        <div class="task">
            <h2>Task 2: Using GPTs</h2>
            <p>Explore and interact with custom GPTs designed for specific tasks. You'll discover how these specialized AI models can assist with literature reviews, data analysis, topic modeling, and more, enhancing your productivity and research capabilities.</p>
            <a href="#" class="button" onclick="openLink('https://claude.site/artifacts/ed105d00-49c4-45fe-a3b7-1dde67e67184')">Explore custom GPTs</a>
        </div>

        <div class="task">
            <h2>Task 3: Creating Your Own GPT</h2>
            <p>Build a custom GPT tailored to your needs. This task guides you through defining your GPT's purpose, setting up instructions, and customizing responses, enabling you to create a personalized AI assistant for your projects or workflows.</p>
            <a href="#" class="button" onclick="openLink('https://claude.site/artifacts/5f92e984-75f5-4f7e-9a20-98be9b8a58a4')">Create your custom GPT</a>
        </div>

        <div class="task">
            <h2>Task 4: Creating Artifacts with Claude AI</h2>
            <p>Use Claude AI to generate creative artifacts like games, programs, or tools. Learn how to write clear, detailed prompts and specify requirements to produce functional and innovative outputs using this advanced AI model.</p>
            <a href="#" class="button" onclick="openLink('https://claude.site/artifacts/434b391d-1304-4a47-8e14-6ff8e24f7d59')">Generate artifacts with Claude</a>
        </div>

        <div class="task">
            <h2>Task 5: AI Image Generation</h2>
            <p>Bring your visual ideas to life by generating images based on your descriptions. This task introduces you to AI tools that transform textual prompts into vivid images, allowing you to create artwork, concept designs, or illustrations effortlessly.</p>
            <a href="#" class="button" onclick="openLink('https://claude.site/artifacts/4e88ceca-4a00-4b17-ab42-1609463f54ab')">Start generating AI images</a>
        </div>

        <div class="task">
            <h2>Task 6: AI Image to Video Generation</h2>
            <p>Expand your creative skills by generating both images and videos using AI. Explore tools that enable you to produce short animations or video clips from descriptive prompts, enhancing your ability to create dynamic visual content.</p>
            <a href="#" class="button" onclick="openLink('https://claude.site/artifacts/5a6c714f-99b9-498a-b0c8-0733711c2b1c')">Create AI videos</a>
        </div>

        <div class="task">
            <h2>Task 7: AI Music Creation</h2>
            <p>Compose original music using AI by providing detailed descriptions of genre, mood, instruments, and length. This task helps you create customized musical tracks for various purposes, such as background scores, jingles, or personal projects.</p>
            <a href="#" class="button" onclick="openLink('https://claude.site/artifacts/bfaee81d-bb72-406b-a799-d7c380915953')">Compose AI music</a>
        </div>

        <div class="footer">
            <p><strong>Need a Break?</strong> Vote for your favorite AI film in the <a href="#" onclick="openLink('https://runwayml.com/gen48')">Gen:48 AI film competition</a>.</p>
        </div>
    </div>

    <script>
        const canvas = document.getElementById('interactiveHeader');
        const ctx = canvas.getContext('2d');
        let particles = [];
        const particleCount = 200;
        const connectionDistance = 100;
        let mouse = { x: null, y: null };

        function resizeCanvas() {
            canvas.width = window.innerWidth;
            canvas.height = 400;
        }

        class Particle {
            constructor() {
                this.x = Math.random() * canvas.width;
                this.y = Math.random() * canvas.height;
                this.size = Math.random() * 3 + 1;
                this.baseX = this.x;
                this.baseY = this.y;
                this.density = (Math.random() * 30) + 1;
                this.color = Math.random() < 0.7 ? '#1E407C' : (Math.random() < 0.5 ? '#009CDE' : '#ffffff');
                this.speedX = Math.random() * 2 - 1;
                this.speedY = Math.random() * 2 - 1;
            }

            update() {
                this.x += this.speedX;
                this.y += this.speedY;

                if (this.x > canvas.width || this.x < 0) this.speedX *= -1;
                if (this.y > canvas.height || this.y < 0) this.speedY *= -1;

                let dx = mouse.x - this.x;
                let dy = mouse.y - this.y;
                let distance = Math.sqrt(dx * dx + dy * dy);
                let forceDirectionX = dx / distance;
                let forceDirectionY = dy / distance;
                let maxDistance = 100;
                let force = (maxDistance - distance) / maxDistance;
                let directionX = forceDirectionX * force * this.density;
                let directionY = forceDirectionY * force * this.density;

                if (distance < maxDistance) {
                    this.x -= directionX;
                    this.y -= directionY;
                }
            }

            draw() {
                ctx.fillStyle = this.color;
                ctx.beginPath();
                ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
                ctx.closePath();
                ctx.fill();
            }
        }

        function init() {
            particles = [];
            for (let i = 0; i < particleCount; i++) {
                particles.push(new Particle());
            }
        }

        function animate() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            for (let i = 0; i < particles.length; i++) {
                particles[i].update();
                particles[i].draw();

                for (let j = i; j < particles.length; j++) {
                    const dx = particles[i].x - particles[j].x;
                    const dy = particles[i].y - particles[j].y;
                    const distance = Math.sqrt(dx * dx + dy * dy);

                    if (distance < connectionDistance) {
                        ctx.beginPath();
                        ctx.strokeStyle = `rgba(30, 64, 124, ${0.5 - distance/connectionDistance})`;
                        ctx.lineWidth = 1;
                        ctx.moveTo(particles[i].x, particles[i].y);
                        ctx.lineTo(particles[j].x, particles[j].y);
                        ctx.stroke();
                        ctx.closePath();
                    }
                }
            }
            requestAnimationFrame(animate);
        }

        window.addEventListener('resize', resizeCanvas);
        canvas.addEventListener('mousemove', (e) => {
            mouse.x = e.x;
            mouse.y = e.y;
        });

        resizeCanvas();
        init();
        animate();

        // Function to handle link clicks
        function openLink(url) {
            // Attempt to open the link in a new tab
            window.open(url, '_blank');
            
            // If the above fails, try to navigate in the current window
            setTimeout(function() {
                window.location.href = url;
            }, 100);
        }
    </script>
</body>
</html>
