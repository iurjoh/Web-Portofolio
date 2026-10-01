# Web portfolio prototype

[English](README.md)

## Ideia e processo

Protótipo histórico de portfólio pessoal estático. Código revisado em 01/10/2026. Não foram encontrados plano datado, wireframes ou diário nos arquivos revisados. Biografia existente é conteúdo histórico, não credenciais recém-verificadas. Atualização não muda afirmações pessoais ou destinos de contato.

## Arquitetura e design

index.html/style.css definem navegação, avatar/apresentação, about, quatro projetos placeholder e links sociais. package.json vem do template estático CodeSandbox: start usa serve e build só informa que não há bundler. Branch padrão gh-pages preservada.

Projetos têm títulos/descrições e imagens #. Navegação/Download CV também são #. Caminhos /style.css e /images dependem de raiz de domínio; revise antes de publicar em subcaminho de repo. Confira alt do avatar e foco de teclado.

## Preview e deploy

```bash
python3 -m http.server 8000
```

Comando sugerido, não executado. [URL Netlify original](https://csb-5ehnre.netlify.app/) retornou conteúdo em 01/10/2026, com quatro projetos placeholder. Leitura não comprova assets, links ou mobile. Deploy não alterado.

## Testes e capturas

Manifest revisado sem script automatizado de teste. Nenhum teste manual/navegador. Antes de usar como portfólio atual, confira projetos, CV, assets, mobile e biografia atual aprovada pelo dono. Nenhuma captura adicionada/verificada; futuras imagens datadas em docs/assets/ devem identificar placeholders e evitar dados privados de CV/contato.

## Créditos e licença

Template/código/assets e créditos de terceiros preservados no [apêndice inglês](README.md#original-readme). Nenhuma licença nova. Manifest existente credita CodeSandbox static-template/Ives van Hoorne e declara MIT, preservado.
