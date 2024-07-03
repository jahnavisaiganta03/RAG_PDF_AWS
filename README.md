
# AWS-RAG Application

This application was developed using Docker and Streamlit.

## Overview

The AWS-RAG application utilizes Docker for containerization and Streamlit for creating interactive web applications. It integrates various functionalities related to AWS services and data analysis.

## Features

- **Docker Integration**: Utilizes Docker for containerization, ensuring consistency across different environments.
- **Streamlit Dashboard**: Provides a user-friendly interface powered by Streamlit, allowing interactive data visualization and manipulation.
- **AWS Services**: Integrates with AWS services for tasks such as data storage, retrieval, and analysis.

## Installation

To run this application locally, ensure you have Docker installed. Then, follow these steps:

1. Clone this repository:

   ```
   git clone https://github.com/jahnavisaiganta03/AWS-RAG.git
   ```

2. Build the Docker image:

   ```
   docker build -t pdf-reader-admin .
   ```

3. Run the Docker container:

   ```
   docker run -p 8083:8083 pdf-reader-admin
   ```

4. Access the application in your web browser at `http://localhost:8083`.

## Usage

Once the application is running, you can interact with it through the Streamlit interface. Upload files, perform data analysis, and explore AWS-related functionalities.

## Contributing

Contributions are welcome. For major changes, please open an issue first to discuss what you would like to change.



Feel free to customize this template further based on additional features, specific AWS services used, or any other relevant information about your application.
