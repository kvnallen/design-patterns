Repository Pattern
=====

Por que utilizamos repositórios?

Pontos Positivos:

	* Evita duplicações;
	* Provê uma melhor separação de responsabilidades (domínio é responsável pela lógica, o repositório por se comunicar com o banco ex);
	* Desacopla a camada de visualização do framework
	* Facilita os testes (já que vc pode testar apenas um método do repositório sem precisar mocar todo o controller ex);
	* Simplifica a leitura do código e da intenção;


Pontos Negativos:

	* Aumenta a complexidade do seu software (not so much);


Quando utilizar?

	* Quando o projeto for um pouco maior e houver duplicação de código;


Alternativas:

	* Extension Methods;
	* Métodos específicos (extrair para um método comum);
