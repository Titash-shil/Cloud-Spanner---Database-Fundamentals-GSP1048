# Cloud Spanner - Database Fundamentals || [GSP1048](https://www.cloudskillsboost.google/focuses/54352?parent=catalog) ||

# # Like, comment, share & Don't forget to subscribe [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN) 👍😄🤝

### Run the following Commands in CloudShell

```
export REGION=
```
```
gcloud spanner instances create banking-instance \
--config=regional-$REGION  \
--description="awesome" \
--nodes=1

gcloud spanner databases create banking-db --instance=banking-instance

gcloud spanner instances create banking-instance-2 \
--config=regional-$REGION  \
--description="awesome" \
--nodes=2

gcloud spanner databases create banking-db-2 --instance=banking-instance-2

gcloud spanner databases ddl update banking-db --instance=banking-instance --ddl="CREATE TABLE Customer (
  CustomerId STRING(36) NOT NULL,
  Name STRING(MAX) NOT NULL,
  Location STRING(MAX) NOT NULL,
) PRIMARY KEY (CustomerId);"
```

# Congratulations ..!!🎉  You completed the lab shortly..😃💯

# *Well done..!* 👏

# Thank you for visiting.... :) 🗯️

# [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN)
