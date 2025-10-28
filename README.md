# EX:09 - Keyboard-Automation---Simulate-Keystrokes

### Aim
To simulate typing and keyboard shortcuts in a desktop application (Notepad) to create and save a file, demonstrating keyboard automation capabilities in UiPath.

### Procedure 

1.  **Launch Application:** Use **Start Process** to open the `notepad.exe` executable.
2.  **Type Content:** Use **Type Into** to write the desired text into the main Notepad window.
3.  **Initiate Save:** Use **Send Hotkey** to simulate the $\text{Ctrl+S}$ shortcut, which prompts the "Save As" dialog.
4.  **Type File Name:** Use **Type Into** targeting the file name field in the dialog to enter `"TestFile.txt"`.
5.  **Confirm Save:** Use **Click** to select and press the "Save" button in the dialog.
6.  **Execute:** Run the workflow (`Main.xaml`).

### Output 

<img width="964" height="599" alt="image" src="https://github.com/user-attachments/assets/c586b974-1d34-4ca4-a022-4a0221470861" />
<img width="942" height="590" alt="image" src="https://github.com/user-attachments/assets/87606fce-419a-47a1-8fb3-853407152aba" />


### Result
A new file named **TestFile.txt** will be created and saved in the default location (usually Documents), containing the automated text content.
