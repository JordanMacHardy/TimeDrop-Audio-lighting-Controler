# TimeDrop-Audio-lighting-Controler
This max patch controls the audio and lighting for the time drop art installation

This Max Patch serves three main functions
1) it recieves a midi signaml from the main control knob inside timedrop.
2) it controles the rate and direction of playback based on a time streching algorithm.
3) it creates a pwm signal to trigger the lights in timedrop.

Set up procedures

- make sure the appropriate sound card is selected under options/audio status
- make sure the midi controler is selected in the midi module located in the central upper region of the patch
- set DAC tabs to output to apropriate sound card outputs. Current configuration DAC 1&2 main audio. DAC 3&4 PWM for lighting
  DAC 5&6 recording feed out.
  
  dependencies: Audio files should be in main project folder

