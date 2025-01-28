# AestheticThreads
/* General Styles */
body {
  font-family: 'Poppins', sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f5f5f5;
  color: #333;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background-color: #fff;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.logo h1 {
  font-size: 24px;
  color: #ff6f61;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav a {
  text-decoration: none;
  color: #333;
  font-weight: 500;
}

.cart a {
  font-size: 24px;
  color: #333;
}

.hero {
  background: url('https://via.placeholder.com/1200x400') no-repeat center center/cover;
  height: 400px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #fff;
  text-align: center;
}

.hero-content h2 {
  font-size: 48px;
  margin-bottom: 10px;
}

.hero-content p {
  font-size: 18px;
  margin-bottom: 20px;
}

.btn {
  background-color: #ff6f61;
  color: #fff;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  text-decoration: none;
}

.shop {
  padding: 40px 20px;
  text-align: center;
}

.product-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  padding: 20px;
}

.product-card {
  background-color: #fff;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  text-align: center;
}

.product-card img {
  max-width: 100%;
  border-radius: 10px;
}
[Uploading s// Example: Add hover effect to product cards
const productCards = document.querySelectorAll('.product-card');

productCards.forEach(card => {
  card.addEventListener('mouseover', () => {
    card.style.transform = 'scale(1.05)';
    card.style.transition = 'transform 0.3s ease';
  });

  card.addEventListener('mouseout', () => {
    card.style.transform = 'scale(1)';
  });
});cript.js…]()

.about, .contact {
  padding: 40px 20px;
  text-align: center;
}

footer {
  text-align: center;
  padding: 20px;
  background-color: #333;
  color: #fff;
}
