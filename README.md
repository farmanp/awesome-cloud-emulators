# Awesome Cloud Emulators

A curated list of awesome cloud emulators for developers, testers, and engineers. These tools allow you to run and test cloud environments locally, avoiding the need for live cloud environments and reducing costs. Inspired by [Awesome](https://github.com/sindresorhus/awesome).

---

## Table of Contents

- [Introduction](#introduction)
- [Platform Emulators](#platform-emulators)
- [AWS Emulators](#aws-emulators)
- [Azure Emulators](#azure-emulators)
- [Google Cloud Platform (GCP) Emulators](#google-cloud-platform-gcp-emulators)
- [Oracle Cloud Infrastructure (OCI) Emulators](#oracle-cloud-infrastructure-oci-emulators)
- [Serverless Emulators](#serverless-emulators)
- [Networking and Observability](#networking-and-observability)
- [Other Emulators](#other-emulators)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction

This list provides a collection of cloud emulators that replicate the behavior of popular cloud platforms and services, such as AWS, Azure, Google Cloud Platform (GCP), and Oracle Cloud Infrastructure (OCI). These emulators are invaluable for local development, testing, and debugging, enabling developers to iterate faster and avoid cloud costs during the development phase.

To provide a broader scope, we also include tools compatible with cloud services or that replicate cloud and related behaviors for various use cases.

---

## Platform Emulators

### [MinIO](https://min.io/)
- **Description**: A high-performance, S3-compatible object storage solution often used as a local alternative to AWS S3 for testing and development.
- **Key Features**:
  - High-performance, Kubernetes-native storage solution.
  - Fully open-source with enterprise-grade features.
- **Use Cases**: Testing S3-based applications locally or in hybrid cloud setups.

### [Eucalyptus](https://github.com/eucalyptus/eucalyptus)
- **Description**: An open-source platform for building AWS-compatible private and hybrid clouds.
- **Key Features**:
  - Fully AWS API-compatible.
  - Supports a range of AWS services like EC2, S3, and IAM.
- **Use Cases**: Private cloud deployments with AWS compatibility.

---

## AWS Emulators

### [LocalStack](https://github.com/localstack/localstack)
- **Description**: A fully functional local AWS cloud stack.
- **Key Features**:
  - Emulates a wide range of AWS services including S3, DynamoDB, Lambda, and more.
  - Integrates with CI/CD pipelines and Infrastructure as Code tools like Terraform.
- **Use Cases**: Local development, testing, and debugging of AWS applications.

#### [LocalStack Lambda Guide](https://github.com/localstack/localstack)
- **Description**: A comprehensive guide for setting up AWS Lambda on LocalStack with Terraform.
- **Key Features**:
  - Step-by-step instructions for configuring Lambda locally.
  - Focus on Terraform integration.
- **Use Cases**: Developing and testing Lambda functions in a controlled local environment.

---

## Azure Emulators

### [Azure Service Bus Emulator](https://github.com/Azure/azure-service-bus-emulator-installer)
- **Description**: A tool for local development and testing of Azure Service Bus messaging solutions.
- **Key Features**:
  - Mimics Azure Service Bus for offline development.
  - Reduces dependencies on live Azure environments.
- **Use Cases**: Testing messaging-based applications.

### [Emulator Express](https://learn.microsoft.com/en-us/visualstudio/azure/vs-azure-tools-emulator-express-debug-run?view=vs-2022)
- **Description**: A lightweight tool to run and debug Azure Cloud Services locally.
- **Key Features**:
  - Does not require administrative privileges.
  - Provides a seamless local development experience.
- **Use Cases**: Local debugging and testing of Azure cloud applications.

### [LocalSandbox](https://github.com/mxsdev/LocalSandbox)
- **Description**: A focused emulator for Azure Service Bus, with plans to expand support to other Azure services.
- **Key Features**:
  - Enables offline development and testing.
  - Community-driven development.
- **Use Cases**: Testing Azure Service Bus solutions locally.

---

## Google Cloud Platform (GCP) Emulators

### [FullStory's GCP Emulators](https://github.com/fullstorydev/emulators)
- **Description**: High-quality emulators for GCP services such as Bigtable and Cloud Storage.
- **Key Features**:
  - Provides offline emulation of select GCP services.
  - Simplifies local development workflows.
- **Use Cases**: Testing GCP applications without live cloud resources.

### [Pomerium's GCP Emulators](https://github.com/pomerium/gcpemulators)
- **Description**: A fork of FullStory's emulators, offering additional functionality for GCP services.
- **Key Features**:
  - Provides local replicas of GCP services.
  - Reduces cloud dependency during development.
- **Use Cases**: Offline development and debugging of GCP-based applications.

### [Cloud Spanner Emulator](https://github.com/GoogleCloudPlatform/cloud-spanner-emulator)
- **Description**: Provides a locally-running, emulated instance of Cloud Spanner for development and testing.
- **Key Features**:
  - Simulates Cloud Spanner API locally.
  - Enables cost-effective local development.
- **Use Cases**: Testing applications that rely on Cloud Spanner.

---

## Oracle Cloud Infrastructure (OCI) Emulators

### [OCI Emulator](https://github.com/cameritelabs/oci-emulator)
- **Description**: An open-source emulator that replicates some OCI commands for local development.
- **Key Features**:
  - Implements basic Oracle Cloud API endpoints.
  - Built using Python and Flask.
- **Use Cases**: Testing applications that interact with OCI APIs locally.

### [Oracle Database Appliance (ODA) Simulator](https://docs.oracle.com/en/engineered-systems/oracle-database-appliance/19.21/dalab/setting-oracle-database-adaptive-simulator.html)
- **Description**: Simulates an Oracle Database Appliance environment for testing and management tasks.
- **Key Features**:
  - Enables deployment, management, and patching simulations.
  - Container-based simulator.
- **Use Cases**: Practicing Oracle Database Appliance management in a controlled environment.

### [Oracle NoSQL Cloud Simulator](https://www.oracle.com/downloads/cloud/nosql-cloud-sdk-downloads.html)
- **Description**: A local emulator for Oracle NoSQL Database Cloud Service.
- **Key Features**:
  - Simulates Oracle NoSQL Cloud APIs locally.
  - Provides an environment for debugging and testing.
- **Use Cases**: Local development of NoSQL database applications for Oracle Cloud.

---

## Serverless Emulators

### [AWS SAM Local](https://github.com/aws/aws-sam-cli)
- **Description**: A tool for testing AWS Lambda functions locally.
- **Key Features**:
  - Simulates the AWS Lambda runtime environment.
  - Supports API Gateway emulation.
- **Use Cases**: Local testing of serverless applications.

### [Serverless Framework Offline](https://github.com/dherault/serverless-offline)
- **Description**: Emulates serverless environments for local development.
- **Key Features**:
  - Supports AWS Lambda and API Gateway emulation.
  - Integrates with the Serverless Framework.
- **Use Cases**: Offline development of serverless functions.

---

## Networking and Observability

### [GNS3](https://gns3.com/)
- **Description**: A network emulator for designing and testing virtual networks.
- **Key Features**:
  - Supports cloud network emulation.
  - Integrates with Docker and virtual appliances.
- **Use Cases**: Simulating cloud networking environments.

### [Prometheus Local](https://prometheus.io/)
- **Description**: Local setup for cloud-native monitoring workflows.
- **Key Features**:
  - Supports cloud monitoring emulation.
  - Provides real-time metrics and alerting.
- **Use Cases**: Testing observability solutions locally.

---

## Other Emulators

### [v86](https://github.com/copy/v86)
- **Description**: An x86 PC emulator and x86-to-WASM JIT running in the browser.
- **Key Features**:
  - Runs a full operating system in the browser.
  - Supports various x86 emulation scenarios.
- **Use Cases**: Browser-based testing of x86 architectures.

### [iSH](https://github.com/ish-app/ish)
- **Description**: A Linux shell for iOS.
- **Key Features**:
  - Provides a minimal Linux shell environment on iOS.
  - Runs Alpine Linux natively.
- **Use Cases**: Experimenting with Linux commands and applications on iOS devices.

---

## Contributing

Contributions are welcome! If you know of any cloud emulators that should be included in this list, feel free to open an issue or submit a pull request.

To contribute:
1. Fork this repository.
2. Add your contribution to the appropriate section.
3. Submit a pull request with a clear description of your changes.

---

## License

[MIT](LICENSE)

---

Happy developing! 🚀

