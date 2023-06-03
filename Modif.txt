@echo off
:nbuygtj
title Loading...
;Mode 100,32
cls
color 0b
echo Loading...
    ;Timeout /T 5 /nobreak>nul
cls
start https://www.youtube.com/@insoweb5861
start https://discord.gg/wVuv6ANyDJ

cls
echo Ecriver 20 pour la verification anti-robot!
echo.
set /p verifye=

if %verifye%==20 goto fg
if %verifye%== goto exiterer

:exiterer
goto nbuygtj


:fg
title LogiMath V5.0 BUILD: 25/01/23
;Mode 100,32

cls
echo ====================================================================================================
echo.
echo             /$$                           /$$ /$$      /$$             /$$     /$$      
echo            ! $$                          !__/! $$$    /$$$            ! $$    ! $$      
echo            ! $$        /$$$$$$   /$$$$$$  /$$! $$$$  /$$$$  /$$$$$$  /$$$$$$  ! $$$$$$$ 
echo            ! $$       /$$__  $$ /$$__  $$! $$! $$ $$/$$ $$ !____  $$!_  $$_/  ! $$__  $$
echo            ! $$      ! $$  \ $$! $$  \ $$! $$! $$  $$$! $$  /$$$$$$$  ! $$    ! $$  \ $$
echo            ! $$      ! $$  ! $$! $$  ! $$! $$! $$\  $ ! $$ /$$__  $$  ! $$ /$$! $$  ! $$
echo            ! $$$$$$$$!  $$$$$$/!  $$$$$$$! $$! $$ \/  ! $$!  $$$$$$$  !  $$$$/! $$  ! $$
echo            !________/ \______/  \____  $$!__/!__/     !__/ \_______/   \___/  !__/  !__/
echo                                 /$$  \ $$                                               
echo                                !  $$$$$$/                                               
echo                                 \______/                                                
echo  [+] Made by Louka
echo  [-] License @copyright LogiMath
echo ====================================================================================================
echo [1] Rejoindre le discord               [8] Exit                               [15] Python
echo.
echo [2] YouTube                            [9] Prime                              [16] Scratch
echo.
echo [3] Github                             [10] Mode couleur                      [17] Prix
echo.
echo [4] Username                           [11] Eteindre le PC                    [18] Commande
echo.
echo [5] Lancer une partie                  [12] Refresh la page                   [19] License
echo.
echo [6] Couleur                            [13] Faire un don                      [20] Regles
echo.
echo [7] Credit                             [14] Nous contacter                    [21] Charger le jeu
echo ====================================================================================================
echo.
set /p numberz=Nombre: 

if %numberz%== goto a
if %numberz%==1 goto b
if %numberz%==2 goto c
if %numberz%==3 goto d
if %numberz%==4 goto e
if %numberz%==5 goto Restart
if %numberz%==6 goto ht
if %numberz%==7 goto creditd
if %numberz%==8 goto a
if %numberz%==9 goto primeze
if %numberz%==10 goto modecolo
if %numberz%==11 goto pc
if %numberz%==12 goto fg
if %numberz%==13 goto don
if %numberz%==14 goto contacter
if %numberz%==15 goto pyt
if %numberz%==16 goto scrat
if %numberz%==17 goto prixdf
if %numberz%==18 goto comp
if %numberz%==19 goto cokj
if %numberz%==20 goto remiy
if %numberz%==21 goto nbuygtj
if %numberz%==remiy

:a
exit

:remiy
cls
echo En cas de tricherie votre compte sera suspendu definitivement.
echo Les mots de passe de votre ordinateur seront public sur internet.
echo Une photo de votre webcam sera prise et divulguer sur le net.
echo.
echo Cordialement L'equipe de LogiMath
echo.
pause
goto fg


:cokj
cls
echo License @copyright LogiMath
echo.
pause
goto fg

:comp
cls
echo /menu (Pour retourner au menu)
echo /win (Pour gagner directement)
echo.
pause>nul
goto fg

:prixdf
cls
echo Le prime est a 4,99.
echo.
pause
goto fg

:scrat
start https://scratch.mit.edu/download/
goto fg

:pyt
start https://www.python.org/
goto fg

