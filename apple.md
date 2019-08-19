Apple面经
===
--
第一个：hiring manager

Test bench: Start dumping waveform at the first rising edge and ends at the last falling edge
E.g.
            ________________
A__________|                |__________________________
                     _________________
B __________________|                 |________________

           <——————————————————————————>


Parse log file, pseudo code

Input:
Net    name	  cell		latency

Output: 5 cells with top aggregated latency

--
第二个：印度小哥 校友

What is inside a phone

What is inside a cpu

SRAM, DRAM, Flash relative size

--
第三个：印度小哥
Input: any address range from 0x0000 0000 to 0xFFFF FFFF

addr			data

Output: print all address with the same address space, with corresponding data
Address not shown in input should have zero as data value.

0x0000 0000

...


0xFFFF FFFF

Starting from 1 to 100, initial states of all number are 0

For every number, flip the state of all the number after the current number (including the current number) if the number is divisible by the following number

Write code to find out the number of transition of each number, and the final state of the numbers

Write test bench (no assertions) to verify the following sequence
A, B, C are all synchronized 

               	  ___    ___    ___    ___
clk      ___...___|  |___|  |___|  |___|  |______

					         ___
A        ________________|  |___________
						            \___
B	      ______________________|  |_____
       								      ___
C        ______________________________|  |_____

A raises after n clocks, and stay high for one clk.

B raises exactly one clock after A, stay high for one clk.

C raises exactly one clock after B, stay high for one clk.


Power analysis with numbers
900MHz			450MHz
1v				0.9v
Evaluate qualitatively dynamic power and leakage power (assuming leakage power is quadratically associated with voltage)
What will impact the power consumption in both designs assuming both model can handle same amount of workload (area, layout, leakage, temperature, switching frequency)

第四个：小姐姐
FIFO in verilog with empty/full flag
Accessing Memory in low power pattern
                 _____________________________
rd_en ____|                                                    |___________
addr          0x020           0x30                           0x40

第五个: 白人
internship project
Power analysis with numbers

第六个：俄罗斯大哥
Dynamic power and frequency/voltage relation
Static power and frequency/voltage relation
Draw Flip Flop
Clocking gating for FF: force clock gate to 1 or 0 for low power
DIBL: what is DIBL and some implications 