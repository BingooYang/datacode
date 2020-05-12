You can verify the experiment results through the following steps.
If Vaa3D is not built on your computer, you need to follow the instructions in step1 to install it. If you have already built Vaa3D, you can start from step 2.

step1: Build Vaa3D platform, you can refer to the tutorial:
https://github.com/Vaa3D/Vaa3D_Wiki/wiki/Vaa3D-Wiki

step2: Compile "neuron_distance_vn2 plugin", then you can run the plugin on the command line. For example, run the following script to calculate the ESA, DSA and PDS of U-T (Ultra-Tracer) on 67 neurons in whole mouse brain A.

"Vaa3d -x neuron_distance -f neuron_distance -i path of A_GS folder path of A_UT folder  -o path of output result path"

After running the above command, you will get a file named "dis_score.txt". The fourth column, the fifth column and the eighth column of the txt file are ESA, DSA and PDS values, respectively. Their means and standard deviations correspond to the values of U-T in Table IV. 

Same process to get other results in  Table IV and Table VI.