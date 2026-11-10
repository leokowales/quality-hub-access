# QualityHub — canal de autorizações

Este repositório entrega somente envelopes cifrados e assinados por instalação, em `authorizations/<identificador>.json`.

Qualquer pessoa pode baixar os arquivos públicos. O conteúdo da autorização é cifrado para a chave da instalação e assinado pelo responsável; copiar o documento não autoriza outra instalação. Identificadores, números de revisão e histórico de alterações são públicos.

Não publicar cadastro de clientes, e-mails em texto aberto, senhas/hashes, códigos de solicitação, tokens, bancos de dados, chaves privadas ou arquivos de configuração locais.

Manter a revisão mais recente de cada instalação, inclusive revogações. Não restaurar revisões antigas como rollback. Documentos em `tests/` são exclusivos de verificações técnicas isoladas e não autorizam instalações operacionais.

Instaladores e informações de versão ficam em https://github.com/leokowales/quality-hub-distribution .
