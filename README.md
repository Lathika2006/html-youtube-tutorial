# HTML Project Tutorial - Event Page, Tables, and Forms

Welcome to the HTML Project Tutorial repository! This repository contains the starter and final code for two complete projects that will be covered in a YouTube tutorial series. The tutorial series aims to provide comprehensive knowledge about HTML and guide you through building two exciting projects: an Event Page and a project focused on Tables and Forms.

## Project 1: Event Page

In the first project, we will build an Event Page that will cover a wide range of fundamental HTML components. Throughout this project, you will learn how to use the following HTML elements:

- Heading Tags: `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`
- Paragraph Tags: `<p>`
- Anchor Tags: `<a>`
- Body Tag: `<body>`
- HTML Boilerplate: `<html>`
- Image Tag: `<img>`

By the end of this project, you will have a clear understanding of how to structure basic HTML elements and create an appealing Event Page.

## Code 
```
 <!DOCTYPE html>
 <html>
    <head>
        <title>Events</title>
        <link rel="icon" href="img/date.png">
    </head>
    <body bgcolor="black" style="color:white">
        <center>
        <h1> Upcoming Events 📅</h1>
        <h4>Connect, explore, and never miss an event that matches your passion</h4>
        <hr>
        <p>The goal of this event is to provide a seamless and efficient registration process, enabling participants to easily sign up, select sessions, and access all necessary event details. It aims to bring together a diverse group of individuals, offering opportunities for networking, learning, and collaboration. By streamlining the registration process, the event ensures that attendees can focus on making the most of the experience, while fostering a sense of community and knowledge sharing. The focus is on creating an organized, engaging, and impactful event for everyone involved</p>
        <img src="img/event1.png">
        <h1>Photo Gallery</h1>
        <h2>Free Entry | Free Food</h2>
        <p>The Photo Gallery for this event showcases memorable moments captured throughout the event, highlighting the energy, interactions, and key activities. It offers attendees a chance to relive special moments, from insightful sessions to networking opportunities, and share the experience with others. The gallery includes photos of speakers, participants, and behind-the-scenes glimpses, reflecting the diverse and vibrant atmosphere of the event. Whether you're revisiting a session you attended or exploring moments you missed, the gallery provides a visual journey that encapsulates the essence of the event</p>
        </center> 
        <center>
            <img src="img/event2.png">
            <h1>
                <a href="https://www.amazon.in/?tag=msndeskstdin-21&ref=pd_sl_qe0cmyshs_e&adgrpid=1313918052707697&hvadid=82120145791552&hvnetw=o&hvqmt=e&hvbmt=be&hvdev=c&hvlocint=&hvlocphy=149875&hvtargid=kwd-82120809129687:loc-90&hydadcr=5627_2377260&mcid=">Fashion Store</a>
            </h1>
            <h2>Free Entry | Free Food</h2>
            <p>This event celebrates the world of fashion, bringing together designers, brands, and enthusiasts for an exciting showcase of the latest trends and styles. The fashion store event offers a unique opportunity for attendees to explore a curated selection of clothing, accessories, and footwear from both emerging and established designers. With a focus on creativity, innovation, and sustainability, the event provides a platform for fashion lovers to discover new collections, enjoy exclusive discounts, and interact with industry experts. Whether you're looking for the perfect outfit or simply seeking inspiration, this event promises to be a stylish and memorable experience for all</p>
        </center>
        <center>
        <hr>
        <h1>Contact</h1>
        <h2>1234567899|sample@gmail.com</h2>
        <p>6/89,Kamaraj nagar,Tirunelveli</p>
        </center>
    </body>
 </html>
```
## Output

