## Week 8: Setting Up MongoDB with Persistent Storage

1. Created a Persistent Volumes (PV) and Persistent Volume Claims (PVC):
   - Created PV and PVC to allocate and bind storage

2. Created a ConfigMap and a Secret:
   - Used a ConfigMap to store configuration data
   - Used a Secret to securely store database credentials

3. Deployed MongoDB as a StatefulSet:
   - Ensured each pod had persistent storage

## Week 9: Configuring MongoDB Replica Set

1. Initialized a MongoDB replica:
   - Configured one primary pod and two secondary pods to ensure data replication

2. Verified the setup by testing data replication:
   - Inserted data into the primary pod and checked if it replicated to the secondary pods.
