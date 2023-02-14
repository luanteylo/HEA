# HEA
The HEA is a hybrid evolutionary algorithm developed to solve the problem of task scheduling and data allocation in scientific workflows.

## Installation
To run the algorithm, it is necessary to install the dependencies. This task can be easily performed using the install.sh script available in the HEA/setup/ folder.

To compile the project, use the compile.sh file.

## Input Files
The input files can be found in the HEA/input folder.

## Execution

The executable file is located in the bin/ directory.

```
cd HEA/bin

./HEA -c ../input/cluster.vcl -w ../input/miniworkflow.dag  -v
```

* The .vcl file describes the execution environment and the computational resources of each machine in this environment.
* The .dag file describes the workflow that should be scheduled.

## Versioning
Version 1.0 - 2016.

## Author

* **Luan Teylo**  

