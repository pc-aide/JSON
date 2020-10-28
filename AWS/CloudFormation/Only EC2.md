# Only EC2.md

## src
````json
{
  "Resources": {
    "EC2": {
      "Type": "AWS::EC2::Instance",
      "Properties": {
        "AvailabilityZone": "ca-central-1a",
        "ImageId" : "ami-0c2f25c1f66a1ff4d",
        "InstanceType": "t2.micro"
      }
    }
  }
}
````

### O/P
[<img src="https://i.imgur.com/fJzcb3q.png">](https://i.imgur.com/fJzcb3q.png)
