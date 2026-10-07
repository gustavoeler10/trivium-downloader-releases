# Trivium Downloader

Canal público de instaladores e atualizações para macOS. O código de desenvolvimento é mantido separadamente.

[Baixar a versão mais recente](https://github.com/gustavoeler10/trivium-downloader-releases/releases/latest)

Para Macs com Apple Silicon e macOS 14 ou posterior. Abra o DMG e copie Trivium Downloader.app para Aplicativos ou outra pasta gravável. Abra a cópia instalada, fora do DMG. O pacote inclui as ferramentas para baixar músicas e vídeos MP4.

A primeira abertura pode exigir Ajustes do Sistema > Privacidade e Segurança > Abrir Mesmo Assim. Esta edição não possui Developer ID nem notarização Apple. Não é necessário desativar proteções do macOS.

A partir da versão 0.5.0, o app verifica novas versões e prepara atualizações automaticamente. Também há Verificar atualizações no menu Trivium Downloader. As preferências ficam nos Ajustes do app. Downloads em andamento terminam antes do reinício para atualizar. O canal não exige conta ou login; qualquer pessoa com este endereço pode baixar o instalador.

Pacotes e catálogo são assinados com Ed25519 e conferidos pelo Sparkle. O SHA256SUMS de cada release permite conferir os arquivos baixados. Isso não substitui a assinatura Developer ID da Apple.

Licenças acompanham o aplicativo. Fontes exatas e instruções de recompilação de FFmpeg/LAME estão em Fontes no DMG. Referências dos componentes: [Sparkle](https://github.com/sparkle-project/Sparkle), [yt-dlp](https://github.com/yt-dlp/yt-dlp), [FFmpeg](https://ffmpeg.org/), [LAME](https://lame.sourceforge.io/), [CPython standalone](https://github.com/astral-sh/python-build-standalone), [Node.js](https://nodejs.org/).

Use links públicos de conteúdos que você pode baixar. Login, cookies, conteúdos privados e DRM não são suportados nesta edição.
