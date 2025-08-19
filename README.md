# 🚀 Python Exemplos Desktop

> Exemplos de uso para desktop - Aplicações modernas com interface gráfica e terminal

<div align="center">

![Python](https://img.shields.io/badge/Python-3.7+-blue?style=for-the-badge&logo=python)
![CustomTkinter](https://img.shields.io/badge/CustomTkinter-Moderno-green?style=for-the-badge)
![ttkbootstrap](https://img.shields.io/badge/ttkbootstrap-Temas-orange?style=for-the-badge)
![SQLite](https://img.shields.io/badge/SQLite-Banco_de_Dados-lightblue?style=for-the-badge&logo=sqlite)

</div>

## ⚡ Início Rápido

```bash
git clone https://github.com/SesiSenaiDA2025/python_exemplos_desktop.git
pip install customtkinter ttkbootstrap pillow
python app.py  # Executar o sistema completo
```

## 🎯 Projetos em Destaque

<table>
<tr>
<td width="50%">

### 🖥️ **Sistema de Cadastro Completo**
Aplicação completa com autenticação, operações CRUD e interface moderna
- **Pasta**: `com interface/7-py-cadastro`
- **Arquivo**: `app.py`
- **Recursos**: Sistema de login, banco SQLite, troca de temas
- **Tech**: CustomTkinter + SQLite

</td>
<td width="50%">

### 🧮 **Calculadora Inteligente**
Calculadora profissional com operações avançadas e temas
- **Pasta**: `com interface/4-py-calculadora`
- **Arquivo**: `calculadora.py`
- **Recursos**: Operações científicas, seletor de temas, design moderno
- **Tech**: ttkbootstrap + Math

</td>
</tr>
<tr>
<td width="50%">

### 🔐 **Gerador de Senhas**
Gerador de senhas seguras com comprimento personalizável
- **Pasta**: `com interface/5-py-senha`
- **Arquivo**: `senha.py`
- **Recursos**: Geração aleatória, integração clipboard, validação
- **Tech**: CustomTkinter + Random

</td>
<td width="50%">

### 📐 **Calculadora Trigonométrica**
Ferramenta educacional para cálculos trigonométricos
- **Pasta**: `com interface/3-py-interface-trigonometria`
- **Arquivo**: `interface3.py`
- **Recursos**: Feedback visual, validação de entrada, suporte a imagens
- **Tech**: Tkinter + PIL + Math

</td>
</tr>
<tr>
<td colspan="2">

### 🖤 **Sistema de Restaurantes (Terminal)**
Aplicação completa via linha de comando com banco de dados
- **Pasta**: `sem interface/sabor-express_(Normal)`
- **Arquivo**: `app.py`
- **Recursos**: Menu interativo, CRUD completo, armazenamento SQLite
- **Tech**: Python puro + SQLite

</td>
</tr>
</table>

## 🛠️ Tecnologias

| Biblioteca | Propósito | Projetos |
|------------|-----------|----------|
| **CustomTkinter** | Componentes UI modernos | Gerador de Senhas, Cadastro |
| **ttkbootstrap** | Widgets com temas Bootstrap | Calculadora, Formulários |
| **Tkinter** | Interface nativa do Python | Interfaces básicas |
| **SQLite3** | Banco de dados local | Gerenciamento de usuários |
| **PIL/Pillow** | Processamento de imagens | Ícones e gráficos |

## 🎨 Características Principais

- 🌓 **Temas escuro/claro** com alternância suave
- 🔒 **Sistema de autenticação** com login seguro
- 💾 **Operações de banco** (Criar, Ler, Atualizar, Deletar)
- ✅ **Validação em tempo real** para entradas do usuário
- 🎯 **Design moderno** seguindo tendências atuais de UI
- 📱 **Layouts responsivos** que se adaptam ao tamanho da janela

## 📁 Estrutura dos Projetos

```
📦 python_exemplos_desktop
├── 📁 com interface/
│   ├── 🔐 1-py-interface/              # Interface básica
│   ├── 📊 2-py-interface-radio/        # Controles avançados
│   ├── 🎨 3a-ttkbootstap/              # Interface moderna
│   ├── 📐 3-py-interface-trigonometria/ # Calculadora trigonométrica
│   ├── 🧮 4-py-calculadora/            # Calculadora completa
│   ├── 🔑 5-py-senha/                  # Gerador de senhas
│   ├── 💾 6-py-banco-dados/            # Sistema modular
│   ├── 👥 6-py-banco-dados-(Alunos)/   # Versão para alunos
│   └── 🖥️ 7-py-cadastro/              # Sistema completo
└── 📁 sem interface/
    ├── 🍽️ sabor-express_(Normal)/      # Sistema restaurantes básico
    └── 🗄️ sabor-expess_(Grava)/        # Sistema com banco SQLite
```

## 🚀 Executar Qualquer Projeto

### Projetos com Interface Gráfica:
```bash
cd "com interface/4-py-calculadora"
python calculadora.py                    # Calculadora

cd "../5-py-senha"  
python senha.py                         # Gerador de Senhas

cd "../7-py-cadastro"
python app.py                          # Sistema Completo
```

### Projetos de Terminal:
```bash
cd "sem interface/sabor-express_(Normal)"
python app.py                          # Sistema básico

cd "../sabor-expess_(Grava)"
python app.py                          # Sistema com banco
```

## 💡 Caminho de Aprendizado

### Para Interface Gráfica:
1. **Comece com**: `1-py-interface/interface.py` - Conceitos básicos de GUI
2. **Avance para**: `4-py-calculadora/calculadora.py` - Layout e eventos
3. **Avançado**: `7-py-cadastro/app.py` - Arquitetura de aplicação completa

### Para Aplicações Terminal:
1. **Básico**: `sabor-express_(Normal)/app.py` - Lógica e estruturas
2. **Avançado**: `sabor-expess_(Grava)/app.py` - Persistência de dados

---

<div align="center">

**Desenvolvido com ❤️ usando Python**

[⭐ Favoritar este repo](.) • [🐛 Reportar problemas](.) • [🤝 Contribuir](.)

</div>