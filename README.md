# Day - 02 Web Intern Assignment

Registration Form Website

## HTML CODE
```html
<!DOCTYPE html>
<html>
<head>
    <title>Registration Form</title>
    <style>
        h1 {
            font-size: 30px;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }
        form {
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            size: x-small;
            border: 0px solid; 
            padding: 30px;
            max-width: 300px;
            margin: auto;
            border-radius: 10px;
            background-color: #fad6d6;
        }
        input  {
            border: 0px solid;
            padding: 6px;
            max-width: 200px;
            margin: auto;
            border-radius: 30px; 
            
        }
    </style>
</head>
<body align="center">
    <h1>Registration Form</h1>
    <form align="left">
        <label for="firstName">First Name  </label>
        <input type="text" id="firstName" name="firstName" required>
        <br><br>

        <label for="lastName">Last Name </label>
        <input type="text" id="lastName" name="lastName" required>
        <br><br>

        <label for="age">Age </label>
        <input type="number" id="age" name="age" min="18" style="padding: 6px;
            max-width: 60px;">
        <br><br>

        <label for="gender">Gender </label>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label><br><br>

        <label for="phone">Phone Number </label>
        <input type="tel" id="phone" name="phone" minlength="10" required>
        <br><br>

        <label for="email">Email </label>
        <input type="email" id="email" name="email">
        <br><br>
        
        <input type="submit" value="Submit" style="font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif">
        <input type="reset" value="Cancel" style="font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif">
    </form>
</body>
</html>

```
