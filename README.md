# Sealink
<!DOCTYPE html>
<html lang="en">
  <!-- Head start here -->
  <head>
    <meta charset="utf-8">
    <title>Demo Page</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="">
    <meta name="author" content="">

    <!-- Le styles -->
    <link href="http://getbootstrap.com/2.3.2/assets/css/bootstrap.css" rel="stylesheet">
    <style type="text/css">
      body {
        padding-top: 20px;
        padding-bottom: 40px;
      }
  
      .left{  text-align: left !important;
            font-weight: bold;
      }
      .center{  text-align: center !important;
            font-weight: bold;
      }
      .right{  text-align: right !important;
            font-weight: bold;
      }
      a.effect1{
          color: green !important;
      }
      a.effect2{
         color: blue !important;
      }
      a.effect3{
          color: #3A7C9D !important;
      }
    </style>
    <link href="http://getbootstrap.com/2.3.2/assets/css/bootstrap-responsive.css" rel="stylesheet">

    <!-- HTML5 shim, for IE6-8 support of HTML5 elements -->
    <!--[if lt IE 9]>
      <script src="http://getbootstrap.com/2.3.2/assets/js/html5shiv.js"></script>
    <![endif]-->
    <!-- Fav and touch icons -->
    <link rel="apple-touch-icon-precomposed" sizes="144x144" href="http://getbootstrap.com/2.3.2/assets/ico/apple-touch-icon-144-precomposed.png">
    <link rel="apple-touch-icon-precomposed" sizes="114x114" href="http://getbootstrap.com/2.3.2/assets/ico/apple-touch-icon-114-precomposed.png">
    <link rel="apple-touch-icon-precomposed" sizes="72x72" href="http://getbootstrap.com/2.3.2/assets/ico/apple-touch-icon-72-precomposed.png">
    <link rel="apple-touch-icon-precomposed" href="http://getbootstrap.com/2.3.2/assets/ico/apple-touch-icon-57-precomposed.png">
    <link rel="shortcut icon" href="http://getbootstrap.com/2.3.2/assets/ico/favicon.png">
  </head>
  <!-- Head end here -->
  <!-- Body start here -->
  <body>
      <!-- Main content start here -->
      <div class="container">
          <h1>Heading</h1>
          <p>
            <a href='#'>
              <span class='textnav'>Paragraph </span><span class='carat'>></span>
            </a>
            <a href='#'>
              <span class='textnav'>Table </span><span class='carat'>></span>
            </a>
            <a href='#'>
              <span class='textnav'>Image </span><span class='carat'>></span>
            </a>
          </p>
          <p>HTML 4.0 is becoming the standard. As of the writing of this tutorial, Microsoft Explorer version 5.0 is out with full HTML 4.0 support.
          <a href="#" alt="" class="effect1">Netscape Navigator 5.0</a> is not far behind, and soon the commands below will start to become mainstream.</p>
          <p>Here's a quick look at how HTML 4.01 affects tables. You are already familiar with some of the tags and attributes. For example,
          
          <a href="#" alt="" class="effect2">BORDERCOLOR has been</a> in use for a while as a proprietary Internet Explorer tag. It has just now been written into the HTML 4.01 code. </p>
          <p>I have offered as many examples as possible. Many will simply not work because you don't yet have the browser version that
          supports it. Don't worry, neither did I when
          <a href="#" alt="" class="effect3">I wrote this tutorial</a>. Hopefully you'll be able to visit this tutorial in the future to test what your new browser will and will not do. I am only going to hit the tags and attributes new through HTML 4.01 in this tutorial. If you'd like to get into the basics of table creation, start with my table tutorials.</p>
       
          <!-- Table start here -->
          <table border='3' bordercolor='red' id='results' width='500' class="table table-striped table-bordered table-hover">
              <thead>
                  <tr>
                      <td class="left">Heading 1</td>
                      <td class="center">Heading 2</td>
                      <td class="right">Heading 3</td>
                  </tr>                  
              </thead>
              <tbody>
                  <tr>
                      <td>Cell Data</td>
                      <td>Cell Data</td>
                      <td align='right'>Cell Data</td>
                  </tr>
                  <tr>
                      <td class='high'>Cell Data</td>
                      <td>Cell Data</td>
                      <td align='right'>Cell Data</td>
                  </tr>
                  <tr>
                      <td>Cell Data</td>
                      <td>Cell Data</td>
                      <td align='right'>Cell Data</td>
                  </tr>
              </tbody>
          </table>
          <!-- Head end here -->
          <div class="row">
              <div class="span4"></div>
              <div class="span4">
                  <img border='0' height='281' id='image' src='http://www.clipartkid.com/images/607/country-and-mobile-redirect-for-wordpress-dwpsxm-clipart.jpg' width='500'>
              </div>
              <div class="span4"></div>
          </div>    
      </div>
      <!-- Main content end here -->
  </body> <!-- Body end here -->
</html> 
