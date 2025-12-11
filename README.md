# Documentaçao do Modulo de Conexao 
## Descriçao
Este projeto implementa um padrao de conexao segura com o banco de dados, ultilizado Design Patttern para evitar hardcoding

## o que foi feito 
- [x] criaçao do repositorio
- [x] implemntaçao da conexao
- [x] resoluçao de conflitos de merge
- [x] separaçao de configuração 

## Exemplo de uso
Abaixo, o codigo padrao ultilizado pelo arquiteto:


 
``` pyton
# constante de configuraçao 
DB_HOST = "192.168.0.1"

def connectar_banco ():
  """conecta usando a constante definida"""
     return f"conectado ao {DB_host}"
