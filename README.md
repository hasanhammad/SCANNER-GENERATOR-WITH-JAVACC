# SCANNER-GENERATOR-WITH-JAVACC

a simple tokens scanner using JAVACC

HOW TO RUN: 

1- DOWNLOAD (CAL.JJ) FILE

2- RUN CMD THE SAME DIRECTORY WHERE (CAL.JJ) HAS BEEN DOWNLOADED

3- NOW RUN THIS COMMAND LINE (JAVACC "FILENAME".JJ) IN MY CASE: JAVACC CAL.JJ

4- RUN THIS COMMAND LINE (JAVAC "CLASSNAME".JAVA)  "CLASS NAME: IT IS YOUR CLASS IN CAL.JJ FILE"

5- RUN THIS COMMAND LINE (JAVA "CLASSNAME" "INPUTFILENAME".TX) IN MY CASE: JAVA CAL CODE.TXT
   NOTE: THERE IS A TXT FILE (CODE.TXT) WHICH CONTAIN OUR INPUT
   YOU CAN WRITE YOUR INPUT IN A TXT FILE ACCORDING TO YOUR GRAMMER
   
   GRAMMAR :
P ==> D C  
D ==> id = (num , num) , D  
D  ==>  id = (num , num);  
C ==>  {L}  
L ==> S ; L 
L ==>  ԑ  
S ==>  id = (num , num)  
S ==>  X(id)++  
S ==>  X(id)-- 

S ==>  Y(id)++  
S ==>  Y(id)--
