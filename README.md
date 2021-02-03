# robot
building a redundant serial manipulator from scratch.<br/>

Quick roadmap:<br/>

* Single axis controller:<br/>
	* Boards for controller<br/>
		+ prepare BOM<br/>
	* Firmware for controller<br/>
		+ F4 bare<br/>
		+ FOC, maybe on FPGA (input torque/position output signal to fet driver)<br/>
	* Boards for encoder<br/>
		+ 12 bit<br/>
	* Firmware for encoder (if needed)<br/>
* Mechanics:<br/>
	* Select material<br/>
		+ Aluminum<br/>
	* Design<br/>
		+ Light/Simple<br/>
	* Print/cut<br/>
* Main controller:<br/>
	* Redundancy resolution kinematics/dynamics, the single axis controller will run at 20/40kHz so the redundancy resolution should solve at 5kHz in my dreams (maybe a Verilog implementation would come handy here)<br/>
	* Camera (eventually but not now)<br/>
	* F4 on RTOS (or embedded pc?)<br/>
