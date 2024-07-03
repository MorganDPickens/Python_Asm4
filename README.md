# Python_Asm4
# HW4: Drawing

---

### Policy of Due Dates

If you need additional time to complete this assignment, please contact me before the due date. **No excuses or extensions will be accepted after the due date.** You are allowed up to two extensions: the first extension grants an additional two days, and the second extension grants one extra day. After these two extensions, no further extensions will be permitted, and you must submit whatever work you have completed.

---

### Grading Policy for Uncovered Topics

Avoid incorporating advanced topics or functions that haven't been covered in our studies. The use of uncovered/unfamiliar topics or functions like ChatGPT answers may result in a deduction of points.

---

O**ur assignment is to create a complete scene of your own design that meets some minimum requirements for program structure. Don't use any other package like tkinter - GUI with TK.**

### **Objectives**

- Apply the concept of functional decomposition
- Continue practice writing function definitions with parameters
- Gain a small amount of experience with the Gui tools for drawing shapes
- Read and trace the given program then try to make your functions.

### **Specification**

Your program will draw a scene, made up of scene elements. The example TreeTest.py (you can download it from Canvas) draws a scene  made up of 2 simple tree elements and 3 tree cluster elements. Notice that there are 5 function calls in main().  **If you haven't already, I encourage you to read the supplemental reading for this week, particularly the page titled Functional Decomposition -- a Graphical Example**. You may use the GUIStarterCode.py (you can download it from Canvas) or TreeTest.py (you can download it from Canvas) sample programs as a starting point for this assignment.

[Gui.py](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/256625af-eb3f-4fbb-88c8-456a7e862e58/Gui.py)

[TreeTest.py](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/dd855093-3ce1-4400-aeb3-d480596589b3/TreeTest.py)

[GUIStarterCode.py](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2b7144ad-ec5f-4c07-9972-62c37291c675/GUIStarterCode.py)

You will also **need the [Gui.py](http://Gui.py) (you can download it from Canvas) file in the same folder**.  Remember to right-click on this link, then save to a folder with your .py solution. If you download Gui.py multiple times, the name of Gui.py will be changed. **Make sure the name of Gui.py**!

You may keep the trees in your scene if you want to, or not if you prefer. These don't count towards the requirements however.

1. You must write 4 different function definitions; each draws a simple drawing, known as a scene element. Examples of a simple drawing are the tree or the tree cluster in the TreeTest.py. The requirements of your function definitions are as follows:
    - Each function definition must draw **at least two GUI shapes**, or call other functions in your solution at least 3 times (like the tree cluster function)
    - Each function definition must have parameters that allow the call to specify the location and size of the drawing. You can add an additional parameter to specify color, if you'd like.
    - Each function should draw a straight vertical line, using the location and size parameters, for testing purposes, to make sure your function uses the parameters correctly. For example, if the documentation says the drawing is a certain height, this test line will help you ensure that it is. You should comment out the code to draw the straight line, but leave it in the file so that I can uncomment it and run it.
2. Examples of what your functions might draw are a small house, a car, a boat, a bug, a musical instrument, a bird etc., as well as clusters of any other drawings. You can have at most two functions that produce abstract drawings.
3. In main, call each of your functions 3 times; main should contain a total of 12 functions calls to your function definitions. Your final solution will display 12 elements in the scene.
4. Limit your solution to using the language features from the chapters we've covered so far.

### **Documentation and Style**

- Please follow the guidelines found in Comment Descriptions and Documentation Standards, on the class website.
- Make sure your code includes **comments** at the beginning of the file including your name, the date, and a description of your program. Your program description should be at least 2 sentences long. Assume that whomever is reading your comments has not read our homework description.
- Add a block comment just before each function definition explaining what the function does and how its parameters should be used. Imagine you are explaining this for another programmer who does not know the details of your project. This is illustrated in the TreeTest.py sample code.
- Include comments throughout the code (these are often called 'inline comments') that document what is being done and why. Don't state the obvious -- focus on helping the reader understand **why** something is being done.

### **Suggestions**

I recommend implementing one function at a time, and testing as you go.  Testing should include calling your function several times, with different arguments, to ensure that the function uses the parameter values correctly.

Drawing out your images on graph paper will help.

### **Written Report**

Please type up the answers to the following questions and include it at the bottom of your .py file:

1. How did you go about starting this assignment? Where did you get stuck, if at all, and how did you get unstuck?
2. How did you test your program? Does your program meet the homework specification? If not, in what ways does it fall short?
3. What did you learn from this assignment? What would you do differently next time?

### **Grading**

The following table shows the rubric of grading HW 4. 

| Criteria | Rating | Points |
| --- | --- | --- |
| Program runs correctly | Completed 4 drawing functions : 3 pt / function : 12 pt
4 functions to draw | 14pts |
| Documentation | 3pt : Completed
1pt : Basic comments
0pt : No comments on your program | 3pts |
| Written report | 3pt : Completed
2pt : At least, 1~2 sentences
0pt : No written report | 3pts |
|  |  | 20pt |
