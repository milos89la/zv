# zv
zv

<?php
function print_zvezdica($b){
    for($i=0;$i<$b;$i++){
        for($j=0;$j<$b;$j++){
            if(
                ($i==0 || $i==$b-1) ||
                ($j==0 || $j==$b-1 )  ||
                ($i+$j==$b-1)
            )
            {
                echo'*';

            }
            else{
                echo "&nbsp; ";

            }
        }
        echo '<br>' ;
    }
}
print_zvezdica(6);
