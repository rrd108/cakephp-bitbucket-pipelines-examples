# CakePHP 3 Bitbucket Pipelines examples

Examples for CakePHP 3 projekts for Bitbusket pipelines.

I am not a docker expert, so any suggestion are welcome :) I am pretty sure, this is just a working solution but far from optional.

## bitbucket-pipelines-MySQL

An example file for a CakePHP project which uses MySQL for testing. You should have the same `username`, `password` and `database` seetings in your `app.php.default` file, than what are defined here for the MySQL enviroment.

For the MySQL `host` you should use `127.0.0.1` instead of `localhost`.
