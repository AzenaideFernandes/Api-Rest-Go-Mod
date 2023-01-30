# Api-Rest-Go-Mod
Api Rest em linguagem Go <br>
Para executar digite: go run .(Subir o servidor) <br>
Para enviara uma requisição - digite: curl http://localhost:8080/albums <br> <br>
Para adidionar um novo item - digite as linhas abaixo: <br>
curl http://localhost:8080/albums \ <br>
    --include \ <br>
    --header "Content-Type: application/json" \ <br>
    --request "POST" \ <br>
    --data '{"id": "...","title": "...","artist": "...","price": 49.99}' (preencher os dados) <br>
    Para fazer uma requisição por ID - digite: curl http://localhost:8080/albums/ID ( substituir o id) <br>
    
