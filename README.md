
# VSD Squadron RISC V mini Dev Board
![image](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/c6435eca-4c0d-4913-a0b2-3874dcdf37ff)


Board specifications

![Screenshot 2024-03-12 at 20-48-32 VSDSquadron Mini RISC-V development board - VSDSQMinidatasheet pdf](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/58b11788-475a-493b-9ff9-f883b9e41a7c)


### This is my first github repository Intended to update weekly progress
Progress Report

# 1st meeting was held on 16th FEB 2024
Description:Installing the opensorce EDA Tools
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
DEscription:Go inside your your project SFIFO
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
Description:Get familier with iverilog & gtkwave
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
 
Cloning gitub repository

https://github.com/Anmol-S314/iiitb_sfifo.git

```iverilog iiitb_sfifo.v iiitb_sfifo_tb.v

gtkwave iiitb dump.vcd


![Screenshot from 2024-03-07 16-59-28](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/f0b04a25-9662-48f8-8026-e99b4faae700)

![Screenshot from 2024-03-07 16-57-20](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/837ef4f2-3ce2-4fb2-b632-863400741653)


## GLS 

![Screenshot from 2024-03-07 16-58-53](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/eee77db6-08a8-40fa-929a-25c66fefdb85)

![Screenshot from 2024-03-07 16-56-30](https://github.com/avinashjaiswal1598/Risc-V-mini/assets/160040323/d4ff5ffe-f591-4da6-a31f-355badaf2291)
</details>

---



