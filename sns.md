# SNS(Simple Notification Service)
* It is a notification service that is used to send notifications whenever corresponding event takes place.
* It is PUB SUB messaging service.
## Advantages
* Reliable.
* Auto scaling
* Easy architecture.

# Steps to create new SNS
### Step 1
* Search for SNS in AWS.
* Create a new topic.
![](https://github.com/Divyesh-Kambli/pics/blob/master/sns%20crate%20topic.png)

* Fill in name and display name sections.

### Step 2
* Once the topic is created then create subscription for the created topic.
* Select the type of endpoint you want i.e. email is this case.
![](https://github.com/Divyesh-Kambli/pics/blob/master/sns%20create%20subscription.png)
* Enter your email id.

### Step 3

* Once you are done wiht step 2 then a notification email will be send to your email id provided.
* Click on confirm subscription.
![](https://github.com/Divyesh-Kambli/pics/blob/master/sns%20pending.png)
* Then the pending status will be changed to confirmed.

### Step 4 Creating alarm
* Select the instance for which you want to create alarm.
* Click on monitoring.
* Click create alarm and provide necessary conditions.
![](https://github.com/Divyesh-Kambli/pics/blob/master/sns%20creating%20alarm.png)



