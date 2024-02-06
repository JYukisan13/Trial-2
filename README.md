<!DOCTYPE html>

<html>
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <link rel="stylesheet" href="styles.css">
      
        <style>
          ::-webkit-scrollbar {
            display: none;
          }
            body{
                background-color: white;
                overflow: hidden;
                height: 100vh;
            }
            div.subtitle {
                position: absolute;
                left: 100px; 
                color: white;
                top: 140px;
                font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
                font-size: 30px;
            }
            div.headersub {
                position: absolute;
                left: 100px;
                color: rgb(0, 0, 0);
                top: -23px;
                font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
                font-size: 25px;
            }
            div.position {
                position: absolute;
                left: 100px;
                top: 48px;
                color: white;
                font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
                font-size: 40px;
                overflow: hidden;
            }
            div.circle {
                position: absolute;
                top: -1000px;
                left: -1300px;
                height: 3000px;
                width: 3000px;
                background-color: black;
                border-radius: 50%;
                overflow: -moz-hidden-unscrollable;
            }
            .rectangle {
                position: absolute;
                top: 235px;
                left: 100px;
                height: 300px;
                width: 240px;
                background-color: white;
            }
            .topheader {
                position: absolute;
                top: 10px;
                left: 1px;
                height: 34px;
                width: 1700px;
                background-color: white;
            }
            .pfp {
                position: absolute;
                top: 245px;
                left: 110px;
                width: 220px;
                height: 220px;
                filter: grayscale(100%);
            }
            .header {
                position: absolute;
                width: 500px;
                height: 500px;
                color: white;
            }
        </style>
    </head>
    
    <body onwheel="event.preventDefault();">

        <div class="circle"></div>
        <div class="header"></div>
        <div class="position">
            <h1>
                MY PERSONAL WEBSITE
            </h1>
        </div>

        <div class="subtitle">
            <h4>
                GET TO KNOW ME THROUGH THIS WEBSITE!
            </h4>
        </div>

        <div class="rectangle"></div>
        <div class="topheader"></div>

        <div class="headersub">
          <h6>
              Gmail: jamesmichael.siton@gmail.com  |  Phone Number: 0993 821 0947
          </h6>
        </div>
        
        <img class="pfp" src="https://scontent.fmnl8-2.fna.fbcdn.net/v/t39.30808-6/421708118_1111125473254010_1855168662502346903_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=efb6e6&_nc_eui2=AeGA-fnjfXnVoBnuQ7vKE_JoC5HddyTOK6kLkd13JM4rqa7dhIVxg0m5ni-ma_yGEKa7bhOPTu9m6pelRwgihmj6&_nc_ohc=Bm-iHlAjM9sAX-7RmXb&_nc_ht=scontent.fmnl8-2.fna&oh=00_AfBfwXl7xs29ppC0RZNWe7BRntUSfRqYZFUqIYq5EVfchw&oe=65C7498D">
    </body>
</html>
