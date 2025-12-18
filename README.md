# Cloud-Sec-AWS
The Fundamentals of AWS Cloud Security

Aws + Linux + Docker

POC 1

Internet
   |
[ Security Group ]
   |
[ EC2 t3-micro - Ubuntu ]
   |
[ Docker ]
   └── Node.js API (container)

Network
- VPC
- Public Assigng ( Instância estará exposta a internet com IP Público)
- New instance with VPN Security for secure connnectios with other machines (instances) 
   - If the instancie isn't be expost to aws server we need to create a VPN Security Instance for security
 
  * Permission Management - AWS AIM
  * Data Encryption - AWS KMS
  * Network Security Control - Amazon VPC
