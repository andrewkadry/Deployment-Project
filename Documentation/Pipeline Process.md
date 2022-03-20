# pipeline

this project uses CircleCI to create a pipeline

circleci is connected to this repository 

if any changes happened in this repository 

circleci will notice and will run the pipeline as follows:

1. install node 

1. install AWS-CLI

1. install EB-CLI

1. install frontend dependencies

1. install backend dependencies

1. build frontend

1. build backend

1. deploy frontend to S3 Bucket

1. deploy Backend to elastic beanstalk

