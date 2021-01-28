# OpenFISCA repl.it Tutorial

If you're going to be an occasional user, or mostly want to experiment with OpenFISCA, you might find it more useful to use repl.it.

repl.it is a lightweight, browser based platform that can show off the power of rules as code without the technical commitment. 

Here's how to use repl.it to install OpenFISCA (in this case, a core library).

1. Get a repl.it account (it's free - no need for the paid functionality at this point)

2. Create a new Python repository (create new Python). OpenFISCA, which we use to do Rules as Code within DPIE, is built on Python and Numpy. 

3. Import the following URL - https://github.com/energy-savings-scheme/openfisca_nsw_ess_core. This is a small repository which contains a few key variables and parameters used within the ESS.

It will automatically give the repl a unique name - note that all repls have to have unique names. It'll probably be something like openfisca_nsw_ess_core-6. Call it whatever you like.

4. It will open a new window with three parts - a file structure on the left, a README section in the middle, and a terminal on the right. 

You'll see repl.it pull the files from the Github repository in the console - see the below image.

5. Type make install into the terminal and hit enter. This accesses the Makefile, and pulls the relevant dependencies to install OpenFISCA within the repl.it window. 

You'll see a whole bunch of progress bars downloading the relevant libraries in the console, concluding in the below image. 

6. Type make test into the terminal. This will run the test suites in the tests folder (which is within the openfisca_nsw_ess_core folder). 

You should end with something like the below image.

Great! If you've seen this image, you've successfully a. installed OpenFISCA and b. used it to run some tests, demoing its simulation capability. Good job!


