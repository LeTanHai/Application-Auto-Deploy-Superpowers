### Project Submission

The project incluses:

- A text file named `urls.txt` including:
  1. Public Url to GitHub repository (not private) [URL01]
  2. Public URL for your S3 Bucket (aka, your green candidate front-end) [URL02]
  3. Public URL for your CloudFront distribution (aka, your blue production front-end) [URL03]
  4. Public URLs to deployed application back-end in EC2 [URL04]
  5. Public URL to your Prometheus Server [URL05]
- Your screenshots in JPG or PNG format, named using the screenshot number listed in the instructions. These screenshots should be included in your code repository in the root folder.
  1. Job failed because of compile errors. [SCREENSHOT01]
  2. Job failed because of unit tests. [SCREENSHOT02]
  3. Job that failed because of vulnerable packages. [SCREENSHOT03]
  4. An alert from one of your failed builds. [SCREENSHOT04] [SCREENSHOT04-1]
  5. Appropriate job failure for infrastructure creation. [SCREENSHOT05]
  6. Appropriate job failure for the smoke test job. [SCREENSHOT06]
  7. Successful rollback after a failed smoke test. [SCREENSHOT07]  
  8. Successful promotion job. [SCREENSHOT08]
  9. Successful cleanup job. [SCREENSHOT09]
  10. Only deploy on pushed to `master` branch. [SCREENSHOT10]
  11. Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. [SCREENSHOT11] [SCREENSHOT12] [SCREENSHOT13]
  12. Provide a screenshot of an alert that was sent by Prometheus. [SCREENSHOT14] [SCREENSHOT15] [SCREENSHOT16]

- The presentation file "presentation.pdf"

### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### License

[License](LICENSE.md)
