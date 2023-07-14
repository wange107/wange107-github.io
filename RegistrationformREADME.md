
<!DOCTYPE html>
<html>
<head>
    <title>Student Registration Form</title>
</head>
<body  bgcolor=”grey”>
    <h2>Student Registration Form</h2>
    <form action="registration_process.php" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required><br><br>

        <label for="telephone">Telephone Number:</label>
        <input type="tel" id="telephone" name="telephone" required><br><br>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>

        <label for="admission_number">Admission Number:</label>
        <input type="text" id="admission_number" name="admission_number" required><br><br>

        <label for="course">Course:</label>
        <select id="course" name="course" required>
            <option value="">Select Course</option>
            <option value="CBIT">CBIT</option>
            <option value="CIT">CIT</option>
        </select><br><br>

        <label for="gender">Gender:</label>
        <input type="radio" id="male" name="gender" value="Male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="Female" required>
        <label for="female">Female</label><br><br>

       <font color=yellow> <input type="submit" value="Submit">	
    </form>
</body>
</html>
