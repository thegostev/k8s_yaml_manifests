| NAME                 | PROMPT                        | DESCRIPTION                               | EXAMPLE                                                     |
|----------------------|-------------------------------|-------------------------------------------|-------------------------------------------------------------|
| app.yaml             | kubectl create deployment     | Main application deployment manifest      | [yaml/app.yaml](yaml/app.yaml)                                  |
| app-livenessProbe.yaml | kubectl create                  | Liveness probe configuration             | [yaml/app-livenessProbe.yaml](yaml/app-livenessProbe.yaml)        |
| app-readinessProbe.yaml | kubectl create                 | Readiness probe configuration            | [yaml/app-readinessProbe.yaml](yaml/app-readinessProbe.yaml)      |
| app-volumeMounts.yaml | kubectl create                 | Volume mounts configuration              | [yaml/app-volumeMounts.yaml](yaml/app-volumeMounts.yaml)          |
| app-cronjob.yaml     | kubectl create job            | Cron job configuration                   | [yaml/app-cronjob.yaml](yaml/app-cronjob.yaml)                   |
| app-job.yaml         | kubectl create job            | Job configuration                        | [yaml/app-job.yaml](yaml/app-job.yaml)                           |
| app-multicontainer.yaml | kubectl create                | Multi-container app configuration        | [yaml/app-multicontainer.yaml](yaml/app-multicontainer.yaml)      |
| app-resources.yaml   | kubectl apply                 | Resource allocation configuration        | [yaml/app-resources.yaml](yaml/app-resources.yaml)                |
| app-secret-env.yaml  | kubectl create secret         | Environment secrets configuration       | [yaml/app-secret-env.yaml](yaml/app-secret-env.yaml)              |



