<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub README</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Nunito:wght@900&display=swap">
    <style>
        body {
            width: 100%;
            display: flex;
            flex-direction: column;
        }

        .heading {
            display: flex;
            justify-content: space-between;
            padding: 100px;

            .info {
                display: flex;
                flex-direction: column;

                .info-title p {
                    font-family: 'Nunito', sans-serif;
                    font-weight: 900;
                    font-size: 70px;
                    margin: 0;
                }
            }

            .image img{
                width: 250px;
                height: 250px;
            }
        }
    </style>
</head>
<body>
    <div class="heading">
        <div class="info">
            <section class="info-title">
                <p class="info-title-head">hello,</p>
                <p class="info-title-name">I'm Sol.</p>
            </section>
            <section class="info-role">
                <p class="role-first">I'm a frontEnd developer</p>
                <p class="role-second">and graphic designer</p>
            </section>
            <button>see my profile</button>
        </div>
        <div class="image">
            <img src="./img.png" alt="">
        </div>
    </div>
</body>
</html>
