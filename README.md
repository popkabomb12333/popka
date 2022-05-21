html

<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>магазин</title>
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    <div class="header">
        <p class="text_header_one"><span class="header_text_one">для мужчин</span><span class="header_text_two">для женщин</span><span class="header_text_three">для детей</span></p>
        <div class="icon">
            <div class="header_img_dir">
                <img src="./Frame.png" alt="img" class="header_img">
            </div>
            <div class="header_h">
                <h1 class="h">THE LOOP</h1>
            </div>
        </div>
        <p class="text_header_two"><span class="header_one">Оплата</span><span class="header_two">доставка</span></p>
        <div>
            <img src="./Vector.png" alt="png" class="img">
        </div>
    </div>
</body>
</html>

css

.header {
    display: flex;
    justify-content: center;
}
.header_text_one {
    margin-left: 95px;
    margin-top: 30px;
    font-size: 45px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 500;
}
.header_text_two {
    margin-left: 95px;
    margin-top: 30px;
    font-size: 45px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 500;
}
.header_text_three {
    margin-left: 95px;
    margin-top: 30px;
    font-size: 45px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 500;
}
.icon {
    display: flex;
}
.h {
    font-size: 50px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 700;
    line-height: 29px;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    margin-top: 55px;
    margin-left: 30px;
}
.header_img {
    width: 100px;
    margin-top: 23px;
}
.text_header_one {
    margin-top: 43px;
    margin-right: 100px;
}
.text_header_two {
    margin-top: 43px;
    margin-right: 100px;
}
.header_one {
    margin-left: 95px;
    margin-top: 30px;
    font-size: 45px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 500;
}
.header_two {
    margin-left: 95px;
    margin-top: 30px;
    font-size: 45px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 500;
}
.img {
    width: 70px;
    margin-top: 30px;
    margin-left: 50px;
}
