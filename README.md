<!--RMIT University Vietnam
  Course: COSC2430 Web Programming
  Semester: 2023A
  Assessment: Assignment 1
  Author: Duong Tran Le Truong
  ID: 3807528-->


<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Bookstore Website</title>
        <link rel="stylesheet" href="style.css">   
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">     
    </head>
    <body width="device-width">
        <section class="home_navigator">
            <nav>
                <div class="logo">
                    <img src="image/logo.png">
                </div>

                <ul>
                    <li><a href="#Home">Home</a></li>
                    <li><a href="#Fiction">Fiction</a></li>
                    <li><a href="#Non-fiction">Non-fiction</a></li>
                    <li><a href="#Book">Find your books</a></li>
                    <li><a href="#Contact">Contact</a></li>
                </ul>

                <div class="social_icon">
                    <i class="fa-regular fa-magnifying-glass"></i>
                    <i class="fa fa-heart"></i>
                </div>
            </nav>

            <div class="main">
                <div class="main_tag">
                    <h1>WELCOME TO<br><span>Story Shop Book Store</span></h1>

                    <p>
                        Our bookstore was built to deliver a whole new level of experience
                        in reading books. With 24/7 support, new books update everyday and lots of 
                        other features, be sure to give our store a try and you will not regret it!
                    </p>
                    <a href="#" class="main_btn">Learn More</a>
                </div>

                <div class="main_img">
                    <img id="main_img" src="image/table.png">
                </div>
            </div>
        </section>
        
        
        <!-- category 1: fiction books -->>
        <div class="category">
            <h1><a href=#>Fiction</a></h1>
            <div class="category_box">
                <div class="category_card">
                    <div class="cat_book_img">
                        <img src="image/fantasy_1.jpg">
                    </div>
                    <div class="cat_book">
                        <h2><a href="#">Harry Potter and the Philosopher's Stone</a></h2>
                        <p class="writer">J.K Rowling</p>
                        <div class="categories">Fiction, Fantasy</div>
                        <p class="book_price">$25.00  <sub><del>$30.00</del></sub></p>
                        <a href="#" class="f_btn">Learn More</a>
                    </div>
                </div>

                <div class="category_card">
                    <div class="cat_book_img">
                        <img src="image/fantasy_2.jpg">
                    </div>
                    <div class="cat_book">
                        <h2><a href="#">Heroes of Olympus - The Lost Hero</a></h2>
                        <p class="writer">Rick Riordan</p>
                        <div class="categories">Fiction, Fantasy</div>
                        <p class="book_price">$25.00  <sub><del>$30.00</del></sub></p>
                        <a href="#" class="f_btn">Learn More</a>
                    </div>
                </div>

                <div class="category_card">
                    <div class="cat_book_img">
                        <img src="image/fantasy_3.jpg">
                    </div>
                    <div class="cat_book">
                        <h2><a href=#>Percy Jackson and the Lightning Thief</a></h2>
                        <p class="writer">Rick Riordan</p>
                        <div class="categories">Fiction, Fantasy</div>
                        <p class="book_price">$25.00  <sub><del>$30.00</del></sub></p>
                        <a href="#" class="f_btn">Learn More</a>
                    </div>
                </div>

                <div class="category_card">
                    <div class="cat_book_img">
                        <img src="image/horror_1.jpg">
                    </div>
                    <div class="cat_book">
                        <h2><a href="#">IT</a></h2>
                        <p class="writer">Stephen King</p>
                        <div class="categories">Fiction, Horror</div>
                        <p class="book_price">$25.00  <sub><del>$30.00</del></sub></p>
                        <a href="#" class="f_btn">Learn More</a>
                    </div>
                </div>

                <div class="category_card">
                    <div class="cat_book_img">
                        <img src="image/horror_2.jpg">
                    </div>
                    <div class="cat_book">
                        <h2><a href="#">Dracula</a></h2>
                        <p class="writer">Bram Stoker</p>
                        <div class="categories">Fiction, Horror</div>
                        <p class="book_price">$25.00  <sub><del>$30.00</del></sub></p>
                        <a href="#" class="f_btn">Learn More</a>
                    </div>
                </div>

                <div class="category_card">
                    <div class="cat_book_img">
                        <img src="image/horror_3.jpg">
                    </div>
                    <div class="cat_book">
                        <h2><a href="#">The Pit and the Pendulum</a></h2>
                        <p class="writer">Edgar Allan Poe</p>
                        <div class="categories">Fiction, Horror</div>
                        <p class="book_price">$25.00  <sub><del>$30.00</del></sub></p>
                        <a href="#" class="f_btn">Learn More</a>
                    </div>
                </div>
            </div>
        </div>

        <!--category 2: non-fiction books -->
        <div class="category">
            <h1><a href="#">Non-fiction</a></h1>
            <div class="category_box">
                <div class="category_card">
                    <div class="cat_book_img">
                        <img src="image/history_1.jpg">
                    </div>
                    <div class="cat_book">
                        <h2><a href="#">The History Book (Big Ideas Simply Explained)</a></h2>
                        <p class="writer">DK</p>
                        <div class="categories">Non-fiction, History</div>
                        <p class="book_price">$25.00  <sub><del>$30.00</del></sub></p>
                        <a href="#" class="f_btn">Learn More</a>
                    </div>
                </div>

                <div class="category_card">
                    <div class="cat_book_img">
                        <img src="image/history_2.jpg">
                    </div>
                    <div class="cat_book">
                        <h2><a href="#">The Last Mughal</a></h2>
                        <p class="writer">William Dalrymple</p>
                        <div class="categories">Non-fiction, History</div>
                        <p class="book_price">$25.00  <sub><del>$30.00</del></sub></p>
                        <a href="#" class="f_btn">Learn More</a>
                    </div>
                </div>

                <div class="category_card">
                    <div class="cat_book_img">
                        <img src="image/history_3.jpg">
                    </div>
                    <div class="cat_book">
                        <h2><a href="#">Making History: The Storytellers Who Shaped The Past</a></h2>
                        <p class="writer">Richard Cohen</p>
                        <div class="categories">Non-fiction, History</div>
                        <p class="book_price">$25.00  <sub><del>$30.00</del></sub></p>
                        <a href="#" class="f_btn">Learn More</a>
                    </div>
                </div>

                <div class="category_card">
                    <div class="cat_book_img">
                        <img src="image/science_1.webp">
                    </div>
                    <div class="cat_book">
                        <h2><a href="#">The Usborne Book of Science</a></h2>
                        <p class="writer">John Chisholm</p>
                        <div class="categories">Non-fiction, Science</div>
                        <p class="book_price">$25.00  <sub><del> $30.00</del></sub></p>
                        <a href="#" class="f_btn">Learn More</a>
                    </div>
                </div>

                <div class="category_card">
                    <div class="cat_book_img">
                        <img src="image/science_2.jpg">
                    </div>
                    <div class="cat_book">
                        <h2><a href="#">Something Deeply Hidden</a></h2>
                        <p class="writer">Sean Caroll</p>
                        <div class="categories">Non-fiction, Science</div>
                        <p class="book_price">$25.00  <sub><del>$30.00</del></sub></p>
                        <a href="#" class="f_btn">Learn More</a>
                    </div>
                </div>

                <div class="category_card">
                    <div class="cat_book_img">
                        <img src="image/science_3.jpg">
                    </div>
                    <div class="cat_book">
                        <h2><a href="#">Computer Science: An Interdisciplinary Approach</a></h2>
                        <p class="writer">Robert Sedgewick & Kevin Wayne</p>
                        <div class="categories">Non-fiction, Science</div>
                        <p class="book_price">$25.00  <sub><del>$30.00</del></sub></p>
                        <a href="#" class="f_btn">Learn More</a>
                    </div>
                </div>
            </div>
        </div>

        </div>
        

        <!--code for footer-->>
        <footer>
            <div class="footer_main">

                <div class="tag">
                    <img src="image/logo.png">
                    <p>
                        Our bookstore was built to deliver a whole new level of experience
                        in reading books. With 24/7 support, new books update everyday and lots of 
                        other features, be sure to give our store a try and you will not regret it
                    </p>
    
                </div>
    
                <div class="quicklink">
                    <h1>Quick Link</h1>
                    <a href="#Home">Home</a>
                    <a href="#Fiction">Fiction</a>
                    <a href="#Non-fiction">Non-fiction</a>
                    <a href="#Book">Find your books</a>
                    <a href="#Contact">Contact</a>                    
                </div>
    
                <div class="contact">
                    <h1>Contact Info</h1>
                    <a href="#"><i class="fa fa-phone"></i>+84 12 345 6789</a>
                    <a href="#"><i class="fa fa-phone"></i>+84 32 444 699</a>
                    <a href="#"><i class="fa fa-envelope"></i>storyshopbookstore@gmail.com</a>
                    
                </div>
    
                <div class="social">
                    <h1>Follow Us</h1>
                    <div class="social_link">
                        <i class="fa fa-facebook-f"></i>
                        <i class="fa fa-instagram"></i>
                        <i class="fa fa-twitter"></i>
                    </div>
                    
                </div>
    
                <div class="subscribe">
                    <h1>Subscribe to us</h1>
                    <div class="search_bar">
                        <input type="text" placeholder="You email id here">
                        <button type="submit">Subscribe</button>
                    </div>                
                </div>            
            </div>
        </footer>
    </body>
</html>
