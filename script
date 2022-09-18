#!/bin/bash
aws ec2 run-instances --image-id ami-0568773882d492fc8 --count 1 --instance-type t2.micro --key-name ohio --subnet-id  subnet-024d03bfd97905d2e --tag-specifications 'ResourceType=instance,Tags=[{Key=Name,Value=webserver}]'
