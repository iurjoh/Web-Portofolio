# Web portfolio prototype

[English](README.md)

## Demo

[![Abrir demo](https://img.shields.io/badge/demo-live-2ea44f)](https://csb-5ehnre.netlify.app/)

Abra no navegador, sem instalar nada ou usar o terminal. Protótipo histórico com projetos e links placeholder.

## Ideia e processo

Protótipo histórico de portfólio pessoal estático. Código revisado em 01/10/2026. Não foram encontrados plano datado, wireframes ou diário nos arquivos revisados. Biografia existente é conteúdo histórico, não credenciais recém-verificadas. Atualização não muda afirmações pessoais ou destinos de contato.

## Arquitetura e design

index.html/style.css definem navegação, avatar/apresentação, about, quatro projetos placeholder e links sociais. package.json vem do template estático CodeSandbox: start usa serve e build só informa que não há bundler. Branch padrão gh-pages preservada.

Projetos têm títulos/descrições e imagens #. Navegação/Download CV também são #. Caminhos /style.css e /images dependem de raiz de domínio; revise antes de publicar em subcaminho de repo. Confira alt do avatar e foco de teclado.

## Preview e deploy

```bash
python3 -m http.server 8000
```

Comando sugerido, não executado. O preview Netlify original retornou conteúdo em 01/10/2026, com quatro projetos placeholder. Leitura não comprova assets, links ou mobile. Deploy não alterado.

## Testes e capturas

Manifest revisado sem script automatizado de teste. Nenhum teste manual/navegador. Antes de usar como portfólio atual, confira projetos, CV, assets, mobile e biografia atual aprovada pelo dono. Nenhuma captura adicionada/verificada; futuras imagens datadas em docs/assets/ devem identificar placeholders e evitar dados privados de CV/contato.

## Créditos e licença

Template/código/assets e créditos de terceiros preservados no [apêndice inglês](README.md#original-readme). Nenhuma licença nova. Manifest existente credita CodeSandbox static-template/Ives van Hoorne e declara MIT, preservado.

## Retrato da tecnologia e do esforço

Registro das fontes do repositório em 2026-10-14. É um retrato do código, não uma afirmação sobre versões em produção nem sobre a tecnologia disponível no lançamento original.

- **Stack neste registro:** HTML e CSS; package.json preserva um template estático do CodeSandbox. Suas ferramentas não são apresentadas como framework de aplicação original.
- **Registro anterior:** A janela original de desenvolvimento não foi estabelecida nos arquivos revisados; os créditos do template de terceiros permanecem intactos.
- **Janela de calendário observada:** 2026-10-10 a 2026-10-10: apenas registros visíveis de criação/atualização de PRs. Janela completa de implementação não estabelecida.
- **Pull requests:** 1 PR visível: 0 abertos, 1 fechado, consultados em 2026-10-14 antes desta alteração. Fechado não significa mergeado. Histórico apagado/recriado não entra na contagem.
- **Decisão e motivo:** Um protótipo estático registra a estrutura inicial; projetos e links de exemplo permanecem explicitamente históricos, não evidência do portfólio atual.
- **Estimativa de esforço ativo:** indisponível. Não foi estabelecido um registro confiável de tempo nem uma reconstrução delimitada das sessões de trabalho. Contagem de commits e tempo de calendário não são convertidos em horas.

Evidências: arquivos de dependências/código citados acima, histórico Git preservado e lista de PRs do repositório. Versões e contagens pertencem a este registro, não são contadores ao vivo.
