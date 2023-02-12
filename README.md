# registrationform.html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    <link rel="stylesheet" href="./style.css">

</head>
<body>
    <h1>Student Registration Form</h1>
    <div class="main">
    <div class="col">
    <form>

        <h2>Enroll Yourself</h2>

        <div >
            <label for="name">Name: </label>
            <input type="text" id="Name" placeholder="name" name="Name" class="inp">
        </div>

        <div >
            <label for="email">last name:</label>
            <input type="text" id="last name" placeholder="surname" name="Email" class="inp">
        </div>

        <div>
            <label for="website">Email id: </label>
            <input type="text" id="email id" placeholder="www.abc.com" name="email id" class="inp">
        </div>

        <div>
            <label for="Image">Upload Image: </label>
            <input type="file" id="Image" name="Image" class="custom-file-input" onchange="image(event)" class="inp">
        </div>

        <div class="gender">
            <p>Gender: </p>
            <input name="gender" type="radio" id="Male" value="Male">  Male
            <input name="gender" type="radio" id="Female" value="Female">  Female
            <input name="gender" type="radio" id="Others" value="Others">  Others
        </div>

        <div class="skills">
            <p>Skills: </p>
            <input name="html" type="checkbox" value="HTML" id="html"> HTML
            <input name="css" type="checkbox" value="CSS" id="css">  CSS
            <input name="js" type="checkbox" value="JavaScript" id="js">  JavaScript
            <input name="python" type="checkbox" value="Python" id="python">  Python
            <input name="java" type="checkbox" value="Java" id="java">Java
        </div>

        <div class="btn">
            <button type="button" id="btn" class="button">Submit</button>
            <button type="clear" class="button">Clear</button>
        </div>
    </form>
</div>

<div class="col">
    <div class="display">
        <h2 class="h-enrol">Enrolled Students</h2>
        <div class="tp">
        <div class="cards"></div>
    </div>
    </div>
</div>
</div>

<div class="footer">
    @Copyright <a href="https://github.com/GorrelaSupraja?tab=projects" target="_blank">Supraja G</a> 2022 - All Right Reserved
</div>

<script src="./script.js"></script>

</body>
</html>
Footer
