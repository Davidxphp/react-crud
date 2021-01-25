# react-crud

# Back-End com json-server

## 1 - json-serve - como bankend

- criar crud
   - cria uma pas backend
   
   - no terminal - cd crud/backend
   
   - npm init -y
   
      - vai gerar o package-json
      
    - npm i --save json-server@0.13.0 -E
    
       - vai salvar e criar depencias para garantir compatibilidade
       
     - na pasta backend
     
        - criar db.json
          - criar alguns registros para teste
          
          - {
          - "users": [
           {
                "id": 1,
                 "name": "Arthur Oliveira",
                 "email": "aoliveira@cod3r.com.br"
                  },
              {
                 "id": 2,
                  "name": "Maria Julia da Silva",
                  "email": "mjds@empresa.com"
             }
          ]
         - }
         
         
   - no arquivo - package-json
   
   - alterar o script teste por :
   
   -    "start": "json-server --watch db.json --port 3001"
   
   ### npm start
    -  rodar o servidor api rest full com json-serve
    
   # Front-End
   
   - create-react-app frontend
   
   - cd frontend
   
   - yarn start
   
   ### Instalar dependecias para frontend
   
     - "axios": "0.21.1",
     - "bootstrap": "4.6.0",
     - "font-awesome": "4.7.0",
     
     
   
   
