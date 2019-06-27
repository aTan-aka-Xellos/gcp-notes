# GCP notes

Course:  
[Google Cloud Platform Fundamentals: Core Infrastructure](https://www.coursera.org/learn/gcp-fundamentals)


Environment variable:  
```export LOCATION=EU```

Create a backet:  
```gsutil mb -l $LOCATION gs://$DEVSHELL_PROJECT_ID```

Copy a file:  
```
gsutil cp gs://cloud-training/gcpfci/my-excellent-blog.png gs://$DEVSHELL_PROJECT_ID/my-excellent-blog.png
```


