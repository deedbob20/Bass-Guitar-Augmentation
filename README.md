# Bass-Guitar-Augmentation
A Max patch built to detect bass guitar playing technique, through connection with the Wekinator ML Application, allowing audio effects/augmentations to be triggered.


Instructions:

- Open both PS_mfcc_FINAL and ES_MFCC_FINAL Wekinator patches
- Run PS on port 6448 and 12,000.
- Run ES on port 6449 and 12,001.
- Select PS (plucking-style) or ES (Expression style) triggers



Playing Technique Augmentation Mappings: 
PS:
- FS (Finger-style): Clean
- PK (Pluckinh): Reverb
- SP/ST (Slap-pull/Slap-thumb): Delay
- MU (Muted): Play twice to turn Distortion on/off


ES:
- NO (FS) (Finger-style): Clean
- HA (Hammer-on): Turn Reverb on/off
- DN (Dead-note): Play twice to turn Distortion on/off
