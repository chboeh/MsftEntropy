## Answers

[Quick Link](https://portal.loganalytics.io/Demo?q=H4sIAAAAAAAAAwtOTS4tyiypdC1LzStR4OWqUSjPSC1KVXDOzy0oLUktUrC1VVByzs8ryS%2FOdywoCC4qM1RCqArJzE11T81LLUosSU1RsFNITM%2FXMDLJ0AQblJxfCjSSCwCjtDyLYgAAAA%3D%3D)
~~~
SecurityEvent 
| where Computer == "ContosoAppSrv1"
| where TimeGenerated > ago(24h) 
| count 
~~~
> Should be around 26,000 - 35,000 (Changes Daily)

![Answer](Pictures/KQLInvestigation_3.png)
