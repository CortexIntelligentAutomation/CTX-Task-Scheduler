<a href="https://www.cortex-ia.co.uk/" target="_blank"><img src="https://github.com/CortexIATest/CTXImages/blob/master/Cortex-350-120.png" alt="Welcome to Cortex!" width="350" height="120" border="0"></a>

# CTX-Task-Scheduler
The Task Scheduler module should be used to add or manage schedules within a Cortex system. This module contains the Cortex flows and subtasks to perform schedule operations. 

The module allows users to perform the following functionality:
* Add a new Schedule
* Modify and existing Schedule
* Delete existing Schedule(s)


## Table of Contents
1) [Dependencies](#dependencies)
    * [Cortex Version](#cortex-version)
    * [OCIs](#ocis)
    * [Files](#files)
    * [Other](#other)
1) [Support and Warranty](#support-and-warranty)
1) [Installation](#installation)
1) [How to use](#how-to-use)
1) [How you can contribute](#how-you-can-contribute)
1) [Versioning](#versioning)
1) [Licensing](#licensing)

## Dependencies
### Cortex Version
This version of the CTX-Task-Scheduler module was developed in Cortex v6.4.0. Some functionality may not be available in earlier versions of Cortex.

### Browser Language
Please also note that this package is designed to work with Internet Browsers which have been set to English - If other languages are used, the functionality may not work due to the Calendar Control.

### OCIs
The CTX-Task-Scheduler module requires the following Cortex OCIs:
* Cortex Database OCI
* Cortex LivePortal


### Files
The CTX-Task-Scheduler module requires the following files:
* [CTX-Task-Scheduler Studio Package](https://github.com/CortexIntelligentAutomation/CTX-Task-Scheduler/blob/master/CTX-Task-Scheduler.studiopkg)
* [ts-generic-config.txt](https://github.com/CortexIntelligentAutomation/CTX-Task-Scheduler/blob/master/ts-generic-config.txt)

## Support and Warranty 
This module is supplied as a template that you can amend and extend to fit your requirements, as such it is not supported as part of the Cortex Product suite under the Cortex product support agreement.

## Installation
Details of how the module should be imported into Cortex can be found in the [Deployment Plan](https://github.com/CortexIntelligentAutomation/CTX-Task-Scheduler/blob/master/CTX-Task-Scheduler%20-%20Deployment%20Plan.pdf).
Scheduing a flow at startup is developed in Cortex 7.1 version. Refer to above deployment plan for steps to enable this feature.


## How to use
A detailed User Guide has been provided with instructions on how to use the module, available [here](https://github.com/CortexIntelligentAutomation/CTX-Task-Scheduler/blob/master/CTX-Task-Scheduler%20-%20User%20Guide.pdf ). Configuration of each flow/subtask's inputs and outputs are detailed in notes on the flow/subtask workspace.

## How you can contribute
Unfortunately, we cannot offer pull requests at this time or accept any improvements.

## Versioning
The CTX-Task-Scheduler module has the following versions, starting with the most recent:

Version | Release | Functionality | Notes
------------ | ------------- | ----------- | -----------
v1.0 | 04/12/2018 | CTS-Manage-Schedules| Created
v1.0 | 04/12/2018 | CTS-DI-Database-Integration| Created
v1.0 | 04/12/2018 | CTS-GS-Generate-Schedule| Created
v1.0 | 04/12/2018 | CTS-GSC-Generate-Schedule-Components| Created
v1.0 | 04/12/2018 | CTS-AUDS-Add-Update-Delete-Schedule| Created
v2.0 | 30/11/2021 | CTS-Manage-Schedules | updated

## Licensing
All functionality within this module is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

Copyright 2021 Cortex Limited

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
