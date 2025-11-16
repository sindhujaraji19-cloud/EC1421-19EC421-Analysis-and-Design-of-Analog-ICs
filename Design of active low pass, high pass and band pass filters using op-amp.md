
# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
# DESIGN OF ACTIVE LOW PASS,HIGH PASS AND BAND PASS FILTERS USING OP-AMP 

## AIM: 

To design and obtain the frequency response of 
i) First order Low Pass Filter (LPF) 
ii) First order High Pass Filter (HPF) 
iii) Band pass filter
 
## APPARATUS REQUIRED

<img width="625" height="170" alt="image" src="https://github.com/user-attachments/assets/900fc8b3-3a8c-4208-bf52-98cc9e281e21" />

## THEORY
## LOW PASS FILTER 
 A LPF allows frequencies from 0 to higher cut of frequency, fH.  At fH the gain is 0.707 
Amax, and after fH gain decreases at a constant rate with an increase in frequency.  The gain 
decreases 20dB each time the frequency is increased by 10.  Hence the rate at which the gain 
rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in 
frequency.  The frequency f=fH is called the cut off frequency because the gain of the filter at this 
frequency is down by 3 dB from 0 Hz.  Other equivalent terms for cut-off frequency are -3dB 
frequency, break frequency, or corner frequency.
# HIGH PASS FILTER 
The frequency at which the magnitude of the gain is 0.707 times the maximum value of 
gain is called low cut off frequency.  Obviously, all frequencies higher than fL are pass band 
frequencies with the highest frequency determined by the closed –loop band width all of the op
amp. 
# BAND PASS FILTER 
A band pass filter has a pass band between two cutoff frequencies fH and fL such that fH > 
fL.  Any input frequency outside this pass band is attenuated.  There are two types of band-pass 
filters.  Wide band pass and Narrow band pass filters.  We can define a filter as wide band pass if 
its quality factor Q <10.  If Q>10, then we call the filter a narrow band pass filter.  A wide band 
pass filter can be formed by simply cascading high-pass and low-pass sections.  The order of 
band pass filter depends on the order of high pass and low pass sections.

## CIRCUIT DIAGRAM: 
## LOW_PASS
<img width="1080" height="1099" alt="image" src="https://github.com/user-attachments/assets/da3012ad-d9f6-4793-bc84-c0ee91f14294" />

## HIGH-PASS
<img width="1080" height="878" alt="image" src="https://github.com/user-attachments/assets/597c8a16-cf11-4ae1-a25b-4c634108541c" />

## BAND-PASS
<img width="1080" height="817" alt="image" src="https://github.com/user-attachments/assets/137f9af8-bc42-47c2-b275-0fcd7d9ceab4" />


## MODEL GRAPH:
## LOW_PASS
<img width="1080" height="637" alt="image" src="https://github.com/user-attachments/assets/0d89b5cf-ef2d-404d-b6be-efcd3c391b50" />

## HIGH-PASS
<img width="1080" height="853" alt="image" src="https://github.com/user-attachments/assets/cd894df7-cedf-4c27-b411-da1b865e1cd4" />

## BAND-PASS
<img width="1080" height="939" alt="image" src="https://github.com/user-attachments/assets/1b5a135d-0a29-4256-8400-4301f6ef9bd0" />


## PROCEDURE - (LPF & HPF): 
1. Connect the circuit as shown in the circuit diagram. 
2. Select the corresponding cut-off frequency (higher or lower) and determine the value of C&R. 
select the value of R1 & Rf depending on desired passband gain Af.. 
3. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
4. Tabulate the output voltage Vo with respect to different values of input frequency. 
5. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to  get approximately the same characteristic as shown in the model graph. 
# PROCEDURE:BAND PASS FILTER 
1. Select the lower and higher cut-off frequency and calculate the value of R & C for the given 
frequencies. 
2. Design for LPF & HPF separately and then combine the circuit by first placing the HPF 
followed by a LPF (i.e) HPF in series with LPF. 
3. Connect the circuit as shown in the circuit diagram. 
4. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
5. Tabulate the output voltage Vo with respect to different values of input frequency. 
6. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to get approximately the same characteristic as shown in the model graph

## DESIGN:LPF & HPF:

<img width="429" height="324" alt="image" src="https://github.com/user-attachments/assets/b0f0ac0a-3006-494c-9096-e91ae2d6e87c" />

# DESIGN: BAND PASS FILTER
Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.  
1. Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency 
of HPF as fL = 1 KHz.  
2. Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf.  
Let C = 0.1μf.  
3. Calculate R from the expression.  
Given: fH = 2KHz  = 1/ (2πR1C1) 
   Let C1 = 0.1 µF, R1 = 7.9 KΩ 
Given: fL = 400Hz  = 1/ (2πR2C2) 
   Let C2 = 0.1 µF, R2 = 39.8 KΩ 
  Pass band Gain=4 
   Now   Ao = 1 + (Rf / R1)  
               2-1=(Rf / Ri) 
                Ri = Rf 
                 Let  Ri = Rf = 10 KΩ
## TABULATION:
## LOW_PASS
<img width="1080" height="1517" alt="image" src="https://github.com/user-attachments/assets/d7a9eae5-d690-4b71-a89f-e358d98cf202" />


## HIGH-PASS
<img width="1080" height="1235" alt="image" src="https://github.com/user-attachments/assets/c9462451-d1e0-4f8e-b7fc-08ffef167ca5" />

## BAND-PASS
<img width="1080" height="915" alt="image" src="https://github.com/user-attachments/assets/7a667324-a961-4ab0-817b-07e33d2a8ea3" />

## CALCULATIONS:
## LOW_PASS
## HIGH-PASS
## BAND-PASS
## LOW_PASS
## HIGH-PASS
## BAND-PASS
## GRAPH:
## LOW_PASS
<img width="1534" height="1069" alt="image" src="https://github.com/user-attachments/assets/75f50fdc-c4fa-499c-978f-df62e682bf41" />

## HIGH-PASS
<img width="1427" height="1042" alt="image" src="https://github.com/user-attachments/assets/cbf156a2-1bc8-4102-91f5-56ec468dca56" />

## BAND-PASS
<img width="1519" height="1041" alt="image" src="https://github.com/user-attachments/assets/b4e1b64b-62e4-4b50-923a-249c89aee6c6" />

 ## RESULTS:
Thus an Active Low pass, High pass and Band Pass Filters are designed and 
tested using op-amp IC 741. 
