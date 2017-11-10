# tika-python-lambda
Integrating tika-python into AWS Lambda

Using the documentation from AWS, chrismattmann/tika-python, and upsidetravel/bucket-antivirus-function I created a Lambda Function to scan files from an S3 bucket and integrate the functions from both of the projects.
http://docs.aws.amazon.com/lambda/latest/dg/lambda-python-how-to-create-deployment-package.html#deployment-pkg-for-virtualenv
https://github.com/chrismattmann/tika-python
https://github.com/upsidetravel/bucket-antivirus-function

The main function I needed was the Tika - Detect, but the other functions can be added as well.

You can also set this up in conjunction with the AV scan to create an assembly line of scanning.

License

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
