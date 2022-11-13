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

 ###### The ASM Specification files created for this research and the algorithms discussed in the paper are tabulated below
 |AN  |Algorithms             | File Names               |
 |----|-----------------------|--------------------------|
 |1   |Job Handling           |JobInitReqFunMod.casm     |
 |2   |Refined Job Handling   |RefinedJobHandling.casm   |
 |3   |Vmopt Job Initial      |VmoptJobInit.casm         |
 |4   |Threshold job Init.    |ThresholdJobInit.casm     |
 |5   |Fixed Jobs Que.        |FixedJobQue.casm          |
 |6   |Sim.  Jobhand.         |SimJobHandMod.casm        |
 |7   |Vmopt Jobs Que.        |VmoptJobQue.casm          |
 |8   |Multi. Jobhand.        |MultiJobHandMod.casm      |
 |9   |Fixed  Jobs hand       |FixedJobHand.casm         |
 |10  |Vmopt Jobs hand.       |VmoptJobHand.casm         |
 |11  |Pooling Jobs hand.     |PoolJobHand.casm          |
 |12  |Threshold Jobs hand.   |ThresJobHand.casm         |
 |13  |VmCreate Jobs hand.    |VmCreateJobHand.casm      |
 |14  |Job Termination        |JobTermination.casm       |
 |15  |LoadPred. Jobs Init    |LoadPredJobInit.casm      |
 |16  |LoadPred. Job hand.    |LoadPredJobHand.casm      |
 |17  |Virt. Res. Scal. down  |LoadVirtResScalDown.casm  |
 |18  |Pre-scaling Int.       |LoadPreScalInterval.casm  |
 |19  |Cost-Aware Pre-scal.   |LoadCostAwarePSU.casm     | 
 |20  |Simple Initial Phase   |SimpleInitialPhase.casm   |
 |21  |Simple Job Queuing     |SimpleJobQue.casm         |
 |22  |Simple Job Initialising|SimpleJobInitialising.casm|
 |23  |Simple JobHandlingMod. |SimpleJobHandMod.casm     |
 |24  |Refined Job Termination|RefineJobTermination.casm |
 |25  |Refined Initial Phase  |RefinedInitialPhase.casm  |
 |26  |Refined Job Queuing    |RefinedJobQue.casm        |
 
