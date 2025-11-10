# vpc Module 
This module is developed for joindevops. Projects inside joindevops can follow this module to create their VPC 

## Inputs 
* Project (required) - Users should specify their project 
* Environment (required) - Users should specify their environment
* cidr-block (options) - Users can provide their CIDR block. Default is 10.0.0.0/16 

## Outputs 
* vpc_id - Exports VPC ID created 
