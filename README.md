# S3 BASH Back Up

A simple BASH script to backup specified directories to AWS S3.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for personal use and testing purposes.

### Prerequisites

AWS CLI with an IAM user that has authorization to programaticaly access AWS services.

```
The command <aws s3 ls> should return a list of s3 buckets with no errors.  If no buckets exist then the response will be null.
```

### Installing

A step by step series of examples that tell you how to get started.

Step 1:

```
Have S3BackUp.sh and S3PathMaster.txt in the same directory.
```

Step 2:

```
In S3PathMaster.txt replace "newcomer.technology" with the desired S3 bucket name.
Add as many "PATH:" lines as desired.  Ensure that the full path is entered and the directores will be backed up recursively.
Set the LASTUPDATETIME time to zero.
```
Step 3:

```
Execute S3BackUp.sh in a termial from within the same path as the script.
```


## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

1.0 

## Authors

* **Alan Newcomer** - *Initial work* - [alangixxer](https://github.com/alangixxer)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


