# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

<!DOCTYPE html>
<html>
<head>
    <title>web assignment week 2</title>
</head>
<body>
    <h1>Html lists</h1>
    <h3>ordered list</h3>
    <ol type="i" > 
        <li>name</li>
        <li>address</li>
        <li>mobile</li>
        <li>email</li>    
    </ol>
    <h1>HTML IMAGES</h1>
<img src="https://images.pexels.com/photos/19085454/pexels-photo-19085454/free-photo-of-townhouse-entrance-door-with-potted-plants-in-front.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" 
     alt="Image of a front door" 
     width="600">

    <hi>HTML TABLES</hi>
    <table border="1">
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Emails</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Mercy</td>
                <td>202</td>
                <td>567899</td>
                <td>mercyj@gmail.com</td>
            </tr>
            <tr>
                <td>Wanda</td>
                <td>207</td>
                <td>5477852</td>
                <td>wanda@gmail.com</td>
            </tr>
            <tr>
                <td>jay</td>
                <td>2023</td>
                <td>568733</td>
                <td>jay@gmail.com</td>
            </tr>
            <tr>
                <td>shee</td>
                <td>2022</td>
                <td>589219</td>
                <td>shee@gmail.com</td>
            </tr>
            <tr>
                <td>hamiy</td>
                <td>2102</td>
                <td>5214569</td>
                <td>hamiy@gmail.com</td>
            </tr>
        </tbody>
        
    </table>
    <h1>FORM</h1>
<form action="" method="post">
    
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" placeholder="Enter Name" required>
    <br><br>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" placeholder="Enter Email" required>
    <br><br>

    <label for="password">password:</label>
    <input type="password" id="password" name="password" placeholder="Enter password" required>
    <br><br>

    <label for="dob">Date of Birth:</label>
    <input type="date" id="dob" name="dob" required>
    <br><br>

    

    <button type="submit">Submit</button>

</form>

    </form>
</body>

</html>
