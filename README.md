# cratedb-cluster

This repository contains the necessary files to easily set up a CrateDB cluster using Pergola.
A full walkthrough of the setup is available in our [blog post](https://blog.pergola.cloud/pergolize-database-cluster/).

`crate.yml` contains several configuration options that are used to configure the cluster, for example, the data source and authentication.
The documentation for the configuration can be found [here](https://cratedb.com/docs/crate/reference/en/5.5/config/index.html).

`pergola.yaml` is the Pergola Project Manifest to set up and deploy the components and the underlying infrastructure on Pergola.
The documentation for the Project Manifest can be found [here](https://docs.pergola.cloud/docs/reference/project-manifest).
