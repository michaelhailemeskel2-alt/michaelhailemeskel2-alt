<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Michael Hailemeskel | Media & Journalism Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            font-family: 'Poppins', sans-serif;
            background: #0f172a url('https://images.unsplash.com/photo-1598899134739-24c46f58b8c0?auto=format&fit=crop&w=1920&q=80') no-repeat center center fixed;
            background-size: cover;
            color: #f8fafc;
            min-height: 100vh;
            line-height: 1.6;
        }
        .overlay {
            background: rgba(15, 23, 42, 0.92);
            min-height: 100vh;
            padding: 40px 20px;
        }
        .container {
            max-width: 900px;
            margin: auto;
        }
        header {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(135deg, #1e293b, #0f172a);
            border-radius: 16px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
            margin-bottom: 30px;
        }
        header h1 {
            font-size: 2.5rem;
            font-weight: 700;
            color: #38bdf8;
            margin-bottom: 5px;
        }
        header p {
            font-size: 1.1rem;
            color: #94a3b8;
        }
        .section-title {
            font-size: 1.5rem;
            margin-bottom: 20px;
            border-left: 4px solid #38bdf8;
            padding-left: 12px;
            color: #f1f5f9;
        }
        .content-box {
            background: rgba(30, 41, 59, 0.7);
            backdrop-filter: blur(10px);
            padding: 25px;
            border-radius: 12px;
            border: 1px solid rgba(255, 255, 255, 0.08);
            margin-bottom: 30px;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }
        .card {
            background: rgba(30, 41, 59, 0.85);
            backdrop-filter: blur(10px);
            border-radius: 12px;
            padding: 20px;
            border: 1px solid rgba(255, 255, 255, 0.08);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 25px rgba(56, 189, 248, 0.15);
            border-color: rgba(56, 189, 248, 0.4);
        }
        .card h3 {
            color: #f8fafc;
            font-size: 1.2rem;
            margin-bottom: 8px;
        }
        .card p {
            color: #94a3b8;
            font-size: 0.9rem;
            margin-bottom: 15px;
        }
        .btn {
            display: inline-block;
            text-align: center;
            background: #0284c7;
            color: #ffffff;
            padding: 10px 18px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: 600;
            font-size: 0.9rem;
            transition: background 0.2s ease;
        }
        .btn:hover {
            background: #0369a1;
        }
        footer {
            text-align: center;
            margin-top: 50px;
            color: #64748b;
            font-size: 0.85rem;
        }
    </style>
</head>
<body>

<div class="overlay">
    <div class="container">
        
        <header>
            <h1>Michael Hailemeskel</h1>
            <p>Journalism & Media Specialist | Broadcast & Content Production</p>
        </header>

        <!-- About Me Section -->
        <div class="content-box">
            <h2 class="section-title">About Me</h2>
            <p>Welcome! I specialize in broadcast journalism, radio hosting, audio editing, and video media creation. My goal is to produce engaging media content that informs, educates, and inspires audiences.</p>
        </div>

        <!-- Communication Passion Section -->
        <div class="content-box">
            <h2 class="section-title">My Passion for Communication</h2>
            <p>Communication is more than just sharing information—it is about creating understanding, amplifying meaningful voices, and building real connections with an audience. I am deeply passionate about broadcast journalism, compelling visual storytelling, and clear media messaging.</p>
            <br>
            <p>Whether hosting radio programs, editing multi-media packages, or scripting short-form digital media, I bring high energy, integrity, and creative direction to every project I undertake.</p>
        </div>

        <!-- Featured Works Section -->
        <h2 class="section-title">Featured Media Works</h2>
        
        <div class="grid">
            <!-- Project 1 -->
            <div class="card">
                <div>
                    <h3>Video Project 1</h3>
                    <p>Featured broadcast storytelling sample and video production package.</p>
                </div>
                <a href="https://t.me/michaelhmg/2" class="btn" target="_blank">Watch Project</a>
            </div>

            <!-- Project 2 -->
            <div class="card">
                <div>
                    <h3>Video Project 2</h3>
                    <p>Media creation piece covering broadcast journalism concepts.</p>
                </div>
                <a href="https://t.me/michaelhmg/3" class="btn" target="_blank">Watch Project</a>
            </div>

            <!-- Project 3 -->
            <div class="card">
                <div>
                    <h3>Video Project 3</h3>
                    <p>Short feature video produced for broadcast media reporting.</p>
                </div>
                <a href="https://t.me/michaelhmg/4" class="btn" target="_blank">Watch Project</a>
            </div>

            <!-- Audio 1 -->
            <div class="card">
                <div>
                    <h3>Radio Broadcast Audio 1</h3>
                    <p>Audio recording and voice production sample for community broadcasting.</p>
                </div>
                <a href="https://t.me/michaelhmg/5" class="btn" target="_blank">Listen to Audio</a>
            </div>

            <!-- Audio 2 -->
            <div class="card">
                <div>
                    <h3>Radio Broadcast Audio 2</h3>
                    <p>Sound editing and voice hosting audio clip sample.</p>
                </div>
                <a href="https://t.me/michaelhmg/6" class="btn" target="_blank">Listen to Audio</a>
            </div>
        </div>

        <footer>
            <p>&copy; 2026 Michael Hailemeskel. All Rights Reserved.</p>
        </footer>

    </div>
</div>

</body>
</html>
