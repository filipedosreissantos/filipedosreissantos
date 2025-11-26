# 🇧🇷 Filipe dos Reis Santos - Portfólio de Desenvolvedor

Um site de portfólio vibrante e moderno com cores brasileiras, efeitos de glassmorfismo e animações suaves. Construído com HTML, CSS e JavaScript puros - sem frameworks necessários!

![Status do Portfólio](https://img.shields.io/badge/Status-Online-success?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Recursos

- 🎨 **Tema com Cores Brasileiras** - Verde, amarelo e azul vibrantes inspirados na bandeira do Brasil
- 💎 **Design Glassmorfismo** - Efeitos modernos de cartões de vidro em todo o site
- 🎭 **Animações Suaves** - Integração com biblioteca AOS (Animate On Scroll)
- 📱 **Totalmente Responsivo** - Perfeito em desktop, tablet e dispositivos móveis
- ⚡ **Carregamento Rápido** - Desempenho otimizado com JavaScript puro
- 🔄 **Conteúdo Dinâmico** - Busca automática de repositórios do GitHub via API
- 📧 **Formulário de Contato** - Integração direta com mailto
- 🎯 **Otimizado para SEO** - Meta tags e HTML semântico
- 🚀 **Pronto para GitHub Pages** - Implante em minutos

## 🎨 Paleta de Cores

| Cor | Hex | Uso |
|-----|-----|-----|
| Verde | `#009c3b` | Cor primária, botões, destaques |
| Amarelo | `#ffdf00` | Cor secundária, realces |
| Azul | `#002776` | Texto, cabeçalhos, sobreposições |
| Branco | `#ffffff` | Fundo, cartões |

## 📂 Estrutura do Projeto

```
portfolio/
│
├── index.html          # Arquivo HTML principal
├── styles.css          # Todos os estilos com glassmorfismo
├── script.js           # Funcionalidades JavaScript
├── profile.jpg         # Sua foto de perfil
└── README.md          # Documentação do projeto
```

## 🚀 Início Rápido

### Desenvolvimento Local

1. **Clone o repositório**
   ```bash
   git clone https://github.com/filipedosreissantos/portfolio.git
   cd portfolio
   ```

2. **Abra no navegador**
   - Simplesmente abra `index.html` no seu navegador web
   - Ou use um servidor local:
   ```bash
   # Usando Python
   python -m http.server 8000
   
   # Usando Node.js
   npx serve
   ```

3. **Personalize**
   - Substitua `profile.jpg` pela sua própria foto
   - Atualize informações pessoais no `index.html`
   - Personalize cores no `styles.css` (variáveis CSS no topo)
   - Modifique seções de conteúdo conforme necessário

## 🌐 Implantar no GitHub Pages

### Método 1: Usando a Interface Web do GitHub

1. **Crie um novo repositório**
   - Vá para o GitHub e crie um novo repositório
   - Nome: `portfolio` (para site de projeto) ou `seu-usuario.github.io` (para site principal)
   - Não inicialize com README (já temos um)

2. **Envie os arquivos**
   - Clique em "uploading an existing file"
   - Arraste e solte todos os arquivos:
     - `index.html`
     - `styles.css`
     - `script.js`
     - `profile.jpg`
     - `README.md`
   - Confirme as alterações

3. **Ative o GitHub Pages**
   - Vá para Configurações do repositório
   - Role até a seção "Pages"
   - Origem: Selecione branch "main"
   - Pasta: Selecione "/ (root)"
   - Clique em Salvar

4. **Acesse seu site**
   - URL: `https://filipedosreissantos.github.io/portfolio/`
   - Aguarde 2-3 minutos para implantação

### Método 2: Usando Linha de Comando Git

```bash
# Inicialize git (se ainda não foi feito)
git init

# Adicione todos os arquivos
git add .

# Commit
git commit -m "Commit inicial do portfólio"

# Adicione repositório remoto
git remote add origin https://github.com/filipedosreissantos/portfolio.git

# Push para GitHub
git branch -M main
git push -u origin main

# Ative GitHub Pages através das Configurações ou use GitHub CLI
gh repo edit --enable-pages --pages-branch main
```

## 🛠️ Guia de Personalização

### Atualizar Informações Pessoais

**No `index.html`:**

1. **Seção Hero**
   - Linha ~95: Altere seu nome
   - Linha ~102: Atualize título/descrição do cargo
   - Linha ~113-127: Atualize links de redes sociais

2. **Seção Sobre**
   - Linha ~145-180: Modifique formação, experiência e descrições de projetos
   - Linha ~190-210: Atualize estatísticas

3. **Seção Formação Acadêmica**
   - Linha ~200-340: Edite cursos, instituições, períodos e certificações
   - Consulte GUIA-PERSONALIZACAO-FORMACAO.txt para instruções detalhadas

4. **Seção Habilidades**
   - Linha ~240-340: Adicione/remova/modifique cartões de habilidades
   - Ajuste níveis de habilidade no atributo `data-level`

5. **Seção Contato**
   - Linha ~420-440: Atualize email e localização
   - Linha ~445-460: Atualize links de redes sociais

### Personalizar Cores

**No `styles.css`** (Linhas 1-30):

```css
:root {
    /* Altere estes valores */
    --color-green: #SEU_VERDE;
    --color-yellow: #SEU_AMARELO;
    --color-blue: #SEU_AZUL;
    --color-white: #SEU_BRANCO;
}
```

### Adicionar Novas Seções

1. Adicione estrutura HTML no `index.html`
2. Estilize no `styles.css`
3. Adicione link de navegação na navbar
4. Atualize comportamento de rolagem suave no `script.js`

## 📱 Visão Geral das Seções

1. **Hero/Início** - Introdução com efeito de digitação animado
2. **Sobre** - Formação, experiência e projetos notáveis
3. **Formação Acadêmica** - Timeline educacional, cursos e certificações
4. **Habilidades** - Stack técnico com barras de progresso animadas
5. **Projetos** - Projetos em destaque + repositórios do GitHub carregados automaticamente
6. **Contato** - Formulário de contato e links de redes sociais

## 🎯 Detalhamento de Recursos

### Animações
- **Biblioteca AOS** - Animações baseadas em rolagem
- **Efeito de Digitação** - Títulos de cargo rotativos
- **Animação de Contador** - Incremento de estatísticas
- **Barras de Habilidades** - Barras de progresso animadas
- **Fundo Flutuante** - Círculos animados

### Elementos Interativos
- **Navegação Mobile** - Menu hambúrguer
- **Rolagem Suave** - Todos os links âncora
- **Voltar ao Topo** - Botão flutuante
- **Navegação Ativa** - Destaca seção atual
- **Efeitos Hover** - Cartões, botões e links
- **Manipulação de Formulário** - Integração com mailto

### Performance
- **Lazy Loading** - Imagens carregam sob demanda
- **JavaScript Puro** - Sem frameworks pesados
- **CSS Otimizado** - Seletores eficientes
- **Dependências Mínimas** - Apenas AOS + Font Awesome

## 📦 Dependências

- [Font Awesome](https://fontawesome.com/) - Ícones
- [AOS](https://michalsnik.github.io/aos/) - Animações de rolagem
- [Google Fonts](https://fonts.google.com/) - Fontes Poppins & Montserrat

## 🔧 Suporte de Navegadores

- Chrome (mais recente)
- Firefox (mais recente)
- Safari (mais recente)
- Edge (mais recente)
- Navegadores móveis (iOS Safari, Chrome Mobile)

## 📸 Capturas de Tela

### Visualização Desktop
![Desktop](https://via.placeholder.com/800x450/009c3b/ffffff?text=Visualização+Desktop)

### Visualização Mobile
![Mobile](https://via.placeholder.com/400x800/002776/ffffff?text=Visualização+Mobile)

## 🐛 Solução de Problemas

### GitHub Pages não está carregando?
- Aguarde 2-3 minutos após primeira implantação
- Verifique configurações do repositório > Pages está ativado
- Certifique-se de que a branch main está selecionada
- Verifique erros de digitação nos nomes de arquivos (sensível a maiúsculas)

### Imagens não aparecem?
- Verifique se `profile.jpg` está no diretório raiz
- Verifique se o nome do arquivo corresponde exatamente (sensível a maiúsculas)
- Tente limpar o cache do navegador

### Animações não funcionam?
- Verifique se JavaScript está habilitado no navegador
- Verifique se a biblioteca AOS está carregando (verifique console do navegador)
- Certifique-se de ter conexão com internet (AOS carrega do CDN)

## 🎨 Inspiração de Design

- Cores da bandeira brasileira para sensação vibrante e energética
- Glassmorfismo para estética moderna e limpa
- Abordagem minimalista para melhor experiência do usuário
- Design responsivo mobile-first

## 📝 Licença

Este projeto é código aberto e está disponível sob a [Licença MIT](LICENSE).

## 🤝 Contribuindo

Sinta-se livre para fazer fork deste projeto e personalizá-lo para seu próprio portfólio! Se encontrar bugs ou tiver sugestões:

1. Faça fork do repositório
2. Crie um branch de recurso
3. Commit suas alterações
4. Push para o branch
5. Abra um Pull Request

## 📧 Contato

**Filipe dos Reis Santos**
- Email: miguelfilipedosreissantos@gmail.com
- GitHub: [@filipedosreissantos](https://github.com/filipedosreissantos)
- LinkedIn: [filipedosreissantos](https://www.linkedin.com/in/filipedosreissantos)
- Site: [Língua Academy](https://www.linguaacademy.com.br/)

## 🌟 Agradecimentos

- Font Awesome pelos ícones incríveis
- Biblioteca AOS por animações de rolagem suaves
- Google Fonts pela bela tipografia
- Bandeira brasileira pela inspiração de cores 🇧🇷

---

**Feito com ❤️ e ☕ no Brasil**

*Se achou útil, por favor considere dar uma ⭐ no GitHub!*
