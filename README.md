## Banking-Analytics-2020---Credit-Risk-Analytics

Freddie Mac is one of the largest secondary mortgage market actors. Financial institutions sell their
mortgages to Freddie Mac, which stimulates the market as the banks know they can – if they
evaluate their customers correctly – reduce their risk by having a larger institution take the burden
of a default were it to occur. Freddie Mac on the other hand will evaluate the portfolios they buy to
make informed decisions on which mortgages should enter their portfolio. Freddie Mac has been
chartered by the US congress and its mission is to “provide liquidity, stability and affordability to the
nation”. As part of their transparency push, they make available the Single-Family Loan Dataset1
that, as the name implies, covers mortgages to single family households. 

The purpose of this coursework was to develop a fully compliant PD model from the data they make available,
from the raw data to the level 2 calibration, using what have learned in the lectures. The
objective of the coursework is to estimate the capital requirements for Freddie Mac as if they were
a bank. 

We are given information from approximately two million loans, corresponding to operations that
originated between the years 2014 and 2018. The data includes information from the origination of
the loan (variables present in the table “Origination Data File” in the user guide) which can be used
to predict the performance of the loan.We are also given a Default flag (variable “Default”) which marks if the mortgage
has defaulted for the purposes of the coursework.

The following coding:
1. Calculate the WoE and perform the variable selection procedures we see fit;
2. Construct a scorecard which can model the probability of default for the loans;
3. Compare your scoring model with an XGBoosting model and Random Forest model
trained over the data without the WoE transformation;
