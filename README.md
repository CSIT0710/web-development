# web-development
<!DOCTYPE html>
<html>
<head>
    <title>Dynamic Website Example</title>
</head>    
</body>

     <h2>Dynamic Background Color Change</h2>

     <button onclick="changeColor()">Change Background color</button>

     <script>
        function changeColor() {
            let colours = ["lightblue", "lightgreen", "lightpink"]
            let randomIndex = Math.floor(Math.random() * colors.length);
            document.body.style.backgroundColor = colors[randomIndex];
        }
     </script>
</body>     
</html>     
