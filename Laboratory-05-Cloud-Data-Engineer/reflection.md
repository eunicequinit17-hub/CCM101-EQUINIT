# Mission Reflection

This laboratory helped me understand why object storage is commonly used for applications that need to store a large amount of photos and other files. Unlike traditional block storage, object storage is designed for unstructured data and can organize files as objects with their own metadata and identifiers. For a photo-sharing application that may have millions of images, this type of storage is useful because the files can be stored and accessed separately from the application server.

Using Docker also made deploying MinIO easier for me. Instead of manually installing and configuring many components, I was able to start MinIO using one Docker command. The container also provided an isolated environment for the storage server. I only needed to configure the ports and environment variables before accessing the MinIO Web Console.

A bucket is a storage container used to organize objects in object storage. In this activity, I created a bucket named `client-photos`. I then uploaded a sample file to confirm that the bucket was working properly.

For large enterprise companies, protecting object storage data is very important. They can use multiple copies of data, redundancy, backups, replication, and distributed storage systems. These methods can help keep data available even when a physical server or storage device experiences a failure.

My confidence in using the Linux command line is also improving. At first, commands involving Docker and directories were unfamiliar to me. After completing this activity, I became more comfortable checking containers, creating folders, running commands, and working with files. I also learned that carefully checking command results is important because a small error can affect the deployment. Overall, this laboratory gave me more practical experience with Docker, Linux, and cloud storage.
