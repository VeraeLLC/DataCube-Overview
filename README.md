# DataCube-Overview

# VeraeLLC's Blockchain Timestamping Service

## Project Description

**VeraeLLC's Blockchain Timestamping Service** is designed to provide a secure and verifiable method for timestamping digital content. It leverages blockchain technology to ensure that once data is timestamped, its existence at a given time can be proven indefinitely. This service is particularly useful for:

- **Record Keeping**: Legal documents, patents, or any official records.
- **Intellectual Property**: Proving the creation date of artistic works.
- **Data Integrity**: Ensuring that data has not been altered since it was timestamped.

## Project Overview

This project implements a minimalistic blockchain for timestamping purposes with the following components:

- **Blockchain Core**: Using Go for creating a blockchain where each block contains the hash of the data being timestamped along with a timestamp.
- **API Layer**: HTTP endpoints for user interaction, including timestamping data and health checks.
- **Multihash Support**: Flexibility to use different hashing algorithms through the multiformats/multihash library.
- **Local Storage**: JSON Lines format for storing blockchain data and logs locally, with future plans for database integration.
- **Docker Support**: For easy deployment and development.

### Features

#### Completed:

- **Blockchain Implementation**: A basic blockchain with support for multihash.
- **HTTP Server**: Handles requests for timestamping and health checks.
- **Configuration Management**: YAML configuration for server settings, storage, and security.
- **Authentication**: Simple JWT authentication to protect the API.
- **Basic Queueing**: Uses Go channels for request handling simulation.
  
#### In Progress or Planned:

- **Database Integration**: Moving from file storage to a scalable database.
- **Advanced Security**: HTTPS, improved JWT handling, and additional security features.
- **Error Handling and Logging**: More detailed error messages and structured logging.
- **Testing**: Comprehensive unit and integration tests.
- **User Interface**: A web frontend for easier user interaction.

## Getting Started


Access to private repos is required


### Prerequisites

- Go (version 1.18 or later)
- Docker (for containerization)
- Git (for version control)

### Installation

1. **Clone the repository**:
   ```sh
   git clone git@github.com:VeraeLLC/timestamping-service.git
   cd timestamping-service


