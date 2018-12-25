# snapshotalyzer-30000
Project to manage AWS EC2 instance snapshots

## About

This project uses boto3 to manage AWS EC2 instance snapshots

## Configuring

Shotty uses the configuration file created by the AWS clie, e.g.

'aws configure --profile shotty'

## Running

'pipenv run "python shotty.py' <command> <--project=PROJECT>"

*command* is list, start, or stop
*project* is optional
