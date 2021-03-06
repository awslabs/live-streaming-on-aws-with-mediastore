# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.1] - 2021-7-1
### Added
- Updated CFN template for aws-cloudfront-mediastore CDK. 
- MediaStore policy is now retricting to only requests from Amazon CloudFront.
- Updated the README file.
- Dependbot updates to glob-parent and y18n. 

## [1.2.0] - 2020-12-21
### Added
- Updated the source code to build the CloudFormation template using the AWS CDK 

## [1.1.1] - 2020-08-17
### Bugfix
- added permissions for the custom resource to create SSM parameter stores.
- resolved https://github.com/awslabs/live-streaming-on-aws-with-mediastore/issues/2

## [1.1.0] - 2020-06-30
### Added
- Elemental Link as an input option
- changed the MediaLive Encoding segment length from 10 seconds to 4

## [1.0.0] - 2020-04-30
### Added
- CHANGELOG version 1.0.0 release