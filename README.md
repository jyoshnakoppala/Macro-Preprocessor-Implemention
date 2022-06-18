# Macro-Preprocessor-Implemention
A Macro Processor is a program that copies a stream of text from one place to another, making a systematic set of replacements as it does so 

 

A Macro instruction is the notational convenience for the programmer. For every occurrence of macro, the whole macro body or macro block of statements gets expanded in the main source code. Thus, Macro instructions make writing code more convenient.  

Macros are processor directive which will be replaced at compile time 

 

The fundamental functions common to all macro processors are:  

Macro Definition  

A macro definition is enclosed between a macro header statement (MACRO) and a macro end statement (MEND) 

A macro definition consists of macro prototype statement and body of macro. 

 Macro Invocation  

A macro invocation statement (a macro call) gives the name of the macro instruction being invoked and the arguments to be used in expanding the macro 

Macro Expansion 

Each macro invocation statement will be expanded into the statements that form the body of the macro.  

Arguments from the macro invocation are substituted for the parameters in the macro prototype. 

 

 

There are 3 main data structures involved in the design of one pass macro processor:  

Definition table (DEFTAB)  

All the macro definitions in the program are stored in DEFTAB, which includes macro prototype and macro body statements 

 

Name table (NAMTAB)  

The macro names are entered into NAMTAB  

NAMTAB contains pointers to beginning and end of definition in DEFTAB. 

 

Argument table (ARGTAB)  

The third data structure is an argument table (ARGTAB), which is used during expansion of macro invocations.  

When macro invocation statements are recognized, the arguments are stored in ARGTAB according to their position in argument list. 

 

                   

 

ALGORITHM: 
 
STEP 1: Start the program execution. 
STEP 2: Macro instructions are included in a separate file. 
STEP 3: The instructions with ‘macro’,’mend’,’call’ on them should not be printed in the output. 
STEP 4: Print all other instructions such as start, load, store, add, sub etc. with their values. 
STEP 5: Stop the program execution. 
