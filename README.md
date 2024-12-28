<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <pre>
                         <h1>APPLICATION FORM</h1>
    </pre>
    <FORM ACTION="/SUBMIT.PHP" METHOD="POST">
        <LABEL FOR="FIRSTNAME">FIRSTNAME:</LABEL>
        <INPUT TYPE="TEXT" ID="FIRSTNAME" NAME="FIRSTNAME" PLACEHOLDER="ENTER FIRST NAME" REQUIRED>
            <BR><BR>
                <LABEL FOR="DATE OF BIRTH">DATE OF BIRTH:</LABEL>
                <INPUT TYPE="PASSWORD" ID="DATE_OF_BIRTH" NAME="DATE_OF_BIRTH" PLACEHOL DER="MM/DD/YYYY" required>                         <LABEL FOR="AGE">AGE:</LABEL>                                               <INPUT TYPE="NUMBER" ID="AGE" NAME="AGE" MIN="1" MAX="100">
                     <BR><BR>                                                                                                                                                                  
                        <SELECT ID="GENDER">
                            <OPTION GENDER="MALE">MALE</OPTION>
                              <OPTION GENDER="FEMALE">FEMALE</OPTION>  
                        </SELECT>                                                                                                                                                    
                        <BR><BR>
                          <LABEL FOR="POSITION ">POSITION AVAILABLE:</LABEL>
                          <INPUT TYPE="RADIO" ID="JUNIOR DEVELOPER" NAME="POSITON" VALUE="JUNIOR DEVELOPER" >JUNIOR DEVLOPER

                            <INPUT TYPE="RADIO" ID="MID-DEVELOPER" NAME="POSITION" VALUE="MID-LEVEL DEVELOPER">MID-DEVLOPER
                                <INPUT TYPE="RADIO" ID="SENIOR DEVELOPER" NAME="POSTION" VALUE="SENIOR DEVELOPER" >SENIOR DEVLOPER
                                    <BR><BR>
                                        <LABEL FOR="LANGUAGE">PROGRAMMING LANGUAGES:</LABEL>
                                        <INPUT TYPE="RADIO" ID="JAVA" NAME="LANGUAGE" VALUE="JAVA">JAVA
                                            <INPUT TYPE="RADIO" ID="JAVASCRIPT" NAME="LANGUAGE" VALUE="JAVACRIPT" >JAVASRIPT
                                                <INPUT TYPE="RADIO" ID="PYTHON" NAME="LANGUAGE" VALUE="PYTHON" >PYTHON
                                                    <BR><BR>
                                                    <LABEL FOR="PASSWORD">PASSWORD:</LABEL>                                                                                <LABEL FOR="CONFORM PASSWORD">CONFORM PASSWORD:</LABEL>
                                                                                                                                                                        <INPUT TYPE="PASSWORD" ID="CONFORM PASSWORD" NAME="CONFORM PASSWORD" >
                                                    <INPUT TYPE="PASSWORD" ID="PASSWORD" NAME="PASSWORD" PLACEHOLDER="ENTER PASSWORD" >

    </FORM>       
</body>
</html>
