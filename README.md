# JavaScript-events
COLOR CHANGE ON CLICK (EVEN OR ODD)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    
</head>
<body>


       <div class="outer">


   <p id="demo" style="color: black; font-size: 30px; font-family: Verdana, Geneva, Tahoma, sans-serif;"> </p>
   
   <div id="change" style="height:160px; width: 350px; border:solid 2px;">
   
  </div> <br>  
  
  
    <label style="font-size: 25px; color: teal;">ENTER NUMBER</label>
    <input text="text" id="txt"><br>
    <button type="button"  onclick="test();" style="color: teal; width: 25%; ">click</button>

</div>
  

        <script>
           
            document.getElementById('txt').value;
            
           function myfunction(color)
            {
            
                document.getElementById("change").style.background=color;
                
            
        }
            


            function test(){

             
            var txt = document.getElementById('txt').value;
                
               if(txt%2==0)
                {
                    
                    
                       console.log(myfunction("red")); 
                      console.log("DATA IS EVEN");
                      document.getElementById("demo").innerHTML="data is even"

                }
                   
                 else{
                          console.log(myfunction("green"));
                        console.log("DATA IS ODD");
                        document.getElementById("demo").innerHTML="data is odd"

                 } 



            }
           
                 
        </script>

        <style>
              .outer{
                  margin: 10%;
                  margin-left: 25%;
                  padding: 0;
                  border: 1px double;
                  justify-content: center;
                  align-content: center;
                  position: relative;
                  width: 30%;
                  padding: 10%;
              } 
              
               *{
                   text-transform: capitalize;
               } 
        </style>
         
</body>


</html>
