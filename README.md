# QHRR - Quasi Hyper Redundant Robot
Building a 8dof redundant serial manipulator from scratch.<br/>

Quick roadmap:<br/>

* Single axis controller:<br/>
	* Boards for controller<br/>
		+ prepare BOM<br/>
	* Firmware for controller<br/>
		+ F4 bare<br/>
		+ FOC<br/>
	* Boards for encoder<br/>
		+ 12 bit, maybe MHM by iC Haus<br/>
	* Firmware for encoder (if needed)<br/>
	* RGB circle around axis for visuals <br/>
	* Power off brake (multiple under from Ali under testing) <br/>
* Mechanics:<br/>
	* Select material<br/>
		+ Aluminum<br/>
		+ PLA for in house tests<br/>
	* Design<br/>
		+ Light/Simple<br/>
	* Print/cut parts<br/>
* Main controller:<br/>
	* Redundancy resolution kinematics/dynamics, the single axis controller will run at 20/40kHz so the redundancy resolution would be nice to resolve @~5kHz in my dreams (maybe a Verilog implementation would come handy here)<br/>
	* Camera (eventually but not now)<br/>
	* F4 on RTOS or Pynq (most likely Pynq)<br/>
