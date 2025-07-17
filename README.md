# ZapCar Consulta – Site em Desenvolvimento

Este repositório contém a página estática de “Em Desenvolvimento” para o domínio da ZapCar Consulta. O arquivo principal `index.html` apresenta um layout minimalista com spinner de carregamento enquanto o site principal não está disponível.

---

## 📂 Estrutura do Projeto

```
.
├── index.html        # Página principal “Em Desenvolvimento”
├── logo.png          # Logotipo da ZapCar Consulta
└── README.md         # Documentação técnica deste repositório
```

---

## 🛠 Tecnologias

- **HTML5**  
- **CSS3** (inline, com animação @keyframes para spinner)  
- **Responsividade** via meta viewport  
- **Compatibilidade**: navegadores modernos com suporte a Flexbox e animações CSS

---

## 🚀 Como usar

1. **Clone** este repositório:
   ```bash
   git clone https://github.com/seu-usuario/zapcar-consulta-dev.git
   cd zapcar-consulta-dev
   ```
2. **Adicione** ou substitua o logotipo em `logo.png` (formato PNG, max-width 150px).  
3. **Hospede** em um servidor estático ou serviço de hosting (GitHub Pages, Netlify, Vercel, etc.):
   - **GitHub Pages**  
     - Renomeie branch principal para `gh-pages` ou configure nas _Settings_ do repositório.  
     - O arquivo `index.html` será servido automaticamente em `https://seu-usuario.github.io/zapcar-consulta-dev/`.  
   - **Serviços próprios / VPS**  
     - Faça _upload_ de todos os arquivos na pasta raiz do servidor.  
     - Aponte o DNS do seu domínio para o servidor (A record / CNAME).  
4. **Verifique** o carregamento em dispositivos móveis e desktops.

---

## ⚙️ Configurações de Domínio

- **Registro DNS**  
  - **A Record**: aponte para o IP do seu servidor.  
  - **CNAME**: pode apontar para `seu-usuario.github.io` em setups de GitHub Pages.
- **HTTPS**  
  - Configure SSL/TLS (Let’s Encrypt, Cloudflare, etc.).
  - Garanta que `https://` redirecione corretamente para a versão segura.

---

## 🔄 Fluxo de Desenvolvimento

1. Atualize o `index.html` conforme o progresso do site principal.
2. **Commit** e **push** nas branches designadas:
   - `main` / `master`: versão estável “Em Desenvolvimento”
   - `develop`: branch para testes de atualização do aviso
3. Ao finalizar o site principal, substitua este conteúdo pelo novo `index.html` ou pela aplicação completa.

---

## 📝 Contribuições

1. Faça um fork deste repositório.  
2. Crie uma branch feature: `git checkout -b feature/nova-mensagem`.  
3. Faça suas alterações no `index.html` ou adicione novos assets.  
4. Envie um Pull Request detalhando as mudanças.

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).  

---

> _README gerado para facilitar o deploy e manutenção da página “Em Desenvolvimento” no GitHub e servidores estáticos._
