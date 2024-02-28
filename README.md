 <html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
         
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Web Page</h1>
    </header>
    <div class="container">
        <h2>STATE TRANSITION TESTING</h2>
        <p>Hello, I'm a web developer.</p>
        <p>State Transition Testing is a black box testing technique in which changes made in input conditions cause state changes or output changes in the Application under Test. State transition testing helps to analyze behaviour of an application for different input conditions.</p>
        
   <p> State-Transition testing is the one of the black box testing & desing techniques which can be used to derive test cases (or) test for the application functions which go through several states 
        </p>
        <h2> APPLICATION FUNCTIONALITIES &<br>
            SEVERAL STATES </h2>
            <p>For example let us look in to net banking software <br>
                when you visit a site you can see a login details </p>

<img src="sbi.png" alt>
<br>

<p>now you can see the above login page now if you enter the login details and login if the password is wrong it give 2nd time to enter the correct if you enter the correct password you can access the site but if you again enter the wrong password at the 2nd time it gives 3rd chance to enter the correct password in 3rd time if you enter the wrong password the access will be locked and its shows your accoungt is locked</p>
    <br>
    <p> WRONG PASSWORD <br>
        WRONG PASSWORD <br>
        WRONG PASSWORD <br>
        ACCOUNT LOCKED 
    </p>
<img src="state.jpg"alt>
        <br>
        <pr> for the 4th try it will be blocked the access <br>
            and you can't able to acces the data on that site this is the state transition testing  
        </pr>
        <br>






  <p>Identify States: Begin by identifying all possible states the system can be in. These states represent different conditions or situations that the system may encounter during its operation 
<br> 
Identify Transitions: Identify the events or inputs that cause the system to transition from one state to another. These transitions could be triggered by user actions, system events, or other external stimul<br>
Create a State Transition Diagram: A state transition diagram visually represents the states, transitions, and conditions triggering those transitions. It provides a clear overview of the system's behavior.<br>
Design Test Cases: Based on the state transition diagram, design test cases that cover transitions between states, including both valid and invalid transitions. Each test case should specify the initial state, the input or event triggering the transition, the expected outcome, and the resulting state.<br>

Execute Test Cases: Execute the designed test cases against the system under test. Monitor the system's behavior as it transitions between states and verify that it behaves as expected according to the defined transitions.<br>Verify Results: Compare the actual behavior of the system with the expected behavior specified in the test cases. Identify any discrepancies or deviations and report them as defects if necessary.
 



State transition testing is particularly useful for systems with complex behaviors, such as user interfaces, embedded systems, and communication protocols. It helps ensure thorough test coverage by systematically exploring the various states and transitions within the system.




</p>





</div>
</body>
</html>
