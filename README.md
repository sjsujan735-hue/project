# Project Responsive Web Design using Bootstrap
# Date:22/12/25
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribble</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="style css.css">
</head>
<body>
  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand text-white" href="#">Dribble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Services</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <nav class="sorting-navbar">
    <div class="container d-flex justify-content-center">
      <ul class="nav">
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
    <div class="row g-4">
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="c:\Users\admin\Downloads\download.jpeg" class="card-img-top" alt="Placeholder">
          <div class="card-body">
            <h6 class="card-title">Card 1</h6>
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="c:\Users\admin\Downloads\download (12).jpeg" class="card-img-top" alt="Placeholder">
          <div class="card-body">
            <h6 class="card-title">Card 2</h6>
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="c:\Users\admin\Downloads\images (6).jpeg" class="card-img-top" alt="Placeholder">
          <div class="card-body">
            <h6 class="card-title">Card 3</h6>
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="c:\Users\admin\Downloads\images (2).jpeg" class="card-img-top" alt="Placeholder">
          <div class="card-body">
            <h6 class="card-title">Card 4</h6>
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="c:\Users\admin\Downloads\download (14).jpeg" class="card-img-top" alt="Placeholder">
          <div class="card-body">
            <h6 class="card-title">Card 5</h6>
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="c:\Users\admin\Downloads\images (5).jpeg" class="card-img-top" alt="Placeholder">
          <div class="card-body">
            <h6 class="card-title">Card 6</h6>
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="c:\Users\admin\Downloads\images (4).jpeg" class="card-img-top" alt="Placeholder">
          <div class="card-body">
            <h6 class="card-title">Card 7</h6>
          </div>
        </div>
      </div>
      <div class="col-6 col-md-3">
        <div class="card">
          <img src="c:\Users\admin\Downloads\sddefault (1).jpg" class="card-img-top" alt="Placeholder">
          <div class="card-body">
            <h6 class="card-title">Card 8</h6>
          </div>
        </div>
      </div>
    </div>
  </div>

  <section id="contact" class="contact-section">
    <div class="container">
      <h2>Contact Us</h2>
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

  <footer class="text-center py-3">
    <p>&copy; 2024 Dribble. All rights reserved.</p>
  </footer>
</body>
</html>

css
body {
  background: linear-gradient(lightblue, teal);
}
.navbar {
  background-color:black;
}
.navbar .nav-link {
  color: white;
  font-weight: bold;
  margin: 0 10px;
}
.navbar .nav-link:hover {
  color: #16a085;
}
.sorting-navbar {
  background-color:black;
  color: white;
  padding: 10px 0;
}
.sorting-navbar .nav-link {
  color: white;
  font-weight: bold;
  margin: 0 10px;
  border: 2px solid transparent;
  border-radius: 5px;
  padding: 5px 15px;
}
.sorting-navbar .nav-link:hover {
  background-color: #2c3e50;
  border-color: white;
}
.card {
  border: none;
  border-radius: 15px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  transition: transform 0.3s, box-shadow 0.3s;
}
.card:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
}
.card img {
  height: 150px;
  /* width: 150px; */
  background-size: cover;
  border-top-left-radius: 15px;
  border-top-right-radius: 15px;
}
.card-body {
  background-color: black;
  color: white;
  text-align: center;
}
footer {
  margin-top: 50px;
  background-color:black;
  color: white;
}

.about-section {
  background-color: #ecf0f1;
  padding: 50px 20px;
}
.about-section h2 {
  font-size: 2.5rem;
  font-weight: bold;
  color: #2c3e50;
}

/* Services Section */
.services-section {
  background-color: #eab2ef;
  color: white;
  padding: 50px 20px;
}
.services-section h2 {
  font-size: 2.5rem;
  font-weight: bold;
}
.service-card {
  border: none;
  border-radius: 10px;
  background-color: white;
  color:black;
  text-align: center;
  padding: 20px;
  transition: transform 0.3s, box-shadow 0.3s;
}
.service-card:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
}
# OUTPUT:
<img width="1920" height="1200" alt="398783840-6257707b-b13e-4a7c-8b59-34519c919956 `1" src="https://github.com/user-attachments/assets/04c09039-477b-43a1-8bb8-24f4ac822bc6" />
<img width="1920" height="1200" alt="398783513-68c88916-06a1-435c-839a-5c43159d87cb" src="https://github.com/user-attachments/assets/2bb849e0-5fa9-407b-baf4-327e0a7a662e" />

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
