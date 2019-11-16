# Keylogger in C#
## System.Diagnostics::
This is used to gain access to running processes and process modules.

## System.Runtime.InteropServices::
used to import the required DLLs for our KeyLogger, as well as to read keystroke information form specific locations in memory.
(A Keystroke is the pressing of a single key in a physical or virtual keyboard or any other input devices).


## System.Windows.Form ::
This is used to actually run our application, as well as convert keystroke values into readable keys.For example Value--> 'A'.


## WH_KEYBOARD_LL ::
This variable is used to define the type of hook procedure we will be using. The integer 13 defines that we will be using the hook procedure that monitors Low level keyboard input events.




