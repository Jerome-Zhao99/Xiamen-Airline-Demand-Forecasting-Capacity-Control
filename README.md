# Xiamen-Airline-Demand-Forecasting-Capacity-Control
This is a pricing and revenue management project based on the historical sales data provided by Xiamen Airlines. We mainly use the moving average method, EM algorithm and quadratic exponential smoothing method to forecast the demand respectively, and get the demand parameters that obey the normal distribution. Then we use Matlab to carry out simulation experiments and generate the corresponding demand data.Finally, different income control models are established and the optimal income policy is obtained after comparison.

Catalogue
1.Descriptive Statistics	5
  1.1 DOW	5
  1.2 Festival	6
  1.3 Ticket sales	6
  1.4 Policy limitation	7
  1.5 Proportion of different tickets	8
  1.6 Policy	8
  1.7 Seasonal	8
    (1) Daily Sales	8
    (2) Monthly Sales	9
    (3) Quarterly Sales & Yearly Sales	9
2.Averaging Method	11
  2.1Averaging Method Introduction	11
  2.2Averaging Method Operation	11
    (1) Defining restricted and unrestricted time points	11
    (2) Select the restricted value to replace the object	12
    (3) Replace restricted values	12
  2.3Forecasting Demand	12
    (1) Simple Moving Method	12
    (2) Exponential Smoothing Method	13
  2.4 Policy Management	13
    (1)	Comparison	14
    (2)	Optimization idea	15
3. Expectation-Maximization Method	16
  3.1 Assumption	16
  3.2 Formulation of Expectation-Maximization Method	16
    (1) Step 0 (Initialize)	16
    (2) Step 1 (E-step)	16
    (3) Step 2 (M-step)	16
    (4) Convergence test	16
  3.3 Demand Forecasting	16
    (1) Historical Sales Data	16
    (2) Data Pre-processing	16
    (3) Data Processing	17
    (4) The Processed Parameters	18
4.Double Exponential Smoothing Method(DES)	19
  4.1 DES Introduction	19
  4.2 DES Method in XM Airline	19
  4.3 Realizing DES method	22
5.RM simulation	23
  5.1 Process	23
  5.2 Result	24
  5.3 Improvement	24
6. The Hindsight Policy-Certain Demand	26
  6.1 Explanations & Assumptions	26
  6.2 Process	26
  6.2 Shortcoming & Thinking	28
7.Revenue Maximization Policy	29
  7.1 Assumptions	29
  7.2 Data Process	29
  7.3 Policy	33
  7.4 Revenue	33
8. Expected Marginal Seat Revenue (EMSR)	35
  8.1 Protection level	35
  8.2 EMSR-b under DOW	36
  8.3 EMSR-b’s shortcoming	37
9.EMSR_b With Dynamic	39
  9.1 EMSR-b with dynamic	39
10.Revenue Comparison	40
  10.1 Process	40
  10.2 Generate random variates	40
  10.3 Modify the data	41
  10.4 Revenue comparison	42

