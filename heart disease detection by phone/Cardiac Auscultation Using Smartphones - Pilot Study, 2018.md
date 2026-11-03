Cardiac Auscultation Using Smartphones: Pilot Study (2018)
https://pmc.ncbi.nlm.nih.gov/articles/PMC5853766/

words - meaning
auscultation - কানের সাহায্যে শরীরের অভ্যন্তরীণ অঙ্গের (যেমন- হৃদপিণ্ড, ফুসফুস ইত্যাদি) শব্দ শোনা
hemodynamics - রক্ত সঞ্চালন ও এর ভেতরের বল/শক্তির অধ্যয়ন
intercostal - দুই পাঁজরের মধ্যবর্তী ফাঁকা স্থান

reason

1. with advances in imaging and laboratory tests, the importance of cardiac auscultation is less appreciated in clinical practice
2. The widespread use of smartphones provides opportunities

objective

- assess the feasibility of cardiac auscultation using smartphones with no add-on devices
- can algorithms classify heart sound by acceptable accuracy

methods

- developed app CPstethoscope
- heart sound best heard in intercostal spaces
- their heart sounds were recorded in a quiet room that was free from environmental noises
- three android devices used for each participants
- also a reference sound captured through an electronic stethoscope
- transferred into computer
- substract environmental and thermal noise by FFT
- [ We detected the first and second heart sounds without an ECG reference, using a previously reported algorithm. Time-domain signals were transformed into frequency-domain spectrogram features. We developed a diagnostic algorithm using convolutional neural networks, a variant of an artificial neural network that mimics the connections of neurons in the visual cortex of the brain. The convolutional neural network was constructed from 40×40 heart sound spectrogram matrices through 1 input layer. We processed these matrices with 2 convolution-max pool layers whose kernel size was 5×5. Moreover, the number of kernels for each of the 2 convolutional layers was either 8 or 16. Next, a dense, fully connected layer followed the second convolution–max pool layer, and we appended the last readout layer with 5 nodes that corresponded to each disease. We calculated the training loss of function of the network as soft maximum cross-entropy using the values from the readout layer. Finally, we trained the network with the Adam optimizer at a learning rate of 0.001. We used the TensorFlow version 1.2 Python library to compose this network ]
- training was done by found open databases
- classified heart sounds into 5 categories: normal, third heart sound, fourth heart sound (S4), systolic murmur, and diastolic murmur
- algorithm showed 81% diagnostic accuracy with the training sets
- considered the diagnosis to be accurate when the algorithm classified a heart sound into the correct category with 50% or more probability

results

- 46 patients
- 30 was interpretable sound
- rest had low amplitude heart sound
- accuracy of S5 90%, S6 87%, LG 90%

discussion

- (research gap) finding reliable heart sound recording was the most important difficulty
- once interpretable heart sounds are acquired, diagnosis results had high accuracy
- good-quality heart sounds is still far from perfect because of background noise,
- respiration sound was not a problem, as it had different frequency band
- patient factors was important specially patient with irregular heart bit

limitations

- small sample size
- selective participants
- app is only for recording, analysis happened in computer
- variations of result in different devices
- quality may drop in low-end devices
-

research gap

- all in one app required to record, process and diagnosis
- app use with electronic stethoscopes
