# dataset-warehouse

# 新能源汽车动力电池生成式数据集

# CAERI-Huawei AI-Generated Power Battery Dataset for New Energy Vehicles (CH-BatteryGen)

## 简介 | Introduction

本数据集基于真实环境下的实车运行数据，通过AI仿真技术生成。当前发布的数据集为V1.0版本。该生成数据集包含了来自不同类型电池包系统的充电及运行数据，旨在为电池性能评估、故障诊断和寿命分析等领域提供基础数据支持。本数据集仅限学术研究使用。

This dataset is generated via AI techniques based on real-world new energy vehicle (NEV) data. The dataset currently released is version 1.0, which comprises charging/discharging data from various power battery systems, aiming to provide essential data support for battery performance evaluation, fault diagnosis, and lifespan analysis. This dataset is intended for academic research purposes only.

-   **数据集名称 | Dataset Name:** 新能源汽车动力电池生成式数据集 (CH-BatteryGen) / CAERI-Huawei AI-Generated Power Battery Dataset for New Energy Vehicles (CH-BatteryGen)
-   **电池类型 | Battery Types:** 三元锂电池和磷酸铁锂电池 / Ternary Li-ion batteries and Lithium Iron Phosphate Li-ion batteries
-   **数据来源 | Data Source:** 基于真实环境的实车运行数据生成，共计1000台车辆 / Generated from real-world NEV operation data, comprising a total of 1,000 vehicles
-   **所包含的故障类型 | Included Fault Types:** 正常（normal）、高内阻（high_resistance）、容量异常（low_capacity）、自放电（self_discharge） / Normal, High Resistance, Low Capacity, Self-Discharge

## 数据集字段信息 | Dataset Field Information

| 数据字段 Data Field | 含义 Meaning                                | 单位 Unit | 精度 Precision |
| :------------------ | :------------------------------------------ | :-------- | :------------- |
| TIME                | 时间 / Time                                 | 秒 S      | 1              |
| CHARGE_STATUS       | 充放电状态 / Charge status                  | 1 (停车充电 Charging)<br>3 (未充电状态 Driving or standing) | 1              |
| SUM_VOLTAGE         | 总电压 / Total voltage                      | V         | 0.1            |
| SUM_CURRENT         | 总电流 / Total current                      | A         | 0.1            |
| SOC                 | 电池荷电状态 / State of charge              | %         | 1              |
| MAX_CELL_VOLT       | 电池单体电压最高值 / Maximum cell voltage   | V         | 0.001          |
| MIN_CELL_VOLT       | 电池单体电压最低值 / Minimum cell voltage   | V         | 0.001          |
| MAX_TEMP            | 最高温度值 / Maximum temperature            | ℃         | 1              |
| MIN_TEMP            | 最低温度值 / Minimum temperature            | ℃         | 1              |
| VOLT_N              | 单体电压 / Cell voltage N                   | V         | 0.001          |

## 数据集引用 | Citation

如果数据集有助于您的研究工作，请在您出版物的适当位置作引用。参考示例如下：

If this dataset is helpful for your research, please cite it in your publication. The reference example is as follows:

> \[1\] China Automotive Engineering Research Institute & Huawei. (2025). CAERI-Huawei AI-Generated Power Battery Dataset for New Energy Vehicles (CH-BatteryGen) \[Dataset\]. Version 1.0.

## 数据集更新 | Update

我们会持续更新数据集。您可以通过邮件或者网站（稍后正式发布）持续关注数据集最新更新。

We will publish more data to CH-BatteryGen. By subscribing to the CH-BatteryGen by E-mail or the website (which will officially launch later), you will be informed when new data becomes available.

## 联系方式 | Contact

**中国汽研 CAERI:**

-   张宇豪 ZHANG Yuhao: <zhangyuhao01@caeri.com.cn>
-   林彦可 LIN Yanke: <linyanke@caeri.com.cn>

**华为 Huawei:**

-   刘力硕 LIU Lishuo: <liulishuo@huawei.com>
-   金鑫 JIN Xin: <jinxin107@huawei.com>

## 使用条款 | Terms of Use

-   本数据集仅限于学术研究、非商业用途或其他已获授权的特定用途。
-   数据使用者在使用本数据集时应遵守所有适用的法律法规，不得用于侵犯他人隐私、歧视、违法或不当用途。
-   使用者在使用数据时应当尊重数据提供方的知识产权，且需在研究或成果中引用数据来源。
-   未经数据提供方明确许可，不得将数据集全部或部分转让、分发或用于其他商业活动。
-   若违反使用条款，数据提供方有权要求立即停止使用数据，并保留追究法律责任的权利。
-   本数据集的最终解释权归中国汽研数智中心和华为中央研究院所有。

-   This dataset is strictly limited to academic research, non-commercial use, or other specifically authorized purposes.
-   Users must comply with all applicable laws and regulations when using this dataset and shall not employ it in any manner that infringes upon the privacy of others, promotes discrimination, or supports any illegal or improper activities.
-   Users are required to respect the intellectual property rights of the data provider and must acknowledge the data source in any research outputs or publications derived from the dataset.
-   Without explicit permission from the data provider, the dataset---either in whole or in part---must not be transferred, distributed, or used for any commercial activities.
-   In the event of a violation of these terms, the data provider reserves the right to demand an immediate cessation of data use and to pursue legal action.
-   The final interpretation rights of this dataset belong to the CAERI Digital Intelligence Center and the Huawei Central Research Institute.

## 许可协议 | License

CC BY-NC-SA 4.0 (Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International)

---

中国汽研数智中心 | CAERI Digital Intelligence Center  
华为中央研究院 | Huawei Central Research Institute  
2025年2月 | February 2025
```
