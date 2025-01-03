# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fashion Hub</title>
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .hero-section {
            background-color: #b16d6d;
            padding: 80px 0;
            text-align: center;
        }
        .card img {
            height: 200px;
            object-fit: cover;
        }
        .footer {
            background-color: #4e0404;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
    </style>
</head>
<body >

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">FASHION HUB</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Explore</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Sign In</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Sign Up</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section">
        <h1 >Welcome to Fashion Hub</h1>
        <p>Discover stunning design work and inspiration from creative professionals.</p>
    </section>

    <!-- Featured Shots -->
    <section class="container my-5">
        <h2 class="text-center mb-4">Designs</h2>
        <div class="row">
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="C:\Users\admin\Pictures\Saved Pictures\redgown.jpg" class="card-img-top" alt="Shot 1">
                    <div class="card-body">
                        <h5 class="card-title">The Classic RED ball gown</h5>
                        <p class="card-text">A perfection as a baddie ball gown</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="C:\Users\admin\Pictures\Saved Pictures\violetgown.jpg" class="card-img-top" alt="Shot 2">
                    <div class="card-body">
                        <h5 class="card-title">Violet Floral Gown</h5>
                        <p class="card-text">Designed for the nature loving girls. With many layers for the puffy look.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="C:\Users\admin\Pictures\Saved Pictures\greengown.jpg" class="card-img-top" alt="Shot 3">
                    <div class="card-body">
                        <h5 class="card-title">Green Gown</h5>
                        <p class="card-text">This design is for the soft girls especially for the spring vibes.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

   
    <!-- Footer -->
    <footer class="footer">
        <p>Created by SWETHA S V</p>
    </footer>

    <!-- Bootstrap JS, Popper.js, and jQuery -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot (57).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
