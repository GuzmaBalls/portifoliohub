# PortfolioHUB — Portfólio de Engenharia de Software

Portfólio acadêmico inicial para reunir projetos, documentação e aprendizados.

## Estrutura
- `index.html`: página principal.
- `style.css`: estilos responsivos.
- `script.js`: ano automático no rodapé.
- `projetos/projeto-inicial/README.md`: documentação do primeiro projeto.
- `documentacao/evidencias.md`: links e evidências da entrega.

## Publicar no GitHub Pages
1. Crie um repositório público no GitHub, por exemplo `portfoliohub`.
2. Envie os arquivos desta pasta para a raiz do repositório.
3. Acesse **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/(root)` e salve.
6. Aguarde a publicação e teste o endereço informado pelo GitHub.

## Versionamento sugerido
```bash
git init
git add .
git commit -m "feat: cria portfólio inicial"
git branch -M main
git tag -a v1.0 -m "Versão 1.0 do portfólio"
git remote add origin https://github.com/SEU-USUARIO/portfoliohub.git
git push -u origin main
git push origin v1.0
```
Substitua `SEU-USUARIO` pelo seu usuário real. Se o repositório já foi criado no GitHub com arquivos, siga as instruções de conexão do próprio GitHub para evitar conflitos.

Após cada alteração:
```bash
git add .
git commit -m "docs: atualiza portfólio"
git push
```

## Antes de entregar
- [ ] Trocar links genéricos pelos perfis reais.
- [ ] Adicionar projetos reais e tecnologias.
- [ ] Confirmar que o repositório está público.
- [ ] Testar a URL do GitHub Pages.
- [ ] Adicionar o projeto ao LinkedIn.
- [ ] Publicar vídeo de cerca de 5 minutos no YouTube.
- [ ] Inserir links e capturas reais no relatório PDF.
