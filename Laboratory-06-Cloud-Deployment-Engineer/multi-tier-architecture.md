# Multi-Tier Architecture

## What is a Two-Tier Architecture?

A two-tier architecture is a system that is divided into two main parts: the web/application tier and the database tier. The web/application tier deals with user requests, while the database tier is responsible for storing and managing the data needed by the application.

## The Web/Application Tier

The web/application tier handles the website or user interface and receives requests from users through HTTP. In this laboratory, Nextcloud works as the application that users open using a web browser. It provides the interface for accessing and managing the private cloud storage.

## The Database Tier

The database tier stores the information that the application needs to keep. In this project, MariaDB is used as the database container. It stores data such as user account information and other records used by Nextcloud.

## Why Separate Them?

Keeping the application and database in separate containers makes the system easier to organize and manage. Each container has a specific task, which also makes it easier to update, troubleshoot, or expand the system when needed.
