<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BMW Car Models</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <!-- Header -->
  <header>
    <img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.starkinsider.com%2F2020%2F03%2Fnew-bmw-logo-stays-true-to-todays-design-language.html&psig=AOvVaw1mMti1rzU-JO7n8WD8Cojj&ust=1757137979574000&source=images&cd=vfe&opi=89978449&ved=0CBUQjRxqFwoTCKDnoZn3wI8DFQAAAAAdAAAAABAK" alt="BMW Logo" class="logo">
    <nav>
      <ul>
        <li><a href="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.bmw.com%2Fen%2Findex.html&psig=AOvVaw2v9NUF8J8KBdiSELfHcEQn&ust=1757140014814000&source=images&cd=vfe&opi=89978449&ved=0CBUQjRxqFwoTCNCLvuT-wI8DFQAAAAAdAAAAABAE">Home</a></li>
        <li><a href="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.mensxp.com%2Ffine-living%2Fauto%2F22527-10-things-about-bmw-you-must-know.html&psig=AOvVaw3lC72fZkbqgFymzBdQcJIn&ust=1757140048395000&source=images&cd=vfe&opi=89978449&ved=0CBUQjRxqFwoTCJi59_P-wI8DFQAAAAAdAAAAABAE">About</a></li>
        <li><a href="https://www.press.bmwgroup.com/india/article/detail/T0451239EN/mr-hardeep-singh-brar-appointed-as-president-and-chief-executive-officer-of-bmw-group-india?language=en">President</a></li>
        <li><a href="https://www.bmw.in/en/all-models.html">Car Models</a></li>
      </ul>
    </nav>
  </header>
    <h1>Welcome to BMW World</h1>
    <p>Explore BMW’s history, leadership, and legendary car models.</p>
  </section>

  <!-- Sections -->
  <section class="content">
    <h2>Leadership</h2>
    <p>Meet the visionaries behind BMW’s global success.</p>
    <a href="https://www.bmwgroup.com/en/company/leadership-and-governance.html" class="btn">Learn More</a>
  </section>

  <section class="content">
    <h2>Car Models</h2>
    <p>Discover BMW classics, modern icons, and the future of electric cars.</p>
    <a href="https://www.bmw.in/en/all-models.html" class="btn">Explore Models</a>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 BMW Website Project | Built with ❤️ by [Your Name]</p>
  </footer>
</body>
</html>
  
/* General Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background-color: #f5f5f5;
  color: #222;
  line-height: 1.6;
}

/* Header */
header {
  background: #000;
  color: #fff;
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header .logo {https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.starkinsider.com%2F2020%2F03%2Fnew-bmw-logo-stays-true-to-todays-design-language.html&psig=AOvVaw3mRwshKI_ha5FfFp4uuLgT&ust=1757139023216000&source=images&cd=vfe&opi=89978449&ved=0CBUQjRxqFwoTCLCehov7wI8DFQAAAAAdAAAAABAE
  height: 50px;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  color: #1e90ff;
}

/* ELECTRIC MODELS */
.ELECTRIC {
  background: url('https://www.bmw.in/en/topics/Fascination-BMW/electromobility2020-new/electric-cars.html
') no-repeat center center/cover;
  color: white;
  text-align: center;
  padding: 100px 20px;
}

.BMW SUV {BMW X SUV Models & Pricing https://www.bmwusa.com/vehicles/x-models.html
  font-size: 3rem;
}

.BMW SEDAN {BMW Sedan Range: Overview https://www.bmw.in/en/topics/bmw-sedan.html
  margin-top: 10px;
  font-size: 1.2rem;
}

/* Content Sections */
.content {
  animation: fadeIn 2s ease-in;
}
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}

.btn {
  display: inline-block;
  margin-top: 1rem;
  padding: 10px 20px;
  background: #1e90ff;
  color: white;
  border-radius: 5px;
  text-decoration: none;
}

.btn:hover {
  background: #005bb5;
}

/* Footer */
<footer>
  <p>© 2025 BMW Website Project | Built with ❤️ by Tanishka Choudhary</p>
  <a href="#">Instagram</a> | <a href="#">LinkedIn</a> | <a href="#">YouTube</a>
</footer>
@media (max-width: 768px) {
  nav ul {
    flex-direction: column;
    text-align: center;
  }
}
