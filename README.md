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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Week 2 Assignment</title>
</head>
<body>
       
       <header>
        <h1>Welcome to My Web Page</h1>
    </header>

    
    <section>
        <h2>Ordered List</h2>
        <ol type="I">
            <li>Apple</li>
            <li>Guava</li>
            <li>Banana</li>
            <li>Orange</li>
            <li>PineApple</li>
        </ol>
    </section>

    
    <section>
        <h2>Beautiful Scenery</h2>
        <img src="https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg" alt="Scenery Image" width="500">
    </section>

    
    <section>
        <h2>Contact List</h2>
        <table border="1">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Tayanwa Stephen</td>
                    <td>Gbeleaje Esatate, Shagari, Akure</td>
                    <td>+2347063861754</td>
                    <td>stephen.tayanwa@gmail.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Elm St, LA</td>
                    <td>+1 987 654 321</td>
                    <td>jane@gmail.com</td>
                </tr>
                <tr>
                    <td>Mike Johnson</td>
                    <td>789 Oak St, TX</td>
                    <td>+1 555 678 234</td>
                    <td>mike@gmail.com</td>
                </tr>
                <tr>
                    <td>Emily Davis</td>
                    <td>321 Pine St, FL</td>
                    <td>+1 678 345 890</td>
                    <td>emily@gmail.com</td>
                </tr>
                <tr>
                    <td>David Wilson</td>
                    <td>654 Cedar St, WA</td>
                    <td>+1 890 123 456</td>
                    <td>david@gmail.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="POST">
            
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
            <br><br>

            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br><br>

            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required>
            <br><br>

            
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br><br>

            <
            <select id="country" name="country" required>
                <option value="">Select your country</option>
                <option value="nigeria">Nigeria</option>
                <option value="usa">USA</option>
                <option value="canada">Canada</option>
                <option value="uk">UK</option>
                <option value="australia">Australia</option>
            </select>
            <br><br>

            
            <p>Gender:</p>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label>
            <br><br>

            
            <p>Select Your Interests:</p>
            <input type="checkbox" id="Travelling" name="interests" value="Travelling">
            <label for="coding">Travelling</label>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label>
            <br><br>

        
            <input type="submit" value="Register">
        </form>
    </section>

    
    <footer>
        <p>Contact: trapidhub@gmail.com</p>
        <p>Phone: +234 7063861754</p>

    </footer>
</body>
</html>
