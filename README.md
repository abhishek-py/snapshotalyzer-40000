# snapshotalyzer-40000
Demo Project to manage AWS EC2 instance snapshots

##configuring

shotty uses the configuration file created by the AWS cli.

`aws configure --profile shotty`

## running

`pipenv run "python shotty/shotty.py  <commands> <subcommands>
<--project=PROJECT>"`

*command* is instance , volumes or snapshots
*subcommands* depends on command
*project* is optional
