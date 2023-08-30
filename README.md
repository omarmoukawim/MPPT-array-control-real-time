This project aimed at simulating photovoltaic (PV) arrays and a boost
converter in Simulink, integrating the Perturb and Observe (P&O) algorithm for
Maximum Power Point Tracking (MPPT) running on a Texas Instruments board, in particular, the LAUNCHXL-F28379D development kit.  The serial communication between MATLAB and the Texas Instruments board for the purpose of achieving a Processor-in-the-Loop (PiL) simulation has been implemented too.
After simulating the regular P&O an enhanced version of it has been implemented: the variable step version, this to overcome problems that arise in partial shading scenarios.
