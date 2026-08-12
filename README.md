<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Small Tools</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            background: #f5f5f5;
            color: #222;
        }

        header {
            text-align: center;
            padding: 70px 20px 30px;
        }

        header h1 {
            font-size: 48px;
            margin-bottom: 12px;
        }

        header h2 {
            font-size: 20px;
            font-weight: normal;
            color: #666;
        }

        main {
            flex: 1;
            width: 90%;
            max-width: 900px;
            margin: auto;
            text-align: center;
        }

        .description {
            margin: 25px auto 40px;
            max-width: 650px;
            line-height: 1.7;
            color: #555;
        }

        .projects {
            display: flex;
            justify-content: center;
            gap: 18px;
            flex-wrap: wrap;
        }

        .project-btn {
            border: none;
            padding: 15px 28px;
            border-radius: 10px;
            background: #222;
            color: white;
            font-size: 16px;
            cursor: pointer;
            transition: 0.25s;
        }

        .project-btn:hover {
            transform: translateY(-3px);
            background: #444;
        }

        footer {
            text-align: center;
            padding: 25px;
            margin-top: 50px;
            color: #777;
            font-size: 14px;
        }

        @media (max-width: 600px) {

            header {
                padding-top: 60px;
            }

            header h1 {
                font-size: 36px;
            }

            header h2 {
                font-size: 17px;
            }

            .projects {
                flex-direction: column;
                align-items: center;
            }

            .project-btn {
                width: 220px;
            }
        }
    </style>
</head>

<body>

    <!-- HEADER -->
    <header>
        <h1>Small-Tools</h1>
        <h2>This is all Developing Tools</h2>
    </header>


    <!-- MAIN CONTENT -->
    <main>

        <!-- DESCRIPTION -->
        <section class="description">
            <p>
                This 'Small-Tools' is used to usefull tools.
            </p>
        </section>


        <!-- PROJECT BUTTONS -->
        <section class="projects">

                <a href="photoeditor.html"  class="project-btn">Photo Editor</a>
                <a href="QR code generator.html"  class="project-btn">QR Code Generator</a>
                <a href="password generator.html"  class="project-btn">Password Generator</a>
                <a href="flames.html"  class="project-btn">Flames</a>
        </section>

    </main>


    <!-- FOOTER -->
    <footer>
        ©Small Tools
    </footer>
</body>
</html>





