# Api-Rest-Go-Mod
Api Rest em linguagem Go usando a Framework Gin <br>
Para executar digite: go run .(Subir o servidor) <br>
Para enviar uma requisição - digite: curl http://localhost:8080/albums <br> <br>

Para adidionar um novo item - digite as linhas abaixo: <br>
curl http://localhost:8080/albums \ <br>
    --include \ <br>
    --header "Content-Type: application/json" \ <br>
    --request "POST" \ <br>
    --data '{"id": "...","title": "...","artist": "...","price": 49.99}' (preencher os dados) <br><br>
    
    Para fazer uma requisição por ID - digite: curl http://localhost:8080/albums/ID ( substituir o id) <br>
    
    Para enviar uma requisição para visualizar itens incluidos - digite as linhas abaixo: <br>    
    curl http://localhost:8080/albums \ <br>
    --header "Content-Type: application/json" \ <br>
    --request "GET" <br>
    
    
