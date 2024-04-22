# PHP_Cookies

<body style="background-color: lightblue;text-align: center;">


    <?php 

        $name = "user";
        $value = "<img src='upload\Mehedi.jpg'>";

        setcookie($name,$value,time()+5);

        if(isset($_COOKIE['user'])){

            echo "{$_COOKIE['user']}";
        }
        else{
            echo "Cookies Not Set";
        }



        //session_start();
        //echo $_SESSION['user'] = "<img src='upload\Mehedi.jpg'>";

    
    ?>
   
      
    
</body>

