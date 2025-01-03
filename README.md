# Project Responsive Web Design using Bootstrap
## Date:24/12/2024

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
<html>

<head>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>

<body
    style="background-image: url(download\ \(2\).gif); max-height: 100hv;width: 100%; background-repeat: no-repeat; background-size: 100%;">

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark ">
        <div class="container-fluid">

            <a class="navbar-brand" href="https://www.google.co.in/" title="google.com "
                style="font-family: fantasy;">Dribble Website</a>

            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse  " id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item"><a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="about.html">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <br><br><br>
    <div class="container-fluid  " style="text-align: center;">
        <h1 class=" align-middle display-1 text-danger"><br> <b>WELCOME TO DIGITAL WORLD <br> </b> COME AND TRY</h1><br>
        <button type="button" class="btn btn-primary btn-lg" href="service.html">TRY IT</button> <br>
        <br>
        <p class="text-secondary"> <b></b></p>
    </div>
    <div class="container-fluid bg-info">
        <div class="d-flex justify-content-center mt-5 pt-5">
            <div class="col-lg-3">
                <img src="laptop 2.jpg" alt="this is first background-image" class="img-thumbnail w-75 h-75 rounded">
            </div>
            <div class="col-lg-3">
                <img src="phone image.avif" alt="this is first background-image" class="img-thumbnail w-75 h-75 rounded">
            </div>
            <div class="col-lg-3">
                <img src="smart watch image.webp" alt="this is first background-image" class="img-thumbnail w-75 h-75 rounded ">
            </div>
            <div class="col-lg-3">
                <img src="head phone 2.jpg" alt="this is first background-image" class="img-thumbnail w-75 h-75 rounded ">
            </div>
        </div>
    </div>
    <footer class="bg-dark text-light text-center py-3">
        <div class="container">
            <h1>&copy; Designed and develeped by SANTHA BABU G</h1>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
        crossorigin="anonymous"></script>
</body>

</html>

```

## OUTPUT:
![alt text](<Screenshot (93).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
