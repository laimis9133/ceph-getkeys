# ceph-getkeys
Get any Ceph S3 bucket keys using RadosGW admin API via GO.  
Script retreives access and secret keys via RadosGW admin user and generates configurations used by awscli/boto3 as well as MinIO.  
Docker image is small weight (15MB) and can be added as an initial Kubernetes pod for any administrative tasks on a Ceph cluster. Enjoy.
