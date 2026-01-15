## Q1
index=botsv3  sourcetype="aws:cloudtrail"
userIdentity.type=IAMUser
|stats count by userIdentity.userName 
|sort userIdentity.username

## Q2
index=botsv3 sourcetype=aws:cloudtrail NOT eventName=ConsoleLogin

## Q3
index=botsv3 sourcetype=hardware

## Q4
index=botsv3 sourcetype=aws:cloudtrail eventName=PutBucketAcl

## Q5
index=botsv3 sourcetype=aws:cloudtrail eventName=PutBucketAcl

## Q6
index=botsv3 sourcetype=aws:cloudtrail eventName=PutBucketAcl

## Q7
index=botsv3 sourcetype=aws:s3:accesslogs frothlywebcode PUT 200

## Q8
1.
index=botsv3 sourcetype=winhostmon

2.
index=botsv3 sourcetype=winhostmon
|stats count by OS
