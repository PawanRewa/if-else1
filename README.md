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
 
