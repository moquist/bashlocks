bashlocks
=========

Locks. For bash on Linux.

### Dependencies ###
Depends on Linux's /proc/.

### Useful for cron ###
Put ```liblocks``` and ```lock-exclusive``` both in your ```/usr/local/bin/``` and you can safely put sometimes-long-running jobs in cron without worrying about them trampling each other.

Example usage: ```lock-exclusive /tmp/mylockfile.lock some-long-job.sh```

### Useful for general locking needs ###
```liblocks``` is just a library used by ```lock-exlusive```; ```liblocks``` can be sourced in your own scripts and used for other types of locks.

See ```liblocks``` for more examples.
