# Ex.07 Restaurant Website
## Date: 28.04.2025
## Name: R.Harikrishnan
## Reg.No: 

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
H.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Delizia Restaurant</title>
  <style>
    body { font-family: 'Segoe UI', sans-serif; margin: 0; padding: 0; }
    header { background-color: #8b0000; color: white; padding: 20px; text-align: center; }
    nav a { color: white; margin: 0 15px; text-decoration: none; }
    .hero { background-image: url('https://via.placeholder.com/1200x400'); background-size: cover; color: white; text-align: center; padding: 100px 20px; }
    .menu, .about, .reservation { padding: 40px 20px; }
    .menu-item { margin: 20px 0; }
    .menu-item h3 { margin-bottom: 5px; }
    .reservation input, .reservation textarea { width: 100%; padding: 10px; margin-top: 10px; }
    .reservation button { padding: 10px 20px; margin-top: 10px; background-color: #8b0000; color: white; border: none; }
    footer { background-color: #333; color: white; text-align: center; padding: 20px; }
  </style>
</head>
<body>

  <header>
    <h1>Delizia Restaurant</h1>
    <nav>
      <a href="#menu">Menu</a>
      <a href="#about">About</a>
      <a href="#reservation">Reservation</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to Delizia</h2>
    <p>Authentic Italian Cuisine – Fresh, Handmade, Delicious</p>
  </section>

  <section id="menu" class="menu">
    <h2>Our Menu</h2>
    <div class="menu-item">
      <h3>Margherita Pizza - $12</h3>
      <p>Classic pizza with fresh tomatoes, mozzarella, and basil.</p>
    </div>
    <div class="menu-item">
      <h3>Spaghetti Carbonara - $14</h3>
      <p>Traditional Roman dish with pancetta and creamy egg sauce.</p>
    </div>
    <div class="menu-item">
      <h3>Tiramisu - $7</h3>
      <p>Layered dessert with espresso-soaked ladyfingers and mascarpone.</p>
    </div>
  </section>

  <section id="about" class="about">
    <h2>About Us</h2>
    <p>At Delizia, we serve authentic Italian dishes made from scratch with fresh ingredients. Family-owned and operated since 2005, we take pride in bringing the taste of Italy to your table.</p>
  </section>

  <section id="reservation" class="reservation">
    <h2>Make a Reservation</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <input type="date" required />
      <input type="time" required />
      <textarea rows="4" placeholder="Special requests..."></textarea>
      <button type="submit">Book Now</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Delizia Restaurant. All rights reserved.</p>
  </footer>

</body>
</html>
```
        
            
## OUTPUT:

![Screenshot 2025-04-28 194805](https://github.com/user-attachments/assets/02142142-f03e-43b0-a419-621ff621f866)

![Screenshot 2025-04-28 194815](https://github.com/user-attachments/assets/293dcd3e-03ef-4ae5-bcbb-57f048598d0e)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
