# K8S

# Introduction
Vamos criar um ambiente K8S com uma API que persiste em um banco

# Getting Started

** Connection String


	"AplicacaoModelo": "Data Source=entidadequalquer-sql-svc, 1433;Initial Catalog=AplicacaoModelo;User ID=sa;Connect        Timeout=30;Encrypt=False;TrustServerCertificate=False;ApplicationIntent=ReadWrite;MultiSubnetFailover=False;MultipleActiveResultSets=true;Password=a7rm551VVXty3j/ahn6z7w=="
	
** Url para consumo da API(POST)
	
	http://localhost:31002/api/EntidadeQualquer
	
** Body para consumo da API 
	
	{
		"Nome":"Eduardo",
		"Sobrenome":"Silva",
		"DataNascimento":"1970-11-23"
	}
 
** Dados para conectar no banco SQL 

	Server Name: localhost:31001
	User: sa 
	Senha: Banco@2022
	
 
