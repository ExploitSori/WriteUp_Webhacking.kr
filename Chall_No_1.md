#Webhacking.kr_Challenge No.1  

php source code auditing 
```php
<?php  
if(eregi("[^0-9,.]",$_COOKIE[user_lv])) $_COOKIE[user_lv]=1;  
if($_COOKIE[user_lv]>=6) $_COOKIE[user_lv]=1;  
if($_COOKIE[user_lv]>5) @solve();  
?>  
```
> level<5&&level>=6  

chrome Application Cookie edit install  
level cookie modifi  

clear!~
