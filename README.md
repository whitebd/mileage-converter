Mileage-Converter
=================

Converts mpg to kpl

<!DOCTYPE> 
 
        <html xmlns="http://www.w3.org/1999/xhtml"> 
          <head>
           <title>Gas Mileage</title>
            <meta http-equiv="content-type" content="text/html; charset=iso-8859-1" />

           <script type = "text/javascript">
              /*<![CDATA[*/
              function calcMPG() 
          { 
             var KPL= document.forms[0].KPL.value;
             var MPG= document.forms[0].MPG.value;
             
             if(isNaN(KPL)
               isNaN(MPG))          {
               window.alert("You must enter a number");
              }
                else
             {
               {
                 
              document.forms[0].KPL.value= ((MPG*.425)).toFixed(1);
       }
     }
   }

             /*]]>*/
            </script>
      </head>

      <body>
