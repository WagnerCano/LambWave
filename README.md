# LambWave

This repository hosts the data used in the fourth chapter of my MsC thesis and in the article entitled "Autoregressive Models for Damage Prognosis in Smart Structures" (doi:10.20906/CPS/CON-2016-0209).

Read section 2 of the article for more details about the experimental procedure.

The files were named in the following scheme:

[basename] _ [testname] [numrept] _ [nummeas] _ [freq] KHz__5ciclos _ [pathname] .csv

basename = 'PL0402';                                                    % Name of the plate used throught the tests

testname = ['Ref'; 'Dn1'; 'Dn2'; 'Dn3'; 'Dn4'; 'Dn5'; 'Dn6'; 'Dn7'];    % Name of the condition tested (Ref1 to Ref3: no damage; Dn1 to Dn7: progression of damage)

freq = [100; 150; 200; 250; 300];                                       % Excitation frequencies used (in kHz)

numrept = 1:3;                                                          % Number of times the measurement of each tested condition was repeated

nummeas = 10;                                                           % Number of measurements per condition tested

pathname = 'B3_A3';                                                     % Transducer path (only A3-B3 available)
