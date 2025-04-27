<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration and Contacts Page with Multimedia</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        table, th, td {
            border: 1px solid black;
            border-collapse: collapse;
            padding: 8px;
        }
        h1, h2 {
            color: #4CAF50;
        }
    </style>
</head>

<body>

    <!-- Main Heading -->
    <h1>Welcome to Our Webpage!</h1>

    <!-- Ordered List with Roman Numerals -->
    <h2>Our Services</h2>
    <ol type="I">
        <li>E-commerce Platform</li>
        <li>Inventory Collection</li>
        <li>Community Selling</li>
        <li>Producer-Consumer Connection</li>
        <li>Logistics Support</li>
    </ol>

    <!-- External Image from Pexels -->
    <h2>Our Community</h2>
    <img src="https://images.pexels.com/photos/3184436/pexels-photo-3184436.jpeg" 
         alt="Community Team" 
         width="600">

    <!-- Table of Contacts -->
    <h2>Team Contacts</h2>
    <table>
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
                <td>Jane Doe</td>
                <td>123 Main St, NY</td>
                <td>+1 555-1234</td>
                <td>jane@example.com</td>
            </tr>
            <tr>
                <td>John Smith</td>
                <td>456 Market St, CA</td>
                <td>+1 555-5678</td>
                <td>john@example.com</td>
            </tr>
            <tr>
                <td>Emily Johnson</td>
                <td>789 Elm St, TX</td>
                <td>+1 555-8765</td>
                <td>emily@example.com</td>
            </tr>
            <tr>
                <td>Michael Brown</td>
                <td>321 Oak St, FL</td>
                <td>+1 555-4321</td>
                <td>michael@example.com</td>
            </tr>
            <tr>
                <td>Sarah Davis</td>
                <td>654 Pine St, WA</td>
                <td>+1 555-6789</td>
                <td>sarah@example.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Audio Element -->
    <h2>Listen to Our Theme Music 🎵</h2>
    <audio controls>
        <source src="your-audio-file.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <!-- Video Element -->
    <h2>Watch Our Story 🎬</h2>
    <video width="600" controls>
        <source src="your-video-file.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="post">

        <!-- Name Field -->
        <label for="name">Full Name:</label><br>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

        <!-- Email Field -->
        <label for="email">Email Address:</label><br>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

        <!-- Password Field -->
        <label for="password">Password:</label><br>
        <input type="password" id="password" name="password" placeholder="Create a password" minlength="6" required><br><br>

        <!-- Date Field -->
        <label for="dob">Date of Birth:</label><br>
        <input type="date" id="dob" name="dob" required><br><br>

        <!-- Dropdown Field -->
        <label for="role">Select Your Role:</label><br>
        <select id="role" name="role" required>
            <option value="">--Select--</option>
            <option value="producer">Producer</option>
            <option value="distributor">Distributor</option>
            <option value="customer">Customer</option>
        </select><br><br>

        <!-- Radio Buttons -->
        <label>Gender:</label><br>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label><br>

        <input type="radio" id="female" name="gender" value="female" required>
        <label for="female">Female</label><br>

        <input type="radio" id="other" name="gender" value="other" required>
        <label for="other">Other</label><br><br>

        <!-- Checkboxes -->
        <label>Interests:</label><br>
        <input type="checkbox" id="ecommerce" name="interests" value="ecommerce">
        <label for="ecommerce">E-commerce</label><br>

        <input type="checkbox" id="logistics" name="interests" value="logistics">
        <label for="logistics">Logistics</label><br>

        <input type="checkbox" id="technology" name="interests" value="technology">
        <label for="technology">Technology</label><br><br>

        <!-- Submit Button -->
        <input type="submit" value="Register">
    </form>

</body>
</html>

