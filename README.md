### Version control

In this repository, we are implementing DVC to switch between codes and its respective data at that time. Git handles the code versioning (just do git checkout). But git stores the information of the data (data.csv.dvc), through which DVC does the data versioning from your local or S3 or google drive.

In the nutshell, DVC is utilising the power of Git and S3/Drive/local to version back to previous data. 

