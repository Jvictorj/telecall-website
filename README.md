# 🚀 Telecall - Plataforma CPaaS

## Projeto Final — Módulo I (Front-End)

Curso de Análise e Desenvolvimento de Sistemas

Um site institucional moderno para a **Telecall**, empresa líder em comunicações integradas (CPaaS - Communications Platform as a Service), com foco em acessibilidade e performance.

---

## ✨ Destaques do Projeto

### 🎨 Arquitetura CSS Modular

- **10 arquivos de design system** com tokens centralizados
- **BEM naming convention** para máxima manutenibilidade
- **CSS variables** para tema claro/escuro automático
- **50%+ redução** em duplicação de código
- **5 breakpoints responsivos** (480px, 580px, 820px, 1120px, 1300px)

### 🖼️ Otimização de Imagens

- `object-fit: contain` em todas as imagens
- Dimensionamento automático sem distorção
- Logos (200px), ícones (24-80px), ilustrações (150-600px)

### 🌙 Modo Escuro Completo

- Toggle automático com persistência em localStorage
- Funciona em todas as 8 páginas
- Menu mobile com controle independente
- Carregamento automático da preferência do usuário

### ♿ Acessibilidade

- **Controle de tamanho de fonte** (aumentar/diminuir)
- **Modo escuro/claro** totalmente funcional
- **Navegação por teclado** otimizada
- **Labels semânticos** em formulários
- **ARIA attributes** implementados

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Descrição |
|-----------|-----------|
| **HTML5** | Estrutura semântica e acessível |
| **CSS3** | Modular com design system centralizado |
| **JavaScript** | Vanilla JS (sem dependências) |
| **Git** | Versionamento com histórico limpo |
| **AWS S3** | Hospedagem estática |

---

## 📁 Estrutura do Projeto

```bash
telecall-website-unisuam-project/
├── css/
│   ├── variables.css           # Design tokens
│   ├── reset.css               # CSS reset
│   ├── components.css          # Componentes reutilizáveis
│   ├── sections.css            # Seções de layout
│   ├── services.css            # Cards de serviços
│   ├── examples.css            # Exemplos
│   ├── advantages.css          # Vantagens
│   ├── forms.css               # Formulários
│   ├── footer.css              # Footer
│   ├── responsive.css          # Media queries
│   ├── style.css               # Homepage
│   ├── 2fa.css                 # 2FA page
│   ├── google.css              # Google Verified Calls
│   ├── sms.css                 # SMS page
│   ├── numeromascara.css       # Número Máscara
│   ├── cadastro.css            # Registration
│   ├── redefinir.css           # Password Reset
│   ├── login.css               # Login
│   └── page-template.css       # Template reference
├── JavaScript/
│   ├── Darkmode.js             # Theme toggle
│   ├── menu-toggle.js          # Mobile menu
│   ├── fontsize.js             # Font size control
│   ├── Login.js                # Login validation
│   ├── register.js             # Registration
│   └── ...
├── IMG/
│   ├── imagens/                # Images
│   ├── icon-serviços/          # Service icons
│   ├── Icons/                  # General icons
│   ├── icons-2/                # Illustrations
│   ├── Quem usa/               # Use cases
│   └── SpaaS/                  # Platform screenshots
├── home.html                   # Homepage
├── index.html                  # Landing page
├── 2fa.html                    # 2FA authentication
├── google.html                 # Google Verified Calls
├── numeromascara.html          # Phone masking
├── sms.html                    # SMS service
├── cadastro.html               # Registration
├── login.html                  # Login
├── redefinir.html              # Password reset
└── README.md                   # Este arquivo
```

---

## 🚀 Quick Start

### Instalação Local

```bash
# Clone o repositório
git clone https://github.com/Jvictorj/telecall-website-unisuam-project.git

# Entre na pasta
cd telecall-website-unisuam-project

# Abra no navegador (sem servidor necessário)
# Abra: ./index.html ou ./home.html
```

**Não requer nenhuma dependência!** O projeto é 100% estático.

---

## 🎯 Páginas Disponíveis

