# Devolut utils 

This Docker image is designed with a set of essential tools to facilitate troubleshooting in Kubernetes clusters. 

# Usage and tools 
The image, built on Alpine Linux 3.19, includes the following tools:

curl: A command-line tool for making HTTP requests, useful for testing connectivity and retrieving information from Kubernetes APIs.

iputils: Provides a collection of utilities for basic network troubleshooting, including tools like ping and traceroute.

busybox-extras: A lightweight version of BusyBox with additional utilities, offering various essential commands for system debugging.

wget: Enables the retrieval of files and resources from the web, aiding in fetching necessary files for diagnostics.

net-tools: Includes classic networking tools like ifconfig and netstat, helpful for inspecting network configurations within the Kubernetes environment.

bind-tools: Offers DNS-related utilities like dig, aiding in troubleshooting DNS resolution issues within Kubernetes clusters.

postgresql-client: Allows interaction with PostgreSQL databases, assisting in diagnosing database-related problems.

mariadb-client: Provides tools to interact with MariaDB databases, facilitating troubleshooting of database-related issues.

aws-cli: The AWS Command-Line Interface, useful for troubleshooting and interacting with AWS resources if your Kubernetes setup involves AWS services.
