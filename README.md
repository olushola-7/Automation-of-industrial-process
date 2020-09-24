# Automation-of-industrial-process
This project explains an industrial process that involves picking and placing a material/product on a conveyor and a pusher pushing it to a box at a specified destination detected by a proximity sensor. The process continues to run automatically after the ready switch and start buttons are activated until the toggle switch is switched to stop. The logic is handled by a PLC (Mitsubishi FX series PLC). Thousands of materials/products can be placed in a day. This is a good application of industrial automation implementing a PLC, pick and place robot, pusher and a conveyor.

Mitsubishi PLC was used in this project. The program/source code is written using GX Developer FX software (A software for writing, editing and downloading/uploading program to/from Mitsubishi FX series PLC). You will need to install GX Developer FX to be able to open the project/view the source code after you have unzipped it. 

BRIEF EXPLANATION OF THE PROGRAM
When the stop/ready toggle switch (X21) is switched to ready position and the start push button (X20) is pressed and released, the robotic arm (supply command-Y0) picks the material/product and the conveyor (Y1) starts simultaneously. The robotic arm place the material/product on the conveyor. The material/product is then moved forward until it is detected by a proximity sensor (X0). The conveyor stops and a pusher (Y2) pushes the material/product to a box. The process repeats itself automatically until the stop/ready toggle switch is switched to stop.

The source code is written using ladder logic programming language. View the JPG files in this repository
for the io assignment, flow chart etc for better understanding.




For further explanation or clarification on this project, send a mail to: akandeolushola14@gmail.com or sholagentle@yahoo.com. You can also send a WhatsApp message to: +2348029266470.
