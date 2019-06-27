# GCP notes

Course:  
[Google Cloud Platform Fundamentals: Core Infrastructure](https://www.coursera.org/learn/gcp-fundamentals)


Environment variable:  
```export LOCATION=EU```

Create a backet:  
```gsutil mb -l $LOCATION gs://$DEVSHELL_PROJECT_ID```

Copy a file:  
```gsutil cp gs://cloud-training/gcpfci/my-excellent-blog.png gs://$DEVSHELL_PROJECT_ID/my-excellent-blog.png```


## Kubernetes  
Get pods:  
```kubectl get pods```

Get services:  
```kibectl get services```

Create kubernetes cluster:  
```gcloud container clusters create my-cluster-name --zone $MY_ZONE --num-nodes 3```

Run container:  
```kubectl run nginx --image=nginx:1.10.0```


## App engine

Deploy app:  
```gcloud app deploy ./index.yaml ./app.yaml```
