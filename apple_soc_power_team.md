Apple面经 -- SoC Power Team
===

###第一个：hiring manager
######Question 1
    Test bench: Start dumping waveform at the first rising edge and ends at the last falling edge
    E.g.
	             ________
    A  ______|           |_______________________
	                  ________ 
    B  _________|            |_________________
                 <-------->
######Question 2
    Using pseudo code to parse log file
    Input:
    Net      name	     cell		latency
    a.net    a.name      a.cell     a.latency
    b.net    b.name      b.cell     b.latency
    c.net    c.name      c.cell     c.latency
    d.net    d.name      d.cell     d.latency
    .
    .
    .
    Output:
    5 cells with top aggregated latency
---

###第二个：印度小哥 校友
######Question 1
	What is inside a phone？
######Question 2
	What is inside a cpu？
######Question 3
	The  relative size of SRAM, DRAM and Flash

---
###第三个：印度小哥
######Question 1
	Input: any address range from 0x0000 0000 to 0xFFFF FFFF
	E.g.
	addr					data
	0x0000 0008        a
	0x0000 0012         b
	.
	.
	.
	
	Output: print all address with the same address space, with corresponding data
	Address not shown in input should have zero as data value.
	E.g.
	addr					data
	0x0000 0000        0
	0x0000 0004        0
	0x0000 0008        a
	.
	.
	.
	0xFFFF FFFF        0
######Question 2
	Starting from 1 to 100, initial states of all number are 0
	For every number, flip the state of all the number after the current number (including the current number) if the number is divisible by the following number
	Write code to find out the number of transition of each number, and the final state of the numbers
######Question 3
	Write test bench (no assertions) to verify the following sequence
	A, B, C are all synchronized 
	                        ___       ___      ___      ___
	clk      ___.......___|     |___|     |___|    |___|     |______
	                                    ___      
	A        _________________|    |_____________________
	                                              ___   
	B        ________________________|    |_____________
	                                                        ___      
	C        ______________________________|     |_______
	A raises after n clocks, and stay high for one clk.
	B raises exactly one clock after A, stay high for one clk.
	C raises exactly one clock after B, stay high for one clk.
######Question 4
	Power analysis with numbers
	900MHz			450MHz
	1v				     0.9v
	Evaluate qualitatively dynamic power and leakage power (assuming leakage power is quadratically associated with voltage)
	What will impact the power consumption in both designs assuming both model can handle same amount of workload (area, layout, leakage, temperature, switching frequency)
---
###第四个：小姐姐
######Question 1
	FIFO in verilog with empty/full flag
######Question 2
	Accessing Memory in low power pattern
	               _____________________________
	rd_en ____|                                           |___________
	addr         0x020        0x30          0x40
---
###第五个: 白人
######Question 1
	internship project
######Question 2
	Power analysis with numbers
---
###第六个：俄罗斯大哥
######Question 1
	Dynamic power and frequency/voltage relation
######Question 2
	Static power and frequency/voltage relation
######Question 3
	Draw Flip Flop
######Question 4
	Clocking gating for FF: force clock gate to 1 or 0 for low power
######Question 5
	DIBL: what is DIBL and some implications 
