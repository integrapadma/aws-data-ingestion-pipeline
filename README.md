# AWS Data Ingestion Pipeline 🌊

![AWS Data Ingestion Pipeline](https://img.shields.io/badge/Version-1.0.0-blue.svg) ![Python](https://img.shields.io/badge/Python-3.8%2B-green.svg) ![AWS](https://img.shields.io/badge/AWS-S3-orange.svg)

Welcome to the **AWS Data Ingestion Pipeline** project! This educational project demonstrates how to build a data ingestion pipeline using AWS S3 and Lake Formation. The focus is on structuring the bronze layer of a Data Lake with Python. 

## Table of Contents

1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Getting Started](#getting-started)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)
9. [Releases](#releases)

## Project Overview

The AWS Data Ingestion Pipeline project aims to streamline the process of ingesting data into a Data Lake. It leverages AWS services, specifically S3 and Lake Formation, to create a robust data architecture. This project serves as an academic exploration into data engineering and data science principles.

The pipeline allows users to:

- Ingest CSV files into S3.
- Transform data using Python and Pandas.
- Store data in Parquet format for efficient querying.

This project is ideal for students and professionals looking to deepen their understanding of data ingestion and lake formation.

## Technologies Used

- **AWS S3**: For data storage.
- **AWS Lake Formation**: For managing data lakes.
- **Python**: For scripting and data manipulation.
- **Pandas**: For data analysis and transformation.
- **Parquet**: For efficient data storage.
- **Boto3**: For AWS service integration.

## Getting Started

To get started with this project, you will need to have the following prerequisites:

1. An AWS account.
2. Python 3.8 or higher installed on your machine.
3. Basic knowledge of AWS services, especially S3 and Lake Formation.
4. Familiarity with Python and data manipulation libraries like Pandas.

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/integrapadma/aws-data-ingestion-pipeline.git
   ```

2. Navigate to the project directory:

   ```bash
   cd aws-data-ingestion-pipeline
   ```

3. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Configure your AWS credentials. You can do this by setting environment variables or using the AWS CLI.

### Usage

To use the data ingestion pipeline, follow these steps:

1. Place your CSV files in the designated input folder.
2. Run the ingestion script:

   ```bash
   python ingest_data.py
   ```

3. The script will upload the CSV files to S3 and convert them to Parquet format.

4. You can monitor the progress and check the output in the specified S3 bucket.

### Contributing

We welcome contributions to this project! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

### Contact

For questions or suggestions, feel free to reach out to the project maintainer:

- **Name**: Your Name
- **Email**: your.email@example.com

### Releases

To download the latest release, visit the [Releases](https://github.com/integrapadma/aws-data-ingestion-pipeline/releases) section. If you want to run a specific file, please download and execute it as instructed in the release notes.

---

Thank you for checking out the AWS Data Ingestion Pipeline project! We hope you find it useful for your data engineering and data science endeavors.