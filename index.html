

<?php
 $host = "localhost";
 $username = "root";
 $password = "";
 $databasename = "abbrivez";


 $conn = mysqli_connect($host, $username, $password) or die("cannot connect to db");
 $db = mysqli_select_db($conn, $databasename) or die("cannot select db");
 $output = "";

 //collect

    if(isset($_POST['search'])){
        $searchQuery = $_POST['search'];


        if( !empty($_POST['search']) ){
            $query = mysqli_query($conn, "SELECT * FROM meaning WHERE title LIKE '%$searchQuery%' " ) or die("could not search database");
            $count = mysqli_num_rows($query);

           

            if($count == 0){
                $output = 'There were no search results';
            } else {
                while($row = mysqli_fetch_array($query)){
                    $title = $row['title'];
                    $description = $row['descriptions'];


                    $output .= '<div class = "check-output" 
                    style= "box-shadow: 0px 3px 10px #000;
                            padding:1.5rem; 
                            background-color:#fff;
                            "> '
                     .$description.'</div>';
                }
            }
        } else {
            $output = "There was no search results";
        }
    }



?>


<?php

$host = "localhost";
$username = "root";
$password = "";
$databasename = "abbrivez";


$conn = mysqli_connect($host, $username, $password) or die("cannot connect to db");
$db = mysqli_select_db($conn, $databasename) or die("cannot select db");

$title = "";
$description = "";
$error1 = "Add A title Please";
$error2 = "Add a meaning";
$errors = array();
$success= "Your Abbrievation has been added succesfully";
$print= "";

// if user enters an abbrievation and its meaning, run this script

   // validating the queries using the post method

   if(isset($_POST['add'])){
       $title = mysqli_real_escape_string($conn, $_POST['title']);
       $description = mysqli_real_escape_string($conn, $_POST['descriptions']);


       // ensuring the form is  filled correctly

       if(empty($title)){
           echo ($error1);

       }

       if(empty($description)){
           echo ($error2);
       }

       // once no error is discovered, run the following script

       if(empty($errors) == 0){
           $sql = "INSERT INTO meaning(title, descriptions ) VALUES ('$title', '$description')";

       }

       if ($conn->query($sql) === TRUE) {
        echo $success;
    }
   }



?>






<!DOCTYPE html>
<!--[if lt IE 7]>      <html class="no-js lt-ie9 lt-ie8 lt-ie7"> <![endif]-->
<!--[if IE 7]>         <html class="no-js lt-ie9 lt-ie8"> <![endif]-->
<!--[if IE 8]>         <html class="no-js lt-ie9"> <![endif]-->
<!--[if gt IE 8]><!--> <html class="no-js"> <!--<![endif]-->
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>ABBRIVEZ</title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="css/style.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    </head>
    <body>
        <!--[if lt IE 7]>
            <p class="browsehappy">You are using an <strong>outdated</strong> browser. Please <a href="#">upgrade your browser</a> to improve your experience.</p>
        <![endif]-->
        
    </body>
    <div class="container"> 
        <header class="header">
            <div class="menu">
                <div class="menu-item">
                        abbrivez
                </div>
            </div>

            
            <!-- check social media abbrievation section -->

            <div class="check">
                <p class="check-text">
                    Check your social media abbrievations 
                </p>
                <div class="check-search">
                    <form action = "index.php" method= "post" class="check-form">
                        <input type="text" name="search" value="" class="check-form-input" placeholder="Enter Your Abbrievation" required>
                        <button class="check-form-btn" type="submit"> SEARCH </button>
                    </form>
                </div>
                <div class="check-output">
                <?php print $output; ?>
                </div>

            </div>

        </header>

                    <!-- add social media abbrievation section --> 

        <div class="add">
            <div class="add-text">
                Add your own social media abbrievations
                
            </div>
            <div class="add-form">
                <form action="POST" class="form" action="">
                    <input type="text" class="add-input1" placeholder="Enter abbrievation" name="title" required>
                    <input type="text" class="add-input2" placeholder="Enter meaning" name="descriptions" required>
                    <button class="add-button" type="submit" name="add"> ADD </button>
                </form>
                <div class="print">
                    <?php print $success; ?>
                </div>


                
            </div>
        </div>
                        <!-- quote  section -->

        <div class="quote">
            <div class="quote-body">
                <p class="quote-heading">FAMOUS QUOTES </p>
                <p class="quote-text"> A STICH IN TIME SAVES NINE    - <em>anonynmous</em> </p>
            </div>
        </div>

        <div class="footer">
            <div class="foooter-body">
                

                <div class="footer-social">
                    <p class="footer-social-text">You can follow me and my work on <a href="https://www.github.com/ddamox"><i class="fa fa-github "> </i></a>
                         <a href="https://www.twitter.com/ddamox"><i class="fa fa-twitter "> </i></a> 
                         <a href="https://www.codepen.io/ddamox"><i class="fa fa-codepen "> </i></a>
                    </p>
                    
                    <p class="footer-email"> You can just shoot a  <a href="https://www.twitter.com/ddamox"><i class="fa fa-envelope "> </i> </a>at me <a href="www.gmail.com/damilolashofoluwe01" class="email"> damilolashofoluwe01@gmail.com</a></p>
                </div>
                <div class="footer-text">
                    
                        developed  with  &nbsp; <i class="fa fa-heart" style="color:red;" ></i>&nbsp; by &nbsp; &nbsp;<p class="name">  <em>Damilola Spencer </em>  </p> &nbsp; &nbsp; for his portfolio site.
                            &copy; abbrivez
                    </div>
            </div>
        </div>
    </div>
</html>           
