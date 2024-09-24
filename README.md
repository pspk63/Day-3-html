# Card Design Template

A simple, elegant card design template using HTML and CSS. The card showcases an image with a hover effect and a call-to-action button, perfect for website UI elements like landing pages or promotional sections.

## Features
- Responsive card design with an image, title, description, and button.
- Hover effect for a modern look.
- Customizable content and styles.

## Preview

![Card Preview](https://img.freepik.com/free-photo/colourful-traditional-mexican-house_23-2151769198.jpg?size=626&ext=jpg)

## Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Card</title>
    <style>
        body{
            background-color: black;
        }
        .card{
            width: 350px;
            border: 2px solid rgb(201, 199, 199);
            color: rgb(0, 0, 0);
            background-color: white;
            border-radius: 10px;
            padding: 10px;
            margin: 170px auto;
        }
        .card:hover{
            box-shadow: 10px 0px 30px 10px rgb(4, 137, 226);
        }
        .card img{
            width: 100%;
            border-radius: 10px;
        }
        .card h2{
            text-align: center;
            margin-top:0px;
            font-size: 30px;
            font-family:system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }
        .card p{
            margin-top: -15px;
            font-size: 19px;
            text-align: center;
        }
        .card a{
            margin-left: 90px;
            text-decoration: none;
            color: rgb(0, 204, 255);
            background-color: black;
            padding: 8px 50px;
            border-radius: 7px;
        }
    </style>
</head>
<body>
    <div class="card">
        <img src="https://img.freepik.com/free-photo/colourful-traditional-mexican-house_23-2151769198.jpg?size=626&ext=jpg" alt="A beaytiful House">
        <h2>A Beautiful House</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi fugit iure asperiores id earum excepturi, ea fuga, ut ducimus architecto corrupti quis ad repudiandae impedit quam neque deleniti nobis saepe.</p>
        <a href="#">Join Now</a>
        <br><br>
    </div>
</body>
</html>
