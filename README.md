# kys
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image and Table Page</title>
    <style>
        body {
            font-family: sans-serif;
            text-align: center;
            margin: 20px;
        }
        img {
            max-width: 100%;
            height: auto;
            border: 2px solid #333;
            margin-bottom: 20px;
        }
        table {
            width: 50%;
            margin: 0 auto 20px auto;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
        .home-button {
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            border: none;
            cursor: pointer;
            text-decoration: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <h1>Welcome to the Sample Page</h1>

    <!-- Image Section -->
    <h2>Our Image</h2>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQVKIfjuuicGUFmAjpJ8HgmemeuuMXqrPSYrg&s" alt="leather">

    <!-- Table Section -->
    <h2>Data Table</h2>
    <table>
        <thead>
            <tr>
                <th>cost per foot</th>
                <th>cost per yrd</th>
                <th>cost per hide</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1ft, x 10$</td>
                <td>2ft, x 9$</td>
                <td>3ft, x 7$</td>
            </tr>
            <tr>
                <td>1yrd, x 10S</td>
                <td>2yrd, x 9$</td>
                <td>3yrd, x 7$</td>
            </tr>
            <tr>
                <td>1 hide, x 10$</td>
                <td>2 hide, x 9$</td>
                <td>3 hide, x 7$</td>
            </tr>
        </tbody>
    </table>

 
    <a href="https://elicair.github.io/expir/" class="home-button">Go to Home Page</a>

</body>
</html>
