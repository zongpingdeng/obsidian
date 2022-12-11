
| State Estimator| Model | Assumed distribution| Computational cost|
|-----|-----|-----| ------| 
|Kalman filter (KF)| Linear|Gaussian|Low|
|Extended Kalman filter (EKF)|Locally linear|Gaussian|Low (if the Jacobians need to be computed analytically)|
|Unscented Kalman filter (UFK)|Nonliear|Gaussian|Medium|
|Particle filter(PF)|Nonlinear|Non-Gaussian|High|
