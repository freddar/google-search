<!DOCTYPE html>
<html lang="en">

    <head>
        <meta charset ="UTF-8">
        <title>Fred's Google Search</title>
        <link rel="stylesheet" type="text/css" href="style.css" />
    </head>

    <body>
        <div class="content">

            <!--Links Header-->
            <header>
                <div class="header_search_links" id="links">
                    <a class="header_links" id="image-search" href="https://images.google.com/?hl=en" target="_blank">Images</a>
                    <a  class="header_links" id="advanced-search" href="https://images.google.com/?hl=en" target="_blank">Advanced Search</a>
                </div>
            </header>
           
            <!--Google Image-->
            <div class="google" id="image">
                 <img alt="Google" id="logo" src="img/google_logo.png">
            </div>

            <!--Search Form-->
            <div class= "search" id= "searchform">
                <form action="https://google.com/search">
                    <div class="input">  
                        <div class= "pics">   
                            <div class ="magnify">  
                                <div class ="magnify-left">
                                    <span class="magnify-glass-left">  
                                        <svg class="glass" focusable="false" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                                <path d="M15.5 14h-.79l-.28-.27A6.471 6.471 0 0 0 16 9.5 6.5 6.5 0 1 0 9.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z"></path>
                                        </svg>
                                    </span>
                                </div>
                            </div>  
                            <div class="speak">
                                <div class="speak-right">
                                    <div class="speak-loud">
                                            <svg class="micro" focusable="false" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                                <path d="m12 15c1.66 0 3-1.31 3-2.97v-7.02c0-1.66-1.34-3.01-3-3.01s-3 1.34-3 3.01v7.02c0 1.66 1.34 2.97 3 2.97z" fill="#4285f4"></path>
                                                <path d="m11 18.08h2v3.92h-2z" fill="#34a853"></path>
                                                <path d="m7.05 16.87c-1.27-1.33-2.05-2.83-2.05-4.87h2c0 1.45 0.56 2.42 1.47 3.38v0.32l-1.15 1.18z" fill="#f4b400"></path>
                                                <path d="m12 16.93a4.97 5.25 0 0 1 -3.54 -1.55l-1.41 1.49c1.26 1.34 3.02 2.13 4.95 2.13 3.87 0 6.99-2.92 6.99-7h-1.99c0 2.92-2.24 4.93-5 4.93z" fill="#ea4335"></path>
                                            </svg>     
                                    </div>
                                </div>    
                            </div>
                        </div>
                        <div class="input-holder">
                            <input type="text" name="q" id="search_input" placeholder="Search Google">
                        </div>
                    </div>
                    <div class="submit">
                        <input type="submit" value="Google Search" class="buttons" id="search_button">
                        <input type="submit" value="I'm Feeling Lucky" class="buttons" id="lucky_button">
                    </div>
                </form>
            </div>

            <!-- FOOTER -->
            <footer>
                <div id= "footer-1"> 
                    <a href="#"> England</a>
                </div>
                <div id= "footer-2">
                    <ul id="footer-left">
                      <li><a href="#">Advertising</a></li>
                      <li><a href="#">Business</a></li>
                      <li><a href="#">About</a></li> 
                    </ul>
                    <ul id="footer-right">    
                      <li><a href="#">Privacy</a></li>
                      <li><a href="#">Terms</a></li>
                      <li><a href="#">Settings</a></li>
                    </ul> 
                </div>
            </footer>      
        </div>  
    </body>
</html>