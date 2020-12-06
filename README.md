# digitalclock
Digital Clock counts every seconds, minutes &amp; hours at every positive edge of the clock cycle. The code also has a reset input to start the digital clock from 00:00:00. The code and test bench snippet is shown down below.

INSTALLATION GUIDE for I-Verilog & GTK Wave-

Step 1: Download and Install everything by clicking the checkboxes from the file: " http://bleyer.org/icarus/iverilog-v11-20200824-x64_setup.exe "

Step 2: Create a shortcut to your Desktop

Step 3: Open the Iverilog Folder

Step 4: Copy and Paste the Verilog Code File and Verilog Test File at your preferred place within the folder (Suppose file name are MUXCode and MUXTest respectively)

Step 5: Click on the address bar --> type cmd --> Terminal Opens --> Write " iverilog -o mysim MUXCode.v MUXTest.v " --> Enter

Step 6: Type: " vvp mysim "

---- CHECK THE OUTPUTS-------

For viewing your wave:

-------Insert the following commands under inital block in your test file--------

$dumpfile("example.vcd");

$dumpvars(0,<Test Bench Module Name>);

---------------------------------------------------------------------------------

Repeat Steps 1-6, then:

Step 7: gtkwave example.vcd

---------------------------------------------------------------------------------

See the results!!

 

______________________________________

Note: Code and Test Files should be saved with a .v extension

If any problem, try writing the code in Notepad++ : https://notepad-plus-plus.org/downloads/v7.8.8/

