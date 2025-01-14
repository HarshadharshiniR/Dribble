# Project Responsive Web Design using Bootstrap
## Date:31/12/2024

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
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-dark text-light">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble Clone</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#home">home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#features">Features</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                    <li class="nav-item">
                        <a href="#signup" class="btn btn-success ms-2">Sign Up</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    
    <section class="text-center py-5 bg-secondary">
        <div class="container ">
            <h1 class="display-4 text-light">Discover Creative Works</h1>
            <p class="lead text-light">Explore and share inspiring designs from creators around the world.</p>
        </div>
    </section>
    <section class="py-5 bg-dark">
        <div class="container">
            <div class="row">
            <h2 class="text-light text-center mb-4">Our Featured Works</h2>
                <div class="col-md-3">
                    <img src="accesories.jpeg" height="300px" width="300px"  alt="Work 1" >
                    </div>
                    <div class="col-md-3"><img src="haircare.jpeg" height="300px" width="300px"  alt="Work 2"></div>
                    <div class="col-md-3"><img src="footwear.webp" height="300px" width="300px"  alt="Work 3"></div>
                    <div class="col-md-3"><img src="handbags.webp" height="300px" width="300px"  alt="Work 4"></div>
                    <div class="col-md-3"><img src="jewellery.jpeg" height="300px" width="300px"  alt="Work 5"></div>
                    <div class="col-md-3"><img src="skincare.webp" height="300px" width="300px"  alt="Work 6"></div>
                    <div class="col-md-3"><img src="perfume.jpeg" height="300px" width="300px"  alt="Work 7"></div>
                    <div class="col-md-3"><img src="watches.jpeg" height="300px" width="300px"  alt="Work 8"></div>

                </div>
                </div>
                
    </section>
    
    <footer class="bg-dark text-light py-3">
        <div class="container text-center">
            <p>&copy; Designed and developed by HarshaDharshini &copy;2024</p>
        </div>
    </footer>

</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot (43).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
