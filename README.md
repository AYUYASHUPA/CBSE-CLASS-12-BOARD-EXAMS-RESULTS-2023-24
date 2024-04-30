# CBSE-CLASS-12-BOARD-EXAMS-RESULTS-2023-24
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Board Exams Results 2024</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            text-align: center;
            margin-bottom: 20px;
        }
        #logo {
            width: 150px;
            height: auto;
        }
        #banner {
            width: 100%;
            height: auto;
            margin-bottom: 20px;
        }
        form {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        input[type="text"],
        input[type="number"],
        input[type="submit"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        input[type="submit"] {
            background-color: #4caf50;
            color: #fff;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
        .result-img {
            text-align: center;
            margin-top: 20px;
        }
        .result-img img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <img id="logo" src="path_to_your_logo_image.png" alt="Logo">
            <img id="banner" src="path_to_your_banner_image.png" alt="Banner">
            <h1>Board Exams Results 2024</h1>
        </header>
        <form id="resultForm" onsubmit="return showResult()">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="roll">Roll Number:</label>
            <input type="number" id="roll" name="roll" required>
            <input type="submit" value="Submit">
        </form>
        <div class="result-img" id="resultImg" style="display: none;">
            <img src="path_to_predefined_image.png" alt="Result Image">
        </div>
    </div>

    <script>
        function showResult() {
            var name = document.getElementById("name").value.toUpperCase();
            var roll = document.getElementById("roll").value;
            if (name === "AYUSHMAN YASHVARDHAN UPADHYAY" && roll === "22637917") {
                document.getElementById("resultImg").style.display = "block";
            } else {
                alert("Invalid name or roll number.");
            }
            return false; // Prevent form submission
        }
    </script>
</body>
</html>
