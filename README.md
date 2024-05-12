## Date:12.05.2024

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pharma Company</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Pharma Company</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#" onclick="showSection('home')">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#" onclick="showSection('about')">About</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                            data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            Products
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <a class="dropdown-item" href="#" onclick="showSection('product')">Medicines</a>
                        </div>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#" onclick="showSection('contact')">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <div id="home" class="container my-5">
        <h1>Welcome to Pharma Company</h1>
        <p>At PharmaCure Pharmaceuticals, we are dedicated to enhancing lives through innovative healthcare solutions. As a leading pharmaceutical company, we strive to deliver high-quality medications and healthcare products to meet the diverse needs of patients worldwide.

          <h2>Our Commitment to Excellence</h2>
          
          With a relentless commitment to excellence, we adhere to the highest standards of quality, safety, and efficacy in everything we do. From research and development to manufacturing and distribution, we prioritize precision and integrity to ensure that our products consistently meet regulatory requirements and exceed customer expectations.
          <br>
          <br>
          <h2>Innovative Research and Development</h2>
          
          Driven by a passion for innovation, our dedicated team of scientists and researchers continually explore new frontiers in pharmaceutical science. Through cutting-edge research and development initiatives, we aim 
          <br>
          <br>
          
        <h2> Product Portfolio</h2>
          
          Our comprehensive product portfolio encompasses a wide range of therapeutic areas, including cardiovascular health, respiratory disorders, neurology, oncology, and more. From essential medications to specialized treatments, we offer a diverse array of pharmaceutical products designed to support health and wellness across the lifespan.
          
          
          <h2>Join Us in Advancing Healthcare</h2>
          
          Whether you are a healthcare professional, investor, or potential partner, we invite you to join us in our mission to advance healthcare and improve lives worldwide. Together, we can make a meaningful difference in the lives of patients and communities everywhere.</p>
    </div>

    <div id="about" class="container my-5" style="display: none;">
        <h1>About Us</h1>

         <p> Welcome to PharmaCure Pharmaceuticals, where innovation meets compassion in the pursuit of better health for all. </p>
          
          <h2>Our Mission</h2>
          
          At PharmaCure Pharmaceuticals, our mission is simple yet profound: to enhance lives through innovative healthcare solutions. We are driven by a deep commitment to improving the health and well-being of individuals and communities worldwide. Through our relentless pursuit of excellence in pharmaceutical research, development, and manufacturing, we strive to make a meaningful difference in the lives of patients and healthcare professionals alike.
          
         <h3> Our Vision</h3>
          
          Our vision is to be a global leader in healthcare innovation, renowned for our commitment to quality, integrity, and patient-centric care. We aspire to set new standards of excellence in pharmaceutical science and to revolutionize the way healthcare is delivered and experienced around the world. By leveraging cutting-edge technology, fostering strategic partnerships, and nurturing a culture of creativity and collaboration, we aim to shape the future of healthcare and create lasting value for society.
          
          <h3>Our Values</h3>
          
          At PharmaCure Pharmaceuticals, our values serve as the foundation of everything we do. Integrity, quality, and patient focus are at the core of our business philosophy, guiding our decisions and actions each day. We believe in transparency, honesty, and ethical conduct in all aspects of our operations, from research and development to marketing and distribution. We are committed to upholding the highest standards of safety and efficacy in our products, ensuring that patients can trust in the quality and reliability of our medications.
          
          <h3>Our Commitment to Innovation</h3>
          
          Innovation is the lifeblood of PharmaCure Pharmaceuticals. We are dedicated to pushing the boundaries of pharmaceutical science and exploring new frontiers in healthcare innovation. Our team of scientists, researchers, and healthcare professionals are united by a shared passion for discovery and a relentless pursuit of excellence. Through cutting-edge research, advanced technology, and a spirit of collaboration, we strive to develop groundbreaking treatments and therapies that address unmet medical needs and improve patient outcomes.
          
          <h3>Join Us in Making a Difference</h3>
          
          Whether you are a patient, healthcare professional, investor, or potential partner, we invite you to join us in our mission to advance healthcare and improve lives worldwide. Together, we can harness the power of innovation and compassion to create a healthier, more equitable world for all. Thank you for choosing PharmaCure Pharmaceuticals as your partner in health.</p>
    </div>

    <div id="product" class="container my-5" style="display: none;">
        <div class="row">
            <div class="col-md-6">
                <img src="med.jpg" class="img-fluid" alt="Product Image">
            </div>
            <div class="col-md-6">
                <h2>Cardio care</h2>
                <p>CardioCare is a revolutionary medication designed to support cardiovascular health and promote overall well-being. Formulated with a unique blend of clinically proven ingredients, CardioCare is specifically crafted to address the complex needs of individuals seeking to maintain a healthy heart and circulation.</p>
                <h3>Price: $99.00</h3>
                <button type="button" class="btn btn-primary">Add to Cart</button>
                
            </div>
        </div>
    </div>

    <div id="contact" class="container my-5" style="display: none;">
        <h1>Contact Us</h1>
        <p>For more information about PharmaCure Pharmaceuticals and our products and services, please contact us today. We look forward to hearing from you and exploring opportunities for collaboration and partnership..</p>
        <br><br>
        <address>1243,pharma street,lasvegas</address>
        <br><br>
        <h4>1234567890</h4>
    </div>

    <!-- Footer -->
    <footer class="footer mt-auto py-3 bg-light">
        <div class="container text-center">
            <span class="text-muted">Pharma Company &copy; 2024</span>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

    <script>
        function showSection(sectionId) {
            document.querySelectorAll('.container').forEach(function (container) {
                container.style.display = 'none';
            });
            document.getElementById(sectionId).style.display = 'block';
        }
    </script>
</body>
</html>

```

## OUTPUT:

![image](https://github.com/Vigneshv-23/Pharma/assets/110780412/fa89193a-053a-4284-96a2-88605f4e9631)
![image](https://github.com/Vigneshv-23/Pharma/assets/110780412/892de75a-331a-4766-aee1-aa63bcb4f263)
![image](https://github.com/Vigneshv-23/Pharma/assets/110780412/05d52595-d313-448d-974d-f700c320826b)
![image](https://github.com/Vigneshv-23/Pharma/assets/110780412/ab1b222f-7dd7-425b-b33f-9627f0109912)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
