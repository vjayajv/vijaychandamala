---
layout: default
---

# COMMANDS,SCRIPTS AND STUFF

## ES-clustering
-----------------
cluster.name: "docker-cluster"
network.host: 0.0.0.0
node.name: master
node.master: true
node.data: true
http.port: 9200
discovery.zen.ping.unicast.hosts: ["node1", "node2","master"]
discovery.zen.minimum_master_nodes: 1
  xpack.license.self_generated.type: basic

  
  
## BASH if regexp matching
-------------------------

if [[ $a =~ ^.*omestring ]]; 
then   
  echo "do something" 
else if [[ $a =~ ^somestrin.*$ ]]; 
then   
  echo "something else" 
else   
  echo "none of those" 
fi 
fi  

## Run any one of the following command on Linux to see open ports:
-----------------------------------------------------------------
  
sudo lsof -i -P -n | grep LISTEN
sudo netstat -tulpn | grep LISTEN
sudo lsof -i:22 ## see a specific port such as 22 ##
sudo nmap -sTU -O IP-address-Here
  
  
## Never ask for password
------------------------
  
username ALL=(ALL) NOPASSWD: ALL
  

## ES read-only error
--------------------
  
ES indices turn to read-only mode when there's no space left on the host machine.
clearing space alone won't fix the issue, running this will instead.
  
curl -XGET localhost:9200/_cat/indices?pretty >test.txt
readarray -t list <<< "$(cat test.txt | awk '{ print $3 }')"
for (( i=0; i<${#list[@]}; i++ )); do curl -X PUT "localhost:9200/"${list[i]}"/_settings" -H 'Content-Type: application/json' -d'{"index.blocks.read_only_allow_delete": null}}'; done
printf "\nRead-only-allow-delete set to null for following indices\n  --------------------------------------- \n"
printf "%s\n" "${list[@]}"
  

  
## REDIS NO-PASSWORD SET ERROR
-----------------------------
  
docker exec -it redis bash
cd tmp && mkdir dbfile && redis-cli
CONFIG GET requirepass
config set requirepass 2Vv2d4&A?5aZjb4v&fq@
auth 2Vv2d4&A?5aZjb4v&fq@
CONFIG GET requirepass
CONFIG SET dir /tmp/dbfile/
CONFIG SET dbfilename temp.rdb
BGSAVE  
