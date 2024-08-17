# One-Click Apps for Akamai Connected Cloud

This repository contains the deployment scripts and Ansible playbooks for two Akamai Connected Cloud Marketplace apps that I developed and published: **JupyterLab** and **InfluxDB**. These apps have been submitted as pull requests to the official Akamai Compute Marketplace project, have been merged, and are now fully deployable on Akamai Connected Cloud.

## Akamai Connected Cloud Marketplace Apps

### 1. JupyterLab
- **Description**: JupyterLab is a web-based interactive development environment for Jupyter notebooks, code, and data.
- **Deployment**: The Ansible playbook for JupyterLab is located in the `linode-marketplace-jupyterlab` folder. The deployment shell script can be found as `jupyterlab-deploy.sh`.
- **PR Link**: [JupyterLab Pull Request #81](https://github.com/akamai-compute-marketplace/marketplace-apps/pull/81)

### 2. InfluxDB
- **Description**: InfluxDB is an open-source time series database designed to handle high write and query loads.
- **Deployment**: The Ansible playbook for InfluxDB is located in the `linode-marketplace-influxdb` folder. The deployment shell script can be found as `influxdb-deploy.sh`.
- **PR Link**: [InfluxDB Pull Request #120](https://github.com/akamai-compute-marketplace/marketplace-apps/pull/120)

## Usage
To deploy these apps on Akamai Connected Cloud:

1. **Create an Account or Log In**: Start by creating an Akamai Cloud Manager account or logging into your existing account.
2. **Navigate to the Marketplace**: Once logged in, go to the Marketplace section of the Akamai Cloud Manager dashboard.
3. **Select the App**: Choose the app you wish to deploy—either JupyterLab or InfluxDB.
4. **Customize the Deployment**: Configure the app according to your requirements, including setting up resources, regions, and other customizable options.
5. **Deploy**: Once configured, initiate the deployment, and your app will be up and running on Akamai Connected Cloud.

For more detailed guidance, refer to the following deployment guides:
- **Deploy JupyterLab** through the Linode Marketplace: [JupyterLab Guide](https://www.linode.com/docs/marketplace-docs/guides/jupyterlab/)
- **Deploy InfluxDB** through the Linode Marketplace: [InfluxDB Guide](https://www.linode.com/docs/marketplace-docs/guides/influxdb/)

## Contributions
Those looking to contribute directly to the Akamai Compute Marketplace should review the [Contribution Guide](https://github.com/akamai-compute-marketplace/marketplace-apps/blob/main/docs/CONTRIBUTING.md).

## License
These applications are subject to the Akamai Compute Marketplace License. Please review the license [here](https://github.com/akamai-compute-marketplace/marketplace-apps/blob/main/LICENSE) for more information.
