=-=-=-=-= Installing =-=-=-=-=
1. Move the compressed file to your VM.
2. Extract it there.
3. Add your assembly files.

The directory structure should look like this:

Atam1Tests
├── test_all.sh   # The script
├── ex1.asm       # Assembly files
├── ex2.asm
├── ex3.asm
├── ex4.asm
├── ex5.asm
├── tests1/        # Test directories
│   ├── test1      # Test files inside "test1"
│   ├── test2
│   └── ...
├── tests2/
├── tests3/
├── tests4/
└── tests5/

Note: The tests will run even if you don`t add all the assembly files.
So if you add for example ex2.asm and ex4.asm - only tests2 and tests4 will run.


=-=-=-=-= Running =-=-=-=-=
1. open the terminal in the directory with test_all.sh
2. chmod +x test_all.sh
3. ./test_all.sh


=-=-=-=-= Adding more tests =-=-=-=-=
Feel free to add and share more test cases.
To add a test, name it whatever you like and put it in the testsN (1 <= N <= 5) folder. 


Good luck with the debugging!

