Ex. No : 1 	 
 
GENERATION  OF  ELEMENTARY  DISCRETE - TIME  SEQUENCES 
Date  : 	
 
 
AIM: 	 
 
To write a MATLAB  program to generate various  discrete- time sequences. 
 	 
SOFTWARE   REQUIRED: 
 
MATLAB (R2020)  software. 
 
ALGORITHM: 
 
UNIT IMPULSE RESPONSE: 
•	Start the program 
•	Enter the value of N 
•	Generates zeros and ones for the corresponding values of  n to get the impulse response 
•	Plot the output. 
 
UNIT STEP RESPONSE: • Start the program 
•	Enter the value of  N 
•	Generates ones for the corresponding values of n to get the unit step response 
•	Plot the output. 
 
EXPONENTIAL RESPONSE 
•	Start the program 
•	Enter the value of N 
•	Generates the corresponding values of n to get the exponential response 
•	Plot the output. 
 
UNITRAMPRESPONSE: 
•	Start the program 
•	Enter the value of N 
•	Generates the corresponding values of n to get the unit ramp response 
•	Plot the output. 
 
 
SINEWAVE: 
•	Start the program 
•	Enter the value of N 
•	Generates the corresponding values of n to get the sine wave using sin function • 	Plot the output. 
 
COSINE WAVE: 
•	Start the program 
•	Enter the value of N 
•	Generates the corresponding values of n to get the cosine wave using cos function 
•	Plot the output.  
  
 
PROGRAM: 
 
clc; clear all; 
close all; 
 
%UNIT IMPULSE SIGNAL% 
N=8; n=0; x=ones(1,1); subplot(3,3,1); stem(n,x); xlabel('n'); 
ylabel('x(n)'); 
title('UNIT IMPULSE SIGNAL'); 
 
%UNIT STEP SIGNAL% 
N=8; n=0:1:N-1; x=ones(1,N); subplot(3,3,2); stem(n,x); xlabel('n'); 
ylabel('x(n)'); 
title('UNIT STEP SIGNAL'); 
 
%UNIT RAMP SIGNAL% 
N=8; n=0:1:N-1; x=0:1:N-1; subplot(3,3,3); stem(n,x); xlabel('n'); 
ylabel('x(n)'); 
title('UNIT RAMP SIGNAL'); 
 
%EXPONENTIAL WAVE% 
N=8; n=0:1:N-1; x=exp(n); subplot(3,3,4); stem(n,x ); xlabel('n'); 
ylabel('x(n)'); 
title('EXPONENTIAL WAVEFORM'); 
 
 
%SINE WAVE% 
N=8; n=0:1:N-1; x=sin(.2*pi*n); subplot(3,3,5); stem(n,x); xlabel('n'); 
ylabel('x(n)'); 
title('SINE WAVE'); 
 
%COSINE WAVE% 
N=8; n=0:1:N-1; x=cos(.2*pi*n); subplot(3,3,6); stem(n,x); xlabel('n'); 
ylabel('x(n)'); 
title('COSINE WAVE'); 
 
  
RESULT: 
 
Thus the generation of various discrete time sequences has been performed using MATLAB program. 
