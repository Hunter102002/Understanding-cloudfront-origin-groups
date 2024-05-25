# AWS CloudFront Origin Group Configuration for Improved Content Delivery

## Objective

This project aimed to set up and understand AWS CloudFront Origin Groups by configuring an S3 bucket and an EC2 instance as origins for a CloudFront distribution. The project demonstrates skills in configuring CloudFront distributions, setting up redundancy and failover for content delivery, and managing origins using Amazon S3 and EC2.

### Skills Learned

- Amazon S3 Management: Creating and configuring S3 buckets and managing object permissions.
- Amazon EC2 Management: Launching and configuring EC2 instances for web content delivery.
- CloudFront Configuration: Setting up CloudFront distributions and configuring origin groups for redundancy and failover.
- Networking and Security: Managing security groups and access permissions for AWS resources.
- Content Delivery Network (CDN) Management: Understanding and implementing CDN strategies using AWS CloudFront.

### Tools Used

- Amazon S3: For storing static content.
- Amazon EC2: For serving dynamic web content.
- Amazon CloudFront: For setting up the content delivery network with origin groups.
- AWS Management Console: For configuring and managing all AWS resources.


### Outcome

The project successfully demonstrated the setup of an AWS CloudFront distribution with an origin group, allowing content to be served from both an S3 bucket and an EC2 instance. This setup provides redundancy and failover capabilities, ensuring high availability and reliability of content delivery. By completing this project, I showcased skills in CDN configuration and advanced AWS networking.

## Steps

Create an S3 Bucket

<img width="1314" alt="Screenshot 2024-05-22 at 6 01 11 PM" src="https://github.com/Hunter102002/Understanding-cloudfront-origin-groups/assets/98543129/7b7a781f-b531-4d53-a25f-61aa11b013d0">

Upload documents to folder

<img width="800" alt="Screenshot 2024-05-22 at 6 01 52 PM" src="https://github.com/Hunter102002/Understanding-cloudfront-origin-groups/assets/98543129/5196eae7-5ee8-49c3-90b2-0a5cc966cf66">

Make bucket public assessable

<img width="968" alt="Screenshot 2024-05-22 at 6 04 56 PM" src="https://github.com/Hunter102002/Understanding-cloudfront-origin-groups/assets/98543129/edba68e6-da42-410e-8c5e-55b3eafa1761">

Create Cloudfront distribution

<img width="1312" alt="Screenshot 2024-05-22 at 6 06 24 PM" src="https://github.com/Hunter102002/Understanding-cloudfront-origin-groups/assets/98543129/2bd3feb7-85da-4ec9-a626-021c2742116c">

Launch EC2 instance

<img width="1232" alt="Screenshot 2024-05-22 at 6 16 08 PM" src="https://github.com/Hunter102002/Understanding-cloudfront-origin-groups/assets/98543129/9bf53469-00bb-416f-83bb-76cffedbc3c9">

Test public IPV4 Address

<img width="898" alt="Screenshot 2024-05-22 at 6 21 17 PM" src="https://github.com/Hunter102002/Understanding-cloudfront-origin-groups/assets/98543129/b246031d-83ca-4b29-a013-508ff3b56c06">

Add EC2 as the Origin and create Origin Group

<img width="1074" alt="Screenshot 2024-05-22 at 6 25 48 PM" src="https://github.com/Hunter102002/Understanding-cloudfront-origin-groups/assets/98543129/dd66e1c0-47fe-42b9-accb-8a472ae6a810">

Test Origin Group

<img width="693" alt="Screenshot 2024-05-22 at 6 26 28 PM" src="https://github.com/Hunter102002/Understanding-cloudfront-origin-groups/assets/98543129/e1be3b3b-af2f-41b1-ba76-f5d0a9606d2d">

Now test other origin 

<img width="763" alt="Screenshot 2024-05-22 at 6 26 55 PM" src="https://github.com/Hunter102002/Understanding-cloudfront-origin-groups/assets/98543129/c6e695dd-3cca-4103-98a6-3688d053462d">

