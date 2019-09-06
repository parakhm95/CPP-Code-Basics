# CPP-Code-Basics
Useful notes and simple C++ Codes


* namespaces are denoted as std::cout and std::cin where std is the namespace. This helps us declare another cout or cin but with a namespace like pmg. So, the new function becomes pmg::cout or pmg::cin.
* #define <some_thing> <some_other_thing> will replace some_thing with some_other_thing in a literal sense like a wordprocessor. This is called a preprocessor directive. If there is no <some_other_thing>, <some_thing> will be thanos-snapped.
* #ifdef <some_thing> checks for something being declared using #include and if it is true, it will compile things between #ifdef and #endif. #ifndef is the opposite of #ifdef but needs #endif.