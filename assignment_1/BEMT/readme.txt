This folder contains all the codes that you have to run in order to obtain all the data you need for the frequency domain propeller tonal noise code.

Below a checklist of what you have to do practically:
1) Generate the polar database running the script "generate_polar_for_bemt.m". Remember to set the input parameters according to the case you have to run!
2) Run the BEMT code. To do so, modify the input parameters in the script "UserInput.m" according to the case you have to run and then run the script "MainFile.m".
3) Read the output that you will find in the "outputs" folder and extract what you need.
4) Run your frequency domain propeller tonal noise code and compare the SPL at the BPF and harmonics with the reference data. Remember that what we give you is a time history of acoustic pressure, so you will have to compute the SPL in the frequency domain in some way!

We suggest you to create and put your main script and functions in this folder or in a subfolder which a clearly distinguishable name (for example, "tonal_noise_code"). You can take inspiration from the bemt code folder structure or look online. Remember that, if you need to read/write files, you must specify the correct path!
