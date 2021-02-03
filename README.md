# robot
building a redundant serial manipulator from scratch.

Quick roadmap:

1- Single axis controller:
	.Boards for controller
		- prepare BOM
	.Firmware for controller
		- F4 bare
		- FOC, maybe on FPGA (input torque/position output signal to fet driver)
	.Boards for encoder
		- 12 bit
	.Firmware for encoder (if needed)
2- Mechanics:
	.Select material
		- Aluminum
	.Design
		- Light/Simple
	.Print/cut
3- Main controller:
	.Redundancy resolution kinematics/dynamics, the single axis controller will run at 20/40kHz so the redundancy resolution should solve at 5kHz in my dreams (maybe a Verilog implementation would come handy here)
	.Camera (eventually but not now)
	.F4 on RTOS (or embedded pc?)
