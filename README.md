# GALAHTableProcessing

A series of codes to assist with processing the various data sets that come out of GALAH.

cannon_processing reconfigures the output from The Cannon parameter pipeline. 
sme_processing reconfigures the output from SME.
Both of these combine with output from the Iraf reduction pipeline. 
wg4_output combines the cannon, sme, and iraf information into a master table. 

Currently, this code is pretty messy because the input from SME and the Cannon is in flux and 
we are iterating with the WG6 team on output table structure.  
