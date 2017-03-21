TecWEBII
========

Arquivos de Thiers


# Padronização de código Serveloja

| DATA       | DESCRIÃÇO          | RESPONSÁVEL | 
|------------|--------------------|-------------|
| 21/03/2017 | Criação/Publicação | Rafael      |
|            |                    |             |

1. Usar PascalCase para nomes de classes e métodos

2. Usar CamelCase para variável e parâmetros de métodos

3. Usar o prefixo 'I' com CamelCase para nomear interfaces : IEntidade

4. Utilize nomes significativos para nomear variáveis. Não use abreviações.

5. Não use nome de variáveis com um único caractere como i, n, c, s, t. Prefira usar nomes como : indice, temp, contador, etc. A exceção seria a utilização de i para os contadores em laços for/next.

6. Não utilize sublinhado para variáveis locais.Ex: _email 

7. Não utilize nomes de variáveis que são usadas como palavras chaves. 

8. Utilize o prefixo apropriado para cada elemento de interface usado. 

> Ex: Principais controles e abreviações sugeridas:

| Controle    	| Prefixo |
|---------------|---------|
| Label         | lbl     |
| TextBox     	| txt     |
| DataGrid    	| dtg     |
| Button 	    | btn     |
| Hyperlink   	| hlk     |
| DropDownlist 	| ddl     |
| ListBox 	    | lst     |
| DataList    	| dtl     |
| CheckBox    	| chk     |
| RadioButton 	| rdo     |
| Image       	| img     |
| Panel       	| pnl     |
| Table       	| tbl     |


> Usando CamelCase e PascalCase

Poderiamos dizer que atualmente a grande maioria dos desenvolvedores das linguagens C# e VB .NET usa uma mistura de CamelCase com PascalCase.

|  Estrutura                    | Nomenclatura              | Exemplo           | 
|-------------------------------|---------------------------|-------------------|
| Classe                        | Pascal                    | PessoaJuridica    | 
| Interface                     | I + Pascal                | ICliente          | 
| Método Público , Propriedades | Pascal                    | NomeCompleto()    | 
| Método Privado                | Camel Case                | calculaDesconto() |     
| Variável Pública              | Pascal                    | SobreNome         | 
| Variável Privada              | Camel Case                | impostoPredial    |  
| Variável Glocal               | Camel Case com sublinhado | _email            | 
| Constantes             	    | Maiúsculas com sublinhado | VALOR_DESCONTO    |  
