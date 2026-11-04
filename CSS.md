* {
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 36px 20px;
  font-family: Arial, sans-serif;
  color: #243247;
  background: #f3f6fa;
}

.page {
  max-width: 1180px;
  margin: 0 auto;
}

.page-header {
  margin-bottom: 28px;
  text-align: center;
}

.page-header h1 {
  margin: 0 0 8px;
}

.page-header p {
  margin: 0;
  color: #64758a;
}

.products {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 22px;
}

.product-card {
  /* flex-grow: 1, flex-shrink: 1, flex-basis: 250px */
  flex: 1 1 250px;
  max-width: 360px;
  overflow: hidden;
  border: 1px solid #d8e1eb;
  border-radius: 12px;
  background: white;
  box-shadow: 0 8px 20px #20304712;
}

.product-card img {
  display: block;
  width: 100%;
  height: 190px;
  object-fit: cover;
}

.product-info {
  padding: 18px;
}

.product-info h2 {
  margin: 0 0 8px;
  font-size: 1.15rem;
}

.price {
  margin: 0 0 16px;
  color: #28699f;
  font-size: 1.25rem;
  font-weight: bold;
}

button {
  width: 100%;
  padding: 11px;
  border: 0;
  border-radius: 7px;
  background: #28699f;
  color: white;
  font-size: 1rem;
  font-weight: bold;
  cursor: pointer;
}

button:hover {
  background: #1e527e;
}

@media (max-width: 600px) {
  body {
    padding: 24px 14px;
  }

  .product-card {
    flex-basis: 100%;
    max-width: 420px;
  }
}