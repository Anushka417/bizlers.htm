<!DOCTYPE html>
<html>
<head><title>bizlers</title>
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <meta http-equiv="x-ua-compatible"content="ie=edge">
  
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script>
$(document).ready(function(){
  $("form").submit(function(){
    alert("Submitted");
  });
  $("submit").click(function(){
    $("form").submit();
  });  
});
</script>
<style>
body {
  margin: 0;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  width: 5%;
  background-color: #f1f1f1;
  position: fixed;
  height: 100%;
  overflow: auto;
}

li a {
  display: block;
  color: grey;
  padding: 8px 16px;
  text-decoration: none;
}

li a.active {
  background-color: purple;
  color: grey;
}

li a:hover:not(.active) {
  background-color: #555;
  color: white;
}
.search input[type=text]{ 
            width:200px; 
            height:15px; 
            border-radius:70px; 
            border: none; 
  
        } 
          
        .search{ 
            float:right; 
            margin:2px; 
            border: 1px solid black;
            border-radius: 35px;
           background-color:white;
           padding-top: 5px;
           padding-right: 3px;
           padding-bottom: 5px;
          padding-left: 3px;
  
        } 
          
        .search button{ 
            background-color:white; 
            color: grey; 
            float: left; 
            padding: 2px 1px; 
            margin-right: 16px;
            font-size: 12px; 
            border: none; 
            cursor: pointer; 
        } 
        table, td, th 
        {
          border: 1px solid black;
          margin:10px;
        }

       table {

             border-collapse: collapse;
             width: 300%;
            }

       th {
           background-color: rgba(0,0,0,0.3);
           text-align: left;
          }
          th, td {
               padding: 5px 105px 5px 5px;
              
            }
            .blah{
  max-width:180px;
}
input[type=file]{
padding:0px;
background:grey;}

</style>
</head>
<body>

  <nav>
  <div class="hbar" style="position: top; margin-left:0%;"><ul>
  <li><a class="active" href="#home"><i class="fa fa-bars" style="font-size: 30px;"></i></a></li></ul>
    <img src="C:\Users\ANUSHKA\Desktop\company_logo-2.png" alt="company_logo" height="36%" width="36%" style="margin-left: 5%">
    <div style="float:right; font-size: 16px;  ">
      RENEE MCKELVEY&nbsp;&nbsp;&nbsp;&nbsp;<i class="fa fa-user-circle-o" style="float: right;font-size: 30px;">
        </i><br> Account Settings 
    </div>



    <hr>
  </div>
  <div class="vbar"style="position:fixed;margin:0px">
<ul>
   
  <li><a href="#search"><i class="fa fa-search"style="font-size: 28px;"></i></a></li>
  <li><a href="#home"><i class="fa fa-home"style="font-size: 28px;"></i></a></li>
  <li><a href="#graph"><i class="fa fa-area-chart"style="font-size: 28px;"></i></a></li>
  <li><a href="#public"><i class="fa fa-users"style="font-size: 28px;"></i></a></li>
  <li><a href="#setting"><i class="fa fa-cog"style="font-size: 28px;"></i></a></li>
</ul>
</div>
</nav>
  <div class="container ">
    <div class="row">
      <div class= "col-12 col-sm-4 col-md-3"style="margin-left:1%;margin-top:5%;margin-bottom: 10%;">
         <h1 style="color: grey;"> User List </h1>
           
            <div class="search"> 
              
            <form action="#"> 
                
                <button> 
                    <i class="fa fa-search" style="font-size: 18px;float: left"><input type="text"placeholder=" Search.." name="search">
                    </i> 

                </button> 
            </form> 
        
            </div>
            

            <table>
           <tr>
             <th>Name</th>
             <th>Role</th>
             <th>Actions</th>
           </tr>
            <tr>
  <td>Ada Lovelace</td>
  <td>ADmin</td>
  <td><i class="fa fa-pencil" style="font-size:24px"></i></td>
  </tr>
  <tr>
  <td>Grace Hopper</td>
  <td>Developer</td>
  <td><i class="fa fa-pencil" style="font-size:24px"></i></td>
  </tr>
  <tr>
  <td>Margaret Hamilton</td>
  <td>QA</td>
  <td><i class="fa fa-pencil" style="font-size:24px"></i></td>
  </tr>
  <tr>
  <td>Joan Clarke</td>
  <td>Manager</td>
  <td><i class="fa fa-pencil" style="font-size:24px"></i></td>
  </tr>
  <tr>
  <td><script>
    function myFunction(){document.getElementById("frm1").submit();
  }
  </script></td>
  <td><script>
    function myFunction(){document.getElementById("role").submit();
  };</script></td>
  <td><i class="fa fa-pencil" style="font-size:24px"></i></td>
</tr>
</table>

      </div>
      
    </div>

  </div>
   
    
    
   <div class="container"style="margin-left:7%;height:100px;">
     
    <div class="row">
      
      <div class="col-sm-8">
        <h3 style="color: grey;">New User Details  </h3><hr>
          <input type="text" name="username" placeholder="Username">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="email" name="email" placeholder="Email">
          <br><br>
          <form>
          <input type="text" name="firstname" placeholder="First Name">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;<input type="text" name="lastname" placeholder="Last Name">
      
           <br><br>
           <select id="role" name="role">
             <option>Role</option>
             <option>Admin</option>
             <option>Developer</option>
             <option>Manager</option>
             <option>QA</option>
            </select>
             <br><br>
          <input type="checkbox" name="checkbox"><level for="checkbox">Send email confirmation</level>
          <br>
          <br><button style="padding: 2px 8px 2px 8px;background-color: #4B0082;">Add User</button>
          &nbsp;&nbsp;&nbsp;<input class="button" type="button"style="padding: 2px 4px 2px 4px;" onclick="window.location.replace('bizlers.htm')" value="Cancel"></div></form>
           <div class="col-sm-4">
             <h3 style="color: grey;"> Profile Picture </h3><hr>
                
                <p><img id="output" width="200" src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTBpGM-GMRD2fstA4d6A9RsdeEBmYcYimf0QpJwJVYdN4YnV4Ix&usqp=CAU" /></p>
               <p><input type="file"  accept="image/*" name="image" id="file"  onchange="loadFile(event)" style="display: none;"></p>
              <p><button ><label for="file" style="cursor: pointer;">Select Image</label></button></p>
              

                   <script>
                       var loadFile = function(event) {
                       var image = document.getElementById('output');
                         image.src = URL.createObjectURL(event.target.files[0]);
                       };
                        </script>
            </div>
      
    </div>

  </div> 
  
    
</body>
</html>

