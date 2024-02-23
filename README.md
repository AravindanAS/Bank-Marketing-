Bank Marketing Deployment using AWS Sagemaker

![AWS-1-1](https://github.com/AravindanAS/Bank-Marketing-/assets/136828832/33e59d94-2bc2-46ae-9cfb-6aa956c114ce)

The Bank Marketing Dataset contains a reasonable large number of data related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The goal is to predict if the client will subscribe a term deposit.
It is a fairly large dataset with 41K+ rows, a mixture of categorical and continuous columns as well as data imperfections to identify and manage.

1.Sign up for a free AWS account at https://aws.amazon.com

2.In your AWS console search for “sagemaker” and click it

3.Click on Studio

4.Click on Launch SageMaker Studio

The5. first time you launch Sagemaker Studio, you’ll have to do a one time setup.
Select Quick setup
Type a name that’s meaningful
Select create a new role from the dropdown

6.Select “Any S3 bucket” so that your Studio notebooks have access to any data on any S3 bucket in your account. Click Create role

7.Once the role is created, click Submit

8.The setup will take some time. You can see the status on the top of the page

9.Once the setup is done, you’ll see the domain you created with a “Launch app” dropdown Click on “Studio”. DO NOT CLICK ON CANVAS ($$$)!!!!

10.After some loading, your brand new jupyter lab interface running on Sagemaker studio servers will open up. If the loading gets stuck on a white screen, try refreshing the page.
You can clone any github repository. For example, you can clone this course repository: https://github.com/AravindanAS
Follow the lessons in the notebooks/ directory.

11.While running any code, if you get an error that the kernel is still starting, look at the bottom of your screen for the Kernel status

12.You can run the cell once the Kernel status is Idle

13.When you’re done with Sagemaker Studio, REMEMBER to shut down everything to prevent getting charged $!

14.You will get the below message only if you opened at least one jupyter notebook on the studio instance. So if you don’t get this, just create a new notebook, let it start up and then try shutting down again just to be sure.

Getting started

1.get the code from the repository from https://github.com/AravindanAS/Aravindan

2.install required python packages if previously not installed

3.Finally run the code on Jupyter Notebook
