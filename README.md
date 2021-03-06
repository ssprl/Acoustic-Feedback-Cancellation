# Adaptive Noise Injection Based Acoustic Feedback Cancellation


## Overview
Purpose of the application is to demonstrate Acoustic Feedback Cancellation on smartphone devices.  Loudspeaker of the device playes the recorded sound
in real time and microphone again captures it, creating infinite feedback loop. Application uses Adaptive Noise Injection based Algorithm to tackle the feedback problem.

> Abstract
Acoustic feedback cancellation is a challenging problem in
the design of sound reinforcement systems, hearing aids, etc. Acoustic
feedback is inevitable when the acoustic signal path forms a loop
between the microphone and loudspeaker. An efficient short duration
noise injection algorithm is proposed in this paper to estimate the
impulse response of the acoustic feedback path model. The algorithm
does not require any prior information about the acoustic feedback
path. It is capable of optimally estimate the acoustic feedback path
for cancellation, and avoid the occurrence of any howling episode, in
varying acoustic environments. Presented algorithm is efficiently implemented
on smartphone device having close proximity of loudspeaker
and microphone to emulate the feedback condition. The algorithm being
platform-independent can also be implemented for any set-up or system.
The experimental results of the proposed method shows satisfying
results and its ability to track and cancel the acoustic feedback in
changing characteristics of the acoustic path.


## Audio Video Demo

For video demo of the application, please refer: https://www.youtube.com/watch?time_continue=2&v=uJS-AeDTFxk&feature=emb_logo
For audio demo of the application, please refere: https://utdallas.edu/ssprl/hearing-aid-project/video-demonstration/acoustic-feedback-cancellation/


## Requirements
**Install Xcode to run it on local iPhone or mac processor.
**Runs on iPhone with iOS 10+ versions.
Install using .xcodeproj file.

**Privacy Note: Application records through your microphone. App does not save data nor save it, to process later..**


## User guide
More details about how the application was developed is written in [USER GUIDE](AFC_Users-Guide-iOS.pdf) file available in the same folder.

For more details about the algorithm please refer the work:
Efficient Real-Time Acoustic Feedback Cancellation using Adaptive Noise Injection Algorithm. Annual International Conference of the 
IEEE Engineering in Medicine and Biology Society. IEEE Engineering in Medicine and Biology Society. Annual International Conference. NIHMSID: NIHMS1605962.

If you use the work in your research, please cite us.

For more details about related work in signal processing, please visit: https://www.utdallas.edu/ssprl/

## License and Citation

The codes are licensed under open-source MIT license.

## Disclaimer
- This work was supported in part by the National Institute of the Deafness and Other Communication Disorders (NIDCD) of the National Institutes of Health (NIH) under Award 1R01DC015430-04. The content is solely the responsibility of the authors and does not necessarily represent the official views of the NIH.
- The information and materials contained in this website is a presentation of the documented research work carried out by the faculty, students and personnel at the University of Texas at Dallas (UTD). This website including its content is available for public access with the understanding that UTD and the authorized faculty and students contributing to this website make no warranties, either expressed or implied, concerning the completeness, reliability, or suitability of the presented materials for any kind of applications. Neither UTD nor any contributor to this website and its content shall be held liable to any party for any use or misuse of the information and materials contained in this website in any form or shape. Nor does the UTD warrant that the use of this website information is free of any claims of copyright infringement. This website does not endorse any commercial providers or their products. UTD and faculty managing this website reserve the right to remove, update, alter, or take down any and all posted materials on this website at any time without notice.
