### This project deploys a high-availability web app using CloudFormation
The script is broken into 2, first-infrastructure.yaml which will be ran first for first stack and second-infrastructure.yaml which will be ran second for second stack or as an update stack to the first.

To run the script, go to the directory first-infrastructure.yaml is, and run

```
./create.sh <stack-name> first-infrastructure.yaml first-infrastructure-parameter.json
```

And the above stack is successfully created, then run the command below

```
./create.sh <stack-name2> second-infrastructure.yaml second-infrastructure-parameter.json
```
