# Login Dev

Guia rápido para personalizador seu formulário de login.

## 📝 Onde Modificar

### **HTML (index.html)**

| Elemento | Linha | Como Modificar |
|----------|-------|----------------|
| **Título da página** | 10 | Mude `<title>Login</title>` |
| **Título do formulário** | 17 | Altere `<h1>Login Dev</h1>` |
| **Placeholder email** | 19 | Troque o texto em `placeholder="Usuário"` |
| **Placeholder senha** | 23 | Troque o texto em `placeholder="Senha"` |
| **Texto do checkbox** | 27 | Mude "Lembrar minha senha" |
| **Link "esqueci senha"** | 29 | Altere `href="#"` para sua URL |
| **Texto cadastro** | 33 | Mude "Nao tem uma conta?" e o link |

### **CSS (style.css)**

| Elemento | Propriedade | Como Modificar |
|----------|------------|----------------|
| **Fundo** | `background-image` | Troque o caminho da imagem em `./img/pexels-...jpg` |
| **Tamanho container** | `width: 420px` | Aumente/diminua a largura |
| **Cor de fundo (transparente)** | `background-color` | Mude o `rgba()` para mais/menos opaco |
| **Cor do texto** | `color: #fff` | Use outra cor (ex: `#333`) |
| **Cor do botão** | `background-color: #fff` | Mude a cor |
| **Borda dos inputs** | `border: 2px solid rgba(...)` | Ajuste a espessura ou cor |
| **Arredondamento** | `border-radius: 40px` | Diminua para menos arredondado |

## 🖼️ Estrutura de Pastas

```
projeto/
├── index.html
├── style.css
└── img/
    └── pexels-joshsorenson-1714207.jpg
```

## ⚙️ Dicas

- **Fonte**: Está usando Rubik (importada do Google Fonts)
- **Ícones**: Usa Boxicons (já vinculado)
- **Imagem de fundo**: Coloque sua imagem na pasta `img/`git 