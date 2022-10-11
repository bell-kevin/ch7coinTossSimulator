# ch7coinTossSimulator

Create a program that includes a class named "Coin" that simulates tossing a coin to determine if it lands heads up or tails up. Separate this class into a class specification (header) file, and fully code the class in that header file. (NOTE: To create a new header file in an existing project in Visual Studio, look at the Solution Explorer to find "Header Files". Right click on "Header Files", select "Add", then "New Item", then "Header File". This will create a file named Header.h. Rename it Coin.h, and write the class implementation within it.)

The Coin class needs a string member variable named "sideUp", which will hold either "heads" or "tails". Create a default constructor that tosses the coin to determine which side is up. Create a void member function named "toss" that uses a random number to select "heads" or "tails" -- for example, a random number of 1 could mean "heads" and a random number of 0 could mean "tails". Create another function named "getSideUp" that returns the value of the sideUp member variable.

In the main function, create an instance of the Coin class and display which side is up. Then use a loop to toss the coin 20 times. Each time the coin is tossed, display a message that specifies the number of this toss and which side is up. Count how many times it displays heads and how many times it displays tails, and display those values after the loop finishes. (This count does not include the initial toss when the coin was created; only count the results inside the loop.)

Here is an example of the results:

Ch 7 Coin Toss 

Run the program twice and take screenshots of both executions.

 

NOTE: Remember the requirements for a header and a pause at the end of the program, discussed in the reading "Console Applications". These are required in every console application project.

Submission: Submit a single zipped folder containing all of the specified screenshots AND the root folder for the project.

== We're Using GitHub Under Protest ==

This project is currently hosted on GitHub.  This is not ideal; GitHub is a
proprietary, trade-secret system that is not Free and Open Souce Software
(FOSS).  We are deeply concerned about using a proprietary system like GitHub
to develop our FOSS project. I have a [website](https://bellKevin.me) where the
project contributors are actively discussing how we can move away from GitHub
in the long term.  We urge you to read about the [Give up GitHub](https://GiveUpGitHub.org) campaign 
from [the Software Freedom Conservancy](https://sfconservancy.org) to understand some of the reasons why GitHub is not 
a good place to host FOSS projects.

If you are a contributor who personally has already quit using GitHub, please
email me at **bellKevin@pm.me** for how to send us contributions without
using GitHub directly.

Any use of this project's code by GitHub Copilot, past or present, is done
without our permission.  We do not consent to GitHub's use of this project's
code in Copilot.

![Logo of the GiveUpGitHub campaign](https://sfconservancy.org/img/GiveUpGitHub.png)
