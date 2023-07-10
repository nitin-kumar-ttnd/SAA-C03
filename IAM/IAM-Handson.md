## Hands-On

## Steps to Activate MF

### Step 1: Go to IAM Section

![IAM MF Root](.IAM_images/IAM-MF-Root.png)

### Step 2: Click on the Add MFA Security Recommendation and follow the wizard

![MF-App Setup](.IAM_images/MF-APP-SETUP.png)

![SCAN QR MF](.IAM_images/ScanQRforMF.png)

---

## Create User

* Go to IAM
* Click on Users (on left menu)
* Click on add users
* Provide username
* Fill in details in the page shown below:
  ![](.IAM-Handson_images/Specify-User-Details.png)
* On Successful User Creation
  ![](.IAM-Handson_images/User-Created-Successfully.png)

## IAM Policies Handson

## AWS CLI Configure

Go to user > Security Credentials > Create Access Key

In commandline use following command:
`aws configure` and provide your access key id, Secret Access Key, Default region, Default Output (just press enter)
![](.IAM-Handson_images/aws-configure.png)

you can try executing the command (if you have permissions): `aws iam list-users`



