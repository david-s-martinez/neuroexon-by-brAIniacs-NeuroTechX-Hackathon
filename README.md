# NeuroTechX-Hackathon

![alt text](https://github.com/davidmartinez13/neuroexon-by-brAIniacs-NeuroTechX-Hackathon/blob/main/readme_files/neuroexon_logo.png)
The population affected by stroke is projected to quadruple by 2050. And stroke survivors
often experience muscle weakness. This degeneration in the muscles can be problematic and
prevent them from performing everyday tasks. Therefore, they need neurorehabilitation to
train the muscles and regain function. However, this requires repetitive movements and
patients often lack motivation.
Here, we present a hybrid BCI paired with an elbow exoskeleton and haptic feedback to
improve the neurorehabilitation experience. Our system combines Motor Imagery (MI) of leftand right-hand movement and Steady-State Visually Evoked Potentials (SSVEPs) with
stimulations at 8 and 13 Hz to control an elbow exoskeleton. The combination of MI and SSVEPs
improves the accuracy of the system, and the elbow exoskeleton includes a vibrotactile sensor
that provides haptic feedback. The sensory feedback to the user on top of the visual feedback
of the exoskeleton moving improves the user experience and aims to further help restore the
function in the arm.

The system is low cost and portable, implemented using 3D printed materials and a Raspberry
Pi and Arduino board to control the exoskeleton and the haptic feedback system. On the other
hand, the BCI system records the Smarting 24 EEG signals of the user while performing cuebased motor imagery and SSVEPs and processes it extracting the power spectral density (PSD)
and common spatial patterns (CSP) as features. Those features are then passed to an LDA
classifier that outputs the class: left-hand or right-hand movement. This output is then used as
a control signal to move the elbow exoskeleton from the resting position (at 90º) to either 0º
(flexion) or 170º (extension). This movement is preceded by a vibrotactile feedback to the other
arm, which is assumed to be functional in a stroke patient. In the future, error-related potentials
elicited by this feedback is planned to cancel false positive control signals.

References
1 U. N. D. of Economic and S. A. P. Division,World population ageing: 2017 highlights. UN,2017.
2 L. A. Martinez, O. O. Olaloye, M. V. Talarico,S. M. Shah, R. J. Arends, and B. F. BuSha, “Apower-assisted
exoskeleton optimized for pinch-ing and grasping motions,” inProceedings of the2010 IEEE 36th Annual
Northeast Bioengineer-ing Conference (NEBEC), 2010, pp. 1–2
3 G. Pfurtscheller et al., “The hybrid BCI,” Frontiers in Neuroscience, vol. 4, 2010, Accessed: Oct. 30,
2022, Available: https://www.frontiersin.org/articles/10.3389/fnpro.2010.00003