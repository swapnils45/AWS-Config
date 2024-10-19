# AWS-Config

### 🛡️ Elevating Cloud Compliance with AWS Config! 🚀

Thrilled to share my latest project where I harnessed the power of **AWS Config** to ensure our EC2 instances are fully compliant with monitoring standards! 

🔍 **Why It Matters**: In today’s cloud-centric world, maintaining compliance is crucial for security and performance. This project not only reinforces our security posture but also optimizes our cloud resources.

### Here’s How I Did It:

1. **Kickoff with AWS Config**: 
   - Set up AWS Config and configured a delivery channel to keep track of our configuration history in S3.

2. **Crafting a Custom Rule**: 
   - Created a rule named "Monitoring for EC2 Instances" to check monitoring status.
   - Leveraged AWS Lambda to automate compliance checks—if monitoring isn’t enabled, we know right away!

3. **Continuous Monitoring**: 
   - With the rule in place, AWS Config continuously evaluates our instances, ensuring we catch any non-compliance swiftly.

4. **Proactive Alerts**: 
   - Automated alerts for non-compliant instances help us take immediate action, ensuring our environment remains secure and efficient.

🌟 **Key Takeaway**: Embracing AWS Config empowers us to proactively manage compliance and enhances our cloud governance strategy.

If you're interested in cloud compliance, automation, or AWS solutions, let’s connect!.


Don't forgot to add the rules to IAM if you are using a IAM user.

AWSLambdabasicexecution
Cloudwatchfullaccess
AWSEC2fullaccess
AWS_configrole
AWSCloudtrail_Fullaccess.
