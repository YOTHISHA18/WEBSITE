## CODE
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <style>

        body {
            margin: 0;
            box-sizing: border-box;
        }
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #f5f5f5;
        }

        .header .logo {
            font-size: 25px;
            font-family: 'Sriracha', cursive;
            color: #000;
            text-decoration: none;
            margin-left: 30px;
        }

        .nav-items {
            display: flex;
            justify-content: space-around;
            align-items: center;
            background-color: #f5f5f5;
            margin-right: 20px;
        }

        .nav-items a {
            text-decoration: none;
            color: #000;
            padding: 35px 20px;
        }
        .intro {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            width: 100%;
            height: 520px;
            background: url("https://images.unsplash.com/photo-1587620962725-abab7fe55159?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1031&q=80");
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
        }

        .intro h1 {
            font-family: sans-serif;
            font-size: 60px;
            color: #fff;
            font-weight: bold;
            text-transform: uppercase;
            margin: 0;
        }

        .intro p {
            font-size: 20px;
            color: #d1d1d1;
            text-transform: uppercase;
            margin: 20px 0;
        }

        .intro button {
            background-color: #5edaf0;
            color: #000;
            padding: 10px 25px;
            border: none;
            border-radius: 5px;
            font-size: 20px;
            font-weight: bold;
            cursor: pointer;
            box-shadow: 0px 0px 20px rgba(255, 255, 255, 0.4)
        }

        .achievements {
            display: flex;
            justify-content: space-around;
            align-items: center;
            padding: 40px 80px;
        }

        .achievements .work {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 0 40px;
        }

        .achievements .work i {
            width: fit-content;
            font-size: 50px;
            color: #333333;
            border-radius: 50%;
            border: 2px solid #333333;
            padding: 12px;
        }

        .achievements .work .work-heading {
            font-size: 20px;
            color: #333333;
            text-transform: uppercase;
            margin: 10px 0;
        }

        .achievements .work .work-text {
            font-size: 15px;
            color: #585858;
            margin: 10px 0;
        }

        .about-me {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 40px 80px;
            border-top: 2px solid #eeeeee;
        }

        .about-me img {
            width: 500px;
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }

        .about-me-text h2 {
            font-size: 30px;
            color: #333333;
            text-transform: uppercase;
            margin: 0;
        }

        .about-me-text p {
            font-size: 15px;
            color: #585858;
            margin: 10px 0;
        }

        .footer {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #302f49;
            padding: 40px 80px;
        }

        .footer .copy {
            color: #fff;
        }

        .bottom-links {
            display: flex;
            justify-content: space-around;
            align-items: center;
            padding: 40px 0;
        }

        .bottom-links .links {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 0 40px;
        }

        .bottom-links .links span {
            font-size: 20px;
            color: #fff;
            text-transform: uppercase;
            margin: 10px 0;
        }

        .an {
            color: white;
            text-decoration: none;
            font-size: 20px;
            padding: 10px;
        }

        .bottom-links .links a {
            text-decoration: none;
            color: #a1a1a1;
            padding: 10px 20px;
        }
    </style>
    </head>

    <body>
        <header class="header">
            <a href="#" class="logo">Developer</a>
            <nav class="nav-items">
                <a href="#">Projects</a>
                <a href="#">News</a>
                <a href="#">Works</a>
                <a href="#">About</a>
            </nav>
        </header>
        <main>
            <div class="intro">
                <h1>A Web Developer</h1>
                <p>I am a web developer and I love to create websites.</p>
                <button>Learn More</button>
            </div>
            <div class="achievements">
                <div class="work">
                    <i class="fas fa-atom"></i>
                    <p class="work-heading">Projects</p>
                    <p class="work-text">I have worked on many projects and I am very proud of them. I am a very good
                        developer and I am always looking for new projects.</p>
                </div>
                <div class="work">
                    <i class="fas fa-skiing"></i>
                    <p class="work-heading">Skills</p>
                    <p class="work-text">I have a lot of skills and I am very good at them. I am very good at
                        programming and I am always looking for new skills.</p>
                </div>
                <div class="work">
                    <i class="fas fa-ethernet"></i>
                    <p class="work-heading">Network</p>
                    <p class="work-text">I have a lot of network skills and I am very good at them. I am very good at
                        networking and I am always looking for new network skills.</p>
                </div>
            </div>
            <div class="about-me">
                <div class="about-me-text">
                    <h2>About Me</h2>
                    <p>I am a web developer and I love to create websites. I am a very good developer and I am always
                        looking for new projects. I am a very good developer and I am always looking for new projects.
                    </p>
                </div>
                <img src="j1.jpeg" alt="me">
            </div>
        </main>
        <footer class="footer">
            <div class="copy">&copy; 2024 Developer</div>
            <div class="bottom-links">
                <div class="links">
                    <span>More Info</span>
                    <a>Home</a>
                    <a>About</a>
                    <a>Contact</a>
                </div>
            </div>
        </footer>
    </body>

</html>
```

## OUTPUT

![Screenshot_1-4-2025_16548_](https://github.com/user-attachments/assets/3d172e82-8111-4e75-a279-fff92eccbcce)

