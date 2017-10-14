# A Basic Fuzzer 
A basic fuzzer that detects a buffer overflow vulneribilty in the vuln.c file. The vuln.c file contains a malloc statement that can cause a buffer overflow if one or both inputs happen to be greater than 32 bits. The fuz.py file contains the fuzzer code. The fuzzer randomly chooses to bit modify, byte modify or just insert some common buffer overflow triggers in the input file which is then fed to the vuln.c file. The pack.py just generates a valid input file for the program that is to be changed and then used by the fuzzer.   
Note: I donot own the code. I just followed a tutorial online while learning to write fuzzers.        
Resources: https://www.youtube.com/watch?v=BrDujogxYSk                    
           https://github.com/jaybosamiya/security-notes#basics-of-fuzzing
