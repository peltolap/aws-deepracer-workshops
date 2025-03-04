# DeepRacer notebook using Amazon SageMaker RL and AWS RoboMaker services

This folder contains examples of how to use RL to train an autonomous deepracer. This is a jailbreaker for the AWS DeepRacer. This gives a glimse of architecture used to get the DeepRacer working.

## How to use the notebook

1. Login to your AWS account - SageMaker service ([SageMaker Link](https://us-west-2.console.aws.amazon.com/sagemaker/home?region=us-west-2#/dashboard))
2. On the left tab select `Notebook instances`
3. Select `Create notebook instance`
4. Fill up the notebook instance name. In the Additional configuration select atleast 25GB. This is because docker gets installed and takes up space.
5. Create a new IAM role. Give root permission
6. Select the git repository and clone this repository.
7. Then click create notebook instance button at the button
8. This takes like 2 min to create your notebook instance. Then click on the newly created instance and click on the juypter notebook.
9. You will see all the github files and now run `deepracer_rl.ipynb`
10. Run clean robomaker & sagemaker commands in the script only when you are done with training.
