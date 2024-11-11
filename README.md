<html>
    <head>
        <meta cherset="UTF-8">
        <title>Register</title>
<link rel="stylesheet"
href="{{url-for('static',filename='style.css')}}">
    </head>
    <body></br></br></br></br></br>
        <div align="center">
            <div align="center" class="border">
                <div class="header">               
                    <h1 class="word">Register</h1>
                </div></br></br></br>
                <h2 class="word">
                    <form action="{{url-for('Register')}}"
                method="post">
            <div class="msg">{{msg}}</div>
        <input id="username"
    name="username" type="text"
placeholder="Enter Your username"
class="textbox"/>< /br></br>
<input id="password"
name="password" type="password"
placeholder="Enter Your password"
class="textbox"/></br></br></br>
<input id="email" 
name="email" type="text"
placeholder="Enter Your Email ID"
class="textbox"/</br></br>
input type="submit" class="btn"
value="sign UP"></br>
                </form>
                </h2>
                <p class="bottom">Already have an account? <a class="bottom">
                    href="{{url-for('register')}}"> sign up here</a></p>
                    </div>
                </div>
                </body>
                <html>- 
Priyaranjani1825/Priyaranjani1825 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
