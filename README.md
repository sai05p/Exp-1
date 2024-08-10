# Experiment 1
# Aim 
To install Visual Studio Code and writing a program to print hello world, and calculator program.
# Software
Visual Studio Code
# Theory
VS code is a code editor that, with the appropriate extensions, can run all types of programs and codes.

In the codes, MinGW is used to add the c++ extension printing hello world uses the "cout" character output, and the calculator program uses the arithmetic operators sum(+), difference(-), multiplication(*), and division(/).

1) Installation of VS code

   
 a)Use chrome to search for VS code installation
   ![image](https://github.com/user-attachments/assets/965eacc0-2265-491e-9b1b-cda7643c96c1)

 
 b)Click on "I accept agreement" of the pop up which will appear and then click on next.
![image](https://github.com/user-attachments/assets/c15c3399-d76b-4162-9549-25b72b735c15)


c)VS code installation will start
![image](https://github.com/user-attachments/assets/1a469112-4f4f-451b-a745-9deca62f0a8b)
![image](https://github.com/user-attachments/assets/0cb429ff-5e44-415b-8e55-70b0616a6885)
![image](https://github.com/user-attachments/assets/08ecc2f7-3721-424c-97fa-b780956b748e)
![image](https://github.com/user-attachments/assets/5a5c40b5-37ea-418b-aa4d-1f4bdb3ac9ad)


2) Downloading MinGW for compilation 
![image](https://github.com/user-attachments/assets/e33198df-7d07-4f07-bca7-5851235127fe)


a) A pop up window will appear.Click on install.
![image](https://github.com/user-attachments/assets/31162aa4-c1ed-4092-88c4-9915c0288eeb)
![image](https://github.com/user-attachments/assets/857b8b52-aac2-4ee7-b8f4-26938f02aeee)


b) Click all the required boxes for the C and C++ language.
![image](https://github.com/user-attachments/assets/ae58e9db-4fad-4e11-9106-80aa7cf1919d)


c)Go to This PC, open MinGW folder, click on bin folder, a number of files will appear and then copy its path.
![image](https://github.com/user-attachments/assets/f8cea8df-cf33-4157-9515-fca0e8c807bc)


d) In This PC, click on advanced settings, a pop up window will appear, where clikc on Environmental variables.
![image](https://github.com/user-attachments/assets/43db6909-afcc-4b96-8d68-65c34394786f)
![image](https://github.com/user-attachments/assets/c3ae1d96-361f-496a-8ff0-0fef6b1bb3be)


e) Click on New and then paste the copied path. Then click OK.
![image](https://github.com/user-attachments/assets/6b0bb4f3-e4f5-46d4-be81-57cc712e9cc1)


f)All changes are applied and you can use MinGW.
![image](https://github.com/user-attachments/assets/1ec84834-28c0-4647-bb0f-c213050252ec)

THEORY:

This C++ application uses the iostream library to perform input and output operations while demonstrating fundamental programming concepts. 

It contains a C++ program's structure, with the main function serving as the entry point. After asking the user to enter two integers, the software uses simple arithmetic operations to calculate and display the values of their total, difference, product, and quotient. 

It shows how to use cin to read user input and cout to display the results.


Hello World:

```
#include <iostream>
using namespace std;
int main() {
   cout << "Hello World"; 
   return 0;
}
```

Output:
![image](https://github.com/user-attachments/assets/430265ab-1b23-4203-b523-290f8e1de046)

Calculator:
```
#include <iostream>
using namespace std;
int main()
{
    int a,b,sum=0,diff=0,prod=0,q=0;
    cout<<"Enter the first no.:";
    cin>>a;
    cout<<"Enter the second no.:";
    cin>>b;
   
    sum=a+b;
    cout<<"Sum of the given nos. is:"<<sum<<endl;
     diff=a-b;
    cout<<"Difference of the given nos. is:"<<diff<<endl;
     prod=a*b;
    cout<<"Product of the given nos. is:"<<prod<<endl;
     q=a/b;
    cout<<"Division of the given nos. is:"<<q<<endl;
   
}
```
Output:
![image](https://github.com/user-attachments/assets/94d770f6-c3d0-4a32-b5dd-c2ecded6ff40)

# Conclusion 

VS code is a versatile,powerful and user friendly code editor. Along with it, installing MinGW offers essential compiling tools for C and C++. It has a straight forward installing process and is a reliable and efficient compiler for Windows.

Basic concepts like receiving user input, using namespaces, including libraries, and performing arithmetic operations are all combined in the above C++ program. It offers an actual example of basic C++ programming and user interaction by showing how to calculate and display the sum, difference, product, and quotient of two integers.
