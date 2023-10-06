 <!DOCTYPE html>
 <html>
 <head>
 	<meta charset="utf-8">
 	<meta name="viewport" content="width=device-width, initial-scale=1">
 	<title>this is a javascript</title>
 </head>
 <body>
 <script type="text/javascript">
 	var age;
 	age=parseInt(prompt("Enter you age"));
 	if(age>=18)
 		document.write("eligiable for voteing");
 	else
 		document.write("Not eligiable for voteing");
 </script>
 </body>
 </html>


 Greatest number

  <html>
 	<head>
 		
 	</head>
 	<body>
 		<script type="text/javascript">
 			var a=parseInt(prompt("Enter 1st no"));
 			var b=parseInt(prompt("Enter 2nd no"));
 			if(a>b)
 				document.write("a is greater");
 			else
 				document.write("b is greater");
 		</script>
 	</body>
 </html>

 Armstorong Number
 <script>
 			var n,a1,a2,b1,b2;
 			n=parseInt(prompt("Enter any 3 digit no"));
 			a1=Math.floor(n/100);
 			b1=n%100;
 			a2=Math.floor(b1/10);
 			b2=b1%10;
 			x=a1*a1*a1;
 			y=a2*a2*a2;
 			z=b2*b2*b2;
 			if((x+y+z)==n)
 				document.write("armstrong Number");
 			else
 				document.write("not armstrong Number");
 		</script>

   WAP to calculate square if the number is odd and calculate the cube if the number is even?
  
   
   <script>
 		 	function sum(){
         var num=parseInt(prompt("num"));
         
         var res=0;
         if(num%2==0)
           res=num*num*num;
         else
           res=num*num;
         document.write(res);
     }
     sum()
</script>

   *)Nested If--else:-
   *) calculate the greatest number?

   <script type="text/javascript">
 		 	var a=parseInt(prompt("Enter 1st Number"));
 		 	var b=parseInt(prompt("Enter 2nd Number"));
 		 	var c=parseInt(prompt("Enter 3rd Number"));
 		 	if(a>b)
 		 	{
 		 		if(a>c)
 		 			document.write(" a is greater");
 		 		else
 		 			document.write("c is greater");
 		 	}
 		 	else
 		 	{
 		 		if(b>c)
 		 			document.write("b is greater");
 		 		else
 		 			document.write("c is greater");
 		 	}

 		 </script>

    
   check vowel and consonant



   <script>
 		 	var ch=prompt("Enter char");
 		 	if(ch=='a')
 		 		document.write("Vowel");
 		 	else
 		 		if(ch=='e')
 		 			document.write("Vowel");
 		 		else
 		 			if(ch=='i')
 		 				document.write("Vowel");
 		 			else
 		 				if(ch=='o')
 		 					document.write("Vowel");
 		 				else
 		 					if(ch=='u')
 		 						document.write("Vowel");
 		 					else
 		 						document.write("Consonent");
 		 </script>
  
  
 Multiple If:-
 <script>
 		 	 var num=parseInt(prompt("Enter Number"));

 		 	 if(num%3==0)
 		 	 	document.write("Divisible by 3");
 		 	 if(num%5==0)
 		 	 	document.write("Divisible by 5");
 		 	 if(num%7==0)
 		 	 	document.write("Divisible by 7");
 		 	 if(num%9==0)
 		 	 	document.write("Divisible by 9");
 		 </script>

    School marksheet

  <html>
 	<head>
 		  <script>
 		  	var p,c,m,tot,per;
 		  	var p=parseInt(prompt("Enter phy Number"));
 		  	var c=parseInt(prompt("Enter che Number"));
 		  	var m=parseInt(prompt("Entrer math Number"));
 		  	tot=p+c+m;
 		  	per=tot/3
 		  	if(per>60)
 		  		document.write(" 1st div");
 		  	else
 		  		if(per>=50)
 		  			document.write("2nd div");
 		  		else 
 		  		if(per>=40)
 		  			document.write("3rd div");
 		  		else
 		  			document.write("Fail");
 		  </script>
 	</head>
 </html>

   choice ur

   
 <script>
 		    var a,b,c,ch;
 		    ch=parseInt(prompt("Enter ur choice 1) add 2)sub 3) mult 4) div"));
 		    switch(ch)
 		    {
 		    case 1:
 		    	a=parseInt(prompt("Enter 1st no"));
 		    	b=parseInt(prompt("Enter 2nd no"));
 		    	c=a+b;
 		    	document.write("Add"+c);
 		    	break;
 		    case 2:
 		     a=parseInt(prompt("Enter 1st no"));
 		    	b=parseInt(prompt("Enter 2nd no"));
 		    	c=a-b;
 		    	document.write("sub"+c);
 		    	break;
 		    case 3: 
 		    	a=parseInt(prompt("Enter 1st no"));
 		    	b=parseInt(prompt("Enter 2nd no"));
 		    	c=a*b;
 		    	document.write("mult"+c);
 		    	break;
 		    case 4: 
 		    	a=parseInt(prompt("Enter 1st no"));
 		    	b=parseInt(prompt("Enter 2nd no"));
 		    	c=a/b;
 		    	document.write("div"+c);
 		    	break;
 		    default: document.write("invalid choice");
 		    }
 		  	
 </script>

   whail loop   
  
   
   
   <script>
               var i=2;
               while(i<=50)
               {
                    document.write("<br>"+name+""+i);
               
               i=i+2;
          }

    </script>


    
   <script type="text/javascript">
               var i=1,a;
               while(i<=50)
               {
                    a=i*i;
                    document.write("<br>"+a+"");        
                    i=i+1;
               }
     </script>

     1 4 9 16...2500
 
