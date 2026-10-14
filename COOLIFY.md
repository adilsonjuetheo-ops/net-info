# Hospedagem adicional

O site possui um Dockerfile para servir os arquivos estaticos com Nginx e verificacao de saude em /health.

Para utilizar um dominio proprio, configure o DNS para o servidor de hospedagem, adicione o dominio no painel e valide o HTTPS apos a propagacao. Preserve os registros de email existentes.

Os detalhes operacionais do ambiente ficam na documentacao local do proprietario, fora do repositorio publico.

Publicacao automatica configurada: atualizacoes na branch main iniciam um deploy por webhook assinado. Segredos ficam nos servicos e nao no repositorio.

