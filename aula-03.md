# Criado por: Pablo Henrique D. D. de Lima

# 📝 Resumo da Aula 03 - Desenvolvimento Web

## 🔄 Versionamento

O **versionamento** é o controle das alterações realizadas em um projeto ao longo do tempo. Ele permite registrar mudanças, recuperar versões anteriores e acompanhar a evolução do código.

Com o versionamento, é possível:

* Saber quem fez alterações
* Voltar para versões anteriores
* Trabalhar em equipe sem conflitos

Ferramentas como o Git são amplamente utilizadas para esse controle.

---

## 💾 Backup

O **backup** é a cópia de segurança de arquivos ou sistemas, com o objetivo de evitar perda de dados.

Ele é utilizado principalmente para:

* Recuperação em caso de falhas
* Proteção contra perda de arquivos
* Armazenamento seguro de informações

---

## ⚖️ Diferença entre Versionamento e Backup

Embora pareçam semelhantes, eles possuem funções diferentes:

* **Versionamento:** controla e registra mudanças ao longo do tempo
* **Backup:** apenas armazena cópias de segurança

Ou seja, o versionamento acompanha a evolução do projeto, enquanto o backup protege contra perda de dados.

---

## 🏷️ Nomeação (Tags) e Versionamento Semântico

A **nomeação por tags** é utilizada para marcar versões específicas de um projeto.

Um padrão comum é o **Versionamento Semântico (SemVer)**, que utiliza três números:

* **Major (X):** mudanças grandes que quebram compatibilidade
* **Minor (Y):** novas funcionalidades sem quebrar o sistema
* **Patch (Z):** correções de bugs

Exemplo:

```
1.2.3
```

* 1 = major
* 2 = minor
* 3 = patch

---

## ⭐ Importância do Versionamento

O versionamento é essencial no desenvolvimento de software porque:

* Garante organização do código
* Facilita o trabalho em equipe
* Permite rastrear erros
* Possibilita العودة a versões anteriores com segurança
* Ajuda no controle de releases

---

## 🚀 Deploy

O **deploy** é o processo de publicar uma aplicação para que ela fique disponível na internet.

Na aula, foi apresentada a ferramenta **Vercel**, muito utilizada para hospedar projetos web.

### 🔁 Fluxo de Deploy

O processo funciona da seguinte forma:

1. O código é desenvolvido localmente
2. É enviado para um repositório no GitHub
3. O Vercel se conecta ao GitHub
4. Sempre que há atualização no repositório, o Vercel faz o deploy automaticamente

### 🌐 Caminho do Projeto

```
Computador → Git → GitHub → Vercel → Site no ar
```

Esse processo permite automação, rapidez e facilidade na publicação de projetos web.

---

## 💭 Considerações sobre a aula

A aula apresentou conceitos fundamentais como versionamento, backup e deploy, que são essenciais para o desenvolvimento web moderno. Além disso, foi possível entender como ferramentas como GitHub e Vercel trabalham juntas para automatizar a publicação de aplicações, tornando o processo mais eficiente e seguro.

