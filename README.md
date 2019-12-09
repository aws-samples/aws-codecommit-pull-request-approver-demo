## PullRequestApproverBlogDemo

This is a starter Java project that includes the code required to integrate [SonarQube](https://www.sonarqube.org/) with [AWS CodeCommit approval rules](https://aws.amazon.com/about-aws/whats-new/2019/11/aws-codecommit-enables-enforcing-approval-rule-workflows-for-pull-requests/), and is meant to be used alongside the blog post *Integrating SonarQube as a pull request approver on AWS CodeCommit*. This project builds using [Apache Maven](https://maven.apache.org/).

The project includes an Amazon CloudFormation template to help provision resources for this demo, as well as an AWS CodeBuild buildspec.yml which will facilitate communication betwen your SonarQube instance and AWS CodeCommit.

## Dependencies

- [SonarScanner for Maven](https://docs.sonarqube.org/latest/analysis/scan/sonarscanner-for-maven/)
- [JUnit](http://junit.sourceforge.net/junit3.8.1/)

## License

This library is licensed under the MIT-0 License. See the LICENSE file.
