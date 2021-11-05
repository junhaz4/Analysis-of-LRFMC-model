# Analysis-of-LRFMC-model
This project uses LRFMC model to analyze customer characteristics of airline companies in China.

The raw data is obtained by web crawling and stored in air_data.csv

Description of raw data:

MEMBER_NO会员卡号

FFP_DATE入会时间

FIRST_FLIGHT_DATE第一次飞行日期

GENDER性别

FFP_TIER会员卡级别

WORK_CITY工作地城市

WORK_PROVINCE工作地所在省份

WORK_COUNTRY工作地所在国家

AGE年龄

LOAD_TIME观测窗口的结束时间

FLIGHT_COUNT飞行次数

BP_SUM观测窗口总基本积分

EP_SUM_YR_1第一年精英资格积分

EP_SUM_YR_2第二年精英资格积分

SUM_YR_1第一年总票价

SUM_YR_2第二年总票价

SEG_KM_SUM观测窗口总飞行公里数

WEIGHTED_SEG_KM观测窗口总加权飞行公里数（Σ舱位折扣×航段距离）

LAST_FLIGHT_DATE末次飞行日期

AVG_FLIGHT_COUNT观测窗口季度平均飞行次数

AVG_BP_SUM观测窗口季度平均基本积分累积

BEGIN_TO_FIRST观察窗口内第一次乘机时间至MAX（观察窗口始端，入会时间）时长

LAST_TO_END最后一次乘机时间至观察窗口末端时长

AVG_INTERVAL平均乘机时间间隔

MAX_INTERVAL观察窗口内最大乘机间隔

ADD_POINTS_SUM_YR_1观测窗口中第1年其他积分（合作伙伴、促销、外航转入等）

ADD_POINTS_SUM_YR_2观测窗口中第2年其他积分（合作伙伴、促销、外航转入等）

EXCHANGE_COUNT积分兑换次数

avg_discount平均折扣率

P1Y_Flight_Count第1年乘机次数

L1Y_Flight_Count第2年乘机次数

P1Y_BP_SUM第1年里程积分

L1Y_BP_SUM第2年里程积分

EP_SUM观测窗口总精英积分

ADD_Point_SUM观测窗口中其他积分（合作伙伴、促销、外航转入等）

Eli_Add_Point_Sum非乘机积分总和

L1Y_ELi_Add_Points第2年非乘机积分总和

Points_Sum总累计积分

L1Y_Points_Sum第2年观测窗口总累计积分

Ration_L1Y_Flight_Count第2年的乘机次数比率

Ration_P1Y_Flight_Count第1年的乘机次数比率

Ration_P1Y_BPS第1年里程积分占最近两年积分比例

Ration_L1Y_BPS第2年里程积分占最近两年积分比例

Point_NotFlight非乘机的积分变动次数
