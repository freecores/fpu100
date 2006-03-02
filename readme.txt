The Compilation order is:

fpupack.vhd
pre_norm_addsub.vhd
addsub_28.vhd
post_norm_addsub.vhd
pre_norm_mul.vhd
mul_24.vhd
vcom serial_mul.vhd
post_norm_mul.vhd
pre_norm_div.vhd
serial_div.vhd
post_norm_div.vhd
pre_norm_sqrt.vhd
sqrt.vhd
post_norm_sqrt.vhd
comppack.vhd
fpu.vhd

***For simulation ****
\test_bench\FPU_II\*.* ( a reliable reference FPU is needed for the testbench. For more info read readme.txt in test_bench)

tb_fpu.vhd 

To run then the simulation just execute fpusim.bat in a command prompt.