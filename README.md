# snapshotaws
demo project to manage the AWS EC2 instance snapshots

This project is a demo and uses the boto3 to manage the AWS EC2 instance snapshots.

## Configurring

shotty uses the configuration file created by the AWS cli. eg.

`aws configure --profile shotty`

## Running

`pipenv run "python shotty/shotty.py <commands> <subcommands>
<--project=PROJECT>"`

*command* is instances, volumes or snapshots
*subcommands* - depends on the command
*project* is optional
