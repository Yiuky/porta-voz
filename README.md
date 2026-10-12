# Porta-Voz — uma IA que faz ligações por você

O Porta-Voz é um app Android em que uma assistente de voz com inteligência artificial **liga por você**: cota preços,
marca horários, confere contas, navega nos menus automáticos ("digite 1 para…") e traz o resultado escrito.
**Você decide**: se aparecer um preço, um horário ou uma condição nova, ela pede um instante e pergunta a você na hora.

> Versão de teste, distribuída aqui até a chegada à Google Play. O código-fonte não é público.

## Baixar

Vá em **[Releases](../../releases/latest)** e baixe:

| Arquivo | Para quem |
|---|---|
| **Porta-Voz-0.3.0.apk** | Versão completa (recomendada para testar) |
| Porta-Voz-0.3.0-loja.apk | A mesma versão que irá para a Google Play (sem ler o registro de chamadas e sem enviar SMS direto) |

Conferência (SHA-256):
```
a32375ac7a87ec6466d7b5e56f5bfa803ec28a02976d4150159b67454e217dfe  Porta-Voz-0.3.0.apk
1b4b5f520b089bf7379a56284b1ad8ba80818e966f28dd539e1c45611467a947  Porta-Voz-0.3.0-loja.apk
```

## Requisitos
- Android 12 ou mais novo, com linha celular (a IA fala em ligações comuns, não no WhatsApp).
- Uma chave **gratuita** do Google Gemini (o app mostra onde pegar: aistudio.google.com/apikey).
- Wi-Fi na primeira ativação (veja abaixo).

## Instalar
1. Baixe o APK no celular e abra. Se o Android pedir, permita "instalar apps desta fonte".
2. Abra o Porta-Voz. No **Início**, siga a preparação:
   - **Motor de áudio:** ative as Opções do desenvolvedor (Configurações → Sobre o telefone → Informações do software →
     toque 7 vezes em "Número de compilação"), toque em **Parear (uma vez)**, ligue a Depuração sem fio, toque em
     "Parear o dispositivo com um código" e digite o código na notificação do Porta-Voz. Depois disso o app ativa o
     motor sozinho, inclusive ao reiniciar o celular (com Wi-Fi).
   - **Seu nome e a chave da IA:** preencha, toque em Testar e em Concluir.
3. Peça uma ligação no Início (por exemplo: "ligue para a padaria X e pergunte até que horas abre no domingo") e
   toque em **Ligar agora**.

Por que o "motor"? O Android não deixa um app comum falar e ouvir dentro de uma ligação; o motor roda com a permissão
que a Depuração sem fio concede, só no seu celular.

## O que ele faz
- Ligações com objetivo; lote (a mesma pergunta para vários contatos); retorno com a sua decisão.
- Menus automáticos: escolhe as opções, aprende o caminho de cada número e avisa quando o menu muda.
- Perguntas ao vivo com respostas de um toque na notificação; "assumir a ligação" a qualquer momento.
- Recepcionista: atende quando você não pode e anota o recado.
- Secretária de mensagens (conversas que você liberar).
- Histórico com gravação, transcrição, busca e "continuar a ligação"; ligar mais tarde.

## Privacidade
Sem servidor próprio e sem anúncios. Gravações e conversas ficam no seu celular; o áudio da ligação vai ao Google
Gemini pela **sua** chave. Leia a [política de privacidade](PRIVACIDADE.md).

## Observações desta versão de teste
- Quando o app chegar à Google Play, será preciso **desinstalar esta versão** antes de instalar a da loja (as
  assinaturas são diferentes); exporte o que quiser guardar pelo Histórico.
- Testado num Samsung Galaxy (Android 16, VoLTE). Outros aparelhos podem se comportar diferente: use **Ajustes →
  Enviar diagnóstico** e abra uma [issue](../../issues) contando o que houve.
- A IA se apresenta como assistente virtual e avisa quando a ligação é gravada. Use com responsabilidade.
