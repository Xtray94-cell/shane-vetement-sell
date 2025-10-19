body {
  font‑family: Arial, sans‑serif;
  margin: 0;
  padding: 0;
}

header, footer {
  background‑color: #333;
  color: white;
  padding: 1em;
  text‑align: center;
}

nav a {
  color: white;
  margin: 0 1em;
  text‑decoration: none;
}

main {
  display: flex;
  flex‑wrap: wrap;
  padding: 1em;
}

.products {
  flex: 2;
  display: flex;
  flex‑wrap: wrap;
  gap: 1em;
}

.product {
  border: 1px solid #ccc;
  padding: 1em;
  width: 200px;
  text‑align: center;
  background: #f9f9f9;
}

.product img {
  max‑width: 100%;
  height: auto;
}

.cart {
  flex: 1;
  border‑left: 2px solid #eee;
  padding‑left: 1em;
  background: #f3f3f3;
}
