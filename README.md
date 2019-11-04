PROJECT TITLE:  
Open Weather Forecasting 

Prerequities:
•	Used UFT Tool and VB Script language
•	Used Node.js as server.
•	Installed npm and used it for hosting the application locally.
•	Written automated test cases in UFT using VB script.
•	Run the test cases using the test data.

Installing:
•	Please Download UFT tool and install it.
•	Choose Add-in option: Web, Java, ActiveX
•	Download Node.js and install it.
•	Install npm.

Running the tests:
Written automated test cases using VB Script language based on the test data and run the tests.

Breakdown into end to end test:
Depends upon the requirements breakdown the test cases into different scenarios and written test cases according to that.

Coding style tests:
SystemUtil.Run "iexplore.exe","http://localhost:3000/",,SHOW_MAXIMISED.
Written the test case to access the application.

Deployment:
Used Jenkins for deploying the code.

Built with:
UFT: The tool used
Node.js: Hosting the application locally.

License:
The tool is licensed under Microsoft.


Challenges briefly:
•	Developing the automation scripts in UFT was tricky as all the objects in the application were being identified as Web Elements.
•	Had to spent considerable time initially to align the objects in web elements as a data set. 
•	It was slightly challenging as most of the objects had indifferent properties.
•	None of the elements had properties like HTML id or name. Hence identifying the objects uniquely was hard.
•	To thoroughly test all the features plenty of test cases were required.



We can discuss more in detail during the interview. Thankyou.

