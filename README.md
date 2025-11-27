# infinispan
inifinispan HA cluster setup


# PUT DATA INTO CACHE
`$ docker compose exec infs1 /bin/bash`  
`$ cd bin/`  
`$ ./cli.sh -c localhost:11222`  
`$ cache <CACHE_NAME>`  
`$ put <KEY> <VALUE>`  

# GET DATA
`$ cache <CACHE_NAME>`  
`$ get <KEY>`  

# PUSH STATE TRANSFER
`$ site push-site-state --cache=<CACHE_NAME> --site=<TARGET_SITE>`  
