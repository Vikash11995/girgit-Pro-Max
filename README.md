# girgit-Pro-Max
```code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Girgit Pro Max</title>
</head>
<style>
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    nav {
        display: flex;
        justify-content: space-around;
        align-items: center;
        background-color: #333;
        color: white;
        position: sticky;
        width: 100%;
        padding: 10px;
        
    }
    nav a{
        text-decoration: none;
        color: white;
        border: 1px solid white;
        padding: 7px;
        border-radius: 5px;
    }
    nav a:hover{
        background-color: white;
        color: black;
    }
    .container{
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
        height: 100vh;
        gap: 10px;
        border:  5px solid #3332;
    }
    #grey{
        width: 100px;
        height: 100px;
        background-color: grey;
        border:  2px solid #3332;
    }
    #red{
        
        width: 100px;
        height: 100px;
        background-color: red;
        border:  2px solid #3332;
    }
    #yellow{
        width: 100px;
        height: 100px;
        background-color: yellow;
        border:  2px solid #3332;
    }
    #brown{
        width: 100px;
        height: 100px;
        background-color: brown;
        border:  2px solid #3332;
    }
    #black{
        width: 100px;
        height: 100px;
        background-color: black;
        border:  2px solid #3332;
    }
    #lightblue{
        width: 100px;
        height: 100px;
        background-color: lightblue;
        border:  2px solid #3332;
    }
    #lavender{
        width: 100px;
        height: 100px;
        background-color: lavender;
        border:  2px solid #3332;
    }
    #aqua{
        width: 100px;
        height: 100px;
        background-color: aqua;
        border:  2px solid #3332;
    }
</style>
<body>
    <nav>
        <a href="index.html"><span>Home</span></a>
        <a href="https://www.youtube.com/shorts/TrnePQcMpqU"><span>Youtube</span></a>
    </nav>
    <div class="container">
        <span id="grey"></span>
        <span id="black"></span>
        <span id="yellow"></span>
        <span id="red"></span>
        <span id="lightblue"></span>
        <span id="lavender"></span>
        <span id="aqua"></span>
        <span id="brown"></span>
    </div>
    <script>
        const colors = document.querySelectorAll('.container span');
        console.log(colors);
        colors.forEach(color => {
            color.addEventListener('click', (e) => {
                console.log(e.target.id);
                document.body.style.backgroundColor = e.target.id;
            });
        });
    </script>
</body>
</html>
```
