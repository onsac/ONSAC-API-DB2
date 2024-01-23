
<h3 align="center"> ONSAC API DB2</h3>


# Parametros de PayLoad - aio-bot-put-sienge-baixa-titulos

```sh
{
    "env"        : "sienge-hmg-db2",
	"template"   : "aio-bot-put-sienge-baixa-titulos",
 	"parametros" : { 
      "empresa" : "1000",
      "conta"   : "FIDC-001",
      "titulo"  : "249008",
      "parcela" : "1"
	  }
  }
```
# Parametros de PayLoad - aio-bot-put-sienge-movimentacao-bancaria

```sh
 {
    "env"         : "sienge-hmg-db2",
	"template"    : "aio-bot-put-sienge-movimentacao-bancaria",
 	"parametros"  : { 
       "empresa"          : "1000",
       "conta"            : "FIDC-001",
       "titulo"           : "249008",
       "operacao"         : "1",
       "documento"        : "QFID",
       "numero_documento" : "061223-FIDC01-00001",
       "parcela"          : "1",
       "valor"            : "62.932,68",
       "centro_custo"     : "10001",
       "plano_financeiro" : "2030104"
	   }
  }
```
