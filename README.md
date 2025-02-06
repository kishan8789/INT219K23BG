
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Website Task</title>

    <style>

        * {

            margin: 0;

            padding: 0;

            box-sizing: border-box;

        }



        body {

            font-family: Arial, sans-serif;

            line-height: 1.6;

            background-color: white;

            color: grey;

        }



        header {

            background-color: rgb(5, 196, 5);

            color: #fff;

            padding: 20px 10px;

            text-align: center;

        }



        nav ul {

            list-style: none;

            display: flex;

            justify-content: center;

            margin-top: 10px;

        }



        nav ul li {

            margin: 0 15px;

        }



        nav ul li a {

            color: white;

            text-decoration: none;

            font-size: 18px;

        }



        .card-container {

            display: flex;

            justify-content: space-between;

            flex-wrap: wrap;

            padding: 20px;

        }



        .left-section {

            display: flex;

            flex-direction: column;

            width: 48%;

        }



        .card {

            background-color: white;

            border: 1px solid #ccc;

            border-radius: 8px;

            box-shadow: 0 4px 6px black;

            padding: 15px;

            text-align: center;

        }



        .card h2 {

            color: green;

            margin-bottom: 10px;

        }



        .card + .card {

            margin-top: 15px;

        }



        .right-section {

            width: 48%;

            display: flex;

            align-items: flex-start;

        }



        footer {

            position: fixed;

            bottom: 0;

            left: 0;

            width: 100%;

            background-color: black;

            color: white;

            text-align: center;

            padding: 10px;

        }



        footer a {

            color: rgb(6, 142, 6);

            text-decoration: none;

            margin: 0 10px;

        }



        footer a:hover {

            text-decoration: underline;

        }

    </style>

</head>

<body>

    <header>

        <nav>

            <h1>Welcome to Your Website Task</h1>

            <ul>

                <li><a href="#">Home</a></li>

                <li><a href="#">About</a></li>

                <li><a href="#">Contact</a></li>

            </ul>

        </nav>

    </header>

    <main>

        <div class="card-container">

            <div class="left-section">

                <div class="card">

                    <h2>About CSS</h2>

                    <p>Cascading Style Sheets (CSS) allow you to style and layout your web pages, adding colors, spacing, and more.</p>

                </div>

                <div class="card">

                    <h2>Box Model</h2>

                    <p>The CSS box model describes the rectangular boxes generated for elements. It includes margins, borders, padding, and the actual content.</p>

                </div>

            </div>

            <div class="right-section">

                <div class="card">

                    <h2>Responsive Design</h2>

                    <p>Responsive design ensures your webpage looks great on all devices, from desktops to mobile phones.</p>

                </div>

            </div>

        </div>

    </main>

    

    <footer>

        <p>Created by Kishan Kumar | Follow us on  

            <a href="#">Instagram</a> |

            <a href="#">Twitter</a> |

            <a href="#">LinkedIn</a>

        </p>

    </footer>

    

</body>

</html>





