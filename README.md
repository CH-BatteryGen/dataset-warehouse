# CH-BatteryGen

## Introduction

This dataset is generated via AI techniques based on real-world new energy vehicle (NEV) data. The dataset currently released is version 1.0, which comprises charging/discharging data from various power battery systems, aiming to provide essential data support for battery performance evaluation, fault diagnosis, and lifespan analysis. This dataset is intended for academic research purposes only.

-   Dataset Name: CAERI-Huawei AI-Generated Power Battery Dataset for New Energy Vehicles  (CH-BatteryGen) 
-   Battery chemistries:  Ternary Li-ion batteries (NCM) and Lithium Iron Phosphate Li-ion batteries (LFP)
-   Battery type:  Prismatic cell
-   Data Source: Generated from real-world NEV operation data, comprising a total of 1,000 vehicles
-   Included Fault Types: normal、high_resistance、low_capacit、self_discharge/ Normal, High Resistance, Low Capacity, Self-Discharge
-   More details:
-   The capacity of LFP batteries： 150 Ah for packs containing 28 cells; 200Ah for packs containing 124 cells
-   The capacity of NCM batteries with low capacity fault: 180Ah
-   The file *faults details - LFP batteries.xlsx* contains detailed parameters of faulty LFP batteries, including severity, fault cell id, fault value, and is released to support research tasks such as fault analysis and fault severity/level prediction.

## Dataset Field Information

|  Data Field |  Meaning                                | Unit |  Precision |
| :------------------ | :------------------------------------------ | :-------- | :------------- |
| TIME                | Time                                 | S      | 1              |
| CHARGE_STATUS       | Charge status                  | 1 (Charging)<br>3 ( Driving or standing) | 1              |
| SUM_VOLTAGE         | Total voltage                      | V         | 0.1            |
| SUM_CURRENT         | Total current                      | A         | 0.1            |
| SOC                 | State of charge              | %         | 1              |
| MAX_CELL_VOLT       | Maximum cell voltage   | V         | 0.001          |
| MIN_CELL_VOLT       | Minimum cell voltage   | V         | 0.001          |
| MAX_TEMP            | Maximum temperature            | ℃         | 1              |
| MIN_TEMP            | Minimum temperature            | ℃         | 1              |
| VOLT_N              | Cell voltage N                   | V         | 0.001          |

## Citation


If this dataset is helpful for your research, please cite it in your publication. 

## Update

We will publish more data to CH-BatteryGen. By subscribing to the CH-BatteryGen by E-mail or the website (which will officially launch later), you will be informed when new data becomes available.

## Contact

CAERI ：
linyanke@caeri.com.cn 林彦可 LIN Yanke
zhangyuhao01@caeri.com.cn 张宇豪 ZHANG Yuhao

Huawei：
liulishuo@huawei.com 刘力硕 LIU Lishuo
jinxin107@huawei.com 金鑫 JIN Xin



## Terms of Use

-   This dataset is strictly limited to academic research, non-commercial use, or other specifically authorized purposes.
-   Users must comply with all applicable laws and regulations when using this dataset and shall not employ it in any manner that infringes upon the privacy of others, promotes discrimination, or supports any illegal or improper activities.
-   Users are required to respect the intellectual property rights of the data provider and must acknowledge the data source in any research outputs or publications derived from the dataset.
-   Without explicit permission from the data provider, the dataset---either in whole or in part---must not be transferred, distributed, or used for any commercial activities.
-   In the event of a violation of these terms, the data provider reserves the right to demand an immediate cessation of data use and to pursue legal action.

## License

CC BY-NC-SA 4.0 (Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International)

