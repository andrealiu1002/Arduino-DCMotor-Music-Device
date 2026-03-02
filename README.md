Built an Arduino-based generative sound installation as my final project for the Synthesis Theory course at Peabody. 
A DC motor spins a disc with black/white patterns, while an IR sensor switches between Phrygian, major, and minor scales, creating different harmonic moods.

A joystick and a photoresistor control the rhythmic “feel”: the X-axis adds jitter to the tempo, 
the Y-axis and ambient light change the density of rests and note length, and a knob sets the global root note/register. 
The whole system runs with non-blocking timing using millis(), so the motor, sensors, and audio can all respond in real time without delay().
