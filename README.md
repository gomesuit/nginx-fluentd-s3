# nginx-fluentd-s3

## install fluentd
```
curl -L https://toolbelt.treasuredata.com/sh/install-redhat-td-agent2.sh | sh
td-agent-gem install fluent-plugin-s3
```

## install nginx
```
yum install -y nginx
```

## install awscli
```
curl "https://bootstrap.pypa.io/get-pip.py" -o "get-pip.py"
python get-pip.py
pip install awscli
aws configure
```
