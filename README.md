# 5.000 Exercícios Infantis — Landing Page

## Como subir no GitHub + Netlify (domínio grátis)

### 1. Criar repositório no GitHub
1. Acesse https://github.com/new
2. Nome: `5mil-exercicios` (ou o que quiser)
3. Deixe **Público**
4. Clique **Create repository**
5. Copie a URL do repositório (ex: https://github.com/SEU_USUARIO/5mil-exercicios.git)

### 2. Subir os arquivos (rode no terminal / VS Code)
```bash
git remote add origin https://github.com/SEU_USUARIO/5mil-exercicios.git
git branch -M main
git add .
git commit -m "landing page inicial"
git push -u origin main
```

### 3. Deploy grátis no Netlify
1. Acesse https://netlify.com e crie conta grátis (pode entrar com o GitHub)
2. Clique **Add new site → Import an existing project**
3. Escolha **GitHub** e selecione o repositório `5mil-exercicios`
4. Clique **Deploy site**
5. Em ~30 segundos seu site estará no ar em algo como `https://5mil-exercicios.netlify.app`

### 4. Personalizar o domínio grátis (opcional)
- No painel do Netlify → **Domain settings → Options → Edit site name**
- Mude para algo como `exerciciosdoseufilho.netlify.app`

### 5. Domínio próprio (opcional — ~R$40/ano)
- Compre no Registro.br ou Hostinger
- No Netlify → **Domain settings → Add custom domain**

---

## Onde substituir as imagens
Abra o `index.html` e procure os blocos `<div class="img-placeholder">`.
Substitua cada um por uma tag `<img>`:
```html
<img src="sua-imagem.jpg" alt="descrição" style="width:100%;border-radius:14px;object-fit:cover;">
```

## Onde colocar o link do checkout
Procure `SEU_LINK_DE_CHECKOUT_AQUI` no arquivo e substitua pela URL do seu checkout (Kiwify, Yampi, SigiloPay...).
