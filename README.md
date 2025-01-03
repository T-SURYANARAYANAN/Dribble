# Project Responsive Web Design using Bootstrap
## Date:25-12-24

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
    <title>Restaurant Website</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-light bg-warning">
    <a class="navbar-brand" href="#">Restaurant Name</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
            <li class="nav-item">
                <a class="nav-link" href="#">Home</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Menu</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">About</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Contact</a>
            </li>
        </ul>
    </div>
</nav>

<!-- Hero Section -->
<div class="jumbotron jumbotron-fluid text-center">
    <div class="container">
        <h1 class="display-4">Welcome to Surya's Restaurant</h1>
        <p class="lead">Experience the best culinary delights.</p>
        <a class="btn btn-primary btn-lg" href="#" role="button">Explore Menu</a>
    </div>
</div>

<!-- Menu Section -->
<div class="container mt-5">
    <h2 class="text-center">Our Menu</h2>
    <div class="row">
        <div class="col-md-4">
            <div class="card mb-4">
                <img src="lasagna-5994612_1280.jpg" class="card-img-top" alt="Dish 1">
                <div class="card-body">
                    <h5 class="card-title">Dish 1</h5>
                    <p class="card-text">A delicious description of Dish 1.</p>
                </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card mb-4">
                <img src="restaurant-449952_1280.jpg" class="card-img-top" alt="Dish 2">
                <div class="card-body">
                    <h5 class="card-title">Dish 2</h5>
                    <p class="card-text">A delicious description of Dish 2.</p>
                </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card mb-4">
                <img src="spring-roll-6760871_1280.jpg" class="card-img-top" alt="Dish 3">
                <div class="card-body">
                    <h5 class="card-title">Dish 3</h5>
                    <p class="card-text">A delicious description of Dish 3.</p>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- Footer -->
<footer class="bg-secondary text-center py-4">
    <p>&copy; 2024 Surya's Restaurant    All rights reserved.</p>
</footer>

<!-- Scripts -->
<script src="project/app1/static/lasagna-5994612_1280.jpg"></script>
<script src="project/app1/static/restaurant-449952_1280.jpg"></script>
<script src="project/app1/static/spring-roll-6760871_1280.jpg"></script>
</body>
</html>


```

## OUTPUT:

![alt text](<Screenshot 2024-12-26 135735.png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
