#to check for port availability  
telnet 127.0.0.1 11434  
telnet 127.0.0.1 3000

#to start  
docker compose up -d

#to check logs  
docker logs -f ollama
docker logs -f open-webui

#to access ollama using openwebui  
http://localhost:3000/  

#to stop  
docker compose stop

#to restart with new data  
docker compose down --volumes  
