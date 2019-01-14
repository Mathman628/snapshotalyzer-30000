# snapshotalyzer-30000

Demo project to manage AWS EC2 instance snapshots. From an A Cloud Guru course. 

## About

This project is a demo, using boto3 to manage AWS EC2 instance snapshots. From an A Cloud Guru course.

## Configuring 

shotty uses the configuration file created by the AWS cli. e.g.

`aws configure --profile shotty`

## Running

`pipenv run python shotty/shotty.py <command> <subcommand> <--project=PROJECT>`

*command* is instances, volumes or snapshots
*subcommand* - depends on command
*project* is optional