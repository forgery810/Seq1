# Seq1
Drum Sequencer VST

# Installation
Currently for Windows only. This will hopefully change.
Copy the Seq1 folder to a directory that your DAW searches for vsts. Install through the DAW as you normally would. 
This has only been tested on FL Studio. Feedback is appreciated.

If you find this vst useful, please consider donating. It does represent quite a bit of work.

# Instructions
Click the purple squares on the right to load samples into each slot. The sequencer playback is controlled by your DAW. The purple rectangle on the left controls the time division. Rates around 1/16 are recommended. After 1/32 or so the sequencer may not function properly.

This does not have an presets options at the moment, therefore it might be best to load a kit and save a preset using your DAW before you create a pattern to always have a starting point to go back to.

rs1 - resets the first sequencer
rs2 - the second

n1:4 - skips the first trig every 4 passes.
1:3 - plays the first of every 3 passes.
34:4 - plays third and fourth of every 4 passes.
etc

en1 - trigs 1st envelope
etc

an1
an2 - sends lfo or envelope output to and logic module. And module must have one lfo (pulse waveshape recommended) and one envelope to function. Will send multiple trigs at rate of lfo while envelope is high to selected sample.


