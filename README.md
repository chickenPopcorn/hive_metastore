# hive-metastore-on-k8s
Setup for running Hive Metastore on Kubernetes.

# How to Use

Dockerfile for Metastore
 * Uses [Hive Metastore Standalone service](https://cwiki.apache.org/confluence/display/Hive/AdminManual+Metastore+3.0+Administration).

Yaml for MariaDB
 * Simple and not optimized.

Yaml for init-schemas
 * One-time K8s job to initiate the MariaDB tables.

Yaml for Metastore