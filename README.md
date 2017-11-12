# Remote-Access-to-IPython-Notebooks-via-SSH

    $ ipython notebook --no-browser --port=8889
    
on your local terminal , write
    
    $ssh -N -f -L localhost:8888:localhost:8889 remote_user@remote_host
    
And then, type in address bar 

localhost:8888
