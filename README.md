# Ex.05 Book Front Cover Page Design
## Date:18.12.2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html>
<head>
    <title>Veil of 1875</title>

    <!-- Old-style serif font -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&display=swap" rel="stylesheet">

    <style>
        body {
            background-color: #111;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: Arial, sans-serif;
        }

        .book {
            width: 400px;
            height: 600px;
            background:
                linear-gradient(rgba(0,0,0,0.55), rgba(0,0,0,0.8)),
                url("bg.jpg");
            background-size: cover;
            background-position: center;
            color: #f2f2f2;
            text-align: center;
            padding: 30px;
            box-sizing: border-box;
            border-radius: 6px;
            box-shadow: 0 0 25px rgba(0,0,0,0.9);
            position: relative;
        }

        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 42px;
            letter-spacing: 2px;
            margin-top: 80px;
        }

        h2 {
            font-size: 18px;
            font-weight: normal;
            color: #d0d0d0;
            margin-top: 15px;
        }

        .author {
            position: absolute;
            bottom: 40px;
            width: 100%;
            left: 0;
            font-size: 16px;
            color: #e5e5e5;
        }
    </style>
</head>
<body>

<div class="book">
    <h1>Veil of 1875</h1>
    <h2>A Mother’s Vow Written in Blood</h2>

    <div class="author">
        Written by<br>
        <strong>Sreejaa</strong>
    </div>
</div>

</body>
</html>

```

## OUTPUT:

<img width="1920" height="1080" alt="Screenshot (2341)" src="https://github.com/user-attachments/assets/fb1852b8-f59e-47c2-b9cf-8400619ad79b" />

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
