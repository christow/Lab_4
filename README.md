# Lab_4
Materials for Laboraotry number 4 NiOSR. Today we are going to work with g++, Make and CMake. To start working  on today's class please clone this repository using the commands learned during the previous class. Today we are having 4 tasks. Before each task you can enter appropriate folder and open howto.txt file which contains the link to the small tutorial which will help you with solving the task. Webpages with tutorials are there just for reading giving a hint how to solve the tasks below not for doing them end to end. Please use them as a reference.
## Task 0
Please enter a folder named step_1 and open main.cpp with the text editor of your choice. In the file you can see that there are 3 classes. One is a base class and two are derived classes. 
As you are now familiar with the content of the main.cpp file please compile it from command line using g++ command.
## Task 1
Given the main.cpp file in step_1 please create a folder my_step_2 and place each class from the main.cpp in a separate .cpp and .h file. Remember to use preprocessor directives to avoid duplicated inclusion of the file. After separating classes please update main.cpp file to include header files of each class and compile the project using g++ with -c option.
## Task 2
For the set of files in my_step_2 please create a Makefile which will do the compiliation process for you. A link to example Makefile could be found in the howto.txt file in step_2 folder. 
## Task 3
Please copy set of files from step_2 to my_step_3 and create a CMakeLists.txt which will perform the whole compilation process for you. A link to example CMakeLists.txt could be found in the howto.txt file in step_3 folder (read STEP 1 and STEP 2)
## Task 4 
Plese copy set of files from step_3 to my_step_4 and structer them, so the .cpp files are in /src folder and .h files are in /include folder. After doing that please create CMakeLists.txt to compile the project. Please remember about include directories directive. When compling the project please create a /build folder where all build data will be stored. This will make your project nice and clean.

Comment: one can find the solution of their tasks in relevan folders downloaded from the repository. So please after each task please comapre the content of the folder `my_step_number` with `step_number`.

