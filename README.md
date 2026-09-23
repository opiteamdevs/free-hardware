# 📱 Adeus, Coleira Digital (Digital Collar)

> O celular é seu, o hardware é seu, mas quem manda nele é a lojinha de aplicativos? Chega disso.

Um manifesto e guia de resistência digital para desenvolvedores, entusiastas e usuários que estão cansados de jardins murados, telemetria invisível e restrições absurdas impostas em nome de uma suposta "segurança".

## 🛑 Qual é a Ideia?

As grandes corporações e os sistemas financeiros transformaram o smartphone em uma algema dourada. Se você ativa o **Modo Desenvolvedor** para trabalhar, é tratado como criminoso por apps de bancos. Se você ousa destravar o **Bootloader**, perde o acesso aos seus próprios serviços. 

Este repositório existe para incentivar a soberania digital, o uso de alternativas livres (como PWAs e F-Droid) e o retorno do verdadeiro controle do hardware para as mãos de quem comprou.

## 💻 Comandos Úteis (ADB)
Quer começar a limpar os serviços indesejados e recuperar o fôlego do seu aparelho? Veja alguns comandos básicos de ADB (Android Debug Bridge):

```bash
# Verificar se o dispositivo está conectado
adb devices

# Listar pacotes instalados no sistema
adb shell pm list packages

# Desinstalar / desativar pacotes do usuário atual (ex: serviços desnecessários)
adb shell pm uninstall -k --user 0 com.google.android.gms
