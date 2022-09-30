# Dofus Linux (fixed and updated)
##  Wineprefix autônomo

O script usa a versão Wine do Lutris, que inclui os patches de prótons da Valve, bem como outras correções criadas pela comunidade.

Adições/correções:
- o problema do jogo ficou em 56% no lançamento
- wineserver trava de tempos em tempos (jogo congelado)
- jogabilidade mais suave
- Suporte DXVK

NB: O script deve ser reiniciado após cada atualização!

##  Uso
###  Vinho
- copie o script no diretório do jogo, por padrão: ~/.config/Ankama/zaap/dofus (ctrl+h para ver arquivos ocultos)
- abra um terminal e execute ```./dofus-linux.sh configure```
- espere e feche o jogo
- reinicie o jogo via Ankama Launcher :)

###  DXVK
Se o seu hardware for compatível com vulkan, o script permite configurar o DXVK para Dofus.
- feche o jogo
- iniciar ```./dofus-linux.sh dxvk```
- reinicie o jogo via Ankama Launcher :)
