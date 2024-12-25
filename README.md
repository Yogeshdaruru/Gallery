# Ex.08 Design of Interactive Image Gallery
# Date:
# AIM:
To design a web application for an inteactive image gallery with minimum five images.

# DESIGN STEPS:
## Step 1:
Clone the github repository and create Django admin interface.

## Step 2:
Change settings.py file to allow request from all hosts.

## Step 3:
Use CSS for positioning and styling.

## Step 4:
Write JavaScript program for implementing interactivity.

## Step 5:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Photo Gallery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            color: #333;
        }

        header {
            background-color: #4682b4;
            color: white;
            padding: 1rem 2rem;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 1rem 0 0;
            display: flex;
            justify-content: center;
            gap: 1rem;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        nav ul li a:hover {
            background-color: #5a9bd6;
        }

        #gallery {
            padding: 2rem;
            text-align: center;
        }

        #gallery h2 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        .photo-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            padding: 1rem;
        }

        .photo-grid a {
            text-decoration: none;
        }

        .photo-grid img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .photo-grid img:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        footer {
            background-color: #4682b4;
            color: white;
            text-align: center;
            padding: 1rem;
            position: absolute;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Interactive Photo Gallery</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#about">About</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section id="gallery">
            <h2>Gallery</h2>
            <div class="photo-grid">
                <a href="C:\Users\admin\OneDrive\Desktop\images (1).jpeg"><img src="C:\Users\admin\OneDrive\Desktop\images (1).jpeg" alt="Photo 1"></a>
                <a href="C:\Users\admin\OneDrive\Desktop\images (2).jpeg"><img src="C:\Users\admin\OneDrive\Desktop\images (2).jpeg" alt="Photo 2"></a>
                <a href="C:\Users\admin\OneDrive\Desktop\images (3).jpeg"><img src="C:\Users\admin\OneDrive\Desktop\images (3).jpeg" alt="Photo 3"></a>
                <a href="C:\Users\admin\OneDrive\Desktop\images (4).jpeg"><img src="C:\Users\admin\OneDrive\Desktop\images (4).jpeg" alt="Photo 4"></a>
                <a href="C:\Users\admin\OneDrive\Desktop\images (5).jpeg"><img src="C:\Users\admin\OneDrive\Desktop\images (5).jpeg" alt="Photo 5"></a>
                <a href="C:\Users\admin\OneDrive\Desktop\images (6).jpeg"><img src="C:\Users\admin\OneDrive\Desktop\images (6).jpeg" alt="Photo 6"></a>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 yogesh's Interactive Photo Gallery. All rights reserved.</p>
    </footer>
</body>
</html>
```
# OUTPUT:
![Screenshot (35)](https://github.com/user-attachments/assets/cc2937b3-99ca-43b3-9e81-060f9b3d68fc)
![Screenshot (36)](https://github.com/user-attachments/assets/fd9cf3ce-1955-4293-83bd-ec96a003cafa)
![Screenshot (37)](https://github.com/user-attachments/assets/55b5358c-0ddb-4f52-b5de-19fcc4b021e3)
![Screenshot (38)](https://github.com/user-attachments/assets/a3cc3b1c-78fb-483c-a3f3-2f30595557b5)
![Screenshot (39)](https://github.com/user-attachments/assets/2168ab90-ae2b-4240-a4c5-f702ed02461d)

# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
