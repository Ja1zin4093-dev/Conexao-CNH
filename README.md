# Conexão CNH

## Descrição do projeto

O **Conexão CNH** é um aplicativo mobile que conecta alunos em processo de habilitação a instrutores de trânsito credenciados e autoescolas.

Pelo aplicativo, o aluno pesquisa prestadores próximos, filtra por preço, serviço, avaliação e disponibilidade, compara opções, consulta a agenda e solicita a aula prática. O instrutor ou a autoescola recebe a solicitação, aceita ou recusa, gerencia seus horários e conversa com o aluno. Após a aula realizada, o aluno avalia o serviço.

A plataforma conta ainda com um ambiente administrativo responsável pela validação do credenciamento dos prestadores, pela moderação de avaliações e pela análise de denúncias.

## Problema abordado

Quem está tirando a primeira habilitação enfrenta um mercado fragmentado e sem transparência:

- Não existe um canal centralizado que reúna instrutores e autoescolas disponíveis; a busca depende de indicação informal.
- Preços, serviços e cargas horárias não são comparáveis antes do primeiro contato.
- O aluno não tem meio prático de verificar se o instrutor é de fato credenciado.
- O agendamento é feito por telefone ou mensagem, sem registro estruturado, o que gera conflitos de horário.
- Não há histórico de avaliações que sirva de referência sobre a qualidade do serviço.

Do outro lado, instrutores autônomos e autoescolas de menor porte têm pouca visibilidade e dependem quase exclusivamente do boca a boca para conseguir alunos.

## Objetivos

### Objetivo geral

Desenvolver um aplicativo mobile que centralize a busca, a comparação e o agendamento de aulas práticas de direção, oferecendo transparência ao aluno e visibilidade aos prestadores de serviço.

### Objetivos específicos

1. Permitir a busca de instrutores e autoescolas por localização, preço, serviço, avaliação e disponibilidade.
2. Oferecer uma ferramenta de comparação entre prestadores.
3. Disponibilizar um módulo de agenda com cadastro de disponibilidade e bloqueio de horários.
4. Implementar o fluxo completo de solicitação e agendamento de aulas.
5. Prover um canal de comunicação integrado entre aluno e prestador.
6. Registrar avaliações vinculadas a aulas efetivamente realizadas.
7. Construir um ambiente administrativo para validação de credenciamento, moderação e denúncias.
8. Modelar um banco de dados relacional normalizado, com integridade referencial e regras de negócio garantidas no SGBD.

## Integrantes da equipe

- João Gabriel Rocha Rosa
- Hugo Thiago

## Principais tecnologias previstas

### Aplicativo mobile
- **React Native com Expo** — desenvolvimento multiplataforma (Android e iOS)
- **TypeScript** — linguagem do aplicativo
- **Expo Router** — navegação entre telas
- **TanStack Query** — consumo da API e gerenciamento de estado

### Backend
- **PHP 8.3 com Laravel 11** — API REST
- **Laravel Sanctum** — autenticação por token
- **Eloquent ORM** — mapeamento objeto-relacional
- **Filament** — painel administrativo

### Banco de dados
- **MySQL 8.0** — SGBD relacional
- **MySQL Workbench** — modelagem do DER
