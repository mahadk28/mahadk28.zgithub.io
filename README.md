<!DOCTYPE html>
<html lang="en">
    <head>
        <link rel="stylesheet" href="./styles.css">
        
    </head> 
    <body>
        <div class="container">
            <div >
                <h1 class = "header_text">Hi Boyas, Would you like to be my Valentines??</h1>
                <h1 class = "header_text">BY MAHAS></h1>
            </div>
            <div class="gif_container">
                <img src="<iframe src="https://giphy.com/embed/kZqbBT64ECtjy" width="480" height="480" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/hello-kitty-cute-kZqbBT64ECtjy">via GIPHY</a></p>" alt="Cute animated illustration">
            </div>
            <div class = "buttons">
                <button class="btn" id = "yesButton" onclick="nextPage()">Yes</button>
                <button class="btn" id="noButton" onmouseover="moveButton()" onclick="moveButton()">No</button>
                <script>
                    function nextPage() {
                        window.location.href = "yes.html";
                    }
                    
                    function moveButton() {
                        var x = Math.random() * (window.innerWidth - document.getElementById('noButton').offsetWidth) - 85;
                        var y = Math.random() * (window.innerHeight - document.getElementById('noButton').offsetHeight) - 48;
                        document.getElementById('noButton').style.left = `${x}px`;
                        document.getElementById('noButton').style.top = `${y}px`;
                    }
                </script> 
            </div>
        </div>
       
    </body> 
</html>
