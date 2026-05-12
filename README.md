# servidor-ia
* Prender con docker compose up -d
* Instalar ollama y elegir el modelo de ia que quieras poner en el docker
## IMPORTANTE
- Tiene que ser instalado dentro del docker si no no funcionara 
    - docker exec -it ollama pull modelo 
    - ej docker exec -it ollama ollama pull qwen2.5:0.5b
    - docker exec -it ollama ollama run qwen2.5:0.5b
* Ollama escucha por el puerto 11434 y el servidor utiliza el puerto 80