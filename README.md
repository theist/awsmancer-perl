# awsmancer-perl
Quick hack script to call aws with their own generated json skeletons

All the aws-cli commands nos support input by json files, to generate these files you can call any command 
with `--generate-cli-skeleton` parameter, which dump a json template.

Those skeletons can be used as input for the other parameter `--cli-input-json` as a way to specify parameters for AWS
API calls.

This script gets those skeletons, lets you edit it and uses the edited file to call aws cli.


