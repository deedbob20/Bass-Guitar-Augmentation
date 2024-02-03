# Bass-Guitar-Augmentation
A Max patch built to detect bass guitar playing technique, through connection with the Wekinator ML Application, allowing audio effects/augmentations to be triggered.

The Max Patch allows for either Plucking Styles (PS) or Left-hand Expression Styles (ES) to be detected, using the corresponding Wekinator file.

NOTE: The Machine Learning (SVM) algorithms in the Wekinator have been trained using my Fender Jazz Bass, the classification is unlikely to be as effective when using different bass guitars. However, the Wekinator classifiers can easily be retrained using a different Bass Guitar, by feeding it a number of samples of each playing technique, across all frets of the instrument.

For my Fender Jazz Bass, I achieved classification scores of 78% accuracy for detection of plucking-styles (PS) and 69% accuracy for detection of expression-styles (ES). See if you can improve upon this!


Instructions:

- Open both PS_mfcc_FINAL and ES_MFCC_FINAL Wekinator patches
- Run PS on port 6448 and 12,000.
- Run ES on port 6449 and 12,001.
- Select PS (plucking-style) or ES (Expression style) triggers


Playing Technique Augmentation Mappings: 
PS:
- FS (Finger-style): Clean
- PK (Plucking): Reverb
- SP/ST (Slap-pull/Slap-thumb): Delay
- MU (Muted): Play twice to turn Distortion on/off

ES:
- NO (FS) (Finger-style): Clean
- HA (Hammer-on): Turn Reverb on/off
- DN (Dead-note): Play twice to turn Distortion on/off
