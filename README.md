# EXP.NO.1-EXPERIMENTAL-VERIFICATION-OF-VARIOUS-TYPES-OF-SAMPLING-TECHNIQUES
 

1.Experimental Verification Of Signal Sampling Using Various Types Such as 
    i) Natural Sampling
    ii) Flat Top Sampling

## AIM
 To perform experimental verification of various types of sampling such as natural sampling and flat top sampling.
## APPARATUS REQUIRED
Trainer Kit, DSO (10MHz), Patch Cords, Power Supply (0-30V)   
## PROCEDURE
**NATURAL SAMPLING:**
1. Refer to the block diagram and carry out the following connections and switch setting.
2. Connect power supply in proper polarity to the kit DCL-10 and switch it on.
3. Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer and the BUF OUT part of the buffer to the IN post of the flat top sampling block by means of the connecting chords provided.
4. Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4).
5. Using clock selector switch (S1) select 8khz sampling frequency.
6. Using switch (Sw2) select 50% duty cycle.
7. Connect the OUT post of the flat top sampling block to the input IN1 of the second order low pass Butterworth filter and take necessary observations as mentioned below.
8. Repeat the procedure for the 2khz sine wave signal as input.

**SAMPLE AND HOLD**:
1. Refer to the block diagram and carry out the following connection and switch setting.
2. Connect power supply in proper polarity to the kit DCL-01 and switch it on.
3. Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer and the BUF OUT part of the buffer to the In post of the flat top sampling block by means of the connecting chords provided.
4. Connect the sampling frequency clock in the internal mode INT clk using switch(Sw4).
5. Using clock selector switch(S1) select 8khz sampling frequency.
6. Using switch (Sw2) select 50% duty cycle.
7. Connect the OUT post of the flat top sampling block to the input IN 1 of the second order low pass Butterworth filter and take necessary observation as mentioned below.
8. Repeat the procedure for the 2khz, sine wave signal as input.

**FLAT TOP SAMPLING:**
1. Refer to the block diagram and carry out the following connection and switch setting.
2. Connect power supply in proper polarity to the kit DCL-01 and switch it on.
3. Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer and the BUF OUT part of the buffer to the In post of the flat top sampling block by means of the connecting chords provided.
4. Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4).
5. Using clock selector switch(S1) select 8khz sampling frequency.
6. Using switch (Sw2) select 50% duty cycle.
7. Connect the OUT post of the flat top sampling block to the input IN 1 of the second order low pass Butterworth filter and take necessary observation as mentioned below.
8. Repeat the procedure for the 2khz, sine wave signal as input
## CIRCUIT DIAGRAM
**NATURAL SAMPLING:**

![image](https://github.com/user-attachments/assets/be8015bb-f29d-4499-8b80-47c2c0dedfb0)

**SAMPLE AND HOLD**:

![image](https://github.com/user-attachments/assets/0099a7d4-4f74-4108-bd5a-4dd207cf96b4)

## MODEL GRAPH
**NATURAL SAMPLING:**

![image](https://github.com/user-attachments/assets/0b15e693-c04d-46c6-af98-2a651bd3d570)

**FLAT TOP SAMPLING:**

![image](https://github.com/user-attachments/assets/50540466-8251-4b9a-9708-06a3ab4ae18b)


## TABLE

![image](https://github.com/user-attachments/assets/6ec0cb35-2900-408d-9a1c-776e3dbb75d1)


## OUTPUT GRAPHS

## RESULT 
Thus the sampling and reconstruction of the given input signal is done using different types of sampling techniques (Natural, Flat top, Sample and Hold) circuit.
