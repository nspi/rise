# Photoplethysmography Imaging Dataset

## Introduction

This dataset accompies the work *´´Feasibility of Photoplethysmography Imaging of the Sole of the Foot''* that is currently under review. After acceptance, more information will be added. Data has been acquired during the [DAAD RISE](https://www.daad.de/rise/) internship of T. Lovelace at the University of Applied Sciences and Arts Dortmund. 

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
- *img*.jpg*: Video frames
- *img_time.csv*: Points in time of frame acquisition
- *PO.mat*: Ground truth signal obtained by pulse oximetry

<table>
<tr><th>Palm of the hand </th><th>Sole of the feet</th></tr>
<tr><td>

| ID| Heart Rate (bpm)¹ | Attempts | Data | 
|------- |:-----:| :-----:|:-----:|
| 1      | 55 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/7iYIUWwnAC3ffpr)  |
| 2      | 61 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/LJl2hndg3O90Re2)  |
| 3      | 86 | 2 | [Link](https://fh-dortmund.sciebo.de/index.php/s/hEFfqEFzHRmuHFz)  |
| 4      | 65 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/f3e6sBNuydUH9Wd)  |
| 5      | 82 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/v1ZRctsYBT0laun)  |
| 6      | 69 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/A82uHCYNKw3PwdJ)  |
| 7      | 83 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/3Vl4jtSEDirqwsR)  |
| 8      | 79 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/77RHEZoy1G2k45j)  |
| 9      | 102| 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/tDvxA6pcVP3FGuf)  |
| 10     | 66 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/TorLW0lPIjd62eZ)  |
| 11     | 65 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/pgfB4RU6bFgVXzV)  |
| 12     | 73 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/vZfx8l7BOCT4X4Y)  |
| 13     | 59 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/qYZD9nIyhqCePnH)  |
| 14     | 60 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/J80Lfx6uk08Z0Zb)  |
| 15     | 74 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/X31vVmBvxhu9Um5)  |
| 16     | 64 | 3 | [Link](https://fh-dortmund.sciebo.de/index.php/s/H3d4YgCRkDpkrbq)  |
| 17     | 75 | 3 | [Link](https://fh-dortmund.sciebo.de/index.php/s/xAdzNJjZAAKYdrY)  |
| 18     | 64 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/nObuBnyQEqZSXRH)  |
| 19     | 76 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/FmOVMOQPWsR3f6S)  |
| 20     | 97 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/KTLsnWUf5ziPW17)  |
| 21     | 83 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/mwhJ7NWGAbCWOu3)  |

</td><td>

| Heart Rate (bpm)¹  | Attempts | Data | 
|:-----:| :-----:|:-----:|
| 53 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/DyzupOEMBSHTa1y) |
| 53 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/4BaVLLZGFGz4Aiu) |
| 78 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/Myklefs34CdER4o)  |
| 60 | 3 | [Link](https://fh-dortmund.sciebo.de/index.php/s/TDOiY5OKR2pkO3r)  |
| 76 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/5oMqntWVakU6ygF)  |
| 62 | 2 | [Link](https://fh-dortmund.sciebo.de/index.php/s/YiL0C0q8VkFfMS3)  |
| 77 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/GatBvAtHJDEUHll)  |
| 65 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/WU5mQ8XsybYWCwe)  |
| 111 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/w9h4Z6ZN1rHEjyd)  |
| 64 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/w3s15B8NLCXj1yr)  |
| 61 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/ORVRCmNPRgBgNLG)  |
| 68 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/lCqDtoIg4BMOoWk)  |
| 56 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/c09wICmyDPt34xu)  |
| 64 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/xIT4xZiCzZpuWm8)  |
| 66 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/A3MZdwUIYR5exN8)  |
| 59 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/AC0hQShG5jROsX0)  |
| 74 | 2 | [Link](https://fh-dortmund.sciebo.de/index.php/s/EXs1neSG0ENqDOe)  |
| 57 | 1 | [Link](https://fh-dortmund.sciebo.de/index.php/s/oyblFVZeDEKmzl4)  |
| 67 | 2 | [Link](https://fh-dortmund.sciebo.de/index.php/s/UjJYUPMqeQrWvAq)  |
| 94 | 2 | [Link](https://fh-dortmund.sciebo.de/index.php/s/yIaX53GBMxKw22e)  |
| 85 | 2 | [Link](https://fh-dortmund.sciebo.de/index.php/s/izGODoheoVl5LXs)  |

</td></tr> </table>

¹ obtained from finger pulse oximetry
</table>
