
# Visual Studio Code Debugger tutorial

1. What is Visual Studio Code?
    
    Visual Studio Code(VScode) is one of the most popular programming tools in the market espeially in web development. Unlike most of IDEs out there. VScode aims to be lightweights but not as extreme as some older tools like Vim or Emacs. Even though Visual Studio and Clion is still the go to option for C++ development in the industry, VScode does have some adnatages, which will be covered in the Feature Reading section, aginst those powerful IDEs. 

2. How to set up Debugger for C++ project

    **Get Start with Debugger**
    
    Let's say we have a simple program called  `example.cpp`.

    ```C++
    #include <iostream>

    using std::cout;

    int main(){
    
        cout << "Hello Debugger!\n";
        
    }
    ```
    or if you prefer to look in VScode.

    <!-- <Figure 1: Overview of VScode> -->

    And we would like to debug this. If you are first time using debugger for this program (which we are in this case). You have to set up the debugger first.

    **Config Debugger setting**

    First make sure you have the *C++ extension* installed in VScode. If not, simply go to the *extension tab*, and search for *C/C++* in the search box on top. It is usually the first one which is offered by Microsoft. 

    <!-- <Figure 2: Debugger picture> -->

    After install the extension, go to the 'Run and Debug' section in the left bar. Make sure you are looking at your `cpp` file. It's not necessary but it would let VScode know you want to debug a C++ file which can make our life easier later.
    <!-- <Figure 3: Debugger picture> -->
    Then click 'Run and Debug' to start setting up the debugger.
    <!-- <Figure 4: Debugger picture> -->
    Then in the middle top of your screen. It should ask you to select a type of compiler to debug. It really doesn't matter which compiler you choose. It should give us the same result in general.
    <!-- <Figure 5: Debugger picture> -->
    <!-- <Figure 6: Debugger picture> -->

    Then you should see a `launch.json` file opened up. It should look like this.
    <!-- <Figure 7: Overview of launch.json> -->

    **Run Debugger**
    Now you have everything set up. You can start 'Debugging' your code.
    <!-- Figure 8: Run Debugger -->

    

3. Personal thoughts on VScode debugger
4. Feature readings
    - Useful Extensions for C++ programming
    - Useful tricks on C++
    
