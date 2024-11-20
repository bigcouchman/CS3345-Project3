# CS3345-Project3
# Instruction: Set up
- Make sure JDK (Java) is installed before testing!
- Unzip npd220001 folder, import the p3-testcascases-t0-t5 folder there for test cases
    (The name for the test case folder can be name however, instead of a space use a dash)
- Open the code files in any IDE, turn on its terminal, and type cd .. (This helps guide to the parent directory)
# Instruction: Run the program
- Compile P3Driver.java using command: javac npd220001/P3Driver.java (This will create .class files)
- Check the test cases with the command: java npd220001/P3Driver.java npd220001/p3-testcascases-t0-t5/(test case.txt)
- Example: java npd220001/P3Driver.java npd220001/p3-testcascases-t0-t5/p3-t0.txt
- Any additional test cases can be added, just make sure when calling those cases use the correct file path.
# Other ways of testing (In case the above instruction does not work
- In P3Driver.java, replace System.in in new Scanner() with new File("test case full path). This occurs at line 19
# Main Concerns
- In terms of program output there should not be any issues. I'm only concerned about the efficiency of my code and how the time and memory outputs fluctuate on every run. However, this issue may be device dependent. Thank you for reading this!
