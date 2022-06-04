Stepper Class
==============
The Stepper class is a driver is designed to control a set of stepper motor drivers 
via SPI. Specifically, it is designed to interface with the TMC4210, which communicates 
with most any other driver via step and direction signals.


.. autoclass:: stepper.Stepper
   :members:
   :private-members: _posToByte, _byteToPos, _velToByte, _byteToVel, _P_calc, _config
   :undoc-members:
   :show-inheritance:
