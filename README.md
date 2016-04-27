# ansible-role-cfn-s3-bucket
| Variable        | Required           | Default  |
| ------------- |:-------------:| -----:|
| s3_bucket_name      | true |  |
| s3_bucket_region | true | |
| s3_bucket_stack_name | false | <s3_bucket_name>-stack |
| s3_bucket_build_dir     | false      |   "build"  |
| s3_bucket_template_dir | false     | <s3_build_dir>   |
