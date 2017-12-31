# Data-based Motor Control #

## introduction

 Data-based motor control method is a new techonology used for motor controlling by statistic method or machine learning.Unlike the conventional methods, which are usually based on motor's mathmatical model or equivalant circut model,data-based method is independent of motor's model. It depends entirely on the collected data.

## Model-based method

Conventional motor control method usually depends on motor's model. For example, in induction or permanent magnet synchronous motor sensorless control, there are some classical method used as follows:

1. Voltage Model(VM) only
2. Model Reference Adaptive System(MRAS)
3. Full-order Luenberger Observer(FLO)
4. Extented Kalman Filter(EKF)
5. Sliding Mode Observer(SMO)

all of the above methods depend on the motor's mathmatical model. Although these methods work well in most condition, there are some limitation yet.Firstly, we can't derive a completely accurated  motor's mathmatical model, hence when we use a approximated model, some model error generated inevitably.Secondly, as noise is common in motor control application, we actually used a "noisy" model because noise will overlay to real model, which means model-based method have poor performance on anti-noise. Thirdly, in some extrodinary condition, some model-based method may be unstable. For example, in induction motor's low-speed regenerated condition, most of the model based methods are invalid because they will cause stability problem. 

## Data-based method
Thanks to the recent breakthrough in artificiall intelligence techonology, which gives us an alternative thinking to solve the problem. Is there a way, that we can abandon the mathmatical model, instead we totally depend on measured data?


 


