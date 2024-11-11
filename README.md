# Project Responsive Web Design using Bootstrap
## Date: 11-11-2024

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
index.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home - TechMobile</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <link href="styles.css" rel="stylesheet">
</head>
<body>
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="index.html">Tech Mobile</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="index.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="services.html">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Home Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12 text-center">
        <h1>Welcome to Tech Mobile</h1>
      </div>
    </div>
  </div>

  <!-- Image Carousel -->
  <div id="carouselExampleIndicators" class="carousel slide mt-5" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
    </ol>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img class="d-block w-100" src="m1.jpeg" alt="First slide">
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="m2.jpeg" alt="Second slide">
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="m3.jpeg" alt="Third slide">
      </div>
    </div>
    <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>

  <!-- Footer -->
  <footer class="bg-light text-center py-3 mt-5">
    <p>[Atluru Sai Vardhan Reddy - 212221040022]</p>
  </footer>

  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.0.7/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

```
about.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About - MySite</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <link href="styles.css" rel="stylesheet">
</head>
<body>
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="index.html">Tech Mobile</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="index.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="services.html">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- About Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12 text-center">
        <h2>About Us</h2>
        <p>Welcome to TechMobile, your one-stop destination for the latest and greatest in mobile technology. Our journey began with a simple yet powerful vision: to bring cutting-edge mobile devices and exceptional service to our customers, making technology accessible and enjoyable for everyone.</p>
        <p>At TechMobile, we believe in the power of connectivity. Whether you're looking for a top-of-the-line smartphone, a reliable feature phone, or the perfect accessories to complement your device, we have it all. Our wide selection includes products from leading brands such as Apple, Samsung, Xiaomi, OnePlus, and many more.</p>
        <p>What sets us apart is our commitment to quality and customer satisfaction. Our team of knowledgeable and friendly staff is always ready to assist you, offering expert advice and personalized recommendations to help you find the perfect mobile solution. We understand that every customer is unique, and we strive to meet your individual needs with a tailored shopping experience.</p>
        <p>Our store isn't just about selling phones—it's about creating a community of tech enthusiasts. We regularly host events, workshops, and product launches to keep you updated with the latest trends and innovations in the mobile industry. Join us and be a part of a tech-savvy community where you can learn, share, and grow.</p>
        <p>Thank you for choosing TechMobile. We look forward to serving you and helping you stay connected with the world.</p>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-light text-center py-3 mt-5">
    <p>[Atluru Sai Vardhan Reddy - 212221040022]</p>
  </footer>

  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.0.7/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

```
contact.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - MySite</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <link href="styles.css" rel="stylesheet">
</head>
<body>
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="index.html">Tech Mobile</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="index.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="services.html">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Contact Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12 text-center">
        <h2>Contact Us</h2>
        <p>You can reach TechMobile through various convenient ways. Our store is located at 123 Tech Street, Mobile City, India 600001..</p>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-light text-center py-3 mt-5">
    <p>Atluru Sai Vardhan Reddy [212221040022].</p>
  </footer>

  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.0.7/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

```
services.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Services - MySite</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <link href="styles.css" rel="stylesheet">
</head>
<body>
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="index.html">Tech Mobile</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="index.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="services.html">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Services Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12 text-center">
        <h2>Our Services</h2>
        <p>At TechMobile, we offer a comprehensive range of services to meet all your mobile needs. Our mission is to provide you with exceptional support and the latest technology to keep you connected.</p>
        <h3>Mobile Device Sales</h3>
        <p>We stock the latest smartphones, feature phones, tablets, and accessories from top brands such as Apple, Samsung, Xiaomi, OnePlus, and many more. Whether you're looking for the newest model or a budget-friendly option, we've got you covered.</p>
        <h3>Repairs and Maintenance</h3>
        <p>Our experienced technicians are equipped to handle all types of mobile device repairs, including screen replacements, battery issues, software problems, and more. We use only genuine parts to ensure the highest quality of service.</p>
        <h3>Trade-In Program</h3>
        <p>Upgrade your device with ease through our trade-in program. Bring in your old device, and we'll offer you a competitive price towards the purchase of a new one. It's an eco-friendly and cost-effective way to stay up-to-date with technology.</p>
        <h3>Accessories</h3>
        <p>Enhance your mobile experience with our wide selection of accessories, including cases, chargers, headphones, screen protectors, and more. We offer products that combine style and functionality to suit your preferences.</p>
        <h3>Customization</h3>
        <p>Make your device truly yours with our customization services. From personalized cases to custom wallpapers and ringtones, we help you express your unique style through your mobile device.</p>
        
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-light text-center py-3">
    <p>[Atluru Sai Vardhan Reddy - 212221040022]</p>
  </footer>

  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.0.7/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

```
styles.css:
```
body {
    font-family: Arial, sans-serif;
  }
  
  .navbar-brand {
    font-weight: bold;
  }
  
  .navbar-nav .nav-link {
    margin-right: 10px;
  }
  
  .navbar-nav .nav-link:hover {
    color: #0056b3;
  }
  
  .container {
    margin-bottom: 60px; /* Ensure footer stays at the bottom */
  }
  
  .section {
    padding: 60px 0;
  }
  
  img {
    border-radius: 8px;
    margin-bottom: 15px;
  }
  
  .carousel-inner img {
    width: 1%;
    height: 400px; /* Adjust height as needed */
  }
  
  footer {
    background-color: #f8f9fa;
    padding: 20px 0;
    font-size: 1rem;
    color: #666;
    position: absolute;
    bottom: 0;
    width: 100%;
  }

```


## OUTPUT:
![alt text](<Screenshot 2024-11-07 111850.png>)
![alt text](<Screenshot 2024-11-07 111856.png>)
![alt text](<Screenshot 2024-11-07 111902.png>)
![alt text](<Screenshot 2024-11-07 111911.png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
