# Web-Programming-with-MEAN
<html>
    <head>
        <title>
            Application Form
        </title>
    </head>
    <body bgcolor="CCFFFF"> 
        <br>
        <center>
        <h1>Online Application Form</h1>
        </center>
        <h1>Personal Information</h1>
        </center>
        <form>
            <font size = "+2">
            <label>Firstname:</label>
            <input type = "text" name = "Firstname" size = "20"/> <br>
            <label>Lastname:</label>
            <input type = "text" name = "Lastname" size = "20"/> <br> <br>
            <label>DOB:</label>
            <input type = "date" name = "begin" placeholder = "dd-mm-yyyy"/> <br> <br>
            <label>Gender:</label><br>  
            <input type ="checkbox" name ="male"/> Male <br>  
            <input type ="checkbox" name ="female"/> Female <br>  
            <input type ="checkbox" name ="other"/> Other <br> <br>
            <label>Father Name:</label>
            <input type = "text" name = "Father Name" size = "20"/> 
            <lable>Ph.no:</lable>
            <input type = "text" name = "Ph.no" size = "20"/>
            <lable>Occupation:</lable>
            <input type = "text" name = "Occupation" size = "20"/> <br>
            <label>Mother Name:</label>
            <input type = "text" name = "Mother Name" size = "20"/>
            <label>Ph.no:</label>
            <input type = "text" name = "Ph.no" size = "20"/>
            <label>Occupation:</label>
            <input type = "text" name = "Occupation" size = "20"/> <br> <br>
            <lable>Hobbies:</lable>
            <input type = "text" name = "Hobbies" size = "20"/> <br> <br>
            <label>Course:</label>  
            <select>  
                <option value="Course">Course</option>  
                <option value="BCA">BCA</option>  
                <option value="BBA">BBA</option>  
                <option value="B.Tech">B.Tech</option>  
                <option value="MBA">MBA</option>  
                <option value="MCA">MCA</option>  
                <option value="M.Tech">M.Tech</option>  
            </select>
            </font>
            <h1>Academic Performance:</h1> 
            <font size = "+2">
                <label>10th Start year:</label>
                <input type = "text" name = "10th Start year" size = "20"/>
                <label>10th year of pass:</label>
                <input type = "text" name = "10th year of pass" size = "20"/>
                <label>10th CGPA:</label>
                <input type = "text" name = "10th CGPA" size = "20"/> <br>
                <label>Inter Start year:</label>
                <input type = "text" name = "Inter Start year" size = "20"/>
                <label>Inter year of pass:</label>
                <input type = "text" name = "Inter year of pass" size = "20"/>
                <label>Inter CGPA:</label>
                <input type = "text" name = "Inter CGPA" size = "20"/>
            </font>
            <h1>Contact Details:</h1>
            <font size = "+2">
                <label>Phone:</label>  
                <input type="text" name="country code"  value="+91" size="2"/>   
                <input type="text" name="phone" size="10"/> <br> <br>
                <label>Email ID:</label>  
                <input type="email" id="email" name="email" size = "20"/> <br> <br>  
                <label>Address:</label> <br>
                <textarea cols = "80" rows = "5" value = "address"> </textarea> <br> <br>  
                <input type ="checkbox" name ="I Confirm"/> I confirm<br>
                <center>
                    <input type="button" value="Submit"/>
                </center>
            </font>
        </form>
    </body>
</html>
