# teched-dat265
### *Description*
This repository contains the results of various exercises in the TechEd session DAT265.
So when you need to speed up you can download the solution and import it inot EA-Desginer-

### Requirements
You need to have access to an Enterprise Architecture Designer
Enterprise Architecture Designer is an XSA application running on the HANA XSA development stack
It allows to deployment on-premise as well as in the cloud
So there are various availabilities of the product
- EA-Designer as part of SAP HANA2 full use with 5 concurrent users included (As many as wanted reading users)
- EA-Designer as part of SAP HANA2 Express with a 1 concurrent user included (As many as wanted reading users)
- EA-Designer CE (Cloud Edition) 
### Download and Installation
You should download this repository and unpack it.
The files from the single sections can be imported into EA-Designer using the import function in the **Browse** mode
### Known Issues
older version of EA-Designer do had a faulty generation of associations. Make sure relation columns are in the form
 - correct  "targettable_1" "targettable"   the generator of older version do the 
 - false  "targettable"   "targettable"   need to be manual adjusted
it is not allowed to have the same name for column and join


### License
Copyright (c) 2018 SAP SE or an SAP affiliate company. All rights reserved.
