ctrl + R 旋转块方向



$\frac{\text{d}^2 y}{\text{d}x}$ + 4$\frac{\text{d} y}{\text{d}x}$ + 3y = 3 求解微分方程，需要先写成
Simulink中对微分方程的求解往往是利用积分而不是微分,先将微分方程按最高阶导数写在左边,其余写在右边的形式列写如下：
$\frac{\text{d}^2 y}{\text{d}x}$ =  3  - 4$\frac{\text{d} y}{\text{d}x}$ - 3y 


PID D是控制变化速度的，有时不需要，如果跟踪的目标的匀速变化的情况下，则不需要。
The D term helps respond to quick changes, which we don’t need because the sun moves steadily across the sky.