exp 1
<!DOCTYPE html>
<html>
<head>
    <title>Student Registration Form</title>
</head>
<body>
    <h2>Student Registration Form</h2>
    <form action="/submit_registration" method="POST">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        
        <label for="age">Age:</label><br>
        <input type="number" id="age" name="age" min="1" required><br><br>
        
        <input type="submit" value="Register">
    </form>
</body>
</html>
