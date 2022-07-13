<!DOCTYPE html>
<html lang="en">
<head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <meta http-equiv="X-UA-Compatible" content="ie=edge">
      <meta name="author" content="ivan.labasok">

      <title>Ivan Labasok Portfolio</title>

      <!-- stylesheet -->
      <link rel="stylesheet" href="style.css">

      <!-- bootstrap cdns -->
      <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
      <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>

      <!-- google fonts -->
      <link href="https://fonts.googleapis.com/css?family=Roboto+Mono:100,100i,300,300i,400,400i,500,500i,700,700i" rel="stylesheet">

      <!-- terminal effect -->
      <script src="t.min.js"></script>

      <!-- for on scroll animations -->
      <link rel="stylesheet" href="animate.css">
      <script src="wow.min.js"></script>

</head>
<body>
      <div class="wrapper">
            <!--------------- hero section starts here --------------->
            <div class="hero">
                  <div class="header">
                        <h1 class="line anim-typewriter">I make brands matter in culture.</h1>
                  </div>
            </div>

            <div class="scroll-down"></div>
            <!--------------- hero section ends here --------------->

            <div class="container">
                  <div class="hero-content">
                        <br><br>

                        <div class="row">
                              <div class="col-lg-8">

                                    <h3 class="wow fadeInUp" data-wow-delay="1s">My skills.</h3><br>
                                    <p class="wow fadeInUp" data-wow-delay="1.2s">Dart, Flutter experience 2 years</p>
                                    <p class="wow fadeInUp" data-wow-delay="1.2s">Firebase auth & cloud</p>
                                    <p class="wow fadeInUp" data-wow-delay="1.2s">REST API</p>
                                    <p class="wow fadeInUp" data-wow-delay="1.2s">BLoC</p>
                                    <p class="wow fadeInUp" data-wow-delay="1.2s">Commercial experience 1 year</p>
                                    <div class="hr">
                                          <div class="row"></div>
                                    </div>
            
                                    <br><br>
                                    <p class="wow fadeInUp" data-wow-delay="1.2s">Understanding of software development life cycle</p>
                                    <p class="wow fadeInUp" data-wow-delay="1.2s">Understanding of software development life cycle</p>
                                    <p class="wow fadeInUp" data-wow-delay="1.2s">Strong knowledge of networking</p>
                                    <p class="wow fadeInUp" data-wow-delay="1.2s">Good communication skills</p>
                                    <p class="wow fadeInUp" data-wow-delay="1.2s">English - B2, Slovak - B2, Belarussian - Flutent</p>
                              </div>
                        </div>
                  </div>
            </div>

            <div class="container">
                  <div class="hero-content">
                        <br><br>

                        <div class="row">
                              <div class="col-lg-8">

                                    <h3 class="wow fadeInUp" align= "right" data-wow-delay="1.2s">Experience.</h3><br>
                                    <p class="wow fadeInUp" align="right" data-wow-delay="1.4s">2021 - Created "NIOWO" company for uploading apps</p>
                                    <p class="wow fadeInUp" align="right" data-wow-delay="1.4s">February 2021 - Astronomy education app</p>
                                    <p class="wow fadeInUp" align="right" data-wow-delay="1.4s">April 2021 - Market for customers to upload their handmade clothes for selling</p>
                                    <p class="wow fadeInUp" align="right" data-wow-delay="1.4s">July 2021 - Simple card game, which generates catastrophe (15K+ downloads)</p>
                                    <p class="wow fadeInUp" align="right" data-wow-delay="1.4s">First Job as Flutter developer in Belarussian IT company</p>
                                    <p class="wow fadeInUp" align="right" data-wow-delay="1.4s">November - January 2022 - A mobile app that helps teenagers understand their future and find their dream job. The application consists of tests/surveys for teenagers</p>
                                 </div>
                        </div>
                  </div>
            </div>

            <div class="footer">
                  <div class="container">
                        <br><br>

                        <div class="collab">
                              <div class="row">
                                    <div class="col-lg-12">
                                          <p class="wow fadeInUp">Do you want to connect? Just contact me.</p>
                                    </div>
                              </div>
                        </div>

                        <br>

                        <div class="hr">
                              <div class="row"></div>
                        </div>

                        <br><br>

                        <div class="info">
                              <div class="row">
                                    <div class="col-lg-4" id="personal">
                                          <p class="wow fadeInUp">connect with me</p>
                                          <h4 class="wow fadeInUp" data-wow-delay="0.2s">worklabasok@gmail.com</h4>
                                          <br><br>
                                    </div>
                              </div>
                        </div>
                  </div>
            </div>
            <!--------------- footer ends here --------------->

            <br><br><br><br>

      </div>

      <!-- greensock cdn -->
      <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/2.1.2/TweenMax.min.js"></script>

      <script src="https://code.jquery.com/jquery-3.4.1.js"></script>
      <script type="text/javascript">

      // navigation starts here

      $("#toggle").click(function() {
            $(this).toggleClass('on');
            $("#resize").toggleClass("active");
      });

      $("#resize ul li a").click(function() {
            $(this).toggleClass('on');
            $("#resize").toggleClass("active");
      });

      $(".close-btn").click(function() {
            $(this).toggleClass('on');
            $("#resize").toggleClass("active");
      });

      // navigation ends here

      // nav animation

      TweenMax.from("#brand", 1, {
            delay: 0.4,
            y: 10,
            opacity: 0,
            ease: Expo.easeInOut
      })

      TweenMax.staggerFrom("#menu li a", 1, {
            delay: 0.4,
            opacity: 0,
            ease: Expo.easeInOut
      }, 0.1);

      // nav animation ends

      new WOW().init();

      </script>
</body>
</html>
