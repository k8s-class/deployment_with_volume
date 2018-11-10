# Volumes

How to create a volume and attach it to a deployment
```
$ aws ec2 create-volume --size 10 --region us-east-1 --availability-zone us-east-1a --volume-type gp2
  {
      "CreateTime": "2017-08-03T21:33:18.888Z",
      "Size": 10,
      "Encrypted": false,
      "Iops": 100,
      "AvailabilityZone": "us-east-1a",
      "SnapshotId": "",
      "VolumeType": "gp2",
      "State": "creating",
      "VolumeId": "vol-07c063979cb620533"
  }
```
