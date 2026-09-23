# Cloud Storage Types Research

## Comparison of Cloud Storage Types

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| Block Storage | Stores data in fixed-size blocks that can be attached to a virtual machine like a disk drive. | Best for operating systems, databases, and applications that need fast disk access. | AWS EBS |
| File Storage | Stores data as files inside folders and directories that can be shared across systems. | Best for shared files, documents, and applications that need a common file system. | AWS EFS |
| Object Storage | Stores data as objects together with metadata and a unique identifier. | Best for large amounts of unstructured data such as images, videos, backups, and documents. | AWS S3 |

## Why Object Storage is Suitable for the Client

Object Storage is a good choice for the client's photo-sharing application because it is designed to handle large amounts of unstructured data such as user-uploaded images. It can store many files while keeping them accessible through a web-based system, making it suitable for an application that may grow to millions of photos.
