body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #f4f6fb;
  color: #222;
}

header {
  background-color: #244b83;
  color: white;
  padding: 15px 5%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 24px;
  margin: 0;
}

nav {
  display: flex;
  gap: 20px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

.menu-button {
  display: none;
  background: none;
  border: 0;
  color: white;
  font-size: 28px;
  cursor: pointer;
}

.welcome {
  background-color: #dceaff;
  text-align: center;
  padding: 45px 20px;
  margin-top: 25px;
  border-radius: 8px;
}

.welcome h2 {
  font-size: 30px;
  margin-top: 0;
}

.welcome p {
  max-width: 650px;
  margin: 0 auto;
  line-height: 1.6;
}

.heading {
  margin-top: 35px;
  margin-bottom: 15px;
}

.card, .simple-content {
  background-color: white;
  padding: 22px;
  border-radius: 8px;
  border: 1px solid #ddd;
}

.card h3 {
  color: #244b83;
  font-size: 24px;
  margin-top: 0;
}

.card p, .simple-content p {
  line-height: 1.6;
}

.card a, .back-link {
  color: #244b83;
  font-weight: bold;
}

.simple-content {
  margin-top: 25px;
  line-height: 1.6;
}

pre {
  background-color: #eeeeee;
  padding: 15px;
  border-radius: 5px;
  overflow-x: auto;
}

footer {
  background-color: #244b83;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 50px;
}

/*Tablet navigation bar in a horizontal row*/
@media (min-width: 640px) and (max-width: 1023px) {
  nav {
    gap: 12px;
  }
}

/*Desktop navigation bar on the left*/
@media (min-width: 1024px) {
  header {
    position: fixed;
    top: 0;
    left: 0;
    width: 180px;
    height: 100vh;
    box-sizing: border-box;
    display: block;
    padding: 25px 20px;
  }

  .logo {
    margin-bottom: 35px;
  }

  nav {
    display: flex;
    flex-direction: column;
    gap: 18px;
  }

  main {
    margin-left: 200px;
    padding-top: 20px;
  }

  footer {
    margin-left: 200px;
  }
}

/*Smartphone*/
@media (max-width: 639px) {
  header {
    position: relative;
  }

  .menu-button {
    display: block;
  }

  nav {
    display: none;
    position: absolute;
    top: 62px;
    left: 0;
    width: 100%;
    box-sizing: border-box;
    background-color: #244b83;
    padding: 15px;
    gap: 15px;
  }

  nav.show {
    display: flex;
  }
}