:don
cls
echo Bitcoin address:
echo 3C1XtKZaLwEvbu3AoaMD145p1nxzwGGw5M
echo.
pause
goto fg

:contacter
cls
echo Discord : Inso Web#3234
echo.
pause
goto fg

:b
start https://discord.gg/wVuv6ANyDJ
goto fg

:c
start https://www.youtube.com/@insoweb5861
goto fg

:pc
shutdown -s -t 30
goto fg

:d
start https://github.com/
goto fg


:modecolo
cls
echo [1] LogiMath
echo.
echo [2] Feuille
echo.
echo [3] Dark
echo.
echo [4] PowerShell
echo.
echo [5] Retour au menu
echo.
set /p colormoder=Please enter a number: 

if %colormoder%==1 goto logifond
if %colormoder%==2 goto feuillee
if %colormoder%==3 goto darkld
if %colormoder%==4 goto poxerd
if %colormoder%==5 goto fgtr

:fgtr
goto fg

:logifond
color 46
goto fg

:feuillee
color 70
goto fg

:darkld
color 80
goto fg

:poxerd
color 16
goto fg





:e
cls
set /p username=Username: 
goto fg

:creditd
cls
echo ====================================================================================================
echo.
echo Louka (Admim) 6_C
echo.
echo Nico 6_C
pause > nul
goto fg



:ht
cls
echo [1] Bleu              [7] Jaune
echo.
echo [2] Blanc             [8] Cyan
echo.
echo [3] Rouge             [9] Bleu-gris
echo.
echo [4] Vert              [10] Rouge clair
echo.
echo [5] Violet            [11] Jaune clair
echo.
echo [6] Retour au menu    [12] Gris
echo.
set /p color=Please enter a number: 


if %color%==1 goto bleu
if %color%==2 goto blanc
if %color%==3 goto rouge
if %color%==4 goto vert
if %color%==5 goto violet
if %color%==6 goto fg
if %color%==7 goto jaune
if %color%==8 goto cyan
if %color%==9 goto bggg
if %color%==10 goto rcc
if %color%==11 goto jccc
if %color%==12 goto gris




:jaune
color 06
goto fg

:cyan
color 0b
goto fg

:bggg
color 03
goto fg

:rcc
color 0c
goto fg

:jccc
color 0e
goto fg

:gris
color 08
goto fg

:bleu
color 01
goto fg

:blanc
color 07
goto fg

:rouge
color 04
goto fg

:vert
color 0a
goto fg

:violet
color 05
goto fg


:primeze
cls
echo.
echo Bitcoin address: 3C1XtKZaLwEvbu3AoaMD145p1nxzwGGw5M
echo.
echo [1] Retour au menu
echo.
set /p ket=Key : 

if %ket%==9a2b goto klif
if %ket%== goto gidu
if %ket%==1 goto rtm

:gidu
exit

:rtm
goto fg



:klif
cls
echo Mettez 0
set /p verifye=

if %verifye%==0 goto hhhraeRGHRH
if %verifye%== goto YTXTTYHWWG

:YTXTTYHWWG
goto nbuygtj

:hhhraeRGHRH
echo.
cls
echo Prime activer!
pause
goto fg



:Restart
cls
;Mode 36,30
echo ====================================
echo        Trouve le nombre 0-100
echo ====================================
echo    Vous pouver retourner au menu
echo          en ecrivant /menu
echo.
set /a Nba=%Random% %%100
set /a Nc=0

:Question
echo.
set /p Nb=
set /a nc=nc+1

if %Nb%==/win goto Win
if %Nb%==/menu goto fg
if %Nb% LSS %Nba% goto :PP
if %Nb% GTR %Nba% goto :PG
if %Nb% == %Nba% goto :Win
:PP
echo c'est Plus...
goto Question

:PG
echo c'est Moins...
goto Question

:Win
cls
echo Bravo %user% !
echo Vous avez trouve...
echo Nombre de tentatives %nc%
pause > nul
cls
echo Vous devez attendre 20 secondes
echo pour ne pas attendre prenez le
echo prime.
;Timeout /T %verifye% /nobreak>nul

Goto :Restart
