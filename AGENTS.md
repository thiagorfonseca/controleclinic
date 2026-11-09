# Documentação da API do Controle Clinic

Site Mintlify (`docs.json` + páginas MDX). Rode `mint instructions` antes de qualquer tarefa no Mintlify.

## Fonte da verdade

- A aba **Referência da API** é gerada de `https://api.controleclinic.com.br/v1/openapi.json`, servido pelo
  sistema (repositório `cliniccontrole`, arquivo `api/v1.ts`). **Não copie rotas, campos ou escopos para cá à
  mão**: corrija no `api/v1.ts` e, depois do deploy do sistema, clique em **Manual update** no painel do
  Mintlify (mudar a URL não dispara deploy sozinho).
- Os guias (`index.mdx`, `guias/`) repetem o texto de `info.description` e das `tags` do OpenAPI. Mudou lá,
  mude aqui no mesmo dia.

## Regras de conteúdo

- Tudo em português do Brasil, segunda pessoa, frases curtas.
- Nunca documentar rota interna (`/api/internal/*`) nem recursos de admin.
- O nome do produto em tela é sempre **Controle Clinic**. "OnePay" é codinome interno e não aparece aqui.
- Repositório PÚBLICO: nada de chave, ID de clínica real ou dado de paciente nos exemplos.
