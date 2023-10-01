## DOCUMENTAÇÃO

```
acesse após o projeto iniciado
http://localhost:5555/swagger-ui/index.html

```

### No banco de dados mysql crie

- Nome do banco de dados : vollmed_api
- nome da tabela: medicos

### para o post(cadastro)

````
{
"nome": "Rodrigo Ferreira",
"email": "rodrigo.ferreira@voll.med",
"crm": "123456",
"especialidade": "ORTOPEDIA",
"endereco": {
    "logradouro": "rua 1",
    "bairro": "bairro",
    "cep": "12345678",
    "cidade": "Brasilia",
    "uf": "DF",
    "numero": "1",
    "complemento": "complemento"
    }
}
````