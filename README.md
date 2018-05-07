# Photoplethysmography Imaging Dataset

## Introduction

This dataset accompies the work *´´Feasibility of Photoplethysmography Imaging of the Sole of the Foot''* by Nicolai Spicher, Tyler Lovelace, and Markus Kukuk that will be presented at the [13th Annual IEEE International Symposium on Medical Measurements and Applications](http://memea2018.ieee-ims.org/) in Rome, Italy. The preprint of the paper can be found [here](https://www.fh-dortmund.de/de/fb/4/personen/wissMit/spicher/pub.php). The data has been acquired during the [DAAD RISE](https://www.daad.de/rise/) internship of Tyler Lovelace at the University of Applied Sciences and Arts Dortmund in 2017.

## Study population: 
| ID | Gender | Ethnicity | Height (cm) | Weight (kg) | Body-Mass-Index | Age  | 
|------- |:-----:| :-----:|:-----:|:-----:|:-----:|:-----:|
| 1      | m | Caucasian | 180 | 95 | 29.3 | 29 |
| 2      | f | Asian | 170 | 68 | 23.5 | 29     |
| 3      | m | Caucasian | 180 | 80 | 24.6 | 26 |
| 4      | m | Caucasian | 177 | 75 | 23.9 | 29 |
| 5      | m | Caucasian | 175 | 80 | 26.1 | 26 |
| 6      | m | Caucasian | 179 | 85 | 26.5 | 29 |
| 7      | m | Caucasian | 169 | 63 | 22.0 | 30 |
| 8      | m | Asian | 171 | 77 | 26.3 | 25     |
| 9      | m | Caucasian | 184 | 83 | 24.2 | 34 |
| 10     | m | Caucasian | 199 | 93 | 23.4 | 29 |
| 11     | m | Caucasian | 180 | 85 | 26.2 | 26 |
| 12     | m | Caucasian | 182 | 76 | 22.9 | 35 |
| 13     | m | Caucasian | 186 | 75 | 21.6 | 48 |
| 14     | m | Caucasian | 178 | 85 | 26.8 | 30 |
| 15     | m | Caucasian | 189 | 93 | 26.0 | 27 | 
| 16     | m | Caucasian | 180 | 82 | 25.3 | 49 |
| 17     | f | Caucasian | 172 | 80 | 27.0 | 19 |
| 18     | m | Caucasian | 183 | 82 | 24.4 | 34 |
| 19     | f | Caucasian | 166 | 66 | 23.9 | 25 |
| 20     | f | Asian | 168 | 65 | 23.0 | 21     |
| 21     | f | Arab | 163 | 62 | 23.3 | 24      |
| avg    |   |  | 177.6 | 78.5 | 24.8 | 29.9  |
| std    |   |  | 8.4 | 9.6 | 1.8 | 7.5  |  

## Data

Each folder contains:
- _img*.jpg_: Video frames
- _img_time.csv_: Points in time of frame acquisition
- _PO.mat_: Ground truth signal obtained by pulse oximetry

<table>
<tr><th>Palm of the hand </th><th>Sole of the feet</th></tr>
<tr><td>

| ID| Heart Rate (bpm)¹ | Attempts | Data | 
|------- |:-----:| :-----:|:-----:|
| 1      | 55 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/YlCdcH75en36RLL)  |
| 2      | 61 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/jucC4bwPDIkC1EY)  |
| 3      | 86 | 2 | [Link](https://fh-dortmund.sciebo.de/index.php/s/NJXHisLRjnatsD4)  |
| 4      | 65 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/0K6TSl0AQ3gEtoq)  |
| 5      | 82 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/EOANO791V1lAcfN)  |
| 6      | 69 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/VoCvsoS2K2m7mFd)  |
| 7      | 83 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/uMsWebJCUnUr3ad)  |
| 8      | 79 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/W6FeV7s51FV0yvp)  |
| 9      | 102| 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/cx2l4vdVvrXbQ3A)  |
| 10     | 66 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/hmDIqJpNek97iZr)  |
| 11     | 65 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/vyshndi4dJtXRIZ)  |
| 12     | 73 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/fYerluzTQFPMdYv)  |
| 13     | 59 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/ewi9Q1myPpqQAgG)  |
| 14     | 60 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/vTQe8yKRK9ErfwY)  |
| 15     | 74 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/t3vF0o9bYzLVDuj)  |
| 16     | 64 | 3 | [Link](https://fh-dortmund.sciebo.de/index.php/s/jsf6TgDOg0jDg7J)  |
| 17     | 75 | 3 | [Link](https://fh-dortmund.sciebo.de/index.php/s/OSOmlxOkD73y1W0)  |
| 18     | 64 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/pnvg3b7yUeS2X09)  |
| 19     | 76 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/kvxTt5ac9eQOcnU)  |
| 20     | 97 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/FFmEvcMwOU59Okl)  |
| 21     | 83 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/rKy5hS4eoeLRl5e)  |

</td><td>

| Heart Rate (bpm)¹  | Attempts | Data | 
|:-----:| :-----:|:-----:|
| 53 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/DyzupOEMBSHTa1y) |
| 53 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/4BaVLLZGFGz4Aiu) |
| 78 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/0NYZqnAkvq0mSXY)  |
| 60 | 3 | [Link](https://fh-dortmund.sciebo.de/index.php/s/PsOwzCPzJMDGAV5)  |
| 76 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/JCZyIX3LFaCBTCM)  |
| 62 | 2 | [Link](https://fh-dortmund.sciebo.de/index.php/s/Z0RuGFDIgDpaORw)  |
| 77 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/pr5Gal0SVOSs5G2)  |
| 65 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/Vf0hwXsZeYwrNM2)  |
| 111 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/LX1GLN9B7QtBpPa)  |
| 64 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/4OXQ4znR9KpI33b)  |
| 61 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/lyUhbMmXKHuAURg)  |
| 68 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/gvd8LLpidV3UdJE)  |
| 56 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/niw7lPBClC9HGEH)  |
| 64 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/ncQNhGcnbiaC4Tk)  |
| 66 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/SKLjUDVLMlr6pP1)  |
| 59 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/65Q71pV8laO7qxy)  |
| 74 | 2 | [Link](https://fh-dortmund.sciebo.de/index.php/s/k9L16xfk0DJJZkA)  |
| 57 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/V2ljphjnYWl4lM0)  |
| 67 | 2 | [Link](https://fh-dortmund.sciebo.de/index.php/s/DUfPhOPKA7blJkk)  |
| 94 | 2 | [Link](https://fh-dortmund.sciebo.de/index.php/s/rKgNveRqnEsAk3p)  |
| 85 | 2 | [Link](https://fh-dortmund.sciebo.de/index.php/s/O0kK0VH0xlTR6UN)  |

</td></tr> </table>

¹ obtained from finger pulse oximetry
</table>
