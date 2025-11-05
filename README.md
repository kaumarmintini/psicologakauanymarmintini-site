# Site estático para Kauany Marmintini

Arquivos incluídos:
- index.html, sobre.html, psicoterapia.html, agenda.html, contato.html, sala.html, blog.html
- styles.css
- /admin (Netlify CMS): index.html e config.yml
- README com instruções

### Publicar com Netlify (passo-a-passo rápido)
1. Crie um repositório no GitHub com estes arquivos (branch `main`).
2. Crie conta em https://app.netlify.com e clique em "Add new site" → Import from Git.
3. Conecte seu repositório GitHub e faça deploy (Netlify fará o build automaticamente para sites estáticos).
4. No Netlify, ative o Netlify Identity e Git Gateway (Site settings → Identity → Enable Identity).
5. Habilite Git Gateway (Site settings → Identity → Services → Git Gateway). Siga as instruções.
6. Acesse `https://<seu-site>/admin/` e faça login para editar conteúdo.

### Conectar domínio próprio
- No Netlify, vá em Domain settings e adicione seu domínio. Siga as instruções de DNS do Netlify (apontar A/ALIAS ou CNAME conforme instruções).

### Observações importantes
- O painel /admin depende de Netlify Identity + Git Gateway (gratuitos em planos básicos).
- Para área de pacientes e armazenamento seguro de prontuários, considere serviços de backend seguro (este site é um front-end estático).
- Posso ajudar a automatizar o push para GitHub e configurar o Netlify Identity se quiser.

