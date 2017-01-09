# ironLaravel

In order to use [IronMq v3](http://dev.iron.io/worker/reference/api/) with Laravel 4, you will need to make the following changes:

*Update IronMQ version in composer.json to `iron-io/iron_mq": "4.*”`
*Update the host in app/config/queue.php to `"mq-aws-us-east-1-1.iron.io"` instead of `"mq-aws-us-east-1.iron.io"` or 
`"mq-aws-eu-west-1-1.iron.io"` instead of `"mq-aws-eu-west-1.iron.io"`
* In the vendor\laravel\framework\src\Illuminate\Queue\ directory, change replace thes files with the files in this directory:
  **IronConnector.php
  **IronJob.php
  **IronQueue.php
rrr
