# ironLaravel

In order to use [IronMq v3](http://dev.iron.io/worker/reference/api/) with Laravel 4, you will need to make the following changes:
<ul>
<li>Update IronMQ version in composer.json to <code>iron-io/iron_mq": "4.*”</code></li>
<li>Update the host in app/config/queue.php the apporiate v3 host</li>
<li>In the vendor\laravel\framework\src\Illuminate\Queue\ directory, change replace thes files with the files in this directory:<ul>
  <li>IronConnector.php
  <li>IronJob.php
  <li>IronQueue.php</li></li> </ul></ul>

