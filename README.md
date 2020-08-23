# cloudresume
Cloud Resume project instructions can be found here: 
https://cloudresumechallenge.dev/instructions/

This project is designed to demonstrate basic understanding of how to architect a simple serverless application using a wide array of tools.

The front end client view is created using HTML and bootstrap.

The front end files are stored and served using Amazon S3. 

To add a layer of security, a Cloudfront distribution is created to be the entry point for external users and will handle retrieving the S3 files. 

Route 53 was used to purchase and connect a domain name to the Cloudfront distribution.

Codepipeline was used to monitor my github repo where I push new updates. 
Codepipeline will automatically deploy any changes from my repo into the S3 bucket hosting the website.

