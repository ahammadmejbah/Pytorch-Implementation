The data has been downloaded from a dataset in Kaggle provided by Paderborn University (Germany).

https://www.kaggle.com/wkirgsn/electric-motor-temperature

The data set consists of multiple measurement sessions, which can be distinguished from each other by column "profile_id". All recordings are sampled at 2 Hz.

Columns: 

- ambient  :    Ambient temperature as measured by a thermal sensor located closely to the stator.      
- coolant  :    Coolant temperature. The motor is water cooled. Measurement is taken at outflow.     
- u_d      :    Voltage d-component 
- u_q      :    Voltage q-component
- motor_speed : Motor speed    
- torque    :   Torque induced by current  
- i_d       :   Current d-component 
- i_q       :   Current q-component     
- pm        :   Permanent Magnet surface temperature representing the rotor temperature. This was measured with an infrared
- stator_yoke  : Stator yoke temperature measured with a thermal sensor.
- stator_winding : Stator tooth temperature measured with a thermal sensor. 
- profile_id :  Each measurement session has a unique ID.
