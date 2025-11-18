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
    <title>Creative Shots – Yashwanth</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body class="bg-light">

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg bg-white shadow-sm py-3">
    <div class="container">
        <a class="navbar-brand fw-bold text-primary">CreativeShots</a>

        <div class="ms-auto">
            <a class="btn btn-outline-primary btn-sm">Login</a>
        </div>
    </div>
</nav>

<!-- MAIN SECTION -->
<div class="container mt-5">
    <div class="row align-items-start">

        <!-- LEFT – IMAGE LIST (DIFFERENT CARD LOOK) -->
        <div class="col-md-6">

            <!-- Item 1 -->
            <div class="d-flex bg-white p-3 shadow-sm rounded mb-4">
                <img src="https://picsum.photos/270" class="rounded me-3" width="150" height="120">
                <div>
                    <h6 class="fw-bold mb-1">Nature Concept</h6>
                    <p class="text-muted small mb-0">Warm tones and soft lighting for calm visuals.</p>
                </div>
            </div>

            <!-- Item 2 -->
            <div class="d-flex bg-white p-3 shadow-sm rounded mb-4">
                <img src="https://picsum.photos/271" class="rounded me-3" width="150" height="120">
                <div>
                    <h6 class="fw-bold mb-1">Urban UI Layout</h6>
                    <p class="text-muted small mb-0">A clean layout idea inspired by city colors.</p>
                </div>
            </div>

            <!-- Item 3 -->
            <div class="d-flex bg-white p-3 shadow-sm rounded mb-4">
                <img src="https://picsum.photos/272" class="rounded me-3" width="150" height="120">
                <div>
                    <h6 class="fw-bold mb-1">Frost Illustration</h6>
                    <p class="text-muted small mb-0">Soft gradients for winter-themed art.</p>
                </div>
            </div>

        </div>

        <!-- RIGHT – HERO TEXT -->
        <div class="col-md-6 ps-md-5 mt-4 mt-md-0">
            <h1 class="fw-bold">Browse Stunning Visual Shots</h1>
            <p class="text-muted mt-2 mb-4">
                Explore design ideas, color palettes, creative layouts and fresh concepts crafted by designers.
            </p>

            <a class="btn btn-primary px-4 py-2">View Gallery</a>

            <h5 class="fw-bold mt-5">Trending Shots</h5>
            <p class="text-muted small">Updated daily with new creative ideas.</p>
        </div>

    </div>
</div>

<!-- FOOTER -->
<footer class="bg-dark text-center text-white py-3 mt-5">
    <small>Designed by Yashwanth ASV</small>
</footer>

</body>
</html>
```


## OUTPUT:

<img width="1917" height="1049" alt="image" src="https://github.com/user-attachments/assets/35704afb-fa1f-4947-bbba-92eed77c6d01" />

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
