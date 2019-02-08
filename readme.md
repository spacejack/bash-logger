# bash-logger

This is an executable bash wrapper script that launches another executable and adds simple logging to files from stdout and stderr.

Log subdirectories are created by year and month. Eg:

    $APP_LOGS_HOME/2019/01

Each time the script is run two new logfiles will be created, named:

    YYYY-MM-DD.err.log
    YYYY-MM-DD.err.log

where stdout and stderr lines will be timestamped and appended as the app outputs them.
