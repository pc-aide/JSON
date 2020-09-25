# ec2 run-instances.json

## switch
* --dry-run - flag [bool] - to test it our command

## Example
````json
aws ec2 run-instances --dry-run \
	--image-id ami-020caff809d5a5307 \
	--instance-type t2.micro \
	--key-name EC2Ama-01-ca-ctl \
 	--security-group-ids sg-fdsfwfjf722fsdf \
	--user-data file:EC2Ama-Web-SRV.txt \
 	--tag-specifications 'ResourceType=instance,Tags=[{Key=Name,Value=EC2Ama-01}]' \
 	--profile Joe
````
[<img src="https://i.imgur.com/EYx3kzs.png">](https://i.imgur.com/EYx3kzs.png)
[<img src="https://i.imgur.com/zhl3RNf.png">](https://i.imgur.com/zhl3RNf.png)
