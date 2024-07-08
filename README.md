## AWS Blog Generator

This project showcases an approach to blog creation using AWS services. It leverages the power of Amazon Web Services (AWS) to automatically generate blog content based on user-provided topics.

## Technology Stack

- **AWS Lambda**: In this project, Lambda handles incoming API Gateway requests and invokes the blog generation logic.
- **AWS API Gateway**: It acts as the entry point for users to submit blog topic requests.
- **AWS S3**: To store generated blog content.
- **AWS Bedrock**: Foundation opensource model "meta.llama3-8b-instruct-v1:0" is used.
- **Postman**: To experiment with the API

## Demo Screenshots

### lambda function

<img width="533" alt="Screenshot 2024-07-09 002019" src="https://github.com/kiranmajji1620/blog_generation_aws_bedrock/assets/119588005/403f28a6-3076-4aa3-bbaa-93b0bd9bc1f0">

### API Gateway routes

<img width="629" alt="Screenshot 2024-07-09 002154" src="https://github.com/kiranmajji1620/blog_generation_aws_bedrock/assets/119588005/e96c6afc-ad73-41c3-8c78-eeb5e2899e6e">

### Postman POST request

<img width="634" alt="Screenshot 2024-07-09 001829" src="https://github.com/kiranmajji1620/blog_generation_aws_bedrock/assets/119588005/f171d903-3a75-4245-a337-07d6ef2fcb69">

### Stored data in S3 bucket

<img width="903" alt="Screenshot 2024-07-09 002222" src="https://github.com/kiranmajji1620/blog_generation_aws_bedrock/assets/119588005/c0e04906-32e3-41c6-bd90-7daa66b4656b">
The generated content is downloaded from the s3 bucket and saved in the output.txt file.
