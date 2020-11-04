    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>FEMS_TALK</title>
    
        <link rel="shortcut icon" href="images/logo.png">
        <link rel="stylesheet" href="style.css">
        <script type="text/javascript" src="js/jquery.js"></script>
        <script type="text/javascript" src="js/jquery.fullpage.js"></script> 
        <link rel="stylesheet" type="text/css" href="css/lightslider.css">
        <script type="text/javascript" href="javascript/lightslider.js"></script>
        </head>
    <body>
        <div id="fullpage">
            <!--section-1-------->
            <section>
                <!--navigation-->
                <nav>
            
            <!--rightmenu-->
            <div class="r-menu">
               
                <!--sign in-button-->
                <button>Sign In</button>
            </div>
            <div class="logo">
                <img src="images/logo.png" alt="my logo" height="150" width="150">
            </div>

                </nav>

                <div class="">
                </div>
                <!--text-->
                <div class="text">
                    <!--earth-heading-->
                    <div class="earth">
                        <span>F</span>
                        <span>E</span>
                        <span>M</span>
                        <span>S</span>
                        <span>_</span>
                        <span>T</span>
                        <span>A</span>
                        <span>L</span>
                        <span>K</span>
                
                        <!--planet-heading-->
                        <h1>WORLD</h1>
                        <!--button-->
                        <button>READ MORE</button>
                    </div>

                </div>
                <!--social-->
                <div class="social">
                <!--paragraph-->
                <p>Follow Me And Stay Connected With Us</p>
             
            </section>

            <!--section-2-------->
            <section>
                <div class="explore-h">
                    
                    <h1>Explore The Magic Of Blogging</h1>
                    <p>I founder of FEMS_TALK, Femitha Saif...Creates various types of blogging videos.
                        I was always desperate to be a blogger, I learned more about the world of blogging....that is why in this website I will show you the way how I saw the world of Blogging.</p>

                </div>
              
            </section>
            <!--section-3-->
            <section>
                <footer class="footer">Copy right reserved by FEMI_TALKS</footer>
            </section>

        </div>
        <script text="text/javascript">

            $('#fullpage').fullpage();
            $(document).ready(function() {
    $('#autoWidth').lightSlider({
        autoWidth:true,
        loop:true,
        onSliderLoad: function() {
            $('#autoWidth').removeClass('cS-hidden');
        } 
    });  
  });
        </script>
    </body>
    </html>
