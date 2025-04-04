## Passo a passo da configuração do github.

Após instalação do git, primeiramente e necessário configurar o username e o email.

`git config --global user.name "seunome"`
`git config --global user.email "seuemail@email.com"`

com eles já configurados agora é necessário criar uma chave ssh vinculado com seu email do github.
`ssh-keygen -t rsa -C "seuemail@email.com"`

depois da chave criada, será criado uma pasta .ssh no diretorio do seu usuário do computador com arquivos de sua chave, acesse o arquivo "id_rsa.pub", copie o contéudo.
Com sua conta logada no Github, acesse as [configurações](https://github.com/settings/keys) do seu perfil, acesse a parte de SSH and GPG Keys, crie uma nova SSH Key e adicione um nome para ela e copie o conteudo copiado do arquivo na parte de Key.
