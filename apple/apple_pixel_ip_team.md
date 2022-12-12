Apple面经 -- Pixel Ip Integration
===

## Round 1 
###### Question 1
	What is logic equivalence check? 
    What's the advantage and disadvantage of using cadence formality check tool between rtl and Synopsys synthesis gates?
###### Question 2
    What is clock domain crossing?
    Why in some cases we are using 2FF synchronizer while in other cases we are using 3FF synchronizer?
__Hint: Metastability__
###### Question 3
	What are optimization options in Synopsys DC tool?
__Hint: boundary\_optimization, autoungroup, group_path__

---

### Round 2
###### Question 1
	Tell me about your previous project.
###### Question 2
	Tell me about your previous working experience.

---
### Round 3
###### Question 1
	What is clock gating?
###### Question 2
	What is the tradeoff between performance, power and area?
###### Question 3
	Given a circuit and input draw the waveform. (can't remember the detailed circuit but easy)
###### Question 4
	Given a waveform draw the circuit.
	               ___________
	input     ____|           |___________
	               _________________
	output    ____|                 |___________
__Hint: delay input by 2 cycles and add an OR gate__
###### Question 5
	Use mux to implement OR/AND gate.
	
---
### Round 4
###### Question 1
	What is stuck-at fault?
###### Question 2
	What is transition delay fault?
###### Question 3
	What is scan shift/capture?
	
---
### Round 5
###### Question 1
	Synthesis DC is zero wire load model. Why not use physical aware synthesis tool?
###### Question 2
	If you will use physical aware synthesis tool, how to decide the capacitor and resistor?
###### Question 3
	What is the difference between the timing reports of Design Compiler and Prime Time?
###### Question 4
	What is crosstalk?
###### Question 5
	What is congestion?
###### Question 6	
	How to read input delay look up table in library file?
	
---
### Round 6
###### Question 1
	What is timing constraints? Why it is needed?
###### Question 2
	What is input/output delay of a design? What is false_path?
###### Question 3
	What is multicycle_path? What is the command to apply MCP constraints?
###### Question 4
	What is OCV and CRPR?
###### Question 5
	What relationship can two clocks have?
	What is clock exclusivity?
	
---
### Round 7
###### Question 1
	What is setup/hold time?
###### Question 2
	What is the formula of setup/hold time violation?
###### Question 3
	Given a circuit and delay, calculate the minimum clock period to avoid setup violation.
###### Question 4
	Hold time violation is not related with clock frequency. Then how to fix hold time violations?

---
### Round 8
###### Question 1
	What is asynchronous FIFO? What components does it have?
###### Question 2
	Asynchronous FIFO depth calculation.
###### Question 3
	What is gray code? Why use gray code?
###### Question 4
	Convertion between binary and gray code.
###### Question 4
	Sequence detector. Using two methods.
__Hint:Finite state machine, shift register__
###### Question 5
	Single bit data clock domain crossing.
###### Question 6
	Bus clock domain crossing.
