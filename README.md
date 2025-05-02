# aws-s3-cloudwatch-logger
This AWS lab demonstrates how to automatically log S3 upload events to CloudWatch using a Lambda function. The function is triggered by an S3 event and captures file details like filename, size, and timestamp.
# Lab 7 – S3 to CloudWatch Logger

This AWS lab demonstrates how to trigger a Lambda function using S3 events to log file uploads to CloudWatch.

### 🧰 Services Used
- AWS Lambda
- Amazon S3
- Amazon CloudWatch

### 📝 What It Does
When a file is uploaded to an S3 bucket, the Lambda function is triggered. It logs:
- File name
- File size
- Upload timestamp

These logs are sent to CloudWatch Logs for monitoring.

### 📸 Screenshots
- Lambda Function Code ![Screenshot 2025-05-02 195102](https://github.com/user-attachments/assets/c85338c7-ad3b-47ef-8f0e-956825b52878)

- S3 Trigger Setup ![Screenshot 2025-05-02 195346](https://github.com/user-attachments/assets/e3f99c3f-8653-4b52-81b4-521be6a56dd2)
![Screenshot 2025-05-02 195254](https://github.com/user-attachments/assets/43aae54c-953c-4186-8331-9fd4f80fc5ec)

- CloudWatch Log Stream ![Screenshot 2025-05-02 194821](https://github.com/user-attachments/assets/1360f5d5-d93c-478c-9abf-4dbb64fca480)


