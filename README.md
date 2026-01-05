# 🌙 Conversor LUB ↔ LUA

Uma ferramenta web moderna e intuitiva para converter arquivos Lua entre bytecode compilado (LUB) e código fonte (LUA).

[![Deploy on Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/SEU-USUARIO/conversor)

## ✨ Funcionalidades

- **📦 LUB → LUA**: Decompila bytecode Lua para código fonte legível
- **📄 LUA → LUB**: Compila código Lua para bytecode (formato binário)
- **🎨 Interface Moderna**: Design responsivo com glassmorphism e gradientes
- **🖱️ Drag & Drop**: Arraste e solte arquivos facilmente
- **⚡ Processamento Local**: Conversão feita 100% no navegador, sem upload de arquivos
- **📥 Download Imediato**: Baixe o arquivo convertido instantaneamente
- **👁️ Preview de Código**: Visualize o código decompilado antes de baixar

## 🚀 Demo ao Vivo

[Ver Demo](https://seu-projeto.vercel.app)

## 📸 Screenshots

<div align="center">
  <img src="https://via.placeholder.com/800x500/1a1a2e/00d4ff?text=Conversor+LUB+LUA" alt="Screenshot do Conversor" />
</div>

## 🛠️ Tecnologias

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- JavaScript (ES6+)
- FileReader API
- Blob API

## 📦 Como Usar

### Online

Acesse [https://seu-projeto.vercel.app](https://seu-projeto.vercel.app) e comece a usar imediatamente!

### Localmente

1. Clone o repositório:
```bash
git clone https://github.com/SEU-USUARIO/conversor.git
cd conversor
```

2. Abra o arquivo `index.html` no seu navegador ou use um servidor local:
```bash
# Com Python
python -m http.server 8000

# Com Node.js (http-server)
npx http-server

# Com PHP
php -S localhost:8000
```

3. Acesse `http://localhost:8000` no navegador

## 🎯 Como Converter Arquivos

### LUB para LUA (Decompilação)

1. Selecione o modo **LUB → LUA**
2. Arraste e solte um arquivo `.lub` ou clique para selecionar
3. Clique em **Converter Arquivo**
4. Visualize o código decompilado
5. Clique em **Baixar** para salvar o arquivo `.lua`

### LUA para LUB (Compilação)

1. Selecione o modo **LUA → LUB**
2. Arraste e solte um arquivo `.lua` ou clique para selecionar
3. Clique em **Converter Arquivo**
4. Clique em **Baixar** para salvar o arquivo `.lub`

## ⚙️ Deploy na Vercel

### Opção 1: Via GitHub (Recomendado)

1. Faça push do código para o GitHub
2. Acesse [vercel.com](https://vercel.com)
3. Clique em **"Add New Project"**
4. Importe seu repositório do GitHub
5. Configure:
   - **Framework Preset**: Other
   - **Build Command**: (deixe vazio)
   - **Output Directory**: (deixe vazio)
6. Clique em **Deploy**

### Opção 2: Via Vercel CLI

```bash
# Instalar Vercel CLI
npm i -g vercel

# Fazer deploy
vercel

# Deploy para produção
vercel --prod
```

### Opção 3: Botão de Deploy

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/SEU-USUARIO/conversor)

## 📁 Estrutura do Projeto

```
conversor/
├── index.html           # Aplicação principal (HTML + CSS + JS)
├── vercel.json         # Configuração do Vercel
├── README.md           # Documentação
└── .gitignore          # Arquivos ignorados pelo Git
```

## ⚠️ Limitações

- **Decompilação Simplificada**: O decompilador é básico e extrai strings e estrutura geral do bytecode. Para decompilação profissional, considere usar ferramentas especializadas como [unluac](https://sourceforge.net/projects/unluac/) ou [LuaDec](https://github.com/viruscamp/luadec)
- **Compilação Demonstrativa**: A compilação gera um bytecode simplificado. Para compilação real, use `luac` oficial
- **Tamanho de Arquivo**: Recomendado para arquivos até 10MB para melhor performance no navegador

## 🔧 Ferramentas Profissionais Recomendadas

Para trabalho profissional com bytecode Lua, recomendamos:

- **[unluac](https://sourceforge.net/projects/unluac/)**: Decompilador Lua 5.1-5.4
- **[LuaDec](https://github.com/viruscamp/luadec)**: Decompilador Lua robusto
- **[luac](https://www.lua.org/manual/5.1/luac.html)**: Compilador oficial Lua

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/NovaFuncionalidade`)
5. Abrir um Pull Request

## 📝 Ideias para Melhorias

- [ ] Suporte para Lua 5.2, 5.3 e 5.4
- [ ] Decompilador mais avançado com análise de controle de fluxo
- [ ] Syntax highlighting no preview
- [ ] Tema claro/escuro
- [ ] Histórico de conversões
- [ ] Processamento em lote de múltiplos arquivos
- [ ] API REST para conversão programática

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

Desenvolvido por [Seu Nome](https://github.com/SEU-USUARIO)

## 🙏 Agradecimentos

- Comunidade Lua
- Inspirado em ferramentas de decompilação existentes
- Design inspirado em interfaces modernas de desenvolvimento

---

<div align="center">
  Feito com ❤️ e ☕

  [⭐ Star no GitHub](https://github.com/SEU-USUARIO/conversor) • [🐛 Reportar Bug](https://github.com/SEU-USUARIO/conversor/issues) • [💡 Solicitar Feature](https://github.com/SEU-USUARIO/conversor/issues)
</div>
