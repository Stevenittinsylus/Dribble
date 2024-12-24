# Project Responsive Web Design using Bootstrap
## Date: 24/12/24

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
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body>
         <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">SUDHA MEDICALS</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#products">Products</a></li>
          <li class="nav-item"><a class="nav-link" href="#about">About Us</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <div class="container mt-5">
    <div class="jumbotron text-center bg-light p-5">
      <h1>SUDHA MEDICALS</h1>
      <p>Your trusted partner in healthcare solutions.</p>
      <img src="pharmacy.jpg" height="450" width="1200">
    </div>
  </div>
   <!-- Footer -->
   <footer class="bg-primary text-white text-center py-3">
    <p>Designed and Developed by steve sylus(24001421)</p>
  </footer>

  <!-- Products Section -->
  <div id="products" class="container my-5">
    <h2>Our Featured Products</h2>
    <div class="row">
      <div class="col-md-4">
        <div class="card">
          <img src="vit c.webp" class="card-img-top" alt="Product 1">
          <div class="card-body">
            <h5 class="card-title">VITAMIN C TABLET</h5>
            <p class="card-text">vitaminc is s nutient supplement</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="c:\Users\admin\Downloads\clindac.jpg" class="card-img-top" alt="Product 2">
          <div class="card-body">
            <h5 class="card-title">clindac gel</h5>
            <p class="card-text">clindac gel is used to treat acne in skin</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="C:\Users\admin\Downloads\cetzine.webp" class="card-img-top" alt="Product 3">
          <div class="card-body">
            <h5 class="card-title">cetzine</h5>
            <p class="card-text">it is used to treat seasonal cold and fever</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>
    </div>
  </div>
   <!-- Footer -->
  <footer class="bg-primary text-white text-center py-3">
    <p>Designed and Developed by steve sylus(24001421)</p>
  </footer>

  <!-- About Us Section -->
  <div id="about" class="container my-5">
    <h2>About Us</h2>
    <p>Welcome to SUDHA MEDICALS, your trusted partner in health and wellness.  
        
        At sudha medicals, we are dedicated to providing you with safe, reliable, and affordable access to medications and healthcare products. With a focus on convenience and quality, we aim to make your online shopping experience seamless, secure, and personalized.  
        We are a team of healthcare professionals, pharmacists, and customer support experts committed to improving access to medications and promoting health for all. Our platform ensures that you get genuine products sourced from certified manufacturers.  
        
        <h3>What We Offer</h3>  
        Prescription Medications: Easy upload and approval of prescriptions for fast delivery.  
        Over-the-Counter Products: A wide range of OTC medicines, supplements, and wellness items.  
        Health Advice: Trusted tips and advice from our certified pharmacists to help you stay informed.  
        Convenient Delivery: Fast and discreet delivery right to your doorstep.  
        
        <h3>Why choose us?</h3>   
        Quality Assurance: Every product undergoes rigorous checks to ensure authenticity and safety.  
        Affordable Prices: Competitive pricing and regular discounts to make healthcare accessible.  
        Customer Support: Friendly and knowledgeable support available to assist you 24/7.  
        Privacy First: Your health information is treated with the utmost confidentiality.  
        
        We are proud to be a reliable healthcare partner for thousands of customers and look forward to serving you.  
        
        <h4>Your health is our priority!</h4>  
        
        Feel free to contact us for any questions or assistance.  
        
    </div>
   <!-- Footer -->
   <footer class="bg-primary text-white text-center py-3">
    <p>Designed and Developed by steve sylus(24001421)</p>
  </footer>

  <!-- Contact Section -->
  <div id="contact" class="container my-5">
    <h2>Contact Us</h2>
    <form>
      <div class="mb-3">
        <label for="name" class="form-label">Name</label>
        <input type="text" class="form-control" id="name" placeholder="Your Name">
      </div>
      <div class="mb-3">
        <label for="email" class="form-label">Email</label>
        <input type="email" class="form-control" id="email" placeholder="Your Email">
      </div>
      <div class="mb-3">
        <label for="message" class="form-label">Message</label>
        <textarea class="form-control" id="message" rows="3" placeholder="Your Message"></textarea>
      </div>
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
  </div>

  <!-- Footer -->
  <footer class="bg-primary text-white text-center py-3">
    <p>Designed and Developed by steve sylus(24001421)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
    </body>
</html>
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/214ff93b-bd2f-469b-b69e-6900c4b10172)
![image](https://github.com/user-attachments/assets/2b6faf4d-6018-4ed8-b571-632dbf40f58c)
![image](https://github.com/user-attachments/assets/d1224cee-e748-4013-bb27-42db59b04482)
![image](https://github.com/user-attachments/assets/17faeffb-cbf9-46b2-ae16-8077d40d3e72)







## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
