# Sistema de Solicitações de NFS-e

Portal demonstrativo para recebimento de solicitações e pré-análise fiscal, com aprovação bloqueada por campos pendentes.

## Executar

Node.js 20+: `ADMIN_TOKEN=defina-uma-senha-forte npm start`

Acesse `http://localhost:3000`.

**Atenção:** MVP para testes, não adequado para receber dados fiscais reais em produção. A análise é baseada em palavras-chave, não em validação legal automatizada. Não transmite NFS-e. Antes de publicar, implementar autenticação individual, isolamento de empresas, banco persistente, controles contra abuso, auditoria e revisão de segurança.
