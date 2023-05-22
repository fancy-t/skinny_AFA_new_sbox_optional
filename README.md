# skinny_AFA_new_sbox_optional

//This folder contains the relevant dataset for the paper.

//In the file name cnf_file_(**-**)_($R), (**-**) represents the bit interval of fault injection 
and $ represents the number of rounds of fault injection.

//The number of experimental samples for each scenario is 50, and the solving time is set to one hour, 
after which the attack is considered to have failed. cnf_time.txt file gives the solving time for each sample separately.

//location_of_fault_in_datas gives the location of fault for 50 samples separetely.

//The count_cnf_time.py  file is a script file that calls the solver to recover the keys and automatically 
generates the time statistics file.


The reader can download the cryptominisat solver under Ubuntu and 
use count_cnf_time.py to reproduce the experimental results.
