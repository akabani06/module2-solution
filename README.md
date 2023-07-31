# module2-solution
Coursera Test
html :
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bondi</title>
    <link rel="stylesheet" href="css/all.min.css">
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/bootstrap.min.css.map">
    <link rel="stylesheet" href="master.css">
    <link rel="stylesheet" href="js/all.min.js">
</head>
<body>
    <div class="b">Our Minu</div>
  <div class="container">
    <section class="section">
      <div class="section-title1">Chicken</div>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    </section>

    <section class="section">
      <div class="section-title2">Beef</div>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    </section>

    <section class="section">
      <div class="section-title3">Sushi</div>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    </section>
  </div>

</body>
</html>


css :
body {
    font-family: Arial, sans-serif;
  }
  
  .container {
    max-width: 1000px;
    margin: 0 auto;
    padding: 20px;
    overflow: hidden;
  }
  
  .section {
    border: 1px solid black;
    background-color: #f0f0f0;
    margin-bottom: 20px;
    padding: 10px;
    box-sizing: border-box;
    background-color: #726e6e;
    position: relative; /* Added for positioning the section title */

  }
  
  .section-title1,
  .section-title2,
  .section-title3 {
    position:initial;
    top: 10px;
    right: 10px;
    background-color: #333;
    color: white;
    padding: 5px;
    font-weight: bold;
    width: fit-content;
    border: 2px solid black;
  }
  .section-title1 {
    background-color:rgb(176, 82, 100)
      }
    .section-title2 {
     background-color: #cf2121;
  
    }
    .section-title3 {
    background-color: #acc416;
    } 
  /* Desktop View */
  @media screen and (min-width: 992px) {
    .section {
      width: 33.33%;
      float: left;
    }
  }
  
  /* Tablet View */
  @media screen and (min-width: 768px) and (max-width: 991px) {
    .section {
      width: 50%;
      float: left;
    }
    
  }
  
  /* Mobile View */
  @media screen and (max-width: 767px) {
    .section {
      width: 100%;
      float: none;
    }
  }
    .b {
    color: #333;
    text-align: center;
    font-weight: bold;
    margin: 5px;
    padding: 5px;
    font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
    font-size: large;
  }
