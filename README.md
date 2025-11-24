# Project Responsive Web Design using Bootstrap
## Date:20-11-2025

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
Design a navigation bar with links: Inspiration, Find Work, Learn Design, Go Pro, Sign In, Sign Up.

### Step 5:
Add a catchy headline with a search bar.

### Step 6:
Use ```<div>``` containers for each dribbble shot thumbnail.

### Step 7:
Include designer name and likes count below each image.

### Step 8:
Include text like “Find your next design inspiration” with a button (“Join Dribbble” or “Explore”).

### Step 9:
Create a footer with your name and register number.

### Step 10:
Publish the website in the LocalHost.

## PROGRAM :
```html
<html>
    <title>DRIBBLE</title>
    <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
            <div class="container">
                <a class="navbar-brand fs-1 fw-bold" href="#">DRIBBLE</a>
                <div class="d-flex">
                    <a class="nav-link btn btn-light mx-2 text-primary" href="#">Home</a>
                    <a class="nav-link btn btn-light mx-2 text-primary" href="#">About</a>
                    <a class="nav-link btn btn-light mx-2 text-primary" href="#">Contact</a>
                </div>
            </div>
        </nav>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <div class="container">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" href="#">Popular</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Newest</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Random</a>
                    </li>
                </ul>
            </div>
        </nav>
        <div class="container my-5">
            <div class="row row-cols-1 row-cols-sm-2 row-cols-md-4 g-4">
                <div class="col">
                    <div class="card">
                        <img src="1.jpg" class="card-img-top" alt="Placeholder">
                        <div class="card-body">
                            <h6 class="card-title">Joker</h6>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="2.jpeg" class="card-img-top" alt="Placeholder">
                        <div class="card-body">
                            <h6 class="card-title">Kill Bill</h6>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="3.jpg" class="card-img-top" alt="Placeholder">
                        <div class="card-body">
                            <h6 class="card-title">Hobbit</h6>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="4.webp" class="card-img-top" alt="Placeholder">
                        <div class="card-body">
                            <h6 class="card-title">Inglorius Bastards</h6>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="5.jpg" class="card-img-top" alt="Placeholder">
                        <div class="card-body">
                            <h6 class="card-title">Forest Gump</h6>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="6.jpg" class="card-img-top" alt="Placeholder">
                        <div class="card-body">
                            <h6 class="card-title">Ready Player One</h6>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="7.jpg" class="card-img-top" alt="Placeholder">
                        <div class="card-body">
                            <h6 class="card-title">Jurassic Park</h6>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card">
                        <img src="8.jpg" class="card-img-top" alt="Placeholder">
                        <div class="card-body">
                            <h6 class="card-title">Insidious</h6>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <section id="contact" class="contact-section py-5 bg-light">
            <div class="container">
                <h2 class="text-center mb-4">Contact Us</h2>
                <form>
                    <div class="mb-3">
                        <label for="name" class="form-label">Your Name</label>
                        <input type="text" class="form-control" id="name" placeholder="Enter your name">
                    </div>
                    <div class="mb-3">
                        <label for="email" class="form-label">Your Email</label>
                        <input type="email" class="form-control" id="email" placeholder="Enter your email">
                    </div>
                    <div class="mb-3">
                        <label for="message" class="form-label">Message</label>
                        <textarea class="form-control" id="message" rows="3" placeholder="Your message"></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Send</button>
                </form>
            </div>
        </section>
        <footer class="bg-dark text-white text-center py-3">
            <p>&copy; Designed and Developed by KAMLESH Y</p>
        </footer>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
    </body>
</html>
```
## OUTPUT:

<img width="1837" height="1084" alt="image" src="https://github.com/user-attachments/assets/b11dfb9e-6148-4e9d-9403-0688cba215c6" />

<img width="1842" height="1083" alt="image" src="https://github.com/user-attachments/assets/1389fa44-5daa-43bf-b50e-40605ecef33f" />

## RESULT:
The project for responsive web design in creating a clone of dribble.com is completed successfully.
