# GIT ao GITHUB windows

## Comandos 
- DIR  Listar e se situar dentro de um sistema operacional(vai trazer todas as pastas situadas) no Linux = LS
- CD /   Navegar entre as pastas – em qualquer sistema operacional
- CD.. – Para fazer caminho inverso, voltar, retroceder um nível na navegação.
- CLS - Limpar o terminal(organização) – Linux = clear ou CTRL+ L
- Botão TAB – Atalho para completar nome da pasta
- MKDIR – criar pastas – igual nos dois sistemas
- ECHO – criar arquivo - > redirecionar
- DEL – deletar somente arquivos – Linux RM
- RMDIR - deletar toda a pasta e repositórios
- GIT STATUS – TRAZ A INFORMAÇÃO DE COMO ESTÁ MEU ARQUIVO

## COMO GIT FUNCIONA por baixos dos panos
- SHA1 - é um conjunto de funções hash criptográficas projetadas pela NSA(Agencia de segurança nacional dos EUA)
A encriptação gera conjunto de caracteres identificador de 40 dígitos, esse conjunto é único ( identificação de arquivos de uma forma segura e rápida)

## Objetos fundamentais 
- BLOBS – Metadados - o tipo de objeto, tamanho, barra, tipo de conteúdo (hash)
- TREES – armazena blobs , contem metadados, aponta para um blob, ela guarda o nome do arquivo, monta estrutura de onde estão localizados os arquivos.
- COMMITS – ele junta tudo e dá sentido, aponta para o autor e para a mensagem, ele tem um carimbo de tempo. 
Sistema Distribuído
Segurança

Chaves SSH e tokens
SSH – Para o guithub conhecer a nossa máquina
$ ssh-keygen -t ed25519 -C your_email@example.com

## Passos
Iniciar o GIT
Iniciar o versionamento
Criar um commit

GIT INIT – Iniciar repositório 
GIT ADD -  Mover arquivo e conhecer comandos
GIT COMMIT 

-A – Mostra arquivos ocultos
Atalho – CTRL+L limpa tela

MARKDOWN – NAVEGADOR – HTML

Tracked  -arquivos que o git tem ciência deles
- Unmodified – arquivo não modificado
- Modified – sofreu modificação
-	Staged – onde fica os arquivos que estão se preparando para outro tipo de agrupamento ( commit)

