On a fresh machine:

#1 install chef
   
    curl -L https://www.opscode.com/chef/install.sh | bash

#2 run chef-solo:

    chef-solo -c solo.rb -j node.json
