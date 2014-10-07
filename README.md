bashlocks
=========

Locks. For bash on Linux.

Depends on /proc/!

Put liblocks and lock-exclusive both in your /usr/local/bin/ and you can safely put sometimes-long-running jobs in cron without worrying about them trampling each other.

Example usage: ```lock-exclusive /tmp/somelockfile.lock some-long-job.sh```

See ```lock-exclusive``` and ```liblocks``` for more examples.
