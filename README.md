# Si5351vfo_bfo
A combined VFO and BFO using Si5351
The VFO can be adjusted with rotary encoder. Step sizes are selected by momentary push of the encoder switch. 
To select the BFO keep the encoder switch pressed for longer than 1 second  and the current bfo frequency will appear on the second line of display. It too can be adjusted using the rotary encoder and selecting the step size by momentary push of the same switch. 
To bring back normal display of VFO press the switch again for 1+ seconds.

Connect the outputs of VFO and BFO to your rig and enjoy stable VFO.

Important:
In the Si5351 library, edit si5351.h and edit as following:

 #define SI5351_FREQ_MULT      1ULL                // originally it was 100ULL

If this is not done your freq will be one hondredths of displayed freqs.
