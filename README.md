# 50.002_Mini_Project_Part1_Bonus
Code for FPGA test. 

Auto Test: The Alchitry will run the auto test once it starts to run (We set a time delay to debug). In the auto test, we design an FSM has 8 cases (C1-C8, F, P), which means 8 different test cases and fail/pass. In each test cases, it will input one group of x/y/cin, once the output is correct, it will go to the next state until P(Pass). Otherwise, F(Fail) will become the final cases.  If the final case is Pass, it will give output to LED to show it.

Manual Test: The Alchitry will take 3 switches as inputs, which means x/y/cin separately. Then the vitual adder circuit will take these inputs and provide outputs s/cout, which will show in LED separately.
