# Hackathon 1 — Capacitação Trainees 26.2

Enunciado completo: [`Hackathon1_Capacitacao_Trainees_26.2.ipynb`](Hackathon1_Capacitacao_Trainees_26.2.ipynb)

## Passo 1: Fork (só uma pessoa do trio)

O fork cria uma cópia deste repositório na conta de vocês.

1. Abra esta página no GitHub.
2. Clique no botão **Fork** (canto superior direito) e depois em **Create fork**.

## Passo 2: Chamar os colegas (a mesma pessoa)

1. No repositório novo (o fork), vá em **Settings → Collaborators → Add people**.
2. Adicione os outros dois integrantes do trio.
3. Os colegas precisam aceitar o convite que chega por e-mail.

## Passo 3: Baixar para o computador (todos)

```bash
git clone https://github.com/USUARIO-DE-QUEM-FEZ-O-FORK/hackaton-trainee-1.git
cd hackaton-trainee-1
```

## Passo 4: Trabalhar e salvar

Sempre nesta ordem:

```bash
git pull                              # 1. baixa o que os colegas já fizeram
                                      # 2. (façam as mudanças no notebook e salvem o arquivo)
git add .                             # 3. separa as mudanças para salvar
git commit -m "o que vocês fizeram"   # 4. salva as mudanças com uma mensagem
git push                              # 5. envia para o GitHub
```

Exemplo de mensagem: `git commit -m "Implementa listar_presentes"`

## ⚠️ Importante

- **Só uma pessoa mexe no notebook por vez.** Os outros ajudam do lado. Depois de cada `push`, troquem quem está no teclado, e a próxima pessoa começa com `git pull`.
- Se o `git push` der erro, rode `git pull` e depois `git push` de novo.
- Apareceu a palavra **CONFLICT**? Chamem alguém da organização.
