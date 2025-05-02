# Mario Kart 64 Multiplayer ROM Hack
### Fray's Emulator/Console Build (edited by leodexe)
This is a fork of abitalive's Mario Kart 64 Multiplayer Hack which was improved by Fray for better multiplayer experience on emulator and netplay. However there is a conflicting option that prevents MK64 Fray's mod to work on console, so I sacrificed netplay functionality for the sake of enabling console compatibility. If you are looking for Fray's build this will work for offline emulator/console gameplay, but not for netplay.

Este es un fork del hack de Mario Kart 64 Multiplayer de abitalive, que fue mejorado por Fray para mejor experiencia multijugador en netplay y emulador. Sin embargo hay un conflicto con una opción que no permite que el hack se pueda jugar en consola, por lo que sacrifiqué la funcionalidad de netplay para hacer que este hack sea compatible con la consola. Si estás buscando la versión de MK64 Fray's mod para jugar online, esta sirve para jugar sin conexión en emulador y consola, pero no para netplay.

# Changes
## New 15FPS and 20FPS Options for SCALING
- Added 15FPS and 20FPS options to the Scaling Selector, this is intended for use in console since emulators won't be able to emulate the proper pacing. This is useful to practice with a multiplayer 3-4 setting on single and two players.
- Not tested on console, works on Project64 and Nemu for the time being.

- Agregado opciones de 15FPS y 20FPS para el selector de Scaling, estas opciones están hechas para jugarse en consola, ya que los emuladores no son capaces de emular el cambio de velocidad de manera adecuada. Esto es útil si quieres practicar a la velocidad de multiplayer 3-4 en consola con 1 ó 2 jugadores.
- No ha sido testeado en consola, funciona en Project64 y Nemu por el momento.

## New "DISABLE" Option for ITEMS
- Added "Disable" option to the Items Menu. It disables all items boxes, except one in Luigi Raceway and one in Koopa Troopa Beach that always gives Blue Shells. This does not affect Time Trial as you can still freely use the Triple Mushrooms while items are disabled. CPU players will continue to use items in Grand Prix, though. This option will also disable items in Battle Mode.
- Untested on console, works on Project64 and Nemu for the time being.

- Agregado opción "Disable" en el menú de Items. Esto desactiva todas las cajas de objetos, excepto una en Luigi Raceway y una en Koopa Troopa Beach que siempre dan Caparazones Azules. Esto no afecta el Time Trial ya que aun puedes usar los Triple Hongos aun con los items desactivados. Aunque Los jugadores CPU aun podrán usar items en Grand Prix. Esta opción también desactivará los items en Modo Batalla.
- No testeado en consola, funciona en Project64 y Nemu por el momento.

## New TITLE MENU Options
### Lag Fix (Default / Enabled)
- This hack prevents the game from slowing down in 4 player matches, intended for use only with emulators. Not compatible with console and other emulators like Nemu64 and M64PlusFz.
- This setting was removed from this build due to being console incompatible.

- Este hack reduce el lag en partidas multijugador, está hecho para usarse con emuladores, no es compatible con la consola y otros emuladores como Nemu64 y M64PlusFZ.
- Esta opción fue removida de esta build debido a que es incompatible con la consola.

### VS Bomb Karts (Default / Disabled)
- Mini Bomb Karts can now be disabled for VS modes
- This does not affect Battle Mode Bomb Karts, so you still turn into a Bomb Kart after you lose all your balloons.

- Ahora puedes desactivar las bombas en modo VS.
- Esto no afecta las bombas del modo Batalla, por lo que aun te conviertes en un carro bomba después de que pierdas todos tus globos.

### Polling Rate (Default / 30Hz)
- This hack forces the input polling rate to remain at 30Hz when the game pacing is set to 60 FPS.
- This setting is disabled by default, because a lower polling rate implies your inputs will be more inaccurate when playing offline on emulator and console. But it can help prevent the game from lagging when playing online.

- Este hack fuerza la tasa de sondeo para que permanezca en 30Hz cuando la velocidad está en 60FPS.
- Esta opción está desactivada por defecto, puesto que una menor tasa de sondeo implica que tus movimientos serán menos precisos al jugar offline en emulador y consola. Sin embargo, es útil en netplay para reducir el lag.

## Modified TITLE MENU Options
### Game Pacing
- Added a hack which makes the game run at 60 FPS when the 60 FPS pacing option is selected. On console, without overclock the only track you can play at 60FPS is Rainbow Road, if you have a console with overclock you may also try other tracks.
- Añadido un hack que permite que el juego corra a 60FPS cuando la opción de 60FPS está seleccionada. En consola, sin overclock la única pista que se puede jugar a 60FPS es Rainbow Road. Si tienes una consola con overclock podrías probar otras pistas.

### Reorganized Menu Options
- Moved Character Stats and Game Pacing options to the top of the list.
- Movido Character Stats y Game Pacing options a la parte alta del menú.

### Changed Default Settings
- Character Stats are **now again** All Yoshi by default.
- Character Stats **vuelve a ser** All Yoshi por defecto.

- Game Pacing is back again to default, which is intended for use with non-overclocked consoles. If you are playing on emulator or have an overclocked console, select 30 or 60FPS.
- Game Pacing vuelve a ser default, esta opción debe usarse en consolas sin overclock. Si estás jugando en emulador o tienes una consola con overclock, selecciona 30 o 60FPS.

- Trophy Ceremony is back to it's default setting.
- Trophy Ceremony vuelve a su opción por defecto.

- Multiplayer Music is now enabled by default.
- Multiplayer Music ahora está activado por defecto.

# Building (Windows)
- Clone or download the repository.
- Put "Mario Kart 64 (U) [!].z64" in the LIB directory.
- Download and extract [these files](https://drive.google.com/file/d/0B1g_ALmgbOzxSDdWVVA4TXdwWlk/view?usp=sharing) to the Multiplayer_Hack directory.
- Drag and drop mk64_multiplayer_hack.asm onto asm.cmd

- Clona o descarga el repositorio.
- Pon "Mario Kart 64 (U) [!].z64" en el directorio LIB.
- Descarga y extrae [estos archivos](https://drive.google.com/file/d/0B1g_ALmgbOzxSDdWVVA4TXdwWlk/view?usp=sharing) dentro de la carpeta Multiplayer_Hack.
- Arrastra y suelta mk64_multiplayer_hack.asm hacia asm.cmd

# Acknowledgements
- Special thanks to Fray, he's a cool dude.
- Special thanks to Triclon, too, I wouldn't have discovered the amazing group of OverKart64 if he hadn't reply my email. Also helped me a lot with his advice.
- Huge thanks to Rain, helped a lot with the Disable Items code.
- And finally thanks to abitalive himself for this wonderful hack and his crew who also worked to keep alive the competitive community of Mario Kart 64.
[See my Documentation and some MK64 Gameshark codes](https://pastebin.com/D7J2L5yu)

# Reconocimientos
- Agradecimientos especiales a Fray, es un tipo genial.
- También a Triclon, no habría descubierto este maravilloso grupo de OverKart64 si él no hubiera respondido mi correo. Me ayudó mucho con sus consejos.
- Muchas Gracias a Rain, me ayudó bastante con el código para Desactivar Items.
- Y finalmente, gracias a abitalive mismo por este maravilloso hack, también agradezco a su equipo por mantener viva a la comunidad competitiva de Mario Kart 64.
[Mira mi documentación y algunos códigos Gameshark](https://pastebin.com/D7J2L5yu)
