# homepage
<!DOCTYPE html>
<html lang="en">
    <head>
      <meta charset="UTF-8" />
      <meta http-equiv="X-UA-Compatible" content="IE=edge" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <title>SignUp Form</title>
      <style>
        body{
        background:gray
        }
        .wrap{
        width:350px;
        margin:auto;
        background:#00adee;
        margin-top:50px;
        padding:5px;
        }
        form
        {
        padding:10px;
        font-family:arial;
        border:1px dotted white;
        margin:10px;
        }
        h2{
        text-align:center;
        background:pink;
        color:white;
        padding:10px;
        border-radius:10px;
        
        }
        input{
        padding:10px;
        margin:10px;
        border-radius:5px;
        border:none;
        }
        input[type=text],input[type=email],input[type=number],input[type=password]
        {
        width:90%;
        }
        input[type=submit]{
        width:95%;
        background:orange;
        cursor:pointer;
        font-size:18px;
        font-weight:bold;
        color:white;
        }
        input[type=submit]:hover{
        background:green;
        }
        select{
        padding:12px;
        width:30%;
        border-radius:4px;
        }
        
        option{
        padding:12px;
        width:20%;
        
        }
        </style>
    </head>
  
    <body>
      <h2>Online Form</h2>
      <form id="form">
        <div>
          Username:
          <br />
          <input type="text" id="username" required />
        </div>
        <br />
        <div>
          Password:
          <br />
          <input type="password" id="password" required />
        </div>
        <br />
        <div>
          Email:
          <br />
          <input type="email" id="email" required />
        </div>
        <br />
        <div>
          Birth date:
          <br />
          <input type="date" id="birthdate" required />
        </div>
        <br />
        <div>
          City:
          <br />
          <select id="city">
            <option>Mumbai</option>
            <option>New Delhi</option>
            <option>Bangalore</option>
            <option>Hyderabad</option>
          </select>
        </div>
        <br />
        <div>
          Programming Languages Known:
          <br />
          <input type="checkbox" id="c" value="C" />C
          <input type="checkbox" id="cpp" value="C++" />C++
          <input type="checkbox" id="java" value="Java" />Java
          <input type="checkbox" id="javascript" value="JavaScript" />JavaScript
          <input type="checkbox" id="python" value="Python" />Python
        </div>
        <br />
        <button type="submit">Submit</button>
      </form>
      <script src="index.js"></script>
    </body>
  </html>
