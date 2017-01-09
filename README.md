# ironLaravel

In order to use [IronMq v3](http://dev.iron.io/worker/reference/api/) with Laravel 4, you will need to make the following changes:

* Update IronMQ version in composer.json to `iron-io/iron_mq": "4.*”`
* Update the host in app/config/queue.php the apporiate v3 host
* In the vendor\laravel\framework\src\Illuminate\Queue\ directory, change replace thes files with the files in this directory:
  ⋅⋅* IronConnector.php
  ⋅⋅* IronJob.php
  ⋅⋅* IronQueue.php