![image](https://github.com/user-attachments/assets/3cc53a2d-202f-4e6c-8b8d-8531d2f359e9)

https://event43.tiiny.site/

## Project 2: Tables and Forms

In the second project, we will dive deeper into HTML by focusing on two important components: Tables and Forms. Tables are used to present data in a structured format, while forms are essential for user input and data submission. Throughout this project, you will learn to use the following HTML elements:

- Table Tag: `<table>`
- Table Row Tag: `<tr>`
- Table Header Cell Tag: `<th>`
- Table Data Cell Tag: `<td>`
- Form Tag: `<form>`
- Input Tags: `<input>` (various types), `<textarea>`, `<select>`, `<option>`, `<label>`, `<button>`

By the end of this project, you will be proficient in creating tables and forms, and you'll understand how to collect user input and process it.

## Code
# index.html
```
<!DOCTYPE html>
<html>
    <head>
        <title>The Artistic Trio</title>
        <link rel="icon" href="emc.png">
    </head>
    <center>
    <body bgcolor="skyblue" style="color:black">
        <h1>The Artistic Trio🎨</h1>
        <h4>Training | online couse | Book online</h4>
        <p>Providing training and accepting orders for Mehndi, Rangoli, and custom artistic designs</p>
        <hr color="purple">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/jrPzaCgGtdk?si=gZWm1BV_g1omkVHt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        <p>We specialize in offering training in the art of Mehndi, Rangoli, and intricate designs, empowering individuals to explore their creativity and master traditional techniques. Alongside training, we also accept custom design orders to bring your vision to life, whether it's for special occasions, festivals, or personal projects. Our dedication to blending tradition with creativity ensures that every design is unique and crafted with precision. Whether you’re looking to learn or seeking bespoke designs, we are here to cater to your artistic needs with professionalism and passion </p>
        <table border="1" width="500">
            <center>
            <tr bgcolor="pink" >
                <td><h3><center>Offering Courses</center></h3></td>
                <td><h3><center>Accepting Orders</center></h3></td>
            </tr>
            <tr >
                <td><h3><center>Mehndi</center></h3></td>
                <td><h3><center>Brides Mehndi</center></h3></td>
            </tr>
            <tr >
                <td><h3><center>Rangoli</center></h3></td>
                <td><h3><center>Festival Rangoli</center></h3></td>
            </tr>
            <tr >
                <td><h3><center>Paintings</center></h3></td>
                <td><h3><center>Customise Paintings</center></h3></td>
            </tr>
        </center>
        </table>
    
    <p>
        <h2><a href="register.html">Register Course</a></h2>
        <h2><a href="book.html">Booking Orders</a></h2>
        Contact: 
        <a href="https://www.instagram.com/lami_1018/"><font color="purple">instagram</font></a>
        <a href="https://www.youtube.com/@goldenprincess7114"><font color="purple">Youtube</font></a>
    </p>
    </body>
    </center>
</html>
```
# Register Course
```
<!DOCTYPE html>
<html>
    <head>
        <title>The Artistic Trio </title>
        <link rel="icon" href="emc.png">
    </head>
    <center>
    <body bgcolor="skyblue" style="color:black">
        <h1>The Artistic Trio🎨</h1>
        <h4>Training | online couse | Book online</h4>
        <p>Providing training and accepting orders for Mehndi, Rangoli, and custom artistic designs</p>
        <hr color="purple">
        
        <h1>Register Course</h1> 
        <form>
            <table>
                <tr>
                    <td>Name</td><td><input type="text"></td>
                </tr>
                <tr>
                    <td>Age</td><td><input type="number"></td>
                </tr>
                <tr>
                    <td>Gender</td><td><input name="gender" type="radio"> Male<input name="gender" type="radio">Female </td>
                </tr>
                <tr>
                    <td>Email</td><td><input type="email"></td>
                
                <tr>
                    <tr>
                        <td>Address</td><td><input type="text"></td>
                    
                    <tr>
                    <td>Select Course</td>
                    <td>
                        <select>
                            <option>
                                Mehndi
                            </option>
                            <option>
                                Rangoli
                            </option>
                            <option>
                                Painting
                            </option>
                        </select>
                    </td>
                </tr>
                <tr>
                    <td>Experience</td><td><input name="gender" type="radio"> Beginner<input name="gender" type="radio">Intermiate </td>

                </tr>
                <tr >
                    <td><input type="submit"></td>
                    <td><input type="reset"></td>
                <tr>
            </table>
        </form><br><br><br>
        <p>
            
            Contact
            <a href="https://www.instagram.com/lami_1018/"><font color="purple">instagram</font></a>
            <a href="https://www.youtube.com/@goldenprincess7114"><font color="purple">Youtube</font></a>
            <h5><a href="index.html">Home</a></h5>
        </p>
    </center> 
    </body>
```
# Booking Orders
```
<!DOCTYPE html>
<html>
    <head>
        <title>The Artistic Trio </title>
        <link rel="icon" href="emc.png">
    </head>
    <center>
    <body bgcolor="skyblue" style="color:black">
        <h1>The Artistic Trio🎨</h1>
        <h4>Training | online couse | Book online</h4>
        <p>Providing training and accepting orders for Mehndi, Rangoli, and custom artistic designs</p>
        <hr color="purple">
        
        <h1>Booking Orders</h1> 
        <form>
            <table>
                <tr>
                    <td>Name</td><td><input type="text"></td>
                </tr>
                <tr>
                    <td>Age</td><td><input type="number"></td>
                </tr>
                <tr>
                    <td>Gender</td><td><input name="gender" type="radio"> Male<input name="gender" type="radio">Female </td>
                </tr>
                <tr>
                    <td>Email</td><td><input type="email"></td>
                
                <tr>
                    <tr>
                        <td>Address</td><td><input type="text"></td>
                    
                    <tr>
                    <td>Select </td>
                    <td>
                        <select>
                            <option>
                                Brides Mehndi
                            </option>
                            <option>
                                Rangoli
                            </option>
                            <option>
                                Painting
                            </option>
                        </select>
                    </td>
                </tr>
                <tr>
                    <td>Prefered Date</td><td><input type="date"></td>

                </tr>
                <tr >
                    <td><input type="submit"></td>
                    <td><input type="reset"></td>
                <tr>
            </table>
        </form><br><br><br>
        <p>
            
            Contact
            <a href="https://www.instagram.com/lami_1018/"><font color="purple">instagram</font></a>
            <a href="https://www.youtube.com/@goldenprincess7114"><font color="purple">Youtube</font></a>
            <h5><a href="index.html">Home</a></h5>
        </p>
    </center> 
    </body>
```
## Output
![image](https://github.com/user-attachments/assets/26941299-ff22-4a29-bf9c-205477377ef8)

![image](https://github.com/user-attachments/assets/49f18373-ab25-4da4-8c30-f075787a1af5)

![image](https://github.com/user-attachments/assets/9160c5da-0b8a-491a-b9ab-500213dc0699)

## How to Use this Repository

This repository is organized into two main directories: `Event_Page_Project` and `Tables_Forms_Project`. Each directory contains a `starter` folder, which includes the initial code for the respective projects, and a `final` folder with the completed code.

To get started with a specific project, follow these steps:

1. Clone this repository to your local machine using the following command:

   ```
   git clone https://github.com/your-username/html-project-tutorial.git
   ```

2. Navigate to the project folder of your choice, either `Event_Page_Project` or `Tables_Forms_Project`.

3. Inside each project folder, you will find a `starter` and a `final` folder. Open the `starter` folder in your preferred code editor to access the initial code.

4. Follow along with the YouTube tutorial series to build the projects step-by-step. You can use the `starter` code as a starting point and make changes as guided in the tutorial.

5. If you encounter any issues or have questions during the tutorial, feel free to open an issue in this repository. We encourage collaboration and learning together!

## Contributing

If you find any bugs, have suggestions for improvements, or want to add more features to the projects, we welcome your contributions! Simply fork this repository, make your changes, and submit a pull request.

## About the Author

This tutorial series is created and presented by [Agnel John](https://www.youtube.com/@ErrorMakesClever), a passionate web developer with a goal to share knowledge and help others learn HTML effectively.

Enjoy the journey of learning HTML and building exciting projects with us! Happy coding! 🚀🎉
