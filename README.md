# Estimating-Reproduction-Rate-Covid-19
Project for Estimating the Reproduction Rate of Covid-19

## Contents
- [Requirements](#Requirements)     
- [Analysis](#Analysis)
- [References](#References)

## Requirements

```bash
python pip install -r requirements.txt
```
## Analysis

The R0, or basic reproduction rate, is a key indicator in studying the spread of infectious diseases, such as Covid-19. It indicates the average number of people that an infected person can contaminate.

Main analyses carried out:

- Database processing
- SIR model
- Autoregressive process with stationary coefficients
- Autoregressive process with non-stationary coefficients

The SIR model provides an estimate of R0 by analyzing observed infection and cure rates. The value created lies in the precision of these estimates, which can help predict the scale of the epidemic and assess the effectiveness of measures taken to contain it.

In parallel, the use of autoregressive models offers a complementary approach to determining R0. These models exploit historical data on infections and transmission behavior to predict future trends. They can take into account factors such as individual mobility, social distancing policies and other relevant vari- ables to refine R0 estimates. Value creation here lies in the ability to provide accurate and reliable forecasts, enabling decision-makers to take timely preventive action.

Incorporating different models to determine Covid’s R0 also offers additional advantages in terms of robustness and cross-validation of results. By comparing the estimates obtained from the SIR model and the autoregressive models, any discrepancies or inconsistencies can be detected, enabling estimates to be refined and errors minimized. This adds value to the project by reinforcing the reliability of results and providing a better understanding of virus transmission dynamics.

For more details, the final report can be found at Assets.

## References

[1] Draief, M., & Massouli, L. (2010). Epidemics and rumours in complex networks. Cambridge
University Press.
[2] Cori, A., Ferguson, N. M., et al. (2013). A new framework and software to estimate time-
varying reproduction numbers during epidemics. American Journal of Epidemiology, 178(9), 1505-
1512.
[3] Pascal, B., Abry, P., et al. (2022). Nonsmooth convex optimization to estimate the Covid-19
reproduction number space-time evolution with robustness against low-quality data. IEEE Tran-
sactions on Signal Processing.
[4] Amdaoud, M., Arcuri, G., & Levratto, N. (2020). Covid-19 : analyse spatiale de l’influence des
facteurs socio-économiques sur la prévalence et les conséquences de l’épidémie dans les départements
français.
[5] Ives, A. R., & Bozzuto, C. (2020). State-by-State estimates of R0 at the start of COVID-19
outbreaks in the USA.
[6] Fowe, E. P. (2022). Analyse comparative et de cohérence entre les modèles statistiques et par
compartiments sur la prédiction des cas d’infections et décès de la COVID-19 au Québec.