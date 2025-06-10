# KAA-CAL
# Driving Scene Identification (DSI) Dataset
 DSI, a single-label dataset created to demonstrate the proposed approach to developing KAA, a multi-label scene classification model. DSI consists of 31,835 scene images sampled from public driving video datasets, including BDD100K, HSD, and ROADWork Data, and is supplemented with additional images from YouTube videos. these scene attributes include Grade-separated Infrastructure, Road Function, Weather, Work Zone, Weather-related Road Condition, Time of Day, and Intersection Type. In total, DSI provides image-level labels for 24 distinct classes, with each class falling exclusively under one of the seven scene attributes.

## Overview
<p align="center">
  <img src="pic/DSI.png" alt="DSI Overview" width="600" />
</p>

## Dataset Structure

<details>
<summary>Grade-separated Infrastructure (Trn: 4,874; Vld: 1,866; Tst: 1,025)</summary>

| Class             | Trn   | Vld   | Tst |
|-------------------|-------|-------|-----|
| Over-head Bridge  | 3,000 | 1,000 | 500 |
| Tunnel            | 1,136 | 332   | 216 |
| Open Road         | 738   | 534   | 309 |

</details>

<details>
<summary>Road Function (Trn: 3,891; Vld: 1,210; Tst: 639)</summary>

| Class        | Trn   | Vld  | Tst |
|--------------|-------|------|-----|
| Local        | 1,038 | 432  | 339 |
| Arterial     | 1,105 | 260  | 100 |
| Interstate   | 950   | 258  | 100 |
| Collector    | 798   | 260  | 100 |

</details>

<details>
<summary>Weather (Trn: 2,798; Vld: 1,400; Tst: 500)</summary>

| Class    | Trn   | Vld  | Tst |
|----------|-------|------|-----|
| Overcast | 654   | 300  | 100 |
| Clear    | 653   | 300  | 100 |
| Foggy    | 572   | 300  | 100 |
| Snowing  | 561   | 250  | 100 |
| Raining  | 358   | 250  | 100 |

</details>

<details>
<summary>Workzone (Trn: 2,121; Vld: 1,498; Tst: 662)</summary>

| Class | Trn   | Vld  | Tst |
|-------|-------|------|-----|
| Yes   | 1,418 | 964  | 353 |
| No    | 703   | 534  | 309 |

</details>

<details>
<summary>Road Condition (Trn: 2,295; Vld: 957; Tst: 441)</summary>

| Class | Trn   | Vld  | Tst |
|-------|-------|------|-----|
| Snowy | 938   | 325  | 150 |
| Dry   | 811   | 353  | 145 |
| Wet   | 548   | 279  | 146 |

</details>

<details>
<summary>Time-of-day (Trn: 1,656; Vld: 1,022; Tst: 300)</summary>

| Class     | Trn   | Vld  | Tst |
|-----------|-------|------|-----|
| Night     | 708   | 485  | 100 |
| Daytime   | 734   | 400  | 100 |
| Dawn/Dusk | 216   | 164  | 100 |

</details>

<details>
<summary>Intersection Type (Trn: 1,981; Vld: 332; Tst: 367)</summary>

| Class       | Trn   | Vld  | Tst |
|-------------|-------|------|-----|
| None        | 801   | 147  | 111 |
| 4-way       | 673   | 116  | 115 |
| 3-way       | 358   | 50   | 91  |
| Roundabout  | 149   | 19   | 50  |

</details>

## Download url
The DSI dataset is avaliable and can be downloaded at this [url](https://drive.google.com/file/d/1yw4EcfGFGjs2OAa4sWfwQaIDkxDIAR46/view?usp=drive_link).

<pre markdown>
dataset/
├── train/
│   ├── Grade-separated_Infrastructure/
│   │   ├── img001.jpg
│   │   ├── img002.jpg
│   │   └── …
│   ├── Road_Function/
│   │   ├── img001.jpg
│   │   ├── img002.jpg
│   │   └── …
│   ├── Weather/
│   │   └── …
│   ├── Workzone/
│   │   └── …
│   ├── Road_Condition/
│   │   └── …
│   ├── Time-of-day/
│   │   └── …
│   └── Intersection_Type/
│       └── …
├── val/
│   └── （same as train）
└── test/
    └── （same as train）
</pre>
