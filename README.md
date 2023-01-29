# uscan
universal blockchain scan for EVM series 

# Getting Started  

1.Download and build the image

```bash
git clone https://github.com/uchainorg/uscan.git 
cd uscan
docker build -t uscan:latest .
```

2.Run in docker-compose

```bash
docker-compose up -d
```

*docker-compose parameter description*	

| parameter        | description   |  
| --------   | -----  | 
| --rpc_urls      |node ws url  |  
| --db_path      |uscandb path   | 
| --app_title      |   app name   |  
| --unit_display     |   display unit name   |  
| --node_url     |   node http url   |  
