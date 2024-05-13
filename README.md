# Project Responsive Web Design using Bootstrap
## Date:13/04/24

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


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
# home.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> Pharmaceutical Company</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">QnQ Pharmaceutical Company</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              Products
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
              <a class="dropdown-item" href="#">Medicines</a>
              <a class="dropdown-item" href="#">Supplements</a>
              <a class="dropdown-item" href="#">Vacines</a>
            </div>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Content Sections -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-6">
        <h2>Welcome to Our QnQ Pharmacy Company</h2>
        <p>'QnQ'healthcare provide ltd is dedicated to providing the generic drugs to those in need.</p>
      </div>
      <div class="col-md-6">
        <img src="pharmacy.jpeg" alt="Pharmaceutical Company" height="300" width="'400">
      </div>
    </div>
    <div class="row mt-5">
      <div class="col-md-4">
        <h3>Our Products</h3>
        <p>Explore our range of high-quality pharmaceutical products.Our pharmacy offers a diverse selection of medicines to address various health concerns.</p>
        <a href="#" class="btn btn-primary">View Products</a>
      </div>
      <div class="col-md-4">
        <h3>Responsibility</h3>
        <p>We are commited to delivering the best possible healthcare experience for all our costomers.Dispensing medications accurately and safely, including interpreting prescriptions and providing dosage instructions.
         </p>
        <a href="#" class="btn btn-primary">Read more</a>
      </div>
      <div class="col-md-4">
        <h3>Contact Us</h3>
        <p>Always keep in touch with us for any inquiries or feedback for our Company.</p>
        <a href="#" class="btn btn-primary">Contact Us</a>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-light mt-5 py-3">
    <div class="container text-center">
      <p>&copy; 2024 QnQ Pharmacy Company BY NANDHIKA P(212223040125).</p>
    </div>
  </footer>

  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

# product.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Products</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
    .rounded-img {
      border-radius: 50%;
      overflow: hidden;
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">QnQ Pharmacy</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Product Content -->
  <div class="container mt-5">
    <h2 class="text-center mb-4">Our Products</h2>
    <div class="row">
      <div class="col-md-4">
        <div class="card mb-4">
          <img src="cough-syrup.webp" class="card-img-top rounded-img" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Product 1</h5>
            <p class="card-text">Cough plays an important role in clearing irritants and infections from your body, but it can be annoying when the cough persists.</p>
            <a href="#" class="btn btn-primary btn-block">Buy Now</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card mb-4">
          <img src="injuct.webp" class="card-img-top rounded-img" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Product 2</h5>
            <p class="card-text">Your healthcare provider can prescribe manufactured insulin that you take through an injection (shot), injectable pen or pump.</p>
            <a href="#" class="btn btn-primary btn-block">Buy Now</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card mb-4">
          <img src="tablet.jpeg" class="btn btn-primary btn-block" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Product 3</h5>
            <p class="card-text">It comprises a mixture of active substances and excipients, usually in powder form, that are pressed or compacted into a solid dose.</p>
            <a href="#" class="btn btn-primary btn-block">Buy Now</a>
          </div>
        </div>
      </div>
    </div>
  </div>
<!--footer-->
  <footer class="bg-dark text-light mt-5 py-3">
    <div class="container text-center">
      <p>&copy; 2024 QnQ Pharmacy Company BY NANDHIKA P(212223040125).</p>
    </div>
  </footer>

  <!-- Bootstrap JS dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

# about.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Us</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">QnQ Pharmacy</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- About Content -->
  <div class="container mt-5">
    <h2>About Us</h2>
    <p>Hello everyone,</p>
    <p>This is MD of QnQ Healthcare Pvt Ltd, Four years ago we started our company with a grand vision of creating a Society Centric business that would alleviate the extreme financial hardships faced by certain sections of our society in accessing quality healthcare services.</p>
    <p>However, there are alternative drugs that are generics that have the same molecule, strength, dosage, and meet all the quality standards, but cost less... The problem is that people are not aware of this fact. The idea, or rather the myth, that the more expensive a drug is, the better its efficacy and quality, is false. It is not true.</p>
    <p> Our regular customers are enthusiastic and satisfied with our products and services and buy our medicines in large quantities. Our customer base is growing rapidly and we are expanding to different parts of Tamilnadu to meet the demand of our customers and reach out to them.</p>
    <p>After a thorough study of the different facets of the problem, we, a team of 9 Doctors, decided to address this chronic social problem by making available, through our pharmacy, generic drugs that cost less but do not compromise on quality. Thus the research study culminated into a business model and registered as a private limited company - QnQ Healthcare Pvt Ltd company in 2019. The acronym QnQ stands for quality and quantity. All medicines are subjected to stringent quality tests by NABL-affiliated third-party laboratories and are sold at an affordable price, thanks to our valued suppliers and our own pricing policy, which enables our customers to save almost 70% on their medical bills.</p>
    <p>Now the journey continues, with a very dedicated team of professionals we can proudly say that we now have 4 company operated Retail Outlets and 9 Franchise Operated Retail Outlets as of now. We have an ambitious goal to open 100 Retail outlets before the end of this year FY 2023~2024</p>
    <p> Our vision is to provide Quality assured generic medicines to People at an affordable price.</p>
    <p>Thank you for choosing Our QnQ Pharmacy for your healthcare needs. We look forward to serving you!</p>
  </div>
  <!--footer-->
  <footer class="bg-dark text-light mt-5 py-3">
    <div class="container text-center">
      <p>&copy; 2024 QnQ Pharmacy Company BY NANDHIKA P(212223040125).</p>
    </div>
  </footer>

  <!-- Bootstrap JS dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

# contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">QnQ Pharmacy</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Contact Content -->
  <div class="container mt-5">
    <h2>Contact Us</h2>
    <p>If you have any inquiries or feedback, please don't esitate to contact us using the form below:</p>
    <form>
      <div class="form-group">
        <label for="inputName">Name</label>
        <input type="text" class="form-control" id="inputName" placeholder="Enter your name">
      </div>
      <div class="form-group">
        <label for="inputPhone">Phone Number</label>
        <input type="tel" class="form-control" id="inputPhone" placeholder="Enter your phone number">
      </div>
      <div class="form-group">
        <label for="inputEmail">Email address</label>
        <input type="email" class="form-control" id="inputEmail" aria-describedby="emailHelp" placeholder="Enter your email">
      </div>
      <div class="form-group">
        <label for="inputMessage">feedback</label>
        <textarea class="form-control" id="inputMessage" rows="5" placeholder="Enter your message"></textarea>
      </div>
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
  </div>

  <!--footer-->
  <footer class="bg-dark text-light mt-5 py-3">
    <div class="container text-center">
      <p>&copy; 2024 QnQ Pharmacy Company BY NANDHIKA P(212223040125).</p>
    </div>
  </footer>

  <!-- Bootstrap JS dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
## OUTPUT:

![Screenshot 2024-05-13 220055](https://github.com/Nandhika05/Pharma/assets/154419402/71e56064-3914-4bfd-9e51-d4d3472591ba)

![Screenshot 2024-05-13 220130](https://github.com/Nandhika05/Pharma/assets/154419402/6cee5d48-1748-45e1-b247-868ceeb5c68e)

![Screenshot 2024-05-13 220158](https://github.com/Nandhika05/Pharma/assets/154419402/a1b45634-1023-4d00-b4a6-10425c968512)

![Screenshot 2024-05-13 220231](https://github.com/Nandhika05/Pharma/assets/154419402/cc8bf5ae-2140-40cd-98c1-288aff2affb1)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
