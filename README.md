#to check for port availability, else update the same in the compose file  
```telnet 127.0.0.1 11434```  #for ollama  
```telnet 127.0.0.1 3000```   #for openwebui  

#to start  
```docker compose up -d```

#to check logs  
```docker logs -f ollama```  
```docker logs -f open-webui```

#to access ollama using openwebui  
http://localhost:3000/  

#to stop  
```docker compose stop```

#to delete ollama, openwebui and related files/data  
```docker compose down --volumes```
