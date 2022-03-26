###Project2 - Deploy High Availability Web App using CloudFormation########

Commands used to be able to create Stack for this project

-For network Infrastructure Stack:

./create.sh networkinfra network.yml network-params.json

./update.sh networkinfra network.yml network-params.json (in case of update on script to be done)

-For Web App Infrastructure Stack:

./create.sh  webinfra application.yml application-params.json

./update.sh webinfra application.yml application-params.json   (in case of update on script to be done)

for deleting Stack through this command

aws cloudformation delete-stack --stack-name networkinfra

aws cloudformation delete-stack --stack-name webinfra


