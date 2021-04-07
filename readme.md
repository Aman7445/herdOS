## HerdOS ##
<br>

### On Linux install these softwares ###

<li>sudo apt install nasm -y
<li>sudo apt install qemu -y </li>

<br>

### To load the bootsector on Linux ###
<li>nasm boot 32bit-main.asm -f bin -o 32bit-main.bin</li>

<li> qemu_system_x86-64 32bit-main.bin</li>