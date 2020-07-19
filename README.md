# Prototype-IR-Signal-Receiver-and-Decoder
Design and assembly , with a lab partner , of a TV-like signal receiver.

### General Description-What it does
   The end result was a signal receiver capable of accurately decoding signals of (IR) remote controls (31kHz nominal frequency) to distances of up to about 3 metres.The implementation was done on a prototype circuit board.It was designed on paper, tested via pc simulations and lab equipment.
   
### Why this project 
  This project was not focused on a specific application and it was done for a lab project in ECE NTUA engineering school.However, emphasis was put on the concepts of driving photodiode signal,filtering, amplifying and decoding that signal to finally deliver a specific output current on a "crucial device" (simulated as led current).
  
### What this project DID NOT focus on
 > * Perfectly smoothing photodiode signal and figuring out spcific nominal angles for electron excitation.
 > * Strictly filtering input signal around 31Khz. This means, frequencies close enough to 31Khz will still pass.
 > * Having perfect smoothing and expected wave forms in every stage.(Oscillations are possible but do not affect the project goal).Only cared about final stage current output.
 
## DESIGN


<img src="Images/design.jpg">

#### First Steps

* Theoretically , we gain a signal of 20 mV pp when photodiode is excited.
