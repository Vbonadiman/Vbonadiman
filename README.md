## Victor Bonadiman

Técnico de TI numa indústria em Chapecó, Santa Catarina — parque de máquinas,
rede, servidores e ativos. Os sistemas que estão aqui não são a minha função:
escrevi por iniciativa própria, porque sei fazer e porque a operação precisava
deles.

Antes disso foram dois anos de suporte técnico e um de instalações elétricas —
eu cheguei ao software pelo lado de quem usa e conserta. Curso Ciência da
Computação na Unochapecó.

**[Estudos de caso dos meus sistemas →](https://github.com/Vbonadiman/portfolio)**

## Em produção hoje

Projetei, escrevi e mantenho os dois, desde 2024. **São de código fechado** —
aqui está a engenharia, não a fonte.

### Supervisório industrial

*Um painel na fábrica que mostra o que os equipamentos da linha estão fazendo
agora, e guarda o que fizeram.*

- Acompanha todos os registradores de cada equipamento em tempo real, e atualiza
  a tela sem recarregar a página
- Guarda o histórico em banco na própria máquina.
- Alertas configurados por equipamento, incluindo a exposição a NH₃ nos
  analisadores de amônia
- Hoje na linha: mais de 200 equipamentos — insensibilizadores, hidrômetros
  e analisadores de amônia

Comunica MQTT pela rede ou Modbus serial RS485, e qual dos dois
é escolha do usuário.

Na máquina da planta não há nada instalado: Node e PHP vão embarcados no próprio
pacote e o sistema sobe por um executável. A fábrica não é lugar de pedir
instalação de runtime.

Node.js · Express · Socket.IO · SQLite · JWT

### Gestor de acessos e licenças

*O cofre de contas, senhas e licenças de software das quatro empresas do grupo,
com registro de quem mexeu em quê.*

- Uma linha por conta: senha, 2FA, e-mail de recuperação e situação
- Licenças presas à conta — produto, plano, custo e renovação —, que é o que
  responde "quais licenças estão neste e-mail, e quanto custam"
- Três níveis de permissão, e quais empresas cada pessoa enxerga
- Tudo que alguém faz fica registrado, com nome e hora
- Ativos de TI com etiqueta QR: quem está na frente da impressora quebrada
  aponta o celular e abre o chamado dali mesmo, sem conta e sem login
- Puxa contas e licenças direto do provedor de identidade, com uma credencial de
  administrador por empresa

Node.js · Microsoft Graph · exceljs · qrcode

## Código aberto aqui

**[Animacoes](https://github.com/Vbonadiman/Animacoes)** — peças de animação e
de interface tiradas desses sistemas, todas sem dependência. A primeira é a
`particulas-logo`: pontos que se juntam e formam uma logo, 19 KB e sem bundler.

## Agora

Construindo um ERP com CRM: compras, estoque, produção, clientes e a
rastreabilidade de cada equipamento que sai da fábrica, do número de série até o
cliente que comprou.
**[O que já está de pé →](https://github.com/Vbonadiman/portfolio/tree/main/gestao-suprimentos)**

Também extraindo mais peças dos sistemas para o `Animacoes`, e estudando
inteligência artificial e desenvolvimento de software.

Aberto a oportunidades como desenvolvedor.

Os sistemas são fechados; as decisões não. Se quiser saber por que alguma delas
foi tomada daquele jeito, pergunte — ou peça uma demonstração ao vivo.

---

📍 Chapecó, SC · 📫 bonadiman2001@gmail.com · [LinkedIn](https://www.linkedin.com/in/victor-bonadiman-961106251)
