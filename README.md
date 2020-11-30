# OVERVIEW
This package contains files of CoreASM Specifications designed for an Abstract State Machine(ASM) Model for Auto-Scaling Mechanisms(Auto-Scalers). The ASM model was designed with Auto-Scalers developed on the DIScrete event baSed Energy Consumption simulaTor for Clouds and Federations (DISSECT-CF). There are two main categories of auto-scaler files: the reactive auto-scalers and the predictive auto-scalers. There are Six Auto-Scaling Mechanisms(Auto-Scalers) described in this package. Five of them fall into the predictive auto-scalers whilst the reactive auto-scalers has one.

## CATEGORIES OF FILES
 There are four main categories of CoreASM Specification files in this package. The core modules, the job initialization files, the job queuing files, the job handling files.  The auto-scalers are sub-divided into the four categories mentioned above. 

#### CORE MODULES FILES
The files in this category compose of core files required for applying the ASM model to any auto-scaler. There core modules for job initialization, job queuing and job handling. There are also core modules for jobhandling VM requests and other specific functions.


#### JOB INITIALIZATION FILES
The files in this category consist of descriptions of how job processing is initialized in an auto-autoscaling mechanism. The conditions required for this stage are described together with the key state transitions.

#### JOB QUEUING FILES
During job processing, a situation arises where the VMs generated get exhausted. This causes the auto-scalers to enter the job queuing stage for VMs to be selected. The files in this category describe what happens during the job queuing stage, the conditions which cause jobs to be queued and the associated state transitions.

#### JOB HANDLING FILES
The files in this category consist of descriptions of how jobs are processed. Emphases are placed on the jobhandler in the reactive auto-scalers and the joblauncher in the predictive auto-scaler.

###### OTHER AUTO-SCALING MECHANISMS
After the design of the ASM model; the model was applied on an auto-scaler designed to investigate the problem of cost-aware autoscaling along with predicted workloads in service clouds. The auto-scaler produced the expected output.
