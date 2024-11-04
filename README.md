![image](https://github.com/user-attachments/assets/c73c1c3c-e9f9-43b5-be14-04ea00c808df)# Ex.07 Restaurant Website
## Date:03-11-2024

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
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Restaurant</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Heights Rooftop Restaurant</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Discover Delicious Meals!</h2>
            <section class="menu-items">
                <div class="food-item">
                    <img src="https://b.zmtcdn.com/data/pictures/chains/0/21001870/44d51694a5daa2a172edf2263ef6fd33.jpg" alt="Delicious Pasta">
                    <h4>Italian Pastas</h4>
                    <p>A creamy delight with fresh herbs and parmesan cheese.</p>
                </div>
                <div class="food-item">
                    <img src="https://i.pinimg.com/236x/f8/3a/44/f83a4492f7d3278d06a2c98ea4aab23c.jpg" alt="Juicy Burger">
                    <h4>Burgers</h4>
                    <p>Juicy beef patty with lettuce, tomato, and our special sauce.</p>
                </div>
                <div class="food-item">
                    <img src="https://cdn.loveandlemons.com/wp-content/uploads/2024/01/winter-salad-recipe-282x337.jpg" alt="Fresh Salad">
                    <h4>Garden Salads</h4>
                    <p>A mix of fresh greens and seasonal vegetables.</p>
                </div>
                <div class="food-item">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ab/Desserts.jpg/1200px-Desserts.jpg" alt="Dessert">
                    <h4>Chocolate Cakes</h4>
                    <p>Rich and moist chocolate cake with a creamy frosting.</p>
                </div>
            </section>
        </main>
        
        
        <footer>
            <p>MANI SRI LATHA.M</p>
            <p>212223110025</p>
        </footer>
    </div>
</body>
</html>
```

menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Menu</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Heights Rooftop Restaurant</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Delicious Food Items</h2>
            <section class="menu-items">
                <div class="food-item">
                    <img src="https://lh3.googleusercontent.com/p/AF1QipP1RT9Sn-03qn8Ly66-IFOBwSifmuCaq4ZcZL8r=s1360-w1360-h1020" alt="Mirchi Garam Chicken Wings">
                    <h4>Mirchi Garam Chicken Wings</h4>
                </div>
                <div class="food-item">
                    <img src="https://i.ytimg.com/vi/UvEttSIFMyk/maxresdefault.jpg" alt="Cheese Loaded Nachos">
                    <h4>Cheese Loaded Nachos</h4>
                </div>
                <div class="food-item">
                    <img src="https://www.seema.com/wp-content/uploads/2022/08/Malai-Kofta.jpg" alt="Malia Kofta">
                    <h4>Malia Kofta</h4>
                </div>
                <div class="food-item">
                    <img src="https://cookingwithcocktailrings.com/wp-content/uploads/2021/11/Birria-Tacos-114.jpg" alt="Tacos">
                    <h4>Tacos</h4>
                </div>
                <div class="food-item">
                    <img src="https://recipes.heart.org/-/media/AHA/Recipe/Recipe-Images/Classic-Margherita-Pizza-with-Whole-Wheat-Pizza-Crust.jpg?h=684&iar=0&mw=890&w=890&sc_lang=en" alt="Margherita Pizza">
                    <h4>Margherita Pizza</h4>
                </div>
                <div class="food-item">
                    <img src="https://assets.bonappetit.com/photos/624215f8a76f02a99b29518f/1:1/w_2800,h_2800,c_limit/0328-ceasar-salad-lede.jpg" alt="Cesar Salad">
                    <h4>Cesar Salad</h4>
                </div>
                <div class="food-item">
                    <img src="https://img.freepik.com/premium-photo/double-cheeseburger-with-grilled-vegetables-tomato-lettuce-leaf-burger-buns-wooden-board_839035-106.jpg?w=360" alt="Cheeseburger">
                    <h4>Cheeseburger</h4>
                </div>
                <div class="food-item">
                    <img src="https://www.spicebangla.com/wp-content/uploads/2024/04/chicken-tikka-masala.jpg" alt="Chicken Tikka Masala">
                    <h4>Chicken Tikka Masala</h4>
                </div>
                <div class="food-item">
                    <img src="https://www.awesomecuisine.com/wp-content/uploads/2013/07/Mutton-Soup.jpg" alt="Mutton Soup">
                    <h4>Mutton Soup</h4>
                </div>
                <div class="food-item">
                    <img src="https://lh3.googleusercontent.com/p/AF1QipPYnYP7O1EhY1mKnwZW0tMdB3msLZJG-85qm03N=s1360-w1360-h1020" alt="Paneer Kurkure">
                    <h4>Paneer Kurkure</h4>
                </div>
                <div class="food-item">
                    <img src="https://images.eatsmarter.com/sites/default/files/styles/max_size/public/chicken-and-vegetable-tortillas-569686.jpg" alt="Tortillas">
                    <h4>Tortillas</h4>
                </div>
                <div class="food-item">
                    <img src="https://food.fnr.sndimg.com/content/dam/images/food/fullset/2010/12/28/4/FNM_010111-Copy-That-026_s4x3.jpg.rend.hgtvcom.1280.960.suffix/1382545880780.webp" alt="Chocolate Lava Cake">
                    <h4>Chocolate Lava Cake</h4>
                </div>
            </section>
        </main>
        
        <footer>
            <p>MANI SRI LATHA</p>
            <p>212223110025</p>
        </footer>
    <div>
    
</body>
</html>
```
administration.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Administration</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Heights Rooftop Restaurant</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Meet Our Team</h2>
            <div class="team">
                <div class="member">
                    <img src="https://s2.r29static.com/bin/entry/87e/x,80/2191174/image.jpg" alt="Admin 1">
                    <p>John - Manager</p>
                </div>
                <div class="member">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTDBGyr-rm2V-XRucj4ZxwbALq8BXrZGmKp9A&s" alt="Admin 2">
                    <p>Rachael Ray - Chef</p>
                </div>
                <div class="member">
                    <img src="https://static.wikia.nocookie.net/dickinson/images/7/7d/Emily_Dickinson.jpg/revision/latest?cb=20190910235322" alt="Admin 3">
                    <p>Emily  - Waiter</p>
                </div>
                <div class="member">
                    <img src="https://thecocktaillovers.com/wp-content/uploads/2023/03/Monica_Berg-scaled.jpeg" alt="Admin 4">
                    <p>Monica Berg - Bartender</p>
                </div>
                <div class="member">
                    <img src="https://cdn802.pressflex.net/images//672.photo.2.jpg?m=1652791562" alt="Admin 5">
                    <p>Jessica - Hostess</p>
                </div>
                <div class="member">
                    <img src="https://topmanagement.fr/wp-content/uploads/2020/02/DavidLOEW.jpg" alt="Admin 6">
                    <p>David - Accountant</p>
                </div>
            </div>
        </main>
        <footer>
            <p>MANI SRI LATHA</p>
            <p>212223110025</p>
        </footer>

    </div>
    
</body>
</html>
```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Contact Us</title>
</head>
<body>
    <div class="container">
        <header>
            <h1>Heights Rooftop Restaurant</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="administration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <h2>Get in Touch</h2>
            <p>Address: No.86, Block No.5, Manickam Lane, Anna Salai, Guindy, Chennai, Tamil Nadu 600032</p>
            <p>Phone: 089399 94114</p>
            <p>Reservations: eazydiner.com, zomato.com</p>
            <p>Open Hours: 6–11 pm</p>
        </main>
        <footer>
            <p>MANI SRI LATHA</p>
            <p>212223110025</p>
        </footer>

    </div>
    
</body>
</html>
```
## OUTPUT:
![1](https://github.com/user-attachments/assets/15bb6101-86cd-426f-b90a-0f3fabccafd2)
![2](https://github.com/user-attachments/assets/974f3075-9101-4e80-a0d2-3b1ca83c357a)
![3](https://github.com/user-attachments/assets/331b4a40-8383-42fc-9d80-50ec7690bf10)
![4](https://github.com/user-attachments/assets/ad32b2cf-04a3-463a-b71b-f501db71e32c)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
