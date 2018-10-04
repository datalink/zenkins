# zenkins
Simple tool to build a bridge between zabbix and jenkins that
implements discovery feature used to idenfify monitored jobs
according to prefix in the job name, this is script is also 
used to send current job status.

## Install

```
sudo pip install -r requirements.txt
sudo chmod a+x zenkins.py
sudo cp zenkins.conf /etc
```

Don't forget to set the statusOnly password in zenkins.conf
