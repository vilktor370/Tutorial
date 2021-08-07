
# Visual Studio Code Debugger tutorial

## 1. What is Visual Studio Code?
    
Visual Studio Code(VScode) is one of the most popular programming tools in the market espeially in web development. Unlike most of IDEs out there. VScode aims  to be lightweights but not as extreme as some older tools like Vim or Emacs. Even though Visual Studio and Clion is still the go to option for C++ development in the industry, VScode does have some adnatages, which will be covered in the Feature Reading section, aginst those powerful IDEs. 

## 2. Why we need to debug our code?

"Can't we just `cout` everything to see what's going on?". Students always ask this to their insturctors. Personally, I think any ways would work as long as you enjoy it. The problem with print out in between your code is that it's quite a lot work to type those lines code in between your code and comment them out later. Useing a debugger would allow you to jump and stop in any point of your program execution. This is extremely useful and somewhat necessary when you work with large amount of files. Again, this is just one of the many ways to code more efficent. Good programmers pick the one that they are most comfortable at.

## 3. How to set up Debugger for C++ project

## **Get Start with Debugger**

Let's say we have a simple program called  `example.cpp`.

```C++
#include <iostream>

using std::cout;

int main(){

    cout << "Hello Debugger!\n";

}
```

<!-- <Figure 1: Overview of VScode> -->


If it isfirst time using debugger for this program (which we are in this case), you have to set up the debugger first.

## **Config Debugger setting**

First make sure you have the *C++ extension* installed in VScode. If not, simply go to the *extension tab*, and search for *C/C++* in the search box on top. It is usually the first one which is offered by Microsoft. 

![Figure1](/pictures/Config_debugger1.png)

<!-- <Figure 2: Debugger picture> -->
![Figure1](/pictures/Config_debugger2.png)
After install the extension, go to the 'Run and Debug' section in the left bar. Make sure you are looking at your `cpp` file. It's not necessary but it would let VScode know you want to debug a C++ file which can make our life easier later.
<!-- <Figure 3: Debugger picture> -->
![Figure1](/pictures/Config_debugger3.png)
Then click 'Run and Debug' to start setting up the debugger.
<!-- <Figure 4: Debugger picture> -->
![Figure1](/pictures/Config_debugger4.png)

Then in the middle top of your screen. It should ask you to select a type of compiler to debug. It really doesn't matter which compiler you choose. It should give us the same result in general.
<!-- <Figure 5: Debugger picture> -->
![Figure1](/pictures/Config_dbugger5.png)
<!-- <Figure 6: Debugger picture> -->

![Figure1](/pictures/Config_debugger6.png)

Then you should see a `launch.json` file opened up. It should look like this.
<!-- <Figure 7: Overview of launch.json> -->
![Figure1](/pictures/Config_debugger7.png)

## **Run Debugger**

Now you have everything set up. You can start 'Debugging' your code.
<!-- Figure 8: Run Debugger -->
![Figure1](/pictures/Run.png)
    
## 4. Feature readings (Comming soon)
- How to debug your code like a pro
- Useful Extensions for C++ programming
- Useful tricks on C++

# Note

All the source code would be live in this [GitHub repository](https://github.com/vilktor370/Tutorial/).

author: Haochen (Tony) Yu.
Feel free to contact me at: **vilktor370@gmail.com**
