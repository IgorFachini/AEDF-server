# AEDF-server
Servidor na pasta - Server 1.7.10 -

Iniciar o servidor com `run.bat` 

Servidor minecraft 1.7.10

Com mods do pacote Era Do Futuro

# Requisitos
Java, [Shinigama Launcher (Cliente minecraft)](https://teamshiginima.com/update/)

# Preparar cliente para rodar mods

Após baixar e rodar pelo menos uma vez o Shinigama Launcher, fechar o Shinigama e baixar o [Forge](https://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.7.10.html) na versáo 1.7.10, no instalador do forge, instalar apenas o cliente na pasta .minecraft(Pasta de instalaçáo do minecraft).

Após finalizado, abrir o Shinigama Launcher, em Edit Profile
deixar marcado as opçóes 
- User version: 
  1.7.10-Forge ( Ou algo parecido)
- JVM Arguments: 
  ATIVADO, contendo os parámetros
  `-Xmx1G -XX:+UseConcMarkSweepGC -XX:+CMSIncrementalMode -XX:-UseAdaptiveSizePolicy -Xmn128M`
  (Esses parámetros ja vem por padráo, mas caso náo venha, colocar....).

## Instalando Mods, Os mods necessarios para conseguir entrar no servidor

Os mods, devem ficar na pasta `mods` localizado na pasta (.minecraft) que pode ser encontrado no caminho exemplo: `C:\Users\Cyber10\AppData\Roaming\.minecraft`.

Nesse repositorio, basta copiar a pasta, `1.7.10` localizado em `Server 1.7.10/mods/1.7.10`, para a pasta mods de (.minecraft) do seu computador.

Pronto!!!, so iniciar o minecraft.

### EXTRAS, mod para mapa e vida dos mobs no seu cliente.
Nesse repositorio, em `Server 1.7.10` contem a pasta `modsClient`, com dois arquivos, basta copiar esses 2 arquivos para dentro `.minecraft/mods/1.7.10` do seu computador para habilitar o mapa e vida dos mobs.

# OBS

Quando iniciar o Launcher com os mods, náo fique clicando na Janela, ele trava sim para alguns, mas logo volta.
