
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

The MIT License
=======

Copyright (c) 2015 Ivan Ruchkin.

The original model and copyright is by Nicholas Guzzardo, Mike Kabbani, Ethan McGee (2013).

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


# The Carnegie Mellon License

Copyright (c) 2015 Carnegie Mellon University. All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:

1. Redistributions of source code must retain the above copyright
notice, this list of conditions and the following acknowledgments
and disclaimers.

2. Redistributions in binary form must reproduce the above
copyright notice, this list of conditions and the following
disclaimer in the documentation and/or other materials provided
with the distribution.

3. The names "Carnegie Mellon University," "SEI" and/or "Software
Engineering Institute" shall not be used to endorse or promote
products derived from this software without prior written
permission. For written permission, please contact
permission@sei.cmu.edu.

4. Products derived from this software may not be called "SEI" nor
may "SEI" appear in their names without prior written permission of
permission@sei.cmu.edu.

5. Redistributions of any form whatsoever must retain the following
acknowledgment:

This material is based upon work funded and supported by the
Department of Defense under Contract No. FA8721-05-C-0003 with
Carnegie Mellon University for the operation of the Software
Engineering Institute, a federally funded research and development
center.

Any opinions, findings and conclusions or recommendations expressed
in this material are those of the author(s) and do not necessarily
reflect the views of the United States Department of Defense.

NO WARRANTY. THIS CARNEGIE MELLON UNIVERSITY AND SOFTWARE
ENGINEERING INSTITUTE MATERIAL IS FURNISHED ON AN "AS-IS"
BASIS. CARNEGIE MELLON UNIVERSITY MAKES NO WARRANTIES OF ANY KIND,
EITHER EXPRESSED OR IMPLIED, AS TO ANY MATTER INCLUDING, BUT NOT
LIMITED TO, WARRANTY OF FITNESS FOR PURPOSE OR MERCHANTABILITY,
EXCLUSIVITY, OR RESULTS OBTAINED FROM USE OF THE MATERIAL. CARNEGIE
MELLON UNIVERSITY DOES NOT MAKE ANY WARRANTY OF ANY KIND WITH
RESPECT TO FREEDOM FROM PATENT, TRADEMARK, OR COPYRIGHT
INFRINGEMENT.

This material has been approved for public release and unlimited
distribution.

DM-0001534