Image-based transfer learning on Cloud ML
--------------------------------------------------

To run this code first complete the basic setup in google cloud console, follow instructions for [setting up your environment](https://cloud.google.com/ml/docs/how-tos/getting-set-up).

Also, I used Apache Beam (running on Cloud Dataflow) and PIL to preprocess the images into embeddings, so make sure to install the required packages:
```
pip install -r requirements.txt
```

Then, you may follow the instructions in sample.sh.
