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
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="leadership/president.html">President</a></li>
        <li><a href="models/classics.html">Car Models</a></li>
      </ul>
    </nav>
  </header>

  <https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.amarujala.com%2Fautomobiles%2Fbmw-s-1000-rr-and-hero-xpulse-200t-4v-bikes-are-coming-in-december-know-engine-and-price-details&psig=AOvVaw10q2r0EqVSZv2wEh3z3n7F&ust=1757138488920000&source=images&cd=vfe&opi=89978449&ved=0CBUQjRxqFwoTCLDKmJT5wI8DFQAAAAAdAAAAABAE>
  <section class="hero">
    <h1>Welcome to BMW World</h1>
    <p>Explore BMW’s history, leadership, and legendary car models.</p>
  </section>

  <!-- Sections -->
  <section class="content">
    <h2>Leadership</h2>
    <p>Meet the visionaries behind BMW’s global success.</p>
    <a href="leadership/ceo.html" class="btn">Learn More</a>
  </section>

  <section class="content">
    <h2>Car Models</h2>
    <p>Discover BMW classics, modern icons, and the future of electric cars.</p>
    <a href="models/modern.html" class="btn">Explore Models</a>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 BMW Website Project | Built with ❤️ by TANISHKA CHOUDHARY </p>
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

/* Hero Section */
.hero {
  background: url('../images/models/bmw-hero.jpg') no-repeat center center/cover;
  color: white;
  text-align: center;
  padding: 100px 20px;
}

.hero h1 {
  font-size: 3rem;
}

.hero p {
  margin-top: 10px;
  font-size: 1.2rem;
}

/* Content Sections */
.content {
  padding: 2rem;
  text-align: center;
}

.content h2 {
  margin-bottom: 1rem;
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
footer {
  background: #000;
  color: white;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}
