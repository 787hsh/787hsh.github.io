<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Simple Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 20px;
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
            margin: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <h1>Welcome to Your Simple Website</h1>

    <button onclick="redirectToInstructables()">Instructables</button>
    <button onclick="download()">Download</button>
    <button onclick="contact()">Contact</button>

    <script>
        function redirectToInstructables() {
            // You can replace this URL with the actual link to your Instructables page
            window.location.href = 'https://www.instructables.com/';
        }

        function download() {
            // You can replace this URL with the actual link to your download page
            window.location.href = 'https://www.example.com/download';
        }

        function contact() {
            // You can replace this URL with the actual link to your contact page
            window.location.href = 'https://www.example.com/contact';
        }
    </script>

</body>
</html>
