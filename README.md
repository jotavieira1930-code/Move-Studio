# Move Studio · Beta

Uma demonstração local para personal trainers: apresente a ideia, cadastre alunos, organize sessões e monte planos de treino individuais.

## Iniciar no VS Code

1. Abra a pasta do projeto no VS Code.
2. Abra **Terminal → Novo Terminal**.
3. Rode `npm start`.
4. Abra <http://localhost:4173> no navegador.

O projeto usa somente o Node.js, sem bibliotecas externas. Requer Node 20 ou superior. Os dados ficam no arquivo `data/move-data.json`, criado automaticamente na primeira inicialização.

## Acessos de demonstração

| Perfil | E-mail | Senha |
|---|---|---|
| Personal | `personal@move.com` | `123456` |
| Personal · corrida | `fernanda@move.com` | `123456` |
| Personal · calistenia | `diego@move.com` | `123456` |
| Aluna Marina | `marina@email.com` | `123456` |
| Aluno Lucas | `lucas@email.com` | `123456` |
| Aluna Camila | `camila@email.com` | `123456` |

O personal pode cadastrar alunos com e-mail e senha inicial. Cada aluno entra no seu próprio perfil e vê apenas seus horários e planos.

Também é possível criar uma conta pela tela inicial como **aluno** ou **personal**.

## O que a beta demonstra

- Login e sessão local separados por papel (personal/aluno).
- Cadastro, edição e remoção de alunos.
- Calendário semanal e sessões com estados pendente, confirmado e cancelado.
- O aluno solicita um horário; o personal confirma ou cancela.
- O servidor bloqueia reservas sobrepostas e horários passados.
- Planos de treino individuais, com dia da semana, foco, exercícios, séries, intervalos e observações.
- Perfis públicos de personais com apresentação, especialidades, experiência, localização e avaliações.
- Busca para alunos conhecerem profissionais, enviarem uma pergunta pelo chat e pedirem um horário.
- Avaliações de 1 a 5 estrelas após uma sessão confirmada.
- Diário do aluno: passos, corridas, treinos concluídos e dias off.
- Metas semanais, sequência de registros, pontos XP, conquistas e gráficos de evolução.
- Atalho de ajuda com dicas de uso; o assistente contextual completo fica como próxima etapa.
- Lembrete do navegador 30 minutos antes de sessões confirmadas. Ative pelo ícone de sino e mantenha o app aberto.
- Layout responsivo para apresentar a proposta em desktop ou celular.

## Limites desta demonstração

Esta é uma beta para rodar em um computador local. O servidor escuta apenas em `127.0.0.1`; contas, sessões e dados não são compartilhados com outros dispositivos. As credenciais de demonstração são simples por escolha e não devem ser reutilizadas. Os lembretes dependem do navegador estar aberto e de a permissão estar ativada. Uma versão de produção precisaria de hospedagem, banco de dados gerenciado, recuperação segura de senha e entrega de notificações em segundo plano.
