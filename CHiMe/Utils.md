CHiMe4 database
==============================
# Organization
* WSJ0 5k Corpus
* Baseline: data simulation, speech enhancement, Kaldi ASR
* Environment: 1 clean + 4 Noisy = 5 locations, booth (BTH), on the bus (BUS), cafe (CAF), pedestrian area (PED), and street junction (STR)
* config: 1-CH, 2-CH, 6-CH
## Data
* Format : WAV files sampled at 16 kHz
* Type: real (REAL), simulated (SIMU), and clean (ORG)
### Real data 
speech data that is recorded in real noisy environments (on a bus, cafe, pedestrian area, and street junction) uttered by actual talkers. \
### Simulated data
mixing clean speech data with noisy backgrounds to artificially create noisy utterances. \ 
### Dataset
#### Training set
* size: 1600 (real) + 7138 (simulated)
* speakers: 4 + 83
#### Development set
* size:  410 (real) x 4 (environments) + 410 (simulated) x 4 (environments) = 3280 utterances 
* speakers: 4 other speakers than the speakers in the training data
#### Test set
* size:  330 (real) x 4 (environments) + 330 (simulated) x 4 (environments) = 2640 utterances 
* speakers: 4 other speakers than the speakers in the training data

