# tensorflow-1.8.0-without-avx
A build from source of tensorflow 1.8.0 that can run on older machines. Compiled without AVX so won't give you omnious "core dumped" on import.

was built (very slowly) on i7 with the following cpu flags:
flags		: fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov 
pat pse36 clflush dts acpi mmx fxsr sse sse2 ss ht tm pbe syscall nx rdtscp lm c
onstant_tsc arch_perfmon pebs bts rep_good nopl xtopology nonstop_tsc aperfmperf
 pni pclmulqdq dtes64 monitor ds_cpl vmx smx est tm2 ssse3 cx16 xtpr pdcm pcid s
se4_1 sse4_2 popcnt aes lahf_lm tpr_shadow vnmi flexpriority ept vpid dtherm ida
 arat
#Installation
Download the file
Install with "pip install tensorflow-1.8.0-cp27-cp27mu-linux_x86_64.whl"

No GPU support, sorry...
