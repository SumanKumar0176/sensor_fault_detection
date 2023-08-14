# Sensor-Fault-Detection

### Problem Statement
The Air Pressure System (APS) is a critical component of a heavy-duty vehicle that uses compressed air to force a piston to provide pressure 
to the brake pads, slowing the vehicle down. The benefits of using an APS instead of a hydraulic system are the easy availability and long-term
sustainability of natural air.

This is a Binary Classification problem, in which the affirmative class indicates that the failure was caused by a certain component of the APS,
while the negative class
indicates that the failure was caused by something else.

### Solution Proposed 
In this project, the system in focus is the Air Pressure system (APS) which generates pressurized air that are utilized in various functions in 
a truck, such as braking and gear changes. The datasets positive class corresponds to component failures for a specific component of the APS 
system. The negative class corresponds to trucks with failures for components not related to the APS system.

The problem is to reduce the cost due to unnecessary repairs. So it is required to minimize the false predictions.
## Tech Stack Used
1. Python 
2. FastAPI 
3. Machine learning algorithms
4. Docker
5. MongoDB

## Infrastructure Required.

1. AWS S3
2. AWS EC2
3. AWS ECR
4. Git Actions
5. Terraform

## How to run?
Before we run the project, make sure that you are having MongoDB in your local system, with Compass since we are using MongoDB for data storage.
You also need AWS account to access the service like S3, ECR and EC2 instances.




MONGO DB USL:
'''
mangodb+srv://temp-user:U8I5A6oh0jJnVoU@ineuron-ai-projects.7eh1w4s.mongodb.net/admin?authSource=admin%replicaSet=atlas-okvkrd-shard-0&W=majority&readPreference=Primary&retryWrites=true&ssl=true