# Stock_cn_T0_Trend
Here are some trails of trend strategies in Stock_cn T0 trading simulation during Causis Intern. These strategies are relative raw and not carefully crafted. They are not used by Causis in the end. So I extract some sentitive information from the code (including Causis's data, api ,etc.) and public them for mutual learning

## V1.0.1 Tri-Glod Fork Strategy

[ [Report](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/475fc38e-a2d2-49cf-a95a-03f29cbdac3d/T0%E8%B6%8B%E5%8A%BF%E7%AD%96%E7%95%A5_V1.0.1.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220822%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220822T012147Z&X-Amz-Expires=86400&X-Amz-Signature=359cc99f23d53b8404827c46a324c28f88fe4114bccc68e5a23534842d589cc5&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22T0%25E8%25B6%258B%25E5%258A%25BF%25E7%25AD%2596%25E7%2595%25A5_V1.0.1.pdf%22&x-id=GetObject) ]

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

[ [report](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/a76ff884-37cb-4d05-ac2e-3b70edfd5478/T0%E8%B6%8B%E5%8A%BF%E7%AD%96%E7%95%A5v1.0.2.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220822%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220822T012138Z&X-Amz-Expires=86400&X-Amz-Signature=ab45f78554791df98bbce689c9f2695ea78cdbd0746e9c56b49b0ab656ba64dc&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22T0%25E8%25B6%258B%25E5%258A%25BF%25E7%25AD%2596%25E7%2595%25A5v1.0.2.pdf%22&x-id=GetObject) ]

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

   
