# Dashboard Atados

Snapshot publico e estatico dos indicadores agregados de doacoes da Atados.

- periodo publicado: 01/11/2024 a 15/09/2026;
- ultima atualizacao: 15/09/2026;
- fonte dos agregados: TrackMob (doacoes), RD Station (automacoes de e-mail) e Snov.io (cadencias de e-mail);
- atualizacao: automatica (diaria);
- privacidade: nao contem nomes, e-mails, documentos, telefones, tokens ou IDs individuais.

O site esta organizado em cinco visoes: Geral, Doacoes pontuais, Doacoes
recorrentes, RD Station e Snov.io.

A visao de recorrentes classifica cada pessoa que declarou doacao mensal em um
unico estado (em confirmacao, nao confirmado, confirmado e ativo, confirmado e
parou, nunca pagou), seguindo as regras de negocio vigentes do projeto.

A visao Snov.io mostra as cadencias automaticas de e-mail alimentadas a partir
da TrackMob: quantas pessoas se encaixam em cada cadencia, quantas foram
contatadas e o resultado de entrega, abertura, clique e resposta. Campanhas
fora das cadencias de doacao aparecem separadas e ficam fora dos totais.

O site nao consulta APIs no navegador. As credenciais permanecem somente na
automacao que gera o snapshot.
