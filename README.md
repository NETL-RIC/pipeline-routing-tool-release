# CO2 Pipeline Routing Tool README

## Installation and Opening The Tool (Brief)

First, install the entire tool by running CO2Pipeline Setup 0.1.0.exe.
This can be found in the "Releases" section of this github repository, to the right of this text
Then, open the UI window by running C:\Users\[username]\AppData\Local\Programs\apptest\CO2Pipeline.exe, if it's not already open
Then, open the server window by running C:\Users\[username]\AppData\Local\Programs\apptest\CO2PRT_Flask.exe.
Wait for the server program to initialize, waiting until the line "Press CTRL+C to quit" appears on the screen.
Instruction on tool operation can be found by clicking the "Help Documentation" button in the upper-right corner of the UI program window.


## Installation (Detailed)

Install the pipeline routing tool with "CO2Pipeline Setup 0.1.0.exe"

The installer will automatically handle everything after its clicked on, and when finished will open the UI portion of the tool. This is not the entire tool, and the below steps are required for the tool to function.

## Opening The Tool (Detailed)

Navigate to your AppData folder in your computer. On Windows systems, this can be found at C:\Users\[username]\AppData, where [username] is the name of the Windows profile of the computer you are logged into.

Note: The AppData folder may be hidden by default, but can be made visible by clicking the "View" tab and checking the "Hidden items" box at the top of the Windows file browser.

The program needs to have two windows open at the same time to function: the UI window, and the server window. 

### The UI Window

The UI window program is installed at, and can be opened at:

C:\Users\[username]\AppData\Local\Programs\apptest\CO2Pipeline.exe

### The Server Window

The server window program is installed at, and can be opened at:
C:\Users\[username]\AppData\Local\Programs\apptest\CO2PRT_Flask.exe

Open both windows to run the tool. They can be opened in any order.

The server window program will need a minute or two to boot up.
During this process, the window will initially be a black screen, and after a few minutes lines of start-up text will appear, starting with:

	"Matplotlib is building the font cache; this may take a moment".

The server window program will be ready when the following lines appear on-screen:

	* Running on http://127.0.0.1:5000
	Press CTRL+C to quit

During tool operation, the server window will have additional lines of text, these can all be ignored and are information for developers.

When both windows are open, and "Press CTRL+C to quit" has appeared on the server window program, the tool is ready for use. Additional details on tool operation can be found by clicking the "Help Documentation" button in the UI window program of the tool.
