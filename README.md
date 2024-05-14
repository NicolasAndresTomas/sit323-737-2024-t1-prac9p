
## Summary

This project demonstrates the deployment of a MongoDB replica set in a Kubernetes cluster, incorporating persistent storage, ConfigMaps, and Secrets. The setup ensures that MongoDB pods maintain data consistency and high availability.

### Week 8: Setting Up MongoDB with Persistent Storage

1. **Created a PV to allocate storage**:
   - Persistent Volumes (PV) and Persistent Volume Claims (PVC) were created to allocate and bind the storage.

2. **Created a ConfigMap and a Secret**:
   - ConfigMap was used to store non-sensitive configuration data.
   - Secret was used to store sensitive information like database credentials securely.

3. **Deployed MongoDB as a StatefulSet**:
   - Ensured each pod had a unique identity and persistent storage.

### Week 9: Configuring MongoDB Replica Set

1. **Initialized a MongoDB replica set**:
   - Configured one primary pod and two secondary pods to ensure data replication and high availability.

2. **Verified the setup by testing data replication**:
   - Inserted data into the primary pod and ensured it replicated to the secondary pods.
