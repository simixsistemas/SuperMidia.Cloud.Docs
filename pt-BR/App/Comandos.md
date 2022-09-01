# Comandos

`Item {código}`: Retorna Select do item.

`Barras {barras}`: Consulta o código de barras no equipamento e retorna os dados.

`Sql`: Executa o comando sql. Exemplos:
- `SQL SELECT * FROM Item WHERE Oferta = 1 ORDER BY Nome`
- `SQL SELECT * FROM Item WHERE TelaCheia = 1 ORDER BY Nome`
- `SQL SELECT * FROM Mensagem WHERE Lateral = 1 ORDER BY Oid`
- `SQL SELECT * FROM Config`
- `SQL SELECT * FROM Video`

`Demo`: Cria o banco demo (antigo botão das configurações).

`Limpar`: Apaga todos os dados (pelo adb).

`Reconfig`: Apaga todos os dados, configura novamente o servidor e sincroniza.

`ModoNormal`: Oculta as barras do android (se tiver root e monitor instalado), fecha as janelas abertas e inicia a playlist do zero.

`ModoSuporte`: Mostra as barras do android (se tiver root e monitor instalado), não pede senha para acessos restritos.

`ListarApps`: Mostra uma lista dos aplicativos instalados no dispositivo (não precisa de root).

`TemBarras`: Retorna true ou false se estiver com as barras do android ativas (não precisa de root).

`Atualizar`: Força atualização, mesmo que seja para mesma versão (se tiver root e monitor instalado).

`Layout {nome}`: Abre o layout específico.

`Falar`: Fala o texto pelo TTS.

# Manutenção

Apagar itens duplicados:  
`SQL DELETE FROM Item WHERE Oid NOT IN (SELECT MIN(Oid) FROM Item GROUP BY Nome)`

Apagar produtos em tela cheia:  
`SQL DELETE FROM ITEM WHERE TelaCheia = 1`

Apagar mensagens:  
`SQL DELETE FROM Mensagem`

# Demonstração/teste

Consultar códigos de barras:  
`Barras 7894900011517`
