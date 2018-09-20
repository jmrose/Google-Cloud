# Google Cloud


### Managing SDK Components

$ gcloud components list  
  
```code
+----------------------------------------------------------------------------------------------------------------+
|                                                   Components                                                   |
+------------------+------------------------------------------------------+--------------------------+-----------+
|      Status      |                         Name                         |            ID            |    Size   |
+------------------+------------------------------------------------------+--------------------------+-----------+
| Update Available | Cloud SDK Core Libraries                             | core                     |   8.5 MiB |
| Update Available | Cloud Storage Command Line Tool                      | gsutil                   |   3.5 MiB |
| Update Available | gcloud app Python Extensions                         | app-engine-python        |   6.2 MiB |
| Not Installed    | App Engine Go Extensions                             | app-engine-go            | 154.5 MiB |
| Not Installed    | Cloud Bigtable Command Line Tool                     | cbt                      |   6.2 MiB |
| Not Installed    | Cloud Bigtable Emulator                              | bigtable                 |   4.2 MiB |
| Not Installed    | Cloud Datalab Command Line Tool                      | datalab                  |   < 1 MiB |
| Not Installed    | Cloud Datastore Emulator (Legacy)                    | gcd-emulator             |  38.1 MiB |
| Not Installed    | Cloud Pub/Sub Emulator                               | pubsub-emulator          |  33.4 MiB |
| Not Installed    | Cloud SQL Proxy                                      | cloud_sql_proxy          |   3.5 MiB |
| Not Installed    | Emulator Reverse Proxy                               | emulator-reverse-proxy   |  14.5 MiB |
| Not Installed    | Google Container Registry's Docker credential helper | docker-credential-gcr    |   1.8 MiB |
| Not Installed    | gcloud Alpha Commands                                | alpha                    |   < 1 MiB |
| Not Installed    | gcloud Beta Commands                                 | beta                     |   < 1 MiB |
| Not Installed    | gcloud app Java Extensions                           | app-engine-java          | 107.5 MiB |
| Not Installed    | gcloud app PHP Extensions                            | app-engine-php           |  19.1 MiB |
| Not Installed    | gcloud app Python Extensions (Extra Libraries)       | app-engine-python-extras |  28.5 MiB |
| Not Installed    | kubectl                                              | kubectl                  |   < 1 MiB |
| Installed        | BigQuery Command Line Tool                           | bq                       |   < 1 MiB |
| Installed        | Cloud Datastore Emulator                             | cloud-datastore-emulator |  17.7 MiB |
+------------------+------------------------------------------------------+--------------------------+-----------+
```

- python && google model class 사용  
from google.appengine.ext import ndb  


* 참조 : [Creating Entity Models](https://cloud.google.com/appengine/docs/standard/python/ndb/db_to_ndb)
