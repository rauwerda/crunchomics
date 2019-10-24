Bootstrap:docker  
From:ubuntu:16.04

%labels
MAINTAINER HR

%environment
RAWR_BASE=/code
export RAWR_BASE

%runscript
echo "Tqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqq" 
exec /bin/bash /code/rawr.sh "$@"  



%post  
echo "This section happens once after bootstrap to build the image."  
mkdir -p /code  
apt-get install vim  
echo "RoooAAAAR" >> /code/rawr.sh
chmod u+x /code/rawr.sh  
