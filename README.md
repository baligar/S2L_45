## SOUNDSCAPES TO LANDSCAPES (S2L) DATASET

### S2L_45 Dataset (07/06/2020)
<img src="https://github.com/baligar/S2L_45/blob/main/images/val_ROIs_wo_aug.png" width="600">

The **S2L_45** dataset was created as a part of a larger effort of monitoring biodiversity through the [Soundscapes2Landscapes (S2L)](https://soundscapes2landscapes.org/) project. The project seeks to advance animal biodiversity monitoring by making use of Earth-observing satellites. The availability of inexpensive MEMS sound recorders that capture audio of sufficient quality has made possible the scaling of research from single locations and organism, to full animal communities across landscapes. Indeed, the broad geographic scale of the Soundscapes to Landscapes (S2L) project is pioneering.

The dataset consists of two parts:
1. **ROI set** - Regions of Interests with labels are annotated by expert birders and bounded in time and frequency.
1. **Golden Validation** (GV) set - One-minute clips with minute-level coarse labeling of all the species present.

* Number of Classes: **45**
* Total Number of ROIs: **34,968**
* Total Number of GV-set clips: **901**
* Location: **Sonoma County, CA, USA**
* Sites: **586**
* Audio Recorder: **[AudioMoth](https://www.openacousticdevices.info/)**
* Sample Frequency: **48,000 Hz**


Sr.No. | CLASS | ROIs | GV_instances | min_dur (sec) | max_dur (sec) | average_dur (sec) | avg_min_freq (Hz) | avg_max_freq (Hz)
-------|-------|------|--------------|---------------|---------------|-------------------|----------|---------
1 | ACWO | 528 | 67 | 0.09 | 0.48 | 0.22 | 945.43 | 3820.5
2 | AMCR | 553 | 61 | 0.28 | 0.53 | 0.39 | 633.96 | 2607.36
3 | AMRO | 1364 | 53 | 0.19 | 3.5 | 0.85 | 1331.11 | 7390.21
4 | ATFL | 445 | 2 | 0.45 | 0.78 | 0.53 | 1376.67 | 3603.96
5 | BEWR | 503 | 87 | 0.47 | 3.88 | 0.67 | 3464.94 | 6181.01
6 | BGGN | 966 | 12 | 0.12 | 0.86 | 0.63 | 2053.58 | 11104.6
7 | BHGR | 866 | 38 | 0.12 | 0.69 | 0.6 | 1340.7 | 2842.83
8 | BRCR | 609 | 42 | 1.28 | 1.97 | 1.91 | 4036.42 | 8043.72
9 | BTPI | 561 | 6 | 0.59 | 1.1 | 0.72 | 54.63 | 589.51
10 | BTYW | 699 | 16 | 1.5 | 2.84 | 1.64 | 2910.01 | 8054.39
11 | CAQU | 1083 | 30 | 0.22 | 0.48 | 0.32 | 1208.05 | 2155.49
12 | CASJ | 604 | 44 | 0.38 | 1.75 | 1.15 | 976.3 | 4887.09
13 | CAVI | 642 | 23 | 0.28 | 0.66 | 0.37 | 2322.59 | 4989.02
14 | CBCH | 607 | 67 | 0.22 | 1.27 | 0.39 | 5449.34 | 7476.58
15 | CORA | 536 | 47 | 0.72 | 4.43 | 1.06 | 347.69 | 1949.83
16 | COYE | 1038 | 13 | 1.59 | 2.28 | 1.98 | 1893.88 | 7409.39
17 | DEJU | 1345 | 85 | 0.39 | 2.66 | 2.12 | 2483.54 | 6705.8
18 | GHOW | 474 | 3 | 2.81 | 3.1 | 2.87 | 0.0 | 647.17
19 | HOFI | 571 | 35 | 0.19 | 0.25 | 0.22 | 2920.29 | 4397.6
20 | LAZB | 1530 | 4 | 2.11 | 2.16 | 2.13 | 2250.0 | 8064.0
21 | MAWR | 515 | 6 | 1.72 | 2.28 | 1.87 | 3486.1 | 9626.83
22 | MODO | 552 | 27 | 2.31 | 3.58 | 3.1 | 190.1 | 934.37
23 | MOUQ | 520 | 5 | 0.41 | 0.45 | 0.43 | 562.5 | 1969.0
24 | NOFL | 824 | 20 | 2.09 | 7.02 | 3.3 | 1981.23 | 3180.94
25 | NUWO | 562 | 11 | 0.31 | 3.95 | 0.39 | 2638.64 | 4359.42
26 | OATI | 518 | 65 | 0.31 | 0.39 | 0.35 | 4720.99 | 7149.5
27 | OCWA | 1334 | 89 | 1.19 | 3.31 | 1.94 | 2959.76 | 6618.77
28 | PAWR | 695 | 17 | 5.22 | 5.34 | 5.25 | 4613.06 | 8451.05
29 | PIWO | 585 | 5 | 0.86 | 4.14 | 1.49 | 1392.87 | 2341.35
30 | PSFL | 2993 | 125 | 0.34 | 0.69 | 0.38 | 3875.98 | 7237.3
31 | RSHA | 919 | 3 | 0.38 | 2.06 | 0.7 | 866.0 | 3437.37
32 | RWBL | 891 | 69 | 0.84 | 2.58 | 0.89 | 2165.66 | 3666.09
33 | SAVS | 563 | 13 | 1.59 | 1.62 | 1.61 | 4124.0 | 10216.0
34 | SOSP | 1144 | 39 | 0.44 | 3.43 | 0.56 | 1372.55 | 7328.77
35 | SPTO | 819 | 88 | 0.6 | 1.31 | 1.13 | 2992.58 | 7287.75
36 | STJA | 694 | 90 | 0.3 | 1.75 | 1.6 | 1576.9 | 4936.31
37 | SWTH | 605 | 8 | 2.41 | 2.44 | 2.42 | 1312.0 | 6376.0
38 | WAVI | 607 | 53 | 0.38 | 4.5 | 2.1 | 2575.16 | 6387.19
39 | WBNU | 513 | 21 | 0.12 | 0.53 | 0.44 | 1458.86 | 4009.55
40 | WCSP | 500 | 25 | 2.48 | 2.53 | 2.5 | 2344.0 | 6656.0
41 | WEME | 964 | 41 | 0.31 | 3.01 | 0.67 | 1379.96 | 3327.64
42 | WETA | 532 | 12 | 0.22 | 0.77 | 0.32 | 2077.6 | 4207.02
43 | WITU | 471 | 18 | 0.34 | 2.09 | 1.45 | 240.07 | 3086.62
44 | WIWA | 507 | 40 | 1.19 | 2.28 | 1.41 | 3915.6 | 8098.56
45 | WREN | 617 | 30 | 2.09 | 2.92 | 2.37 | 1835.12 | 3580.26
Total:||**34698**|**1655**|||||

Classnames are Four-letter (English Name) Alpha Codes for Bird Species, in accordance with the 61st AOU Supplement (2020). More details: [The Institute for Bird Populations](https://www.birdpop.org/) and Species [List](https://www.birdpop.org/docs/misc/Alpha_codes_eng.pdf). 


## Download
The dataset will be made available soon.
## Results
### Baseline:
> DIMENSIONS OF EXPERTS FOR REAL WORLD ACOUSTIC EVENT DETECTION USING CONVOLUTIONAL NEURAL NETWORKS

> <img src="https://github.com/baligar/S2L_45/blob/main/images/Table_1_21Oct_SB.PNG" width="600">



## Licence
 [MIT Licence](https://github.com/baligar/S2L_45/blob/main/LICENSE) 






