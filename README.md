<!DOCTYPE html>
<html>
<head>
  <title>My Vacation Gallery</title>
  <style>
    .slideshow-container {
      max-width: 100%;
      position: relative;
      margin: auto;
    }

    .mySlides {
      display: none;
    }

    .slideshow-img {
      width: 100%;
      height: auto;
    }

    .caption {
      text-align: center;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <div class="slideshow-container">
    <!-- Slides -->
    <div class="mySlides">
      <img class="slideshow-img" src="pic1.jpg" alt="Vacation Image">
      <div class="caption">
        <p>Description here</p>
      </div>
    </div>
  
    <!-- Add more slide divs here -->
  
    <!-- Navigation arrows -->
    <!DOCTYPE html>
    <html>
    <head>
      <title>My Vacation Gallery</title>
      <style>
        .slideshow-container {
          max-width: 100%;
          position: relative;
          margin: auto;
        }
    
        .mySlides {
          display: none;
        }
    
        .slideshow-img {
          width: 100%;
          height: auto;
        }
    
        .caption {
          text-align: center;
          margin-top: 20px;
        }
      </style>
    </head>
    <body>
      <div class="slideshow-container">
        <!-- Slides -->
        <div class="mySlides">
          <img class="slideshow-img" src="pic1.jpg" alt="Vacation Image">
          <div class="caption">
            <p>Description here</p>
          </div>
        </div>
      
        <!-- Add more slide divs here -->
      
        <!-- Navigation arrows -->
        <!DOCTYPE html>
        <html>
        <head>
          <title>My Vacation Gallery</title>
          <style>
            .slideshow-container {
              max-width: 100%;
              position: relative;
              margin: auto;
            }
        
            .mySlides {
              display: none;
            }
        
            .slideshow-img {
              width: 100%;
              height: auto;
            }
        
            .caption {
              text-align: center;
              margin-top: 20px;
            }
          </style>
        </head>
        <body>
          <div class="slideshow-container">
            <!-- Slides -->
            <div class="mySlides">
              <img class="slideshow-img" src="pic1.jpg" alt="Vacation Image">
              <div class="caption">
                <p>Description here</p>
              </div>
            </div>
          
            <!-- Add more slide divs here -->
          
            <!-- Navigation arrows -->
            <!DOCTYPE html>
            <html>
            <head>
              <title>My Vacation Gallery</title>
              <style>
                .slideshow-container {
                  max-width: 100%;
                  position: relative;
                  margin: auto;
                }
            
                .mySlides {
                  display: none;
                }
            
                .slideshow-img {
                  width: 100%;
                  height: auto;
                }
            
                .caption {
                  text-align: center;
                  margin-top: 20px;
                }
              </style>
            </head>
            <body>
              <div class="slideshow-container">
                <!-- Slides -->
                <div class="mySlides">
                  <img class="slideshow-img" src="pic1.jpg" alt="Vacation Image">
                  <div class="caption">
                    <p>Description here</p>
                  </div>
                </div>
              
                <!-- Add more slide divs here -->
              
                <!-- Navigation arrows -->
                <!DOCTYPE html>
                <html>
                <head>
                  <title>My Vacation Gallery</title>
                  <style>
                    .slideshow-container {
                      max-width: 100%;
                      position: relative;
                      margin: auto;
                    }
                
                    .mySlides {
                      display: none;
                    }
                
                    .slideshow-img {
                      width: 100%;
                      height: auto;
                    }
                
                    .caption {
                      text-align: center;
                      margin-top: 20px;
                    }
                  </style>
                </head>
                <body>
                  <div class="slideshow-container">
                    <!-- Slides -->
                    <div class="mySlides">
                      <img class="slideshow-img" src="pic1.jpg" alt="Vacation Image">
                      <div class="caption">
                        <p>Description here</p>
                      </div>
                    </div>
                  
                    <!-- Add more slide divs here -->
                  
                    <!-- Navigation arrows -->
                    <a class="prev" onclick="changeSlide(-1)"></a>
                    <a class="next" onclick="changeSlide(1)"></a>
                    
                  </div>
                
                  <script>
                    var slideIndex = 1;
                    showSlides(slideIndex);
                
                    // Event listeners for arrow key control
                    document.addEventListener("keydown", function(event) {
                      if (event.keyCode === 37) { // Left arrow key
                        changeSlide(-1);
                      } else if (event.keyCode === 39) { // Right arrow key
                        changeSlide(1);
                      }
                    });
                
                    function changeSlide(n) {
                      showSlides(slideIndex += n);
                    }
                
                    function showSlides(n) {
                      var i;
                      var slides = document.getElementsByClassName("mySlides");
                      
                      // Wrap around to the first slide when reaching the end
                      if (n > slides.length) {
                        slideIndex = 1;
                      }
                      
                      // Wrap around to the last slide when reaching the beginning
                      if (n < 1) {
                        slideIndex = slides.length;
                      }
                      
                      // Hide all slides
                      for (i = 0; i < slides.length; i++) {
                        slides[i].style.display = "none";
                      }
                      
                      // Show the current slide
                      slides[slideIndex - 1].style.display = "block";
                    }
                  </script>
                </body>
                </html>
                <!DOCTYPE html>
                <html>
                <head>
                  <title>My Vacation Gallery</title>
                  <style>
                    .slideshow-container {
                      max-width: 100%;
                      position: relative;
                      margin: auto;
                    }
                
                    .mySlides {
                      display: none;
                    }
                
                    .slideshow-img {
                      width: 100%;
                      height: auto;
                    }
                
                    .caption {
                      text-align: center;
                      margin-top: 20px;
                    }
                  </style>
                </head>
                <body>
                  <div class="slideshow-container">
                    <!-- Slides -->
                    <div class="mySlides">
                      <img class="slideshow-img" src="pic1.jpg" alt="Vacation Image">
                      <div class="caption">
                        <p>Description here</p>
                      </div>
                    </div>
                  
                    <!-- Add more slide divs here -->
                  
                    <!-- Navigation arrows -->
                    <a class="prev" onclick="changeSlide(-1)"></a>
                <a class="next" onclick="changeSlide(1)"></a>
                
                
                  <script>
                    var slideIndex = 1;
                    showSlides(slideIndex);
                
                    // Event listeners for arrow key control
                    document.addEventListener("keydown", function(event) {
                      if (event.keyCode === 37) { // Left arrow key
                        changeSlide(-1);
                      } else if (event.keyCode === 39) { // Right arrow key
                        changeSlide(1);
                      }
                    });
                
                    function changeSlide(n) {
                      showSlides(slideIndex += n);
                    }
                
                    function showSlides(n) {
                      var i;
                      var slides = document.getElementsByClassName("mySlides");
                      
                      // Wrap around to the first slide when reaching the end
                      if (n > slides.length) {
                        slideIndex = 1;
                      }
                      
                      // Wrap around to the last slide when reaching the beginning
                      if (n < 1) {
                        slideIndex = slides.length;
                      }
                      
                      // Hide all slides
                      for (i = 0; i < slides.length; i++) {
                        slides[i].style.display = "none";
                      }
                      
                      // Show the current slide
                      slides[slideIndex - 1].style.display = "block";
                    }
                  </script>
                </body>
                </html>
                
              </div>
            
              <script>
                var slideIndex = 1;
                showSlides(slideIndex);
            
                // Event listeners for arrow key control
                document.addEventListener("keydown", function(event) {
                  if (event.keyCode === 37) { // Left arrow key
                    changeSlide(-1);
                  } else if (event.keyCode === 39) { // Right arrow key
                    changeSlide(1);
                  }
                });
            
                function changeSlide(n) {
                  showSlides(slideIndex += n);
                }
            
                function showSlides(n) {
                  var i;
                  var slides = document.getElementsByClassName("mySlides");
                  
                  // Wrap around to the first slide when reaching the end
                  if (n > slides.length) {
                    slideIndex = 1;
                  }
                  
                  // Wrap around to the last slide when reaching the beginning
                  if (n < 1) {
                    slideIndex = slides.length;
                  }
                  
                  // Hide all slides
                  for (i = 0; i < slides.length; i++) {
                    slides[i].style.display = "none";
                  }
                  
                  // Show the current slide
                  slides[slideIndex - 1].style.display = "block";
                }
              </script>
            </body>
            </html>
            <!DOCTYPE html>
            <html>
            <head>
              <title>My Vacation Gallery</title>
              <style>
                .slideshow-container {
                  max-width: 100%;
                  position: relative;
                  margin: auto;
                }
            
                .mySlides {
                  display: none;
                }
            
                .slideshow-img {
                  width: 100%;
                  height: auto;
                }
            
                .caption {
                  text-align: center;
                  margin-top: 20px;
                }
              </style>
            </head>
            <body>
              <div class="slideshow-container">
                <!-- Slides -->
                <div class="mySlides">
                  <img class="slideshow-img" src="pic1.jpg" alt="Vacation Image">
                  <div class="caption">
                    <p>Description here</p>
                  </div>
                </div>
              
                <!-- Add more slide divs here -->
              
                <!-- Navigation arrows -->
                <a class="prev" onclick="changeSlide(-1)"></a>
            <a class="next" onclick="changeSlide(1)"></a>
            
            
              <script>
                var slideIndex = 1;
                showSlides(slideIndex);
            
                // Event listeners for arrow key control
                document.addEventListener("keydown", function(event) {
                  if (event.keyCode === 37) { // Left arrow key
                    changeSlide(-1);
                  } else if (event.keyCode === 39) { // Right arrow key
                    changeSlide(1);
                  }
                });
            
                function changeSlide(n) {
                  showSlides(slideIndex += n);
                }
            
                function showSlides(n) {
                  var i;
                  var slides = document.getElementsByClassName("mySlides");
                  
                  // Wrap around to the first slide when reaching the end
                  if (n > slides.length) {
                    slideIndex = 1;
                  }
                  
                  // Wrap around to the last slide when reaching the beginning
                  if (n < 1) {
                    slideIndex = slides.length;
                  }
                  
                  // Hide all slides
                  for (i = 0; i < slides.length; i++) {
                    slides[i].style.display = "none";
                  }
                  
                  // Show the current slide
                  slides[slideIndex - 1].style.display = "block";
                }
              </script>
            </body>
            </html>
            
          </div>
        
          <script>
            var slideIndex = 1;
            showSlides(slideIndex);
        
            // Event listeners for arrow key control
            document.addEventListener("keydown", function(event) {
              if (event.keyCode === 37) { // Left arrow key
                changeSlide(-1);
              } else if (event.keyCode === 39) { // Right arrow key
                changeSlide(1);
              }
            });
        
            function changeSlide(n) {
              showSlides(slideIndex += n);
            }
        
            function showSlides(n) {
              var i;
              var slides = document.getElementsByClassName("mySlides");
              
              // Wrap around to the first slide when reaching the end
              if (n > slides.length) {
                slideIndex = 1;
              }
              
              // Wrap around to the last slide when reaching the beginning
              if (n < 1) {
                slideIndex = slides.length;
              }
              
              // Hide all slides
              for (i = 0; i < slides.length; i++) {
                slides[i].style.display = "none";
              }
              
              // Show the current slide
              slides[slideIndex - 1].style.display = "block";
            }
          </script>
        </body>
        </html>
        <!DOCTYPE html>
        <html>
        <head>
          <title>My Vacation Gallery</title>
          <style>
            .slideshow-container {
              max-width: 100%;
              position: relative;
              margin: auto;
            }
        
            .mySlides {
              display: none;
            }
        
            .slideshow-img {
              width: 100%;
              height: auto;
            }
        
            .caption {
              text-align: center;
              margin-top: 20px;
            }
          </style>
        </head>
        <body>
          <div class="slideshow-container">
            <!-- Slides -->
            <div class="mySlides">
              <img class="slideshow-img" src="pic1.jpg" alt="Vacation Image">
              <div class="caption">
                <p>Description here</p>
              </div>
            </div>
          
            <!-- Add more slide divs here -->
          
            <!-- Navigation arrows -->
            <a class="prev" onclick="changeSlide(-1)"></a>
        <a class="next" onclick="changeSlide(1)"></a>
        
        
          <script>
            var slideIndex = 1;
            showSlides(slideIndex);
        
            // Event listeners for arrow key control
            document.addEventListener("keydown", function(event) {
              if (event.keyCode === 37) { // Left arrow key
                changeSlide(-1);
              } else if (event.keyCode === 39) { // Right arrow key
                changeSlide(1);
              }
            });
        
            function changeSlide(n) {
              showSlides(slideIndex += n);
            }
        
            function showSlides(n) {
              var i;
              var slides = document.getElementsByClassName("mySlides");
              
              // Wrap around to the first slide when reaching the end
              if (n > slides.length) {
                slideIndex = 1;
              }
              
              // Wrap around to the last slide when reaching the beginning
              if (n < 1) {
                slideIndex = slides.length;
              }
              
              // Hide all slides
              for (i = 0; i < slides.length; i++) {
                slides[i].style.display = "none";
              }
              
              // Show the current slide
              slides[slideIndex - 1].style.display = "block";
            }
          </script>
        </body>
        </html>
        
      </div>
    
      <script>
        var slideIndex = 1;
        showSlides(slideIndex);
    
        // Event listeners for arrow key control
        document.addEventListener("keydown", function(event) {
          if (event.keyCode === 37) { // Left arrow key
            changeSlide(-1);
          } else if (event.keyCode === 39) { // Right arrow key
            changeSlide(1);
          }
        });
    
        function changeSlide(n) {
          showSlides(slideIndex += n);
        }
    
        function showSlides(n) {
          var i;
          var slides = document.getElementsByClassName("mySlides");
          
          // Wrap around to the first slide when reaching the end
          if (n > slides.length) {
            slideIndex = 1;
          }
          
          // Wrap around to the last slide when reaching the beginning
          if (n < 1) {
            slideIndex = slides.length;
          }
          
          // Hide all slides
          for (i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";
          }
          
          // Show the current slide
          slides[slideIndex - 1].style.display = "block";
        }
      </script>
    </body>
    </html>
    <!DOCTYPE html>
    <html>
    <head>
      <title>My Vacation Gallery</title>
      <style>
        .slideshow-container {
          max-width: 100%;
          position: relative;
          margin: auto;
        }
    
        .mySlides {
          display: none;
        }
    
        .slideshow-img {
          width: 100%;
          height: auto;
        }
    
        .caption {
          text-align: center;
          margin-top: 20px;
        }
      </style>
    </head>
    <body>
      <div class="slideshow-container">
        <!-- Slides -->
        <div class="mySlides">
          <img class="slideshow-img" src="pic1.jpg" alt="Vacation Image">
          <div class="caption">
            <p>Description here</p>
          </div>
        </div>
      
        <!-- Add more slide divs here -->
      
        <!-- Navigation arrows -->
        <a class="prev" onclick="changeSlide(-1)"></a>
    <a class="next" onclick="changeSlide(1)"></a>
    
    
      <script>
        var slideIndex = 1;
        showSlides(slideIndex);
    
        // Event listeners for arrow key control
        document.addEventListener("keydown", function(event) {
          if (event.keyCode === 37) { // Left arrow key
            changeSlide(-1);
          } else if (event.keyCode === 39) { // Right arrow key
            changeSlide(1);
          }
        });
    
        function changeSlide(n) {
          showSlides(slideIndex += n);
        }
    
        function showSlides(n) {
          var i;
          var slides = document.getElementsByClassName("mySlides");
          
          // Wrap around to the first slide when reaching the end
          if (n > slides.length) {
            slideIndex = 1;
          }
          
          // Wrap around to the last slide when reaching the beginning
          if (n < 1) {
            slideIndex = slides.length;
          }
          
          // Hide all slides
          for (i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";
          }
          
          // Show the current slide
          slides[slideIndex - 1].style.display = "block";
        }
      </script>
    </body>
    </html>
    
  </div>

  <script>
    var slideIndex = 1;
    showSlides(slideIndex);

    // Event listeners for arrow key control
    document.addEventListener("keydown", function(event) {
      if (event.keyCode === 37) { // Left arrow key
        changeSlide(-1);
      } else if (event.keyCode === 39) { // Right arrow key
        changeSlide(1);
      }
    });

    function changeSlide(n) {
      showSlides(slideIndex += n);
    }

    function showSlides(n) {
      var i;
      var slides = document.getElementsByClassName("mySlides");
      
      // Wrap around to the first slide when reaching the end
      if (n > slides.length) {
        slideIndex = 1;
      }
      
      // Wrap around to the last slide when reaching the beginning
      if (n < 1) {
        slideIndex = slides.length;
      }
      
      // Hide all slides
      for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";
      }
      
      // Show the current slide
      slides[slideIndex - 1].style.display = "block";
    }
  </script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
  <title>My Vacation Gallery</title>
  <style>
    .slideshow-container {
      max-width: 100%;
      position: relative;
      margin: auto;
    }

    .mySlides {
      display: none;
    }

    .slideshow-img {
      width: 100%;
      height: auto;
    }

    .caption {
      text-align: center;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <div class="slideshow-container">
    <!-- Slides -->
    <div class="mySlides">
      <img class="slideshow-img" src="pic1.jpg" alt="Vacation Image">
      <div class="caption">
        <p>Description here</p>
      </div>
    </div>
  
    <!-- Add more slide divs here -->
  
    <!-- Navigation arrows -->
    <a class="prev" onclick="changeSlide(-1)"></a>
<a class="next" onclick="changeSlide(1)"></a>


  <script>
    var slideIndex = 1;
    showSlides(slideIndex);

    // Event listeners for arrow key control
    document.addEventListener("keydown", function(event) {
      if (event.keyCode === 37) { // Left arrow key
        changeSlide(-1);
      } else if (event.keyCode === 39) { // Right arrow key
        changeSlide(1);
      }
    });

    function changeSlide(n) {
      showSlides(slideIndex += n);
    }

    function showSlides(n) {
      var i;
      var slides = document.getElementsByClassName("mySlides");
      
      // Wrap around to the first slide when reaching the end
      if (n > slides.length) {
        slideIndex = 1;
      }
      
      // Wrap around to the last slide when reaching the beginning
      if (n < 1) {
        slideIndex = slides.length;
      }
      
      // Hide all slides
      for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";
      }
      
      // Show the current slide
      slides[slideIndex - 1].style.display = "block";
    }
  </script>
</body>
</html>

