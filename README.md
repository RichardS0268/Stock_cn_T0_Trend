# Stock_cn_T0_Trend
### Description 👋🏻
Here are some trails of trend strategies in Stock_cn T0 trading simulation during my intern. These strategies are relative raw and not carefully crafted. They are not approved and used by the company in the end. So I wipe out some sentitive information from the code (including company's data, api ,etc.) and public them for mutual learning.

## V1.0.1 Tri-Glod Fork Strategy

### Technical Features:

+ Price MA
+ Volume MA
+ MACD
+ Fluct Indicator

### Features & Signals

> S.CN.SZSE.300618, 2012-12-02

![](https://github.com/RichardS0268/Stock_cn_T0_Trend/blob/main/imgs/V1.0.1_F%26S.png)

### BackTest

1. Pnl

   ![](https://github.com/RichardS0268/Stock_cn_T0_Trend/blob/main/imgs/V1.0.1_Pnl.png)

2. Win Rate

   ![](https://github.com/RichardS0268/Stock_cn_T0_Trend/blob/main/imgs/V1.0.1_win-loss.png)

 3. Technical Analysis

    |                | BUY    | SELL   | TOTAL  |
    | -------------- | ------ | ------ | ------ |
    | Annual Return  | -1.70% | -3.46% | -5.31% |
    | Std            | 1.67%  | 1.60%  | 2.40%  |
    | Sharpe Ratio   | -1.01  | -2.16  | -2.21  |
    | Max DrawDown   | 5.34%  | 8.54%  | 12.79% |
    | Calmar Ratio   | -0.317 | -0.405 | -0.415 |
    | Win Rate       | 0.3974 | 0.3881 | 0.3927 |
    | Win Loss Ratio | 0.8673 | 0.7502 | 0.8073 |

## V1.0.2 Short-Long Term Trend Strategy

### Technical Features

+ KDJ
+ MACD
+ Super Trend
+ Price EMA

### Features & Signals

>  S.CN.SZSE.300618, 2021-09-02

![](https://github.com/RichardS0268/Stock_cn_T0_Trend/blob/main/imgs/V1.0.2_F%26S.png)

### BackTest

1. Pnl

   ![](https://github.com/RichardS0268/Stock_cn_T0_Trend/blob/main/imgs/V1.0.2_Pnl.png)

2. Win Rate

	![](https://github.com/RichardS0268/Stock_cn_T0_Trend/blob/main/imgs/V1.0.2_win-loss.png)

3. Technical Analysis

   |                | BUY   | SELL   | TOTAL  |
   | -------------- | ----- | ------ | ------ |
   | Annual Return  | 0.50% | -1.43% | -0.83% |
   | Std            | 1.11% | 0.76%  | 1.35%  |
   | Sharpe Ratio   | 0.529 | -1.878 | -0.613 |
   | Max DrawDown   | 1.33% | 3.82%  | 4.33%  |
   | Calmar Ratio   | 0.441 | -0.376 | -0.191 |
   | Win Rate       | 0.242 | 0.206  | --     |
   | Win Loss Ratio | 1.285 | 0.597  | --     |

   
