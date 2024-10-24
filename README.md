# EC2WEBSERVERDEPLOYMENT-AUTOMATIONTASK

1.AWSSetup and Instance Management:
  1. Log in to the AWS Management Console:
  - Go to [https://aws.amazon.com/](https://aws.amazon.com/)
  - Enter your credentials and sign in.

  2. Navigate to the EC2 Service:
  - Search for "EC2" in the search bar.
  - Select the EC2 service.

  3. Launch an Instance:
  - Click "Launch Instance."

  4. Choose an AMI (Amazon Machine Image):
  - Select "Amazon Linux 2" for the first instance.
  - Select "Ubuntu Server" for the second instance.

  5. Configure Instance Details:
  - Choose "t2.micro" for both instances.
  - Create or select a key pair.
  - Adjust storage size if needed.
  - Add tags (optional).

  6. Security Groups:
  - Create a new security group or use an existing one.
  - Configure security group rules.

  7. Review and Launch:
  - Review the configuration.
  - Click "Launch Instances."

  8. View Instances:
  - View the instances in the EC2 dashboard.

  9. Connect to Instances:
  - Use SSH to connect to the instances.


2. Instance Management:
      Managing EC2 Instances
      Starting, Stopping, Restarting, and Terminating Instances

      1)Starting:
      Navigate to EC2 dashboard.
      Select instance.
      Click "Start."

      2)Stopping:
      Navigate to EC2 dashboard.
      Select instance.
      Click "Stop."
      Data preserved.

      3)Restarting: 
      Navigate to EC2 dashboard.
      Select instance.
      Click "Restart."
      Can resolve minor issues.

      4)Terminating:
      Navigate to EC2 dashboard.
      Select instance.
      Click "Terminate."
      Caution: Deletes data permanently.

   ##Recreating Instances

1.Create new instance:
   * Launch new instance using same AMI.
   * Configure with same settings.
     2.Copy data (optional):
   * Use `scp` or `rsync` to copy files over SSH.
3. **Configure new instance:**
   * Install software, set up configurations.

**Reinforcing Instance Management Skills**

* **Practice regularly:** Experiment with starting, stopping, restarting, and terminating instances.
* **Create different scenarios:** Try recreating instances with different configurations and use cases.
* **Consider automated management:** Explore tools like AWS CloudFormation or Ansible.
* **Learn about instance lifecycle states:** Understand the different states an instance can be in (running, pending, stopping, etc.) and how to transition between them.
