# EY-2023-ODSC
Notebooks for EY 2023 Open Science Data Challenge.

Link to Full Challenge website can be found here: https://challenge.ey.com/challenges

Full Details are in the Notebooks themselves.



## Brief Overview
### Level 1 (Classification Problem)
**Task**:  _Classify_ whether the given plots of land (inputs are pairs of coordinates) in Vietnam is a rice crop or not.

**Methodology:**
- Logistic Regression (Classifier) is employed
- Key Features extracted: Variance of NVDI and Variance of RVI

### Level 2 (Regression Problem)
**Task**:  Predict the rice crop _yield_ for plots of land (inputs are pairs of coordinates) in Vietnam.

**Methodology:**
- Random Forest (Regressor) is employed
- Key Features extracted: (of VV and VH bands)
   -  Minimum
   -  Maximum
   -  Range
   -  Mean
   -  Auto Correlatiom
   -  Permutation Entropy

## Achievements
- Level 1: 0.97 f1-score
![Screenshot 2023-04-27 at 10 33 51 PM](https://github.com/yjh-jy/EY-2023-ODSC/assets/122341151/e58f3147-f8be-4b6b-a5d3-2d1e61342553)

- Level 2: 0.62 R2-score
![Screenshot 2023-08-09 at 8 41 59 PM](https://github.com/yjh-jy/EY-2023-ODSC/assets/122341151/d2cc0f12-9e79-404e-a436-59be5b6e8d5c)
