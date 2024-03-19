# aws-vs-gcp
Experimenting with training a model in different ways within two cloud service providers


## GCP

### Training a model in Vertex training job

1) push training image to GAR
2) create vertex training job
3) view results?

**EXP 1: sklearn dummy**

Model: sample_sklearn_model
Compute Service: Vertex AI
Compute hardware: n1-standard-4 (w/ 100gb ssd)
Provisioning time: 1 minute 30 seconds
Task time: 30 seconds
Total time: 2 minutes
Cost: 
Notes: startup time was rather long. Not good for quick exp.


**EXP 2: 