# master-nginx
Learn Nginx By Source Code Analysis

### step 01 - download source code & compile it & run it

This is my first try, and I don't configure it in any specific.

    pwd
    # /Users/frank/ave/nginx


    
    # Download the source code
    git clone https://github.com/nginx/nginx
    
    cd nginx

    # compile it with your prefix if you want or configure it when you run it
    ./configure

    # to run it on my own path and easily to check out, I create a directory.
    make logs

    # create a test.conf file, which base on nginx.conf and I just do some modify to make it know where is my work path. which you can view at this repo.


    # For now, you can run it.
    ./objs/nginx -p /Users/frank/ave/nginx -c conf/test.conf





