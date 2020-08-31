# AWS_EC2_Describe-Instances-Intro-01.md

## JSON
````JSON
{
    "Reservations": [
        {
            "Groups": [],
            "Instances": [
                {
                    "AmiLaunchIndex": 0,
                    "ImageId": "ami-016197fd71780ca55",
                    "InstanceId": "i-060e735b5bd35b0c8",
                    "InstanceType": "t2.micro",
                    "KeyName": "EC2W19-02",
                    "LaunchTime": "2020-08-31T17:00:10+00:00",
                    "Monitoring": {
                        "State": "disabled"
                    },
                    "Placement": {
                        "AvailabilityZone": "ca-central-1b",
                        "GroupName": "",
                        "Tenancy": "default"
                    },
                    "Platform": "windows",
                    "PrivateDnsName": "ip-10-0-2-47.ca-central-1.compute.internal",
                    "PrivateIpAddress": "10.0.2.47",
                    "ProductCodes": [],
                    "PublicDnsName": "",
                    "State": {
                        "Code": 16,
                        "Name": "running"
                    },
                    "StateTransitionReason": "",
                    "SubnetId": "subnet-0627827f07a13b997",
                    "VpcId": "vpc-0e6a780c1da796309",
                    "Architecture": "x86_64",
                    "BlockDeviceMappings": [
                        {
                            "DeviceName": "/dev/sda1",
                            "Ebs": {
                                "AttachTime": "2020-08-31T14:35:59+00:00",
                                "DeleteOnTermination": true,
                                "Status": "attached",
                                "VolumeId": "vol-0577b29f8e7c3a9ba"
                            }
                        }
                    ],
                    "ClientToken": "",
                    "EbsOptimized": false,
                    "EnaSupport": true,
                    "Hypervisor": "xen",
                    "NetworkInterfaces": [
                        {
                            "Attachment": {
                                "AttachTime": "2020-08-31T14:35:58+00:00",
                                "AttachmentId": "eni-attach-0b36a0c4be660c6f6",
                                "DeleteOnTermination": true,
                                "DeviceIndex": 0,
                                "Status": "attached"
                            },
                            "Description": "Primary network interface",
                            "Groups": [
                                {
                                    "GroupName": "RDP-IN-Private",
                                    "GroupId": "sg-0234cd4afc87dcb48"
                                },
                                {
                                    "GroupName": "ICMPv4-IN-MyCustomVPC",
                                    "GroupId": "sg-02712deb70bcaf26b"
                                }
                            ],
                            "Ipv6Addresses": [],
                            "MacAddress": "06:4f:84:f2:76:ac",
                            "NetworkInterfaceId": "eni-09b4139d023a2b35d",
                            "OwnerId": "739648617573",
                            "PrivateIpAddress": "10.0.2.47",
                            "PrivateIpAddresses": [
                                {
                                    "Primary": true,
                                    "PrivateIpAddress": "10.0.2.47"
                                }
                            ],
                            "SourceDestCheck": true,
                            "Status": "in-use",
                            "SubnetId": "subnet-0627827f07a13b997",
                            "VpcId": "vpc-0e6a780c1da796309",
                            "InterfaceType": "interface"
                        }
                    ],
                    "RootDeviceName": "/dev/sda1",
                    "RootDeviceType": "ebs",
                    "SecurityGroups": [
                        {
                            "GroupName": "RDP-IN-Private",
                            "GroupId": "sg-0234cd4afc87dcb48"
                        },
                        {
                            "GroupName": "ICMPv4-IN-MyCustomVPC",
                            "GroupId": "sg-02712deb70bcaf26b"
                        }
                    ],
                    "SourceDestCheck": true,
                    "Tags": [
                        {
                            "Key": "Name",
                            "Value": "EC2W19-02"
                        }
                    ],
                    "VirtualizationType": "hvm",
                    "CpuOptions": {
                        "CoreCount": 1,
                        "ThreadsPerCore": 1
                    },
                    "CapacityReservationSpecification": {
                        "CapacityReservationPreference": "open"
                    },
                    "HibernationOptions": {
                        "Configured": false
                    },
                    "MetadataOptions": {
                        "State": "applied",
                        "HttpTokens": "optional",
                        "HttpPutResponseHopLimit": 1,
                        "HttpEndpoint": "enabled"
                    }
                }
            ],
            "OwnerId": "739648617573",
            "ReservationId": "r-044310111bd0bc641"
        },
        {
            "Groups": [],
            "Instances": [
                {
                    "AmiLaunchIndex": 0,
                    "ImageId": "ami-016197fd71780ca55",
                    "InstanceId": "i-092200df967646d74",
                    "InstanceType": "t2.micro",
                    "KeyName": "EC2W19-01",
                    "LaunchTime": "2020-08-31T17:00:10+00:00",
                    "Monitoring": {
                        "State": "disabled"
                    },
                    "Placement": {
                        "AvailabilityZone": "ca-central-1a",
                        "GroupName": "",
                        "Tenancy": "default"
                    },
                    "Platform": "windows",
                    "PrivateDnsName": "ip-10-0-1-79.ca-central-1.compute.internal",
                    "PrivateIpAddress": "10.0.1.79",
                    "ProductCodes": [],
                    "PublicDnsName": "",
                    "PublicIpAddress": "35.183.198.250",
                    "State": {
                        "Code": 16,
                        "Name": "running"
                    },
                    "StateTransitionReason": "",
                    "SubnetId": "subnet-0ba41655b1720027c",
                    "VpcId": "vpc-0e6a780c1da796309",
                    "Architecture": "x86_64",
                    "BlockDeviceMappings": [
                        {
                            "DeviceName": "/dev/sda1",
                            "Ebs": {
                                "AttachTime": "2020-08-31T13:46:50+00:00",
                                "DeleteOnTermination": true,
                                "Status": "attached",
                                "VolumeId": "vol-080766d41db82834a"
                            }
                        }
                    ],
                    "ClientToken": "",
                    "EbsOptimized": false,
                    "EnaSupport": true,
                    "Hypervisor": "xen",
                    "NetworkInterfaces": [
                        {
                            "Association": {
                                "IpOwnerId": "amazon",
                                "PublicDnsName": "",
                                "PublicIp": "35.183.198.250"
                            },
                            "Attachment": {
                                "AttachTime": "2020-08-31T13:46:49+00:00",
                                "AttachmentId": "eni-attach-051f600d321929f2d",
                                "DeleteOnTermination": true,
                                "DeviceIndex": 0,
                                "Status": "attached"
                            },
                            "Description": "Primary network interface",
                            "Groups": [
                                {
                                    "GroupName": "RDP-IN-Public",
                                    "GroupId": "sg-0ab5d896c28bbcfcc"
                                },
                                {
                                    "GroupName": "ICMPv4-IN-MyCustomVPC",
                                    "GroupId": "sg-02712deb70bcaf26b"
                                }
                            ],
                            "Ipv6Addresses": [],
                            "MacAddress": "02:3d:3c:f5:b9:5a",
                            "NetworkInterfaceId": "eni-06c03b12f2e1be16e",
                            "OwnerId": "739648617573",
                            "PrivateIpAddress": "10.0.1.79",
                            "PrivateIpAddresses": [
                                {
                                    "Association": {
                                        "IpOwnerId": "amazon",
                                        "PublicDnsName": "",
                                        "PublicIp": "35.183.198.250"
                                    },
                                    "Primary": true,
                                    "PrivateIpAddress": "10.0.1.79"
                                }
                            ],
                            "SourceDestCheck": true,
                            "Status": "in-use",
                            "SubnetId": "subnet-0ba41655b1720027c",
                            "VpcId": "vpc-0e6a780c1da796309",
                            "InterfaceType": "interface"
                        }
                    ],
                    "RootDeviceName": "/dev/sda1",
                    "RootDeviceType": "ebs",
                    "SecurityGroups": [
                        {
                            "GroupName": "RDP-IN-Public",
                            "GroupId": "sg-0ab5d896c28bbcfcc"
                        },
                        {
                            "GroupName": "ICMPv4-IN-MyCustomVPC",
                            "GroupId": "sg-02712deb70bcaf26b"
                        }
                    ],
                    "SourceDestCheck": true,
                    "Tags": [
                        {
                            "Key": "Name",
                            "Value": "EC2W19-01"
                        }
                    ],
                    "VirtualizationType": "hvm",
                    "CpuOptions": {
                        "CoreCount": 1,
                        "ThreadsPerCore": 1
                    },
                    "CapacityReservationSpecification": {
                        "CapacityReservationPreference": "open"
                    },
                    "HibernationOptions": {
                        "Configured": false
                    },
                    "MetadataOptions": {
                        "State": "applied",
                        "HttpTokens": "optional",
                        "HttpPutResponseHopLimit": 1,
                        "HttpEndpoint": "enabled"
                    }
                }
            ],
            "OwnerId": "739648617573",
            "ReservationId": "r-02aecc3a8c64b25ac"
        }
    ]
}
````
