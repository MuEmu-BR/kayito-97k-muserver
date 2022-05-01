
# MuServer 0.97.11

## Events
* Devil Square
* Blood Castle

## Invasions
* Death King
* Red Dragon
* Goldens

## Bonus Manager
* Experience Rate
* Item Drop Rate
* Common Item Drop Rate
* Exe Item Drop Rate
* Reset Amount
* Grand Reset Amount

## Item Management
* Item Drop
* Item Option
* Item Option Rate
* Item Value
* Item Stack

## Item Bag Management
* ItemBagManager (Item, Monsters)
* ItemBag Normal
* ItemBag Advanced

## ChaosMix
* Chaos Weapon
* Wing 1
* Wing 2
* Devil Square Ticket
* Blood Castle Ticket
* Fruits
* Dinorant
* +10 ~ +11 Plus Level

## Character
* Damage PVP
* Damage PVM
* Reflect PVP
* Reflect PVM
* Damage x Class PVP
* Damage x Class PVM
* Damage Class x Class
* Stuck Rate
* Damage Multiplier
* Guardian Rate (Angel, Satan, Uniria, Dinorant)
* HP, MP, BP Recovery Rate
* Physic and Magic Damage Rate
* Attack Success Rate
* Attack Success Rate PVP
* Speed Rate
* Defense Rate
* Defense Success Rate
* Defense Success Rate PVP

## Skill
* Buffs Timers and Rates
* Skills Damage

## Client Info
* Launcher Block
* IpAddress, Port, Version, Serial
* Window Name, Screenshots Path
* Character Speed Settings
* Reconnect Time
* Rebuilded Window System (Fix Minimize and Window Mode)
* Resolutions from 640x480 to 1920x1080
* Camera 3D + Rotation FIX
* Multilanguage Text.bmd
* Reconnect System
* Stats and Numbers FIX (HP, MP, BP, Monster Damage)
* MiniMap With Zoom and Show/Hide with Tab
* Guild Logo View
* HealthBar (2 types)
* SkyDome (Like Skybox but rounded)
* And Some Important Fixes

## NOTA:
* Nome de usuário, senha e nome máximo de 10 caracteres
* Código pessoal 16 dígitos
* bloc_code 0 ou 1 (BAN)
* AccountLevel 0, 1, 2 ou 3 (VIP)
* AccountExpireDate GETDATE() + 5 -> Data de hoje + 5 dias VIP
* Bloc_Expire GETDATE() + 5 -> Data de hoje + 5 dias de BAN

    USE MuOnline97
    
    INSERT INTO MEMB_INFO (memb___id, memb__pwd, memb_name, sno__numb, bloc_code, AccountLevel, AccountExpireDate, Bloc_Expire)
    VALUES ('usuario', 'contraseña', 'nombre', 'personalcode', 0, 0, GETDATE(), GETDATE())
