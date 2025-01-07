
## NAME: JAYAPRADAN M 

## REG NO: 24900886

## EX NO 7: IMPLEMENTATION  OF  SYNCHRONOUSU UP COUNTER

**AIM:**

To implement 4 bit synchronous up counter and validate functionality.

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 bit synchronous UP Counter**

If we enable each J-K flip-flop to toggle based on whether or not all preceding flip-flop outputs (Q) are “high,” we can obtain the same counting sequence as the asynchronous circuit without the ripple effect, since each flip-flop in this circuit will be clocked at exactly the same time:

![image](https://github.com/naavaneetha/SYNCHRONOUS-UP-COUNTER/assets/154305477/d5db3fa0-e413-404c-b80e-b2f39d82e7e8)


![image](https://github.com/naavaneetha/SYNCHRONOUS-UP-COUNTER/assets/154305477/52cb61eb-d04b-442d-810c-31185a68410b)

Each flip-flop in this circuit will be clocked at exactly the same time.
The result is a four-bit synchronous “up” counter. Each of the higher-order flip-flops are made ready to toggle (both J and K inputs “high”) if the Q outputs of all previous flip-flops are “high.”
Otherwise, the J and K inputs for that flip-flop will both be “low,” placing it into the “latch” mode where it will maintain its present output state at the next clock pulse.
Since the first (LSB) flip-flop needs to toggle at every clock pulse, its J and K inputs are connected to Vcc or Vdd, where they will be “high” all the time.
The next flip-flop need only “recognize” that the first flip-flop’s Q output is high to be made ready to toggle, so no AND gate is needed.
However, the remaining flip-flops should be made ready to toggle only when all lower-order output bits are “high,” thus the need for AND gates.

**PRODECURE**

1.Type the program in Quartus software

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

**PROGRAM**

![WhatsApp Image 2024-12-26 at 11 56 25_4c0ba3f1](https://github.com/user-attachments/assets/6c451ad2-0c8f-4e25-a940-99dd1aab8ae8)


**RTL LOGIC**

![WhatsApp Image 2024-12-26 at 11 56 24_5bf7d9f6](https://github.com/user-attachments/assets/91dd0e68-af03-4613-a8ba-af1e9cf6ac98)


**TIMING DIAGRAM**

![WhatsApp Image 2024-12-26 at 11 56 24_f9643611](https://github.com/user-attachments/assets/0498a4df-4c78-43f0-80db-f9424a9469ab)


**TRUTH TABLE**

![WhatsApp Image 2024-12-26 at 12 00 01_ba24c96f](https://github.com/user-attachments/assets/6142a882-c7eb-4f48-865a-334908c47b4d)

**RESULTS**

Thus to implement 4 bit synchronous up counter and validate functionality done successfully.
