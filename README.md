# EXP.NO.1-EXPERIMENTAL-VERIFICATION-OF-VARIOUS-TYPES-OF-SAMPLING-TECHNIQUES
 

1.Experimental Verification Of Signal Sampling Using Various Types Such as 
    i) Natural Sampling
    ii) Flat Top Sampling

## AIM
 To perform experimental verification of various types of sampling such as natural sampling and flat top sampling.
 
## APPARATUS REQUIRED
Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V)   

## PROCEDURE

NATURAL SAMPLING:

Refer to the block diagram and carry out the following connections and switch setting. 
Connect power supply in proper polarity to the kit DCL-10 and switch it on. 
Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer 
and the BUF OUT part of the buffer to the IN post of the flat top sampling block by means of the 
connecting chords provided. 
Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4). 
Using clock selector switch (S1) select 8khz sampling frequency. 
Using switch (Sw2) select 50% duty cycle. 
Connect the OUT post of the flat top sampling block to the input IN1 of the second order low 
pass Butterworth filter and take necessary observations as mentioned below. 
Repeat the procedure for the 2khz sine wave signal as input. 

FLAT TOP SAMPLING:

Refer to the block diagram and carry out the following connection and switch setting. 
Connect power supply in proper polarity to the kit DCL-01 and switch it on. 
Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer 
and the BUF OUT part of the buffer to the In post of the flat top sampling block by means of the 
connecting chords provided. 
Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4). 
Using clock selector switch(S1) select 8khz sampling frequency. 
Using switch (Sw2) select 50% duty cycle. 
Connect the OUT post of the flat top sampling block to the input IN 1 of the second order low 
pass Butterworth filter and take necessary observation as mentioned below. 
Repeat the procedure for the 2khz, sine wave signal as input

## CIRCUIT DIAGRAM
Natural sampling:
![Screenshot 2025-04-06 195410](https://github.com/user-attachments/assets/ff949c53-fe6b-410a-b992-d8f7ace88436)

Flat-Top Sampling:
![Screenshot 2025-04-06 195449](https://github.com/user-attachments/assets/aeba5db5-96c4-44f9-ad0b-48abea843e70)


## MODEL GRAPH
i) Natural Sampling
![Screenshot 2025-04-06 195558](https://github.com/user-attachments/assets/bc177a39-4917-45fb-b8a3-1190bca01911)

ii) Flat Top Sampling
![Screenshot 2025-04-06 195629](https://github.com/user-attachments/assets/ca2d6588-70f1-4e0c-8307-8a32286693bd)

## TABLE

![WhatsApp Image 2025-04-06 at 19 58 34_11f8c3d5](https://github.com/user-attachments/assets/16712679-5238-4af9-9c3d-02bd8d7b1be7)


## OUTPUT GRAPHS
i) Natural Sampling

![WhatsApp Image 2025-04-06 at 20 11 54_dda9a9a3](https://github.com/user-attachments/assets/c22b68cb-c768-4b27-a804-6b1ed3d3b5d3)

ii) Flat Top Sampling

![WhatsApp Image 2025-04-06 at 20 11 54_bfbfabf8](https://github.com/user-attachments/assets/3b0dfdab-8b45-411b-9f1d-eb518bd224bc)

## RESULT 
Thus the sapmpling and reconstruction of the given input signal is done using different types of sampling techniques.
