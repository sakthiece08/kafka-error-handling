# Kafka Error Handling

This project demonstrates how to handle errors in a Kafka-based application using Spring Boot. It includes retry mechanisms, dead-letter topics (DLT), and validation logic for processing Kafka messages.

## Features

- **Kafka Consumer with Retryable Topics**: Automatically retries message processing a configurable number of times.
- **Dead Letter Topic (DLT)**: Handles messages that fail after all retry attempts.
- **Validation Logic**: Validates incoming messages, including restricted IP address checks.
- **Spring Boot Integration**: Built with Spring Boot for easy configuration and deployment.

## Prerequisites

- Java 17 or higher
- Apache Kafka
- Maven
- Docker (optional, for running Kafka locally)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/sakthiece08/kafka-error-handling.git
cd kafka-error-handling