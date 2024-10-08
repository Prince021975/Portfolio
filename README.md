<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="my.css">
    
</head>
<style>
/* Main container styling */

body {
    margin: 0;
    font-family: 'Arial', sans-serif;
    color: aquamarine; /* Default text color */
    animation: gradientAnimation 15s ease infinite; /* Adjust the duration to control speed */
    background: 
         /* Gradient overlay */
        url('./my-image.jpeg'); /* Your background image */
    background-size: cover; /* Ensure the image covers the entire area */
    background-position: center; /* Center the image */
    
}

@keyframes gradientAnimation {
    0% {
        background: linear-gradient(135deg, #0d1b2a, #1b2631); /* Dark Blue to Dark Purple */
    }
    25% {
        background: linear-gradient(135deg, #0d1b2a, #1b2631); /* Charcoal to Deep Teal */
    }
    50% {
        background: linear-gradient(135deg, #0d1b2a, #1b2631); /* Dark Red to Deep Burgundy */
    }
    75% {
        background: linear-gradient(135deg, #0d1b2a, #1b2631); /* Slate Grey to Dark Slate Blue */
    }
    100% {
        background: linear-gradient(135deg, #0d1b2a, #1b2631);/* Dark Forest Green to Black */
    }}

  

  
  /* Sub-container styling */
  .container-2 {
    display: inline-block; /* Keeps image and text in a block together */
    text-align: center; /* Centers the content inside the block */
    padding: 20px;
  }
  
  /* Styling for the image to make it circular */
  .container-2 img {
    width: 150px; /* Adjust size as needed */
    height: 150px; /* Keep width and height the same for a circle */
    border-radius: 50%; /* Circular effect */
    object-fit: cover; /* Ensures the image doesn't get stretched */
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2); /* Adds a subtle shadow */
  }
  
  /* Main heading style */
  h1 {
    font-family: Arial, sans-serif;
    font-size: 36px;
    color:  aquamarine;;
    margin: 10px 0;
  }
  
  /* Name text style */
  .left {
    font-size: 28px;
    font-weight: bold;
    margin: 5px 0;
  }
  
  /* Subheading for profession */
  h2 {
    font-size: 24px;
    font-weight: normal;
    color:  aquamarine;;
    margin: 5px 0;
  }
  
  /* Line under the section */
  hr {
    width: 50%;
    border: 1px solid #ddd;
    margin: 20px auto;
  }
  
  /* Navbar styling */
.navbar {
    display: flex;
    justify-content: space-between; /* Aligns the logo and links */
    align-items: center;
    padding: 10px 20px;
    background: linear-gradient(135deg, #0d1b2a, #1b2631);
    color: aquamarine; /* Text color */
  }
  
  /* Styling the navigation links */
  .nav-links {
    list-style-type: none; /* Removes bullets */
    display: flex;
  }
  
  .nav-links li {
    margin: 0 15px;
  }
  
  .nav-links a {
    text-decoration: none; /* Removes underline */
    color:  aquamarine; /* Link color */
    font-size: 18px;
    font-weight: bold;
  }
  
  /* Optional: Change link color on hover */
  .nav-links a:hover {
    color: white;
  }
  
  /* Container styling for the rest of the content */
  .container {
    position: relative; /* Needed for positioning */
    width: 100%;
     /* Limit the maximum width */
    padding: 20px;
    border-radius: 10px; /* Rounded corners */
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5); /* Subtle shadow */
    color: aquamarine; /* Text color */
    text-align: center; /* Center text */
    overflow: hidden; /* Hide overflow */
    margin: 50px auto; /* Center container with margin */
}
.video-background {
            position: absolute; /* Positioning */
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover; /* Cover the entire area */
            z-index: -1; /* Place it behind the content */
        }


        @keyframes pulse {
            0%, 100% {
                transform: scale(1);
                opacity: 0.1;
            }
            50% {
                transform: scale(1.1);
                opacity: 0.3;
            }
        }

  
  
  /* General styling for the section */
.skills-section {
    text-align: center;
    margin: 40px 0;
}

.skills-section h2 {
    font-family: 'Montserrat', sans-serif;
    font-size: 30px;
    color: aquamarine;
    margin-bottom: 20px;
}

/* Container for the cards */
.skills-cards {
    display: flex;
    justify-content: space-around; /* Distributes cards evenly */
    flex-wrap: wrap; /* Allows cards to wrap on smaller screens */
    gap: 20px; /* Space between cards */
    padding: 20px;
}

/* Individual card styling */
.card {
    background-color: #1a1a1a; /* Dark background for contrast */
    color:  aquamarine;
    width: 180px;
    padding: 20px;
    text-align: center;
    border-radius: 10px; /* Rounded corners */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Subtle shadow */
    transition: transform 0.3s ease; /* Smooth scaling on hover */
}

/* Scaling the card on hover */
.card:hover {
    transform: scale(1.1); 
    /* Slightly increase the size */
}

/* Icon styling inside each card */
.card i {
    font-size: 50px;
    margin-bottom: 10px;
    color: black /* Gold color for icons */
}

/* Title of each skill */
.card h3 {
    font-size: 20px;
    font-family: 'Montserrat', sans-serif;
    color:  yellow;
    margin-top: 10px;
}
.card.html {
    background: linear-gradient(135deg, #0d1b2a, #1b2631);
/* Soft Red */
    color:  aquamarine; /* White text for contrast */
    border: 1px solid aquamarine;
}
.card.html:hover {
    background: linear-gradient(135deg, #00ff7f, #20b2aa); /* Gradient background on hover */
    color: #0d1b2a; /* Text color on hover */
}

.card.css {
    background: linear-gradient(135deg, #0d1b2a, #1b2631); /* Soft Blue */
    color:  aquamarine; /* White text for contrast */
    border: 1px solid aquamarine;
}
.card.css:hover {
    background: linear-gradient(135deg, #00ff7f, #20b2aa); /* Gradient background on hover */
    color: #0d1b2a; /* Text color on hover */
}

.card.js {
    background: linear-gradient(135deg, #0d1b2a, #1b2631);
    color: #000000; /* Black text for contrast */
    border: 1px solid aquamarine;
}
.card.js:hover {
    background: linear-gradient(135deg, #00ff7f, #20b2aa); /* Gradient background on hover */
    color: #0d1b2a; /* Text color on hover */
}

.card.bootstrap {
    background: linear-gradient(135deg, #0d1b2a, #1b2631);
    color:  aquamarine; /* White text for contrast */
    border: 1px solid aquamarine;
}
.card.bootstrap:hover {
    background: linear-gradient(135deg, #00ff7f, #20b2aa); /* Gradient background on hover */
    color: #0d1b2a; /* Text color on hover */
}
.study{
    padding: 20px;
    margin: 20px;
    justify-content: center;
    text-align: center;
}
.School{
    font-weight: bold;
    font-family: sans-serif;
    margin: 20px;
    text-align: center;

}
.College >h2 {
    margin-top: 20px;
    margin-bottom: 20px;

}
#sch{
    margin-bottom: 20px;
}



</style>
<body>
  <div class="navbar">
    <h1>Prince's Portfolio</h1>
    <ul class="nav-links">
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Projects</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </div>
    <div class="container">
      

      <video autoplay muted loop class="video-background">
        <source src="./Black Playful Animated Welcome Channel Youtube Intro Video.mp4" type="video/mp4">

      </video>
      <div class="container-2">
        <img src="./my-image.jpeg" alt="Prince's Photo">
        <h1 class="left">Prince</h1>
        <h2>Front End Developer</h2>
      </div>
      <hr>
    </div>
    <div class="skills-section">
      <h2>Skills & Technologies</h2>
      <div class="skills-cards">
          <div class="card html">
              <i class="fab fa-html5"></i>
              <h3>HTML5</h3>
          </div>
          <div class="card css">
              <i class="fab fa-css3-alt"></i>
              <h3>CSS3</h3>
          </div>
          <div class="card js">
              <i class="fab fa-js-square"></i>
              <h3>JavaScript</h3>
          </div>
          <div class="card bootstrap">
              <i class="fab fa-bootstrap"></i>
              <h3>Bootstrap</h3>
          </div>
      </div>
  </div>
  
  <div class="study">
    <h1>Studies</h1>
  <div class="College">
    <h2>College</h2>  

    <div>
      <h2>World College Of Technology and Management</h2>
    </div>
    <hr>
    <div class="School">
      <h2 id="sch">School</h2>
    <h2>Basant Valley Public School</h2>
  </div></div>
    </div>
    

    
</body>
</html>
