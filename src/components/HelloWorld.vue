<template>
  <body class="main-layout">
      <!-- loader  -->
      
      <!-- end loader -->
      <div id="mySidepanel" class="sidepanel">
         <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">×</a>
         <a class="active" href="index.html">Home</a>
         <a href="about.html">About</a>
         <a href="games.html">Games</a>
         <a href="tranner.html">Tranner</a>
         <a href="contact.html">Contact</a>
      </div>
      <!-- header -->
      <header>
         <!-- header inner -->
         <div class="head-top">
            <div class="container-fluid">
               <div class="row d_flex">
                  <div class="col-sm-3">
                     <div class="logo">
                        <a href="index.html"><img src="../assets/images/logo.png" /></a>
                     </div>
                  </div>
                  <div class="col-sm-9">
                     <ul class="email text_align_right">
                        <li><a href="Javascript:void(0)"><i class="fa fa-user" aria-hidden="true"></i></a></li>
                        <li><a href="Javascript:void(0)"><i class="fa fa-search" aria-hidden="true"></i></a></li>
                        <li> <button class="openbtn" onclick="openNav()"><img src="../assets/images/menu_btn.png"></button></li>
                     </ul>
                  </div>
               </div>
            </div>
         </div>
      </header>
      <!-- end header -->
      <!-- start slider section -->
      <div  class=" banner_main">
         <div class="container-fluid">
            <div class="row">
               <div class="col-md-12">
                  <div class="club">
                     <figure><img class="sm_n0" src="../assets/images/bbnner.png"> <img class="tes_n0" src="../assets/images/banner1.jpg"> </figure>
                     <div class="poa_t">
                        <h1>Sports club</h1>
                        <p>It is a long established fact that a reader will be distracted by the readable content of a</p>
                     </div>
                  </div>
               </div>
            </div>
         </div>
      </div>
      <!-- end slider section -->
      <div class="footbol">
         <div class="container-fluid">
            <div class="row">
               <div class="col-md-12">
                  <div id="myCarousel" class="carousel slide" data-ride="carousel">
                     <ol class="carousel-indicators">
                        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
                        <li data-target="#myCarousel" data-slide-to="1"></li>
                        <li data-target="#myCarousel" data-slide-to="2"></li>
                     </ol>
                     <div class="carousel-inner">
                        <div class="carousel-item active">
                           <div class="container-fluid">
                              <div class="carousel-caption relative">
                                 <div class="bluid">
                                    <div class="foot_img">
                                       <figure><img src="../assets/images/foot.png" alt="#"/></figure>
                                    </div>
                                    <a class="read_more" href="Javascript:void(0)">Read More </a>
                                 </div>
                              </div>
                           </div>
                        </div>
                        <div class="carousel-item">
                           <div class="container-fluid">
                              <div class="carousel-caption relative">
                                 <div class="bluid">
                                    <div class="foot_img">
                                       <figure><img src="../assets/images/foot.png" alt="#"/></figure>
                                    </div>
                                    <a class="read_more" href="Javascript:void(0)">Read More </a>
                                 </div>
                              </div>
                           </div>
                        </div>
                        <div class="carousel-item">
                           <div class="container-fluid">
                              <div class="carousel-caption relative">
                                 <div class="bluid">
                                    <div class="foot_img">
                                       <figure><img src="../assets/images/foot.png" alt="#"/></figure>
                                    </div>
                                    <a class="read_more" href="Javascript:void(0)">Read More </a>
                                 </div>
                              </div>
                           </div>
                        </div>
                     </div>
                     <a class="carousel-control-prev" href="#myCarousel" role="button" data-slide="prev">
                     <i class="fa fa-angle-left" aria-hidden="true"></i>
                     <span class="sr-only">Previous</span>
                     </a>
                     <a class="carousel-control-next" href="#myCarousel" role="button" data-slide="next">
                     <i class="fa fa-angle-right" aria-hidden="true"></i>
                     <span class="sr-only">Next</span>
                     </a>
                  </div>
               </div>
            </div>
         </div>
      </div>
      <!-- sports -->
      <div class="sports">
         <div class="container">
            <div class="row">
               <div class="col-md-10 offset-md-1">
                  <div class="titlepage text_align_center">
                     <h2>Our Sports Games</h2>
                     <p>variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are goingvariations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going</p>
                     <a class="read_more" href="sports.html">Read More</a>
                  </div>
               </div>
            </div>
            <div class="row d_flex">
               <div class="col-md-3">
                  <div class="sports_main text_align_center">
                     <figure><img  src="../assets/images/sport1.png" alt="#"/></figure>
                     <div class="sports_text">
                        <h3>Game 1</h3>
                        <p>vailable, but the majority have suffered alteration in some form, by injected humour, or randomised words which</p>
                        <a class="read_more" href="sports.html">Read More</a>
                     </div>
                  </div>
               </div>
               <div class="col-md-6">
                  <div class="sports_main text_align_center">
                     <figure><img class="dorder" src="../assets/images/sport2.png" alt="#"/></figure>
                     <div class="sports_text">
                        <h3 class="dark3">Game 2</h3>
                        <p>vailable, but the majority have<br> suffered alteration in some <br>form, by injected humour, or <br> randomised words which</p>
                        <a class="read_more" href="sports.html">Read More</a>
                     </div>
                  </div>
               </div>
               <div class="col-md-3">
                  <div class="sports_main text_align_center">
                     <figure><img src="../assets/images/sport3.png" alt="#"/></figure>
                     <div class="sports_text">
                        <h3>Game 3</h3>
                        <p>vailable, but the majority have suffered alteration in some form, by injected humour, or randomised words which</p>
                        <a class="read_more" href="sports.html">Read More</a>
                     </div>
                  </div>
               </div>
            </div>
         </div>
      </div>
      <!-- end sports -->
      <!-- about -->
      <div class="about">
         <div class="container">
            <div class="row">
               <div class="col-md-12">
                  <div class="titlepage text_align_center">
                     <h2>About Our Club</h2>
                     <p>n some form, by injected humour, or randomised</p>
                  </div>
               </div>
               <div class="col-md-12">
                  <div class="about_img">
                     <figure><img class="img_responsive" src="../assets/images/about_img.png" alt="#"/></figure>
                     <div class="abo_btn">
                        <a href="Javascript:void(0)"><img src="../assets/images/about_btn.png" alt="#"/></a>
                     </div>
                  </div>
               </div>
            </div>
         </div>
      </div>
      <!-- end about -->
      <!-- trannir -->
      <div class="trannir">
         <div class="container">
            <div class="row">
               <div class="col-md-12">
                  <div class="titlepage text_align_center">
                     <h2>Our Club Trannir</h2>
                     <p>n some form, by injected humour, or randomised</p>
                  </div>
               </div>
            </div>
            <div class="row d_flex">
               <div class="col-lg-10 offset-lg-1 col-md-12">
                  <div id="testimo" class="carousel slide our_trannir" data-ride="carousel">
                     <ol class="carousel-indicators">
                        <li data-target="#testimo" data-slide-to="0" class="active"></li>
                        <li data-target="#testimo" data-slide-to="1"></li>
                        <li data-target="#testimo" data-slide-to="2"></li>
                     </ol>
                     <div class="carousel-inner">
                        <div class="carousel-item active">
                           <div class="container">
                              <div class="carousel-caption posi_in">
                                 <div class="trannir_text">
                                    <i><img src="../assets/images/clint.jpg" alt="#"/></i>
                                    <h3>Denial sork</h3>
                                    <span>Trannir</span>
                                    <ul class="social_icon text_align_center">
                                       <li> <a href="Javascript:void(0)"><i class="fa fa-facebook-f"></i></a></li>
                                       <li> <a href="Javascript:void(0)"><i class="fa fa-twitter"></i></a></li>
                                       <li> <a href="Javascript:void(0)"><i class="fa fa-linkedin" aria-hidden="true"></i></a></li>
                                       <li> <a href="Javascript:void(0)"><i class="fa fa-instagram" aria-hidden="true"></i></a></li>
                                       <li> <a href="Javascript:void(0)"><i class="fa fa-youtube-play" aria-hidden="true"></i></a></li>
                                    </ul>
                                 </div>
                              </div>
                           </div>
                        </div>
                        <div class="carousel-item">
                           <div class="container">
                              <div class="carousel-caption posi_in">
                                 <div class="trannir_text">
                                    <i><img src="../assets/images/clint.jpg" alt="#"/></i>
                                    <h3>Denial sork</h3>
                                    <span>Trannir</span>
                                    <ul class="social_icon text_align_center">
                                       <li> <a href="Javascript:void(0)"><i class="fa fa-facebook-f"></i></a></li>
                                       <li> <a href="Javascript:void(0)"><i class="fa fa-twitter"></i></a></li>
                                       <li> <a href="Javascript:void(0)"><i class="fa fa-linkedin" aria-hidden="true"></i></a></li>
                                       <li> <a href="Javascript:void(0)"><i class="fa fa-instagram" aria-hidden="true"></i></a></li>
                                       <li> <a href="Javascript:void(0)"><i class="fa fa-youtube-play" aria-hidden="true"></i></a></li>
                                    </ul>
                                 </div>
                              </div>
                           </div>
                        </div>
                        <div class="carousel-item">
                           <div class="container">
                              <div class="carousel-caption posi_in">
                                 <div class="trannir_text">
                                    <i><img src="../assets/images/clint.jpg" alt="#"/></i>
                                    <h3>Denial sork</h3>
                                    <span>Trannir</span>
                                    <ul class="social_icon text_align_center">
                                       <li> <a href="Javascript:void(0)"><i class="fa fa-facebook-f"></i></a></li>
                                       <li> <a href="Javascript:void(0)"><i class="fa fa-twitter"></i></a></li>
                                       <li> <a href="Javascript:void(0)"><i class="fa fa-linkedin" aria-hidden="true"></i></a></li>
                                       <li> <a href="Javascript:void(0)"><i class="fa fa-instagram" aria-hidden="true"></i></a></li>
                                       <li> <a href="Javascript:void(0)"><i class="fa fa-youtube-play" aria-hidden="true"></i></a></li>
                                    </ul>
                                 </div>
                              </div>
                           </div>
                        </div>
                     </div>
                     <a class="carousel-control-prev" href="#testimo" role="button" data-slide="prev">
                     <i class="fa fa-angle-left" aria-hidden="true"></i>
                     <span class="sr-only">Previous</span>
                     </a>
                     <a class="carousel-control-next" href="#testimo" role="button" data-slide="next">
                     <i class="fa fa-angle-right" aria-hidden="true"></i>
                     <span class="sr-only">Next</span>
                     </a>
                  </div>
               </div>
            </div>
         </div>
      </div>
      <!-- end trannir -->
      <!-- our_club -->
      <div class="our_club">
         <div class="container">
            <div class="row">
               <div class="col-md-10 offset-md-1">
                  <div class="titlepage text_align_center">
                     <h2>Join Our club</h2>
                     <p>anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks</p>
                  </div>
               </div>
               <div class="col-md-12">
                  <div class="club_btn">
                     <a class="read_more " href="Javascript:void(0)">Get In Touch</a>
                     <a class="read_more" href="Javascript:void(0)">Map</a>
                     <a class="read_more" href="Javascript:void(0)">Join now</a>
                  </div>
               </div>
            </div>
         </div>
      </div>
      <!-- end our_club -->
      <!-- footer -->
      <footer>
         <div class="footer">
            <div class="container">
               <div class="row">
                  <div class="col-md-8 offset-md-2">
                     <h3>Follow Us</h3>
                     <ul class="social_icon text_align_center">
                        <li> <a href="Javascript:void(0)"><i class="fa fa-facebook-f"></i></a></li>
                        <li> <a href="Javascript:void(0)"><i class="fa fa-twitter"></i></a></li>
                        <li> <a href="Javascript:void(0)"><i class="fa fa-linkedin" aria-hidden="true"></i></a></li>
                        <li> <a href="Javascript:void(0)"><i class="fa fa-instagram" aria-hidden="true"></i></a></li>
                        <li> <a href="Javascript:void(0)"><i class="fa fa-youtube-play" aria-hidden="true"></i></a></li>
                     </ul>
                     <div class="conta text_align_center">
                        <ul>
                           <li> <a href="Javascript:void(0)"><img src="../assets/images/call.png" alt="#"/> Call +01 1234567890
                              </a>
                           </li>
                           <li> <a href="Javascript:void(0)"><img src="../assets/images/mall.png" alt="#"/> demo@gmail.com
                              </a>
                           </li>
                        </ul>
                     </div>
                  </div>
                  <div class="col-md-8 offset-md-2">
                     <div class="menu_bottom text_align_center">
                        <ul>
                           <li><a href="index.html">Home</a></li>
                           <li><a href="about.html">About</a></li>
                           <li><a href="games.html">Games</a></li>
                           <li><a href="tranner.html">Tranner</a></li>
                           <li><a href="contact.html">Contact</a></li>
                        </ul>
                     </div>
                  </div>
               </div>
            </div>
            <div class="copyright text_align_center">
               <div class="container">
                  <div class="row">
                     <div class="col-md-8 offset-md-2">
                        <p>© 2020 All Rights Reserved. <a href="https://html.design/"> Free Html Template</a></p>
                     </div>
                  </div>
               </div>
            </div>
         </div>
      </footer>
    </body>
</template>
<script type="text/javascript" src="../assets/js/jquery.min.js"></script>
<script type="text/javascript" src="../assets/js/bootstrap.bundle.min.js"></script>
<script type="text/javascript" src="../assets/js/jquery-3.0.0.min.js"></script>
<script type="text/javascript" src="../assets/js/custom.js"></script>
<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import "../assets/css/bootstrap.min.css";
@import "../assets/css/responsive.css";
@import "../assets/css/style.css";
@import "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css";

</style>
