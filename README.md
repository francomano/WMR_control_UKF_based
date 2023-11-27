# WMR_control_UKF_based

The model of a wheeled mobile robot encodes the nonholonomic constraint which results from assuming
no slip between the ground and the wheels. However, in some applications slip cannot be neglected and
controllers that are based on a no-slip model may not work properly. The aim of this project is to robustify
the control performance by compensating the wheel slippage as estimated through an Unscented Kalman
Filter applied on the TIAGo mobile manipulator.
