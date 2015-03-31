# redis-basic

**Step 1**: [Download](http://redis.io/download) Redis 


**Step 2**: Install Redis. If on a Mac/Linux box, go:

    $ wget http://download.redis.io/releases/redis-2.8.19.tar.gz
    $ tar xzf redis-2.8.19.tar.gz
    $ cd redis-2.8.19
    $ make
    $ make test
    
**Step 3**: Run `src/redis-server` which should start your Redis server locally.

**Step 3**:

Open a new terminal window, `cd` to the code directory of this repo and run:

`npm install`

**Step 4**:

Once completed, then run:

`node example.js'

You should see output in the console of Redis commands being run.