Basic example: Localstack, AWS and Ansible

```
$ pip3 install ansible
$ pip3 install awscli
$ ansible-galaxy collection install amazon.aws
$ docker-compose up -d
$ ansible-playbook s3.yaml
$ aws --endpoint-url=http://localhost:4566 s3 ls
2021-03-14 19:19:13 my-test-bucket
```
