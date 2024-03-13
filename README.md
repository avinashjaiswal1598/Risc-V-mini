
# VSD Squadron RISC V mini Dev Board
![image](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/c6435eca-4c0d-4913-a0b2-3874dcdf37ff)


Board specifications

![Screenshot 2024-03-12 at 20-48-32 VSDSquadron Mini RISC-V development board - VSDSQMinidatasheet pdf](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/58b11788-475a-493b-9ff9-f883b9e41a7c)


### This is my first github repository Intended to update weekly progress
Progress Report

# 1st meeting was held on 16th FEB 2024
Description: Installing the opensorce EDA Tools
 <details>
  <summary> Task 1 </summary>
  
- Create Github repository
- install YOSIS
- install iverilog
- install gtkwave

## Graywolf
![Screenshot from 2024-02-22 12-30-19](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/2e601ec6-695f-4fa8-9ada-6d2ba518f49d)

## YOSYS
![Screenshot from 2024-02-22 12-25-19](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/f76091dc-f0a8-47b4-afed-9e21992825c1)
</details>

---


# 2nd call was held on 20th FEB 2024
DEscription: Go inside your your project SFIFO
 <details>
  <summary> Task 2 </summary>
- Mark the input output ports along with input output waveforms for your project

 My project for this interniship is-
# Synchronous First In First Out for Memory Storage and Processing
![Synchronous FIFO pdf](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/f2cc94e1-feac-4f9c-bbbe-b52f01479df5)


input output Waveform 
![Screenshot from 2024-02-26 17-33-33](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/12013901-0785-4613-9dc6-0c0fb84bfc68)
</details>

---

# 3rd call was held on 22nd FEB 2024
Description: Get familier with iverilog & gtkwave
 <details>
  <summary> Task 3 </summary>
- Learn how to use iverilog and gtkwave
- Perform the lab and update github repo
- Analyse how does hardware behaves
  
  Verilog Files contains all the design associated with testbench
  ![image](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/036085aa-366b-482a-9fc7-a6658cb372f2)
  Let us load the MUX into the simulator
  
  `iverilog good_mux.v tb_good_mux.v
  
  I observe the MUX
 
![Screenshot from 2024-02-26 17-33-33](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/ccdc1920-d62f-4838-bf4e-54906abd05d7)
</details>

---

  # 4th call was held on 27th FEB 2024
 Description: Get overview of YOSYS and create GLS
 <details>
  <summary> Task 4 </summary>
  - Using YOSYS create GLS design for MUX
  - create waveform
  - Both Functional Design waveform and GLS waveform should match

 ---
 
![Screenshot from 2024-03-02 11-16-12](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/61f7316d-8081-41bd-bcf3-ff9adf8b9d4e)


![Screenshot from 2024-03-01 12-03-00](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/b47b511e-e841-4124-96bc-d61b2e5c10db)



![gvim](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/7a6a68b4-1020-4d32-8465-f63359ef9c63)


### GLS Design Waveform

![Screenshot from 2024-03-02 11-17-23](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/244f3ae5-3294-4e13-86f7-4834e3de7d08)

### Functional Design Waveform


![GLS DEsign](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/a1a6e96f-42be-4e26-8621-a0bcbc227c51)


### _Both Functional and GLS Design waveform match_!
</details>

---

# 5th Task was given on 1st March 2024
Description: Simulate the wavefome with the given design code and netlist
<details>
  <summary> Task 5 </summary>
 
### Functional design for Synchronous FIFO
 
Cloning github repository

https://github.com/Anmol-S314/iiitb_sfifo.git

`iverilog iiitb_sfifo.v iiitb_sfifo_tb.v`

`gtkwave iiitb dump.vcd`

![Screenshot from 2024-03-13 11-26-38](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/7e286c35-7ead-4556-8490-2e5d7a3e89c8)

![iverilog](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/9b1dc06c-33dd-46b6-bba4-6248a8c39ad7)

Wavefom

![Screenshot from 2024-03-07 16-56-30](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/aee39763-f06a-4484-b6a9-de5b365bc0f9)

Synthesis of Verilog code
To generate netlist inside iiitb_sfifo

`yosys`

![Screenshot from 2024-03-09 11-56-38](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/06d5676b-8833-4f33-9a54-152881535a03)

Reading the library
Reading the design

`read_verilog iiitb_sfifo.v`

![Screenshot from 2024-03-09 12-35-45](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/bcbe23b1-367c-406d-9638-a3c7f0671585)


Synthesising the module

`synth -top iiitb_sfifo`

![Screenshot from 2024-03-09 12-39-51](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/d831f687-de58-4faa-8df1-adb68ebc0dd7)

![Screenshot from 2024-03-09 12-40-42](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/9fb6650a-3601-467f-8f4e-8816d7a1e31f)

To generate netlist 

`abc -liberty`

To write netlist

`write_verilog netlist.v`
`write_verilog -noattr netlist.v`

![Screenshot from 2024-03-09 13-14-42](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/9fe4ffce-f839-4335-91bf-7a7e7b489a52)

`flatten`
`show`

![Screenshot from 2024-03-09 13-20-05](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/81111cf5-37d8-4b4c-919c-2541e2ec0837)

To open netlist

`!gvim netlist.v`

![Screenshot from 2024-03-09 13-21-16](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/789b10cb-9bfc-47b7-bc86-03adc9bf940c)

To verify weather netlist match with the design 

`iverilog ../iiitb_sfifo/verilog_model/primitives.v ../iiitb_sfifo/verilog_model/sky130_fd_sc_hd.v netlist.v iiitb_sfifo_tb.v`
`./a.out`
`gtkwave dump.vcd`

![Screenshot from 2024-03-13 17-07-12](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/d1b340ca-2666-4c33-8151-d13a70e1b04c)

![Screenshot from 2024-03-09 13-30-00](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/b8be6fee-af4c-427c-943a-cc416dd2b15e)


---



