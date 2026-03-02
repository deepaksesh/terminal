Context: 

\\src\\cascadia\\WindowsTerminal\\WindowEmperor.cpp



Query on Copilot chat:

When a window is created via the function CreateNewWindow(), the first time when its created its required to associate the window to its parent which is the current window in context. Can you make the change such that only for the 1st call, you get the window handle of the current window and make the new window as a child of the current window

