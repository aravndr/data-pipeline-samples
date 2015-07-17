![Data Pipeline Logo](https://raw.githubusercontent.com/awslabs/data-pipeline-samples/master/samples/logo/datapipelinelogo.jpeg)

Data Pipeline Samples
=====================
AWS Data Pipeline is a web service that you can use to automate the movement and transformation of data. With AWS Data Pipeline, you can define data-driven workflows, so that tasks can be dependent on the successful completion of previous tasks. You define the parameters of your data transformations and AWS Data Pipeline enforces the logic that you've set up.




# Running the samples

##Install the AWS CLI 
Follow the instructions [here](http://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-set-up.html) to install the AWS CLI

##Create default IAM Roles
From your CLI run the following command to create the the default IAM roles for use in Pipeline Definitions. 

```sh
 $> aws cli 
```

##Get the samples

```sh
 $> git clone https://github.com/awslabs/data-pipeline-samples.git
```


##Disclaimer
The samples in this repository are meant to help users get started with Data Pipeline. They may not be sufficient for production environments. Users should carefully inspect code samples before running them.

_Use at your own risk._

Copyright 2011-2013 Amazon.com, Inc. or its affiliates. All Rights Reserved.

Licensed under the Amazon Software License (the "License"). You
may not use this file except in compliance with the License. A copy of
the License is located at

http://aws.amazon.com/asl/

