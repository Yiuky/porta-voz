# Política de privacidade — Porta-Voz

Última atualização: 12 de outubro de 2026.

O Porta-Voz é um assistente que faz e atende ligações telefônicas e ajuda com mensagens usando inteligência
artificial, a partir do seu celular. Esta política explica que dados o app usa, para quê e para onde vão.

## 1. Resumo
- O app **não tem servidor próprio** e **não vende nem compartilha** seus dados com anunciantes. Não há anúncios.
- Gravações, conversas escritas e o histórico **ficam no seu celular**.
- Para a IA conversar na ligação, o **áudio da ligação** é enviado em tempo real ao **Google (Gemini)**, pela chave
  de IA que **você** cadastra. Textos que você pede à IA (montar uma tarefa, sugerir uma resposta) vão ao provedor de
  IA de texto que você escolher (Google, OpenAI ou Anthropic).
- Nada é enviado a outros destinos sem você configurar (webhook, Gmail, apps de automação).

## 2. Dados usados e finalidade

| Dado | Para quê | Onde fica / para onde vai |
|---|---|---|
| Áudio da ligação (as duas vozes) | A IA ouvir e falar na ligação | Enviado ao Google Gemini durante a ligação; não é guardado pelo app fora do celular |
| Gravação e transcrição | Seu histórico e a revisão do que foi dito | No celular; sai só se você exportar ou compartilhar |
| Número e nome de quem você liga ou de quem liga para você | Fazer a ligação, mostrar o histórico, anotar recados | No celular; o número e o objetivo podem ir ao Google para pesquisar a empresa antes de ligar (opção desligável) |
| Seus dados do perfil (nome, cidade, endereço, e-mail, telefone, CPF, outros) | A IA informar **somente quando pedirem** na ligação | No celular (CPF cifrado); vão para a IA apenas na instrução da ligação; o CPF só com a opção ligada |
| Chaves de IA e senha do Gmail | Acessar os serviços que você escolheu | Cifradas no celular (Android Keystore); vão só para o respectivo serviço |
| Contatos | Achar o número pelo nome (opcional) | Lidos no celular; nome e número escolhidos entram na tarefa |
| Agenda | Ver horários ocupados e marcar compromissos que você decidiu (opcional) | Para a IA vão só horários ocupados, sem títulos |
| Localização aproximada (bairro/cidade) | Tarefas "aqui perto" (opcional) | Na tarefa enviada à IA de texto |
| Notificações de mensagens (WhatsApp, SMS, Telegram) | A secretária ler e responder **só as conversas que você liberar** (opcional) | No celular; o texto da conversa vai à IA de texto para sugerir a resposta |
| E-mails do Gmail (opcional) | Encontrar dados seus para uma tarefa e enviar o resumo das ligações ao seu próprio e-mail | Trechos vão à IA de texto; o resumo vai à sua própria caixa |
| Microfone | Palavra de ativação "Fala, Porta-Voz" e modo voz (opcional) | Reconhecimento da palavra feito no celular (offline) |
| Denúncias de conteúdo | Melhorar o app e coibir respostas impróprias | No celular e, se você enviar, por e-mail ao desenvolvedor |
| Registros técnicos (diagnóstico) | Suporte, quando **você** pedir | Arquivo gerado no celular, sem gravações nem chaves e com números longos mascarados |

## 3. Serviços de terceiros
- **Google Gemini** (voz e texto), **OpenAI** e **Anthropic** (texto, se escolhidos): processam o conteúdo enviado
  conforme as políticas de cada um, com a chave cadastrada por você.
- **Google (Entrar com Google / Gmail API)**: apenas se você conectar o Gmail. O uso dos dados do Gmail segue a
  Política de Dados do Usuário dos Serviços de API do Google, incluindo os requisitos de uso limitado.

## 4. Gravação de ligações
A gravação é opcional (Ajustes). Com o aviso ligado (padrão), a IA informa no início que a ligação é gravada. Você é
responsável por usar o app conforme a lei aplicável às ligações que faz.

## 5. Seus controles
- Ligar ou desligar cada recurso em Ajustes (gravação, agenda, localização, Gmail, secretária, pesquisa na web).
- Apagar ligações, roteiros, conversas e denúncias no app; desinstalar remove todos os dados do celular.
- Desconectar o Gmail no app e revogar o acesso na sua Conta Google.

## 6. Segurança
Comunicação cifrada (TLS) com os serviços; chaves e dados sensíveis cifrados com o Android Keystore; o componente de
áudio só aceita conexões do próprio app.

## 7. Crianças
O app não é destinado a menores de 18 anos.

## 8. Contato
Dúvidas ou pedidos sobre privacidade: pelo e-mail de contato informado na página do app na Google Play.

## 9. Mudanças
Esta política pode ser atualizada; a data no topo indica a versão vigente.
