# CPP-Code-Basics
Useful notes and simple C++ Codes
Includes things I learnt from https://www.learncpp.com.


* namespaces are denoted as std::cout and std::cin where std is the namespace. This helps us declare another cout or cin but with a namespace like pmg. So, the new function becomes pmg::cout or pmg::cin.
* #define <some_thing> <some_other_thing> will replace some_thing with some_other_thing in a literal sense like a wordprocessor. This is called an object-like macro. If there is no <some_other_thing>, <some_thing> will be thanos-snapped.
* #ifdef <some_thing> checks for something being declared using #include and if it is true, it will compile things between #ifdef and #endif. #ifndef is the opposite of #ifdef but needs #endif.
* #if 0 and #endif are essentially directives to not compile anything between them.
* Macros only cause text substitution for normal code. Other preprocessor commands are ignored.
* #include <some_thing> tells compiler to look into its own pre-supplied header files. #include "some_thing.h" means it is user-supplied.
* Use include directories or search directories to store header files to avoid referring to them in the code.
* Header guards help avoid double declaration of variables and functions.
