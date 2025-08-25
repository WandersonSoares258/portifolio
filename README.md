## 📋 Sobre o Projeto

Portfólio profissional desenvolvido para Wanderson Soares, apresentando habilidades, projetos e informações de contato. O site foi construído com design moderno, responsivo e foco na experiência do usuário.

## ✨ Funcionalidades

- **Design Responsivo** - Adaptado para desktop, tablet e mobile
- **Navegação Suave** - Scroll suave entre seções
- **Portfólio Interativo** - Galeria de projetos com filtros
- **Formulário de Contato** - Integração com EmailJS
- **Modo Claro/Escuro** - Toggle entre temas
- **Animações** - Efeitos visuais suaves
- **Otimização SEO** - Meta tags para melhor indexação

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização e animações
- **JavaScript** - Interatividade e funcionalidades
- **EmailJS** - Integração de formulário de contato
- **ScrollReveal** - Animações de scroll
- **Boxicons** - Ícones modernos
- **Google Fonts** - Tipografia (Poppins)

## 🚀 Como Executar

### Pré-requisitos
- Navegador web moderno
- Conexão com internet (para carregar fontes e ícones)

### Instalação Local
```bash
# Clone o repositório
git clone https://github.com/WandersonSoares258/portifolio.git

# Entre na pasta do projeto
cd portifolio

# Abra o arquivo index.html no navegador
# Ou use um servidor local se preferir:
python -m http.server 8000
# ou
npx serve .
```

## 📁 Estrutura do Projeto

```
portifolio/
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── img/
│   │   ├── projects/
│   │   ├── perfil.png
│   │   └── favicon.png
│   └── pdf/
│       └── Curriculo.pdf
├── README.md
└── LICENSE
```

## 🎨 Personalização

Para personalizar este portfólio:

1. Substitua as imagens na pasta `assets/img/`
2. Atualize as informações pessoais no `index.html`
3. Modifique o arquivo `style.css` para alterar cores e estilos
4. Adicione seus projetos na seção de portfólio
5. Atualize o currículo em `assets/pdf/Curriculo.pdf`
6. Configure o EmailJS no `script.js` para o formulário de contato

### Configuração do EmailJS
Para que o formulário de contato funcione:

1. Crie uma conta no [EmailJS](https://www.emailjs.com/)
2. Obtenha seu User ID Público
3. Crie um template de email
4. Substitua as credenciais no arquivo `script.js`:
```javascript
emailjs.init("SEU_USER_ID_PUBLICO");
// E atualize os IDs do serviço e template
```
