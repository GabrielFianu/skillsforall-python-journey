# My very first program before your first program...

## Introduction
It is now time to write and run my first Python 3 program.

---

### 1. Create a file

**Step 1** The first step is to create a new source file and fill it with code.   Search and click IDLE from **start menu**. 

<img width="787" height="243" alt="Image" src="https://github.com/user-attachments/assets/85ac3d2c-a575-4fb7-af77-52f0bf0c4fab" />


Click File in the IDLE menu and choose New file.


<img width="701" height="139" alt="Image" src="https://github.com/user-attachments/assets/0c531572-7963-425d-92f6-d928fcf32515" />


IDLE opens a new window for you. You can use it to write and amend your code. This is the editor window. Its only purpose is to be a workplace in which your source code is treated.


<img width="683" height="313" alt="Image" src="https://github.com/user-attachments/assets/5a201024-97f6-4cd3-a7f1-be6443c03820" />


The editor window is currently untitled, but it's good practice to start work by naming the source file.


<img width="731" height="217" alt="Image" src="https://github.com/user-attachments/assets/ea23adeb-bb37-48da-8f92-2a1177d1867e" />




**Step 2** Click File (in the new window), then click Save as..., select a folder for the new file (the desktop is a good place for your first programming attempts) and chose a name for the new file.

<img width="727" height="315" alt="Image" src="https://github.com/user-attachments/assets/f345cd33-b522-41dc-a14e-baf95cf5092a" />


**Note:** don't set any extension for the file name you are going to use. Python needs its files to have the .py extension, so you should rely on the dialog window's defaults. Using the standard .py extension enables the OS to properly open these files.

**Step 3** Now put just one line into your newly opened and named editor window.

type
```
print("Hisssssss...")
``` 

**Note** Take a closer look at the quotation marks. These are the simplest form of quotation marks (neutral, straight, dumb, etc.) commonly used in source files. Do not try to use typographic quotes (curved, curly, smart, etc.), used by advanced text processors, as Python doesn’t accept them.


**Step 4** Save the file (File -> Save) and run the program (Run -> Run Module).


<img width="748" height="369" alt="Image" src="https://github.com/user-attachments/assets/d14279c0-61c7-4449-b85d-c4ee352b5fe7" />


<img width="696" height="177" alt="Image" src="https://github.com/user-attachments/assets/660e4ef6-97a4-42df-9fbb-584519726010" />



If everything goes okay and there are no mistakes in the code, the IDLE window will show you the effects caused by running the program.

In this case, this is my output.

<img width="681" height="168" alt="Image" src="https://github.com/user-attachments/assets/7181cf63-d35c-429b-aa54-5cc87fe8a4e9" />


---

### 2. How to spoil and fix your code

Now start IDLE again.

**Step 1** Click File, Open, point to the file you saved previously and let IDLE read it in.
Try to run it again by pressing F5 when the editor window is active.
As you can see, IDLE is able to save your code and retrieve it when you need it again.

```
print("Hisssssss...")
``` 

**Step 2** Remove the closing parenthesis again.
```
print"Hisssssss..."
```
The code becomes erroneous. It contains a syntax error now. IDLE should not let you run it.

<img width="405" height="148" alt="Image" src="https://github.com/user-attachments/assets/72eec0b6-5788-43eb-b8d7-bfae97bb0967" />


Try to run the program again. IDLE will remind you to save the modified file. Follow the instructions.
Watch all the windows carefully.

<img width="202" height="151" alt="Image" src="https://github.com/user-attachments/assets/c909d9dc-7a89-4b63-b0c7-762541a02c7f" />

A new window appears – it says that the interpreter has encountered an EOF (end-of-file) although (in its opinion) the code should contain some more text.
The editor window shows clearly where it happened.

**Step 2**Fix the code now. It should look like this:

```
print"Hisssssss..."
``` 
Run it 

**Step 3** Let's spoil the code one more time. 
Remove one letter from the word print. 

```
rint"Hisssssss..."
```

Run the code by pressing F5. What happens now? As you can see, Python is not able to recognize the instruction.

<img width="676" height="301" alt="Image" src="https://github.com/user-attachments/assets/b2f225c7-a1b2-41dc-8f0a-9d4d58c55973" />


You may have noticed that the error message generated for the previous error is quite different from the first one.
This is because the nature of the error is different and the error is discovered at a different stage of interpretation.

The editor window will not provide any useful information regarding the error, but the console windows might.

The message (in red) shows (in the subsequent lines):

Experiment with creating new files and running your code. Try to output a different message to the screen, e.g., roar!, meow, or even maybe an oink!. Try to spoil and fix your code – see what happens.


