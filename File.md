<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: linear-gradient(270deg, #1e1e3f, #004aad, #00c3ff);
            color: white;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            width: 400px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.2);
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(255, 255, 255, 0.3);
        }

        input, select, button {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
        }

        button {
            background: #ff4b2b;
            color: white;
            cursor: pointer;
        }

        button:hover {
            background: #ff416c;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>Register</h2>
        <form>
            <input type="text" placeholder="Full Name" required>
            <input type="email" placeholder="Email" required>
            <input type="password" placeholder="Password" required>
            <input type="date" required>
            <button type="submit">Sign Up</button>
        </form>
    </div>

</body>
</html>
