for installing the environment
->install a virtual environment(sudo pip install virtualenv)
->create the virtual environment(virtualenv env)
->enter the virtual environment(source venv/bin/activate)
->install requirements (pip install -r requirement.txt)
->install reddis:$ curl http://localhost:5000/participate?experiment=button_color&alternatives=red&alternatives=blue&client_id=12345678-1234-5678-1234-567812345678
    sudo apt-get update
    sudo apt-get install build-essential
    sudo apt-get install tcl8.5
    wget http://download.redis.io/releases/redis-stable.tar.gz
    tar xzf redis-stable.tar.gz
    cd redis-stable
    make
    make test
    sudo make install
    cd utils
    sudo ./install_server.sh
    sudo service redis_6379 start
->run localhost python file 
    python localhost
->for database entry make a curl request
    $ curl http://localhost:5008/participate?experiment=button_color&alternatives=red&alternatives=blue&client_id=12345678-1234-5678-1234-567812345678
->for dashboard 
    python dashboard
->for client side start the browser from client/examples/browser/index.html
->click on button if you want to perform the on click count
->see the comparision graph of page rendered vs button clicked on dashboard
    