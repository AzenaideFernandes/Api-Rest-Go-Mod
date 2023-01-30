# Api-Rest-Go-Mod
Api Rest em linguagem Go <br>
Para executar digite: go run .(Subir o srvidor) <br>
Para enviara uma requisição - digite: curl http://localhost:8080/albums <br>
Para adidionar um novo item - digite as linhas abaixo: <br>
curl http://localhost:8080/albums \ <br>
    --include \ <br>
    --header "Content-Type: application/json" \ <br>
    --request "POST" \ <br>
    --data '{"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}' <br>
    
