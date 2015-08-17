
Autonomous Vehicle AADL
========================

This self-driving car model represents the cyber and physical components of a car, and interaction among them.

The main system model is in complete_car_system.aadl. This system consists of six subsystems: 
* Collision prediction
* Collision avoidance
* Collision response
* Networking
* User interaction
* Vehicle actuation

The model contains analysis contracts in a separate [library](https://github.com/bisc/collision_detection_aadl/blob/master/packages/Basic%20Types/analysis_contracts_library.aadl).

This model is described in the paper ["Eliminating Inter-Domain Vulnerabilities..."] (http://dx.doi.org/10.1145/2808705.2808714) You can use it with [ACTIVE](https://github.com/bisc/active), which is based on [OSATE2](https://github.com/osate/osate2-core). 

The original AADL model of (a collision prevention system for use in a telematics architecture) was done in partial fulfillment of the requirements of CPSC 8750 at Clemson University, Spring 2013. Refer to it as [![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.18611.svg)](http://dx.doi.org/10.5281/zenodo.18611)

Copyright
=======

Copyright (c) 2015 Carnegie Mellon University and Ivan Ruchkin
All rights reserved. 
MIT License
This Software includes and/or makes use of certain third party software ("Third Party Software"). Code files that are distributed with this software that are not marked with a Carnegie Mellon University Copyright notice are Third Party Software.  You agree to comply with any and all the Third Party Software terms and conditions listed below and/or contained in any separate license file distributed with this Software. The parties who own the Third Party Software ("Third Party Licensors") are intended third party beneficiaries to this License with respect to the terms applicable to their Third Party Software.  
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED *AS IS*, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE. 
This material is based upon work funded and supported by the Department of Defense under Contract No. FA8721-05-C-0003 with Carnegie Mellon University for the operation of the Software Engineering Institute, a federally funded research and development center. Any opinions, findings and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the United States Department of Defense. This material has been approved for public release and unlimited distribution.  DM-0002665


Third Party Software
=======
collision_detection_aadl

A AADL model of a collision prevention system for use in a telematics architecture

License
=======

The MIT License (MIT)

Copyright (c) 2013 Nicholas Guzzardo, Mike Kabbani, Ethan McGee

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.