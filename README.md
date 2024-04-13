<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Food Delivery</title>
  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <!-- Custom CSS -->
  <style>
    /* Add your custom styles here */
    body {
      padding-top: 60px; /* Adjust according to your navbar height */
    }
    .card {
      margin-bottom: 20px;
    }
  </style>
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">Web App</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <div class="container mt-5" Font-Italic>
    <h1>Welcome to our Food Delivery System</h1> 
    <p>Fill out the form below:</p>
    <form>
      <div class="form-group">
        <label for="name">Name:</label>
        <input type="text" class="form-control" id="name" placeholder="Enter your name">
      </div>
      <div class="form-group">
        <label for="email">Email:</label>
        <input type="email" class="form-control" id="email" placeholder="Enter your email">
      </div>
      <div class="form-group">
        <label for="message">Message:</label>
        <textarea class="form-control" id="message" rows="3" placeholder="Enter your message"></textarea>
      </div>
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
  </div>

  <div class="container mt-5">
    <div class="row">
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="download.jpeg" class="card-img-top" alt="Organic Food">
          <div class="card-body">
            <h5 class="card-title"> Organic food </h5>
            <p class="card-text"></p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="junk.jpeg" class="card-img-top" alt="Junk fods">
          <div class="card-body">
            <h5 class="card-title">Junk food</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="ice cream.jpeg" class="card-img-top" alt="Placeholder Image">
          <div class="card-body">
            <h5 class="card-title">Ice cream</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Bootstrap JS and dependencies -->
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
