# construction-site
construction-site
[node.html](https://github.com/user-attachments/files/22057307/node.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Family construction business website showcasing services, projects, and contact details.">
  <title>Family Construction Co.</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body { font-family: Arial, sans-serif; }
    header { background: url('https://images.unsplash.com/photo-1581090700227-4c4f50b4c2b6') no-repeat center center/cover; height: 70vh; color: white; display: flex; align-items: center; justify-content: center; text-align: center; }
    header h1 { font-size: 3rem; font-weight: bold; }
    .services, .projects, .contact { padding: 60px 0; }
    .footer { background: #222; color: #fff; padding: 20px; text-align: center; }
  </style>
</head>
<body>

  <!-- Hero Section -->
  <header>
    <div>
      <h1>Family Construction Co.</h1>
      <p>Building Dreams with Strength and Quality</p>
      <a href="#contact" class="btn btn-warning mt-3">Get in Touch</a>
    </div>
  </header>

  <!-- Services Section -->
  <section class="services container text-center">
    <h2 class="mb-4">Our Services</h2>
    <div class="row">
      <div class="col-md-4">
        <div class="card shadow-sm p-3">
          <h4>Residential Construction</h4>
          <p>We design and build homes with attention to detail and quality craftsmanship.</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shadow-sm p-3">
          <h4>Commercial Projects</h4>
          <p>From offices to retail spaces, we deliver functional and modern buildings.</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card shadow-sm p-3">
          <h4>Renovations</h4>
          <p>We bring new life to old structures through professional renovation services.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section class="projects bg-light">
    <div class="container text-center">
      <h2 class="mb-4">Our Projects</h2>
      <div class="row">
        <div class="col-md-4 mb-3">
          <img src="https://images.unsplash.com/photo-1590490360182-8b1b59a17f2d" class="img-fluid rounded shadow" alt="Project 1">
          <p>Modern Residential Home</p>
        </div>
        <div class="col-md-4 mb-3">
          <img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e" class="img-fluid rounded shadow" alt="Project 2">
          <p>Commercial Office Block</p>
        </div>
        <div class="col-md-4 mb-3">
          <img src="https://images.unsplash.com/photo-1570129477492-45c003edd2be" class="img-fluid rounded shadow" alt="Project 3">
          <p>Renovated Apartment</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="contact container">
    <h2 class="text-center mb-4">Contact Us</h2>
    <div class="row justify-content-center">
      <div class="col-md-6">
        <form>
          <div class="mb-3">
            <label class="form-label">Name</label>
            <input type="text" class="form-control" required>
          </div>
          <div class="mb-3">
            <label class="form-label">Email</label>
            <input type="email" class="form-control" required>
          </div>
          <div class="mb-3">
            <label class="form-label">Message</label>
            <textarea class="form-control" rows="5" required></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Send Message</button>
        </form>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <div class="footer">
    <p>&copy; 2025 Family Construction Co. | Designed by Johnson</p>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
