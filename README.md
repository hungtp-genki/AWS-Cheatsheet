# AWS-Cheatsheet

## The fundamentals

### Badic knownledge

#### Global infrastructure

##### Regions và Zones

- **Regions**: Region là vùng mà Amazon đặt những data center của họ trong ở đó, có thể xem như trụ sở hay quận khu dùng cho cloud computing. Có thể xem các vùng khả dụng ở đây [Amazon Regions](https://aws.amazon.com/about-aws/global-infrastructure/regions_az/)
- **Availability Zones (AZ)**: Có thể là một hoặc một cụm các data center vận hành cloud computing, một region có thể có một hoặc nhiều AZ trong đó, khi bạn xác định được vùng mình muốn sử dụng bạn sẽ thấy được cá AZ khả dụng trong vùng đó.
- **Edge Location**: Là các vị trí trung gian, lưu trữ và nhận request từ người dùng, giúp tăng tốc cho việc xử lí thông tin cho hệ thống AWS.

Để dễ hiểu, có thể tượng tượng một ngày nào đó Amazon sẽ đặt cơ sở hạ tầng tại Việt Nam và chọn ra ba vùng (region) là Băc Bộ, Trung Bộ, Nam Bộ để đặt các trung tâm dữ liệu (data center). Tại Nam Bộ sẽ đặt 3 trung tâm dữ liệu, một ở HCM, một ở Cà Mau, một ở An Giang và thiết lập mỗi trung tâm dữ liệu thành một AZ, vậy region Nam Bộ sẽ có 3 AZs.

### The services

#### Elastic Compute Cloud (EC2)

##### EC2 là gì?

- OS: Amazon Machine Image (AMI)
- Storage/Disk/Volume: Elastic Block Store (EBS)
- Network: Elastic Network Interface (ENI)
  - Private IP
  - Public IP
- Connection:
  - Security Group
- Tính năng khác trong EC2:
  - Auto Scaling
  - Load balancing

##### Làm sao để tạo một con EC2 (EC2 instance)?

#### Amazon Lambda

#### Simple Storage Service (S3)

#### Database services

#### Relational Database Service (RDS)

#### Amazon DynamoDB

#### Amazon Redshift

#### Amazon Elastic Cache

#### Virtual Private Cloud (VPC)

#### Amazon Route 53

#### Amazon CloudFront

#### Identity and Access Management (IAM)

#### Amazon CloudFormation

#### Amazon CloudTrail

#### Amazon CloudWatch

#### Amazon CodeDeploy

#### Amazon Simple Notification Service (SNS)

#### Amazon Simple Email Service (SES)

## Architecture Principles ❌ ❌ ❌

## Question and answer
