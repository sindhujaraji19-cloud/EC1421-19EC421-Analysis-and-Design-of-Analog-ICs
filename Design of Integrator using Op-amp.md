
# EC1421 - 19EC421 - Analysis-and-Design-of-Analog-ICs
# Design of Integrator using Op-amp.

## AIM:
To design and test the performance of integrator circuits using  Op-amp.

## APPARATUS REQUIRED:

<img width="811" height="206" alt="image" src="https://github.com/user-attachments/assets/fd527bf4-b7bf-4330-9b09-ce7ad607bdeb" />


## THEORY:

INTEGRATOR 
 
A circuit in which the output voltage waveform is the integral of the input voltage 
waveform is the integrator. Such a circuit is obtained by using a basic inverting amplifier 
configuration if the feedback resistor Rf is  replaced by a capacitor Cf .  The expression for the 
output voltage is given as, 

Vo = - (1/Rf C1 ) ∫ Vi dt 
 
Here the negative sign indicates that the output voltage is 180 0 out of phase with the 
input signal. Normally between fa and fb the circuit acts as an integrator. Generally, the value of 
fa < fb . The input signal will be integrated properly if the Time period T of the signal is larger 
than or equal to Rf Cf .

That is, T ≥ Rf Cf 
 
The integrator is most commonly used in analog computers and ADC and signal-wave 
shaping circuits.


## DESIGN
~~~
To obtain the output of an Integrator circuit with component values R1Cf = 0.1ms , Rf = 10 
R1 and Cf = 0.01 µF and also if 1 V peak square wave at 1000Hz is applied as input. 
We know the frequency at which the gain is 0 dB, fb = 1 / (2π R1 Cf) Therefore fb =    
Since fb = 10 fa , and also the gain limiting frequency fa = 1 / (2π Rf Cf) 
We get , R1 =  and hence Rf =

~~~
## CIRCUIT DIAGRAM:
<img width="1080" height="937" alt="image" src="https://github.com/user-attachments/assets/305ecd07-7cd5-4cf1-8016-f142d8b3c127" />




## MODEL GRAPH
<img width="1023" height="1600" alt="image" src="https://github.com/user-attachments/assets/4f8ea4ea-b7a2-4279-87a8-878b2d75f449" />




## PROCEDURE:

1. Connections are given as per the circuit diagram 
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC. 
3. By adjusting the amplitude and frequency knobs of the function generator, appropriate 
input voltage is applied to the inverting input terminal of the Op- Amp. 
4. The output voltage is obtained in the CRO and the input and output voltage waveforms 
are plotted in a graph sheet.

## TABULATION:
<img width="1080" height="820" alt="image" src="https://github.com/user-attachments/assets/a275d5ca-019e-43ba-825a-20ab01a73540" />




## GRAPH:
<img width="1074" height="1600" alt="image" src="https://github.com/user-attachments/assets/faf5722e-c6e8-4e65-bae7-8e3704d2d5dd" />
<img width="1080" height="1501" alt="image" src="https://github.com/user-attachments/assets/107a2e29-e55f-433e-8844-c60ba950e1c7" />





## RESULT:

Thus an Integrator using op-amp are designed and their performance was successfully tested using op-amp IC 741. 
