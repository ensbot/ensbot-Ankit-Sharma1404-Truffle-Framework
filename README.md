# Truffle-Framework
LOTTERY CONTRACT

Introduction :- <br>
The lottery is a simple contract that allows users to send money to the contract that is stored in the contract.
The User has to end the lottery. Once the User ends the lottery a winner will be picked ('randomly' by current blocknumber).
Once the winner was picked only the winner is able to to transfer the money to his account by calling a getPrice funcion.
After the game was ended and the winner took the funds the User can reset the lottery and one can play again.
					
Contracts and Migrations :- <br>
						The contracts folder contains the Lottery.sol contract file as well as two more files:
						LotteryEventDefinitions.sol contains the event definitions of all the events used by the Lottery.sol contract.
						Migrations.sol is a contract provided by the truffle framework that manages the deployments of the Lottery.sol contract.
						The migrations folder contains the migration scrips according to the truffle specification.	


Test setup :-<br>
			The tests for the lottery contract are located in the test folder.<br>
			There are 2 kinds of tests available:<br>
				(a.) Tests written in javascript (using Mocha)<br>
				(b.) Tests written in Solidity<br>
					Both tests-styles were used according to the truffle specification.	

Run the Tests :-<br>
				Make sure to start the testrpc in a separate terminal by running the command: and type "testrpc"<br>
        
To run the test make sure you navigated into the current folder (smart-contract/lottery) folder in your terminal. Then run the command:

Truffle Test :-
			Since running the tests includes compiling the contract(s), you don't have to run truffle compile first - but you can if you want.					