| Página | URL | Descrição |
|--------|-----|-----------|
| **Home** | `home.html` | Homepage com serviços |
| **Landing** | `index.html` | Página principal |
| **2FA** | `2fa.html` | Two-Factor Authentication |
| **Google Verified** | `google.html` | Google Verified Calls |
| **SMS** | `sms.html` | SMS Programável |
| **Número Máscara** | `numeromascara.html` | Phone Masking |
| **Cadastro** | `cadastro.html` | Registro de usuário |
| **Login** | `login.html` | Acesso de usuário |
| **Redefinir Senha** | `redefinir.html` | Password reset |

---

## ✅ Funcionalidades Implementadas

### 🔐 Autenticação

- ✅ Formulário de cadastro com validação
- ✅ Formulário de login
- ✅ Recuperação de senha
- ✅ Validação de CPF e dados pessoais

### 🌗 Acessibilidade

- ✅ **Dark Mode** com toggle e persistência
- ✅ **Font Size Control** (+/- proporção)
- ✅ Navegação por teclado
- ✅ Contraste adequado
- ✅ Labels semânticos

### 📱 Design Responsivo

- ✅ Mobile-first
- ✅ 5 breakpoints
- ✅ Menu mobile interativo
- ✅ Imagens redimensionadas corretamente

### 🎨 Design System

- ✅ Variables centralizadas
- ✅ Componentes reutilizáveis
- ✅ BEM naming
- ✅ Tema consistente

---

## 📊 Estatísticas do Projeto

| Métrica | Valor |
|---------|-------|
| Arquivos CSS | 19 |
| Arquivos HTML | 9 |
| Arquivos JavaScript | 6 |
| Linhas CSS | 4.891+ |
| Design System Files | 10 |
| Redução de Código | 50%+ |
| Breakpoints Responsivos | 5 |

---

## 🔄 Git Workflow

O projeto segue **Conventional Commits**:

```bash
# Commits estruturados
git commit -m "feat: add new feature"      # Nova funcionalidade
git commit -m "fix: resolve bug"           # Correção
git commit -m "docs: update readme"        # Documentação
git commit -m "style: format code"         # Estilo
git commit -m "refactor: improve code"     # Refatoração
```

### Histórico de Refatorações Principais

1. **CSS Modularization** - Design system com 10 arquivos
2. **Image Sizing** - Otimização de imagens com object-fit
3. **Dark Mode Fix** - Funcionamento correto com localStorage

---

## 🌐 Acesso Online

O projeto está hospedado no **AWS S3**:

👉 **[Acessar Telecall Online](https://meu-bucket-telecall-joao.s3.sa-east-1.amazonaws.com/projeto-telecall-main-meu/index.html)**

---

## 📋 Como Contribuir

Contribuições são bem-vindas! Para colaborar:

```bash
# 1. Faça um fork
git clone https://github.com/seu-usuario/telecall-website-unisuam-project.git

# 2. Crie uma branch
git checkout -b feature/sua-funcionalidade

# 3. Commit suas mudanças
git commit -m "feat: descrição clara da mudança"

# 4. Push para origin
git push origin feature/sua-funcionalidade

# 5. Abra um Pull Request
```

**Padrões de código:**

- Usar BEM naming em CSS
- Adicionar comentários em JavaScript complexo
- Testar em ao menos 2 navegadores
- Verificar acessibilidade (teclado + screen reader)

---

## 📚 Documentação Adicional

- **[CSS Architecture](./css/CSS-README.md)** - Detalhes do design system
- **[Verification Report](./VERIFICATION_REPORT.md)** - Relatório de testes

---

## 👥 Autores

- **João Vitor Gomes** - Desenvolvimento principal
- **Paulo Alves** - Colaboração

---

## 📄 Licença

Este projeto foi desenvolvido **exclusivamente para fins acadêmicos**, sem fins comerciais.

© 2025 Telecall Project. Todos os direitos reservados.

---

## 📞 Contato & Suporte

Para dúvidas ou sugestões:

- 📧 Email: [joao@exemplo.com](mailto:joao@exemplo.com)
- 🐙 GitHub: [@Jvictorj](https://github.com/Jvictorj)
- 💼 LinkedIn: [João Vitor](https://linkedin.com)

---
