# Quetion3_Dhiraj
<?php

   $myarray = array(1,2,3,4,5,6,7,8,9,10);
   $total = count($myarray);
   echo "<h1>Display all even numbers</h1>";
                  echo "<ul>";

             foreach($myarray as $rw)
             {
              if(($rw%2) == 0 ){
              echo "<li>".$rw."</li>";
              }
             }
             echo "</ul>";
  ?>
