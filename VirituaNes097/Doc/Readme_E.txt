
VirtuaNES version 0.82 (C)2001-2003 Norix

///////////////////////////////////////////////////////
/// The sentence was got with translation software. ///
///////////////////////////////////////////////////////

============
= Abstract =
============

Be old days good old NES/Famicom emulators.

Think that most of software made in Japan work by the present situation.


================================
= Immunity from responsibility =
================================

This software is a freeware.

An author bears responsibility by no damage by this software at all.
Please use it in responsibility of each person.
An author doesn't bear duty of a revision / version up of this software.

Reproduction is basically free, but change archive contents, and please do not 
do distribution.


================
= Requirements =
================

OS:     Windows98/2000          95(probably it is necessary more than IE4.0)
                                Even Me and XP seem to work.
        DirectX7.0a or higher
CPU:    Pentium200 higher
VIDEO:  Video card for DirectDraw(required)
SOUND:  Sound card for DirectSound(required)
JOYPAD: When there is it, be convenience.:)

Note) MFC42.DLL became needless from v0.20.


======================
= Supported function =
======================

CPU                             All instruction inplemented.
SOUND                           Expansion sound support
                                (FDS,MMC5,VRC6,VRC7,NAMCO106,FME7)
Disk system                     Support(please put BIOS with a directory the 
                                         same as EXE)
Realtime save                   Support(FDS OK)
Drag and drop                   Support(ROM,State,Movie files)
Command line                    Support
Shortcut key                    Support(can change it)
JoyStick                        Support
Expansion controller            Support
Scanline                        Support(can coordinate brightness)
Full-Screen                     Support
8dot unit bank changing         Support
NSF player                      Support
Header revision with a database Support(Can use NesToy or a database file of 
                                        NNNesterJ, and rename it, and use it 
                                        for nesromdb.dat)
Archive files                   Support(LHA,ZIP,RAR,CAB. The details are written 
                                        towards the lower part. Can defrost ZIP 
                                        without DLL.)
Snapshot                        Support
TV frame display                Support
Launcher                        Support
Language plug-in                Support(plug-in is need by all means)
Movie                           Support(append record and rerecord support)

NetworkPlay                     Support(Refer to NetPlay_E.txt)

Cheat                           Support
GameGenie                       Support

PAL mode                        Support

================
= Installation =
================

Develop an archive in a suitable folder, and please put plug-in with the same 
folder.

--------------------------
Be assigned to Preferences
--------------------------

Most optional basic setting is finished by the first activation. Please change 
the back by liking. Think that the folder setting had better do it.

Note) Stored setting in INI from 0.30.

========
= Menu =
========

File(F)
        Open(O)                 Open a ROM file.
        Close(C)                Close a ROM file.(finish emulation)
        ---------------
        NetPlay(N)              Network play.
        Disconnect(D)           Network disconnect.
        Chat(A)                 Display chat window.
        ---------------
        Launcher(L)             Activate launcher.
        ---------------
        ROM Info(I)             Display information of a ROM file.
        WAVE record(W)          Tape it in a WAVE file.(only during emulation)
        ---------------
        Recent Path(P)          Display recent paths.(submenu)
        Recent File(F)          Display recent files.(submenu)
        ---------------
        Exit(X)                 Finish a program.

Edit(E)
        HW Reset(R)             Hardware reset.
        SW Reset(S)             Software reset.
        ---------------
        Pause(P)                Pause of emulation.(toggle)
        ---------------
        State load              Load a state file.
        State save              Save a state file.
        State slot              Can select a maximum 10 slot.
                                Please use it in accordance with the situation.
                                The activation back is always slot 0.
        ---------------
        Movie                   Can display playback and a record of a movie, 
                                information.
        ---------------
        Disk                    Can control a disk system.
        ---------------
        ExtController           Select an expansion controller.
        ---------------
        ExtDevice               Operate an expansion device.
        ---------------
        Snapshot(Z)             Store a current screen to bitmap file.

Option(C)
        Emulator(E)             Setting of an emulator.
        Graphics(G)             Setting of graphics.
        Sound(S)                Setting of sound.
        Controller(C)           Setting of a key arrangement of a controller.
	Joystick Axis Mode(J)	Setting of an analog axis of joystick.
        Shortcut key(K)         Setting of shortcut key.
        Folder(P)               Setting of folder.
        Language(L)             Setting of language plug-in.
        Movie(M)                Setting of Movie.
	Game option(O)		Setting of Game option.(only during emulation)
        ---------------
        FullScreen              Full-screen change.
        Zoom                    Select enlarged size in a window mode.
                                Enlarged size is 4 times from equal times.
        ---------------
        Display TV frame        Display a TV frame.
        FPS Display             Display FPS (the number of frame) in screen 
                                leaning to the left.
                                Display it only during emulation.

Tool(T)
        Cheat support(S)        Activate a cheat code support function.
                                When a cheat support window opens, cannot open 
                                cheat code DIALOG.
        Cheat code(C)           Do a cheat input by code and a load / save.
        -----------------
        Cheat enable(E)         Do enable of all cheat codes.
        Cheat disable(D)        Do disable of all cheat codes.
        -----------------
        GameGenie(G)            Load GameGenie code.
        -----------------
        Viewer(V)               Display various Viewer.

Help(H)
        About(A)                Display information of this program.

===========
= Setting =
===========

-Common-

Default
        Be buttons vomiting each setting item in an initial value.

----------------
Emulator setting
----------------

-CPU core -
Ignore illegal opcode
        Be the setting that you do how when you executed illegal opcode of 
        6502.
        Please use it with OFF basically.
        It is most about the thing which doesn't work well that a bug and a 
        blister of this program can't well.

-Peripheral equipment-
Enable NES 4 plyaer adapter
        Handling of a 4 player adapter is different in NES and Famicom, and 
        there can be the thing that doesn't work by a game well.
        Please try to change this option then.

-Frame rate control-
Auto frame skip
        Work by maximum speed when takes off this option not to coordinate a 
        frame rate.

Throttle use
        Let you work by the frame rate that this option overwhelms shortcut key 
        (toggle) during games, and was appointed.
        This function doesn't act that an auto frame skip is OFF.

slider bar
        Can set a frame rate in a Throttle mode by 10 frame chopping fine.
        Can set it from minimum 10 FPS (1/6 double speed) to maximum 180 FPS 
        (3 double speed).

Disksystem throttle use
        Make you ON when does it in access of a disk system at high speed.

-Others-
Prohibiton of double activation
        Be the options which do not let you start when VirtuaNES started 
        already.
        Send a command line, and the one that started already can start 
        emulation a command line when uses this option that it starts.

Switch to fullscreen on ROM load
        Be options to turn into full-screen with emulation start.

CRC check of state/movie
        When CRC of an image is different, be options canceling reading.
        Establish it for security. Be movement guarantee outside when let you 
        read data of different images.
        Please use this option with ON if possible.

        Note)Check a maker code and a version in case of FDS.

Background movement
        Can work even if doesn't become an active window during emulation.
        Even if an icon changes into it, even full-screen works without 
        relation, but please pay attention because the sounds sounded and grow.

Priority
        Set priority degree of a thread. Please do not change it usually.

----------------
Graphics setting
----------------

-General-
TV aspect correct
        Match the screen ratio with TV size (4:3).
        Because a PC is the screen ratio of 1:1 usually, revise that looks it 
        to lose a screen of NES sideways.
        But a dot has looked in case of low resolution, and don't do a 
        recommended island because seems to have hit a wave and can see a 
        screen.
        Please use it by resolution high as possible.

show 240 lines
        Top and bottom 8 dots are options displaying the thing which is hardly 
        displayed with TV.

No-limit sprite
        The sprite who is more than eight in limitation of hardware on a 1 
        scanline is originally an option letting you display all the shares 
        that aren't displayed.
        Be good, but there seems to be the thing which used limitation well by 
        some games with ON almost.

Screen Left clip
        Remain in a real TV screen, and can't see it with an existing thing as 
        a function of NES, but there is the game that doesn't seem to show 
        rewriting of side scroll and uses.
        Were never a bug and malfunction, but were able to restrain it as a 
        function because there were many a question and demands.

Display TV frame
        Display the frame which seems to be real TV.

Display frame rate
        Calculate, and display the number of frame drawn by screen leaning to 
        the left.

Fake TV mode(scanline)
        Be modes letting leaves a crack every 1 scan line and it seems to be 
        real TV and display it.
        Can coordinate brightness of a line to display in a slider bar of the 
        lower part to a crack.
        Please change it in accordance with liking.

DISK access lamp
	Display the circle that the screen Right is aloft red instead of access 
	lamp of DISKSYSTEM.

-DirectDraw-

Double size rendering
        Be options drawing by size of length and breadth 2 times.

SystemMemory surface
        Get a Sir festival in system memory.

Use HEL
        Do not use HAL, and be options using DirectDraw with HEL.
        Because there is the case that HEL is fast than HAL by a thing, may be 
        effective that tries to test it when thinks that is heavy.

-Full screen-

Note)Screen mode reshuffling became needless when changed system memory and HEL 
     from v0.50.

Sync drawing
        Take VSYNC and the same period, and draw.
        Screen frequency please use this option at the time of 60Hz.
        Scroll can rattle besides it.
        If processing speed is slow, there can be a rattling thing.

Fit screen
        Be options enlarges an image to a lot of screens, and to display.
        Be congenial to a Fake TV mode, and there isn't it.
        This option adjusts it to screen resolution at the time of OFF, and 
        coordinate a position with size automatically.

Resolution
        Select screen resolution to use in full-screen, screen frequency(a 
        number is displayed when can set it, and be 0 besides it.), bit depth.

        8 bits mode and 24 bits mode can seem to be extremely slow with a 
        video card.
        When a frame rate is low to think that machine power is enough, there 
        can be the thing that improves that tries to change bit depth.

        This is similar with a window mode.

-Palette-

Check box
        Check it when uses a palette file.

        A palette file is a binary file of 192 bytes of *64 colors RGB3 byte 
        minutes.

Edit box
        Input a path and the file name of a palette file to use.

Browse button
        Please push it when does a browse of a palette file.

-------------
Sound setting
-------------

-General-

Sound enable
        Do ON/OFF of the sound output.
        Need a sound card even if makes you OFF.

Sampling rate
        Select a rate and the number of to sample to use by sound bit to 
        sample.

Buffer size
        Set size of a buffer.
        As a sound was repeated, be known, and please try to increase it if 
        noise seemed to be sent.
        In addition, please increase it when lowers a frame rate than 60FPS 
        with a Throttle mode.

VolEffect enable
	Use a volume change effect of triangle wave and noise (a bug of Nintendo 
	source or a camouflage function).

Extra sound enable
	Use a sound file of DISKSYSTEM movement sound and Moero!! Pro Yakyuu 
	expansion source.

-Channel-

Slider bar
        Can regulate volume of each channel.
        Usage is the same as volume control of Windows.

Note) Then a sound is broken in the greatest volume all, and don't sound.
      Please take advantage of it for balance adjustment.

------------------
Controller setting
------------------

Note)Get possible to assign two keys from v0.50.

-Combo box-
Please use it when wants to assign two kinds of keys.
Work as the thing that pushed a key if a key of either is pushed when set two 
kinds.
In addition, please pay attention because both buttons to change back into a 
default have been initialized.

-Setting method-

Becoming hollow express a button, and please push joy-stick or a keyboard with 
black and white when clicks that with a mouse because a color changes.

Thus setting of each position is the end.

In addition, don't set it that will neglect it for four or five seconds, and 
be finished.

Clear setting when pushes escape key during setting.

An A button and a B button can set a normal key and rapid-fire key separately.

-Rapid-fire speed-

An A button and a B button can each set rapid-fire speed.
Can't read 20FPS,30FPS in structure of a program by a game.
Please use 10FPS,15FPS then.

Note) Recognize joy-stick to 8. Even if be connected more than it, don't 
      recognize it.
Note) Do setting of an expansion controller here partly.
Note) There are some keys which can't set well. Please approve it beforehand by 
      saying specification.

----------------
Shortcut setting
----------------

Note)Get possible to assign two keys from v0.50.

Because a caption bar flashes on and off with "-Press any key-" when prints 
double click of a thing and the time of the kind that wants to change, please 
push some key.

In addition, don't set it that will neglect it for four or five seconds, and 
be finished.

Clear setting when pushes ESC key during setting.

Please push a SHIFT+ESC key when wants to assign an ESC key.

Can use an Alt key, a Ctrl key, a Shift key as an ornamentation key.

Please push it with the key which wants to use as shortcut simultaneously.

Work as the thing that pushed a key if a key of either is pushed when set two kinds.

Note) A key of the first and the second please pay attention not to assign the 
      same key.
Note) Don't work for an expansion controller besides Alt ornamentation 
      shortcut key with a family basic keyboard when selects it.
Note) There are some keys which can't set well. Please approve it beforehand by 
      saying specification.
Note) Set it, and please get over whether you push default button because 
      shortcut key added later isn't set.

--------------
Folder setting
--------------

Can do relative path appointment from v0.75.

Edit box
        Input a path of a folder.

Borwse
        Push it when does a browse of a folder.

ROM file folder
        Be folders with a ROM file.

Save file folder
        Be folders saving battery backup.

State file folder
        Be folders saving a state. 

Movie file folder
        Be folders saving a movie. 

Snapshot folder
        Be folders taking a snapshot.

WAVE file filder
        Be folders recording a WAVE file.


Note) Make it in a folder the same as a ROM file when doesn't set a save and a 
      state folder.
Note) When a folder doesn't exist, make it automatically. Please do not 
      appoint strange names.

--------
Language
--------

List box
        Select language plug-in to use.

Note) A list doesn't show it even if copies plug-in in a folder after 
      activation.

-----
Movie
-----

Use controller
        Become effective when checks check box. Be set to use 1P automatically 
        when excludes a check entirely.

Start a record from reset
        Start a record from hardware reset in a new record.

Prohibit rerecord of a movie
        Check it when wants to prohibit a rerecord function.

Replay it repeatedly
        Check it when wants to replay a movie repeatedly. Be effective only in 
        playback.

Display pad information
        Display a state of buttons of a pad in movie playback. Can change at 
        any time.

-----------
Game option
-----------

Note)Be functions added by v0.60.

A game screen vibrated, and were able to adjust trash to the cases that went 
with the user side.

When vibration and trash occur by the game that they changed, please try to 
change.

Setting is stored in a "GameOption.ini" file in a folder the same as exe of 
VirtuaNES.

Rendering
        Can change drawing method.

Video mode
        Can change NTSC and PAL.

IRQ
        Change IRQ method.

Note) Can set only during emulation. In addition, there is the case that cannot 
      coordinate well even if adjusts.

Note) An option is saved in order to prevent a gap in movie playback.

========================
= Expansion controller =
========================

---------------
Arkanoid paddle
---------------

Paddle
        Let you move with right and left of a mouse.
Button
        Be mouse left clicks.

Note) When a mouse goes out of a drawing area, get impossible to move.

----------
Hyper shot (Konami's Hyper Olympic(J)/Track & Field(U) controller)
----------

Each assign a controller A button and a B button to a jump, a run button.

---------------------
Family basic keyboard
---------------------

A special key allotment
[STOP]          End
[CLR/HOME]      Home
[GRAPH]         Don't push / to push with PageDown,PageUp.
[KANA]          F12
                Other keys are the same.
Note) Don't work besides Alt ornamentation shortcut key when uses this 
      expansion controller.

------
Zapper
------

Let site move with a mouse, and pull trigger with a left button click.
Because be judged to be outside the limit if site disappears, please take 
advantage of it in select.

Note) When a mouse goes out of a drawing area, site disappears.
      When remains and moves it fast, there can be the thing that a judgment 
      becomes funny.
      Please approve it beforehand.

-------------
Crazy Climber
-------------

A fact didn't exist, but made it when did it with two joy-stick because it was 
troublesome.
A key setting method is similar to a controller, and please set it from a 
[Option]->[Controller] of a menu.

Note) Setting of a direction key of controller 1 and 2 doesn't work when 
      selects this expansion controller.

---------
Top Rider
---------

There isn't setting by DIALOG. Operate it with a key set by controller 1.

Control         Key Map
---------------------------------------
Incline         Right and left
Shift           Up(Toggle)
Willey          Down

Accel           A button
Brake           B button

Start           Start
Select          Select

--------------
Family Trainer
--------------

There is originally with A/B side, but the same key is assigned in both because 
lets you turn over automatically.

---------------
Exciting Boxing
---------------

Set operation according to a name of a key.

---------------
Oekakids Tablet
---------------

Let you move with a mouse, and a left button click is a button.
While a cursor doesn't appear, site for a ray gun leaves tablet.
In addition, be judged that changes mouse cursor at drawing range of tablet 
with the state that put a tablet pen there.

----------
Turbo File
----------

Be classed to an expansion controller, but be one of an expansion device.
A save file is saved by a file name to call "ROM name.vtf" by a save file 
folder.

====================
= Expansion device =
====================

There are the following things as an expansion device.

-DATACH barcode Battler
-Tape

----------------------
DATACH Barcode Battler
----------------------

Use by a game for DATACH Barcode Battler.
Barcode can use a thing of 13 columns and eight columns of a JAN(EAN) code.
A random number generation button generates numerical value of barcode by a 
random number.
Actually, become a state through barcode when pushes a transfer button when it 
was promoted the barcode input.

==============
= NSF Player =
==============

Become a NSF player mode automatically if selects a NSF file in a state the 
same as opening ROM.

Were able to do a key allotment for a NSF player from v0.50. Do an allotment 
method by controller setting.

Pushed the music choice button, and auto-repeat works.

Note) Even if update of a key was what was influenced, and a sound sounded in 
      buffer size as for the para-keyboards of a NSF player, a key becomes not 
      push. In addition, there can be the thing that a key doesn't fit real 
      frequency.(In particular be N106 and FDS. A source of wave memory type is 
      so that doesn't agree in playback frequency.)

============
= Snapshot =
============
A snapshot function is a simple function.

Consider a difference and convenience of environment, and become only bitmap 
file of 256x240dot/256 color.

It was changed in a file name of "file name + date + time + (0.1sec).bmp" by 
v0.50.

Can do folder appointment of a snapshot by folder setting.

============
= Launcher =
============

Please feel it not be it in rest tall handloom ability with quick lunch degree.
In addition, a compression file doesn't support the current place.
Can activate the NES/FDS/NSF file when does double click of a list.
Can sort it when clicks an indication item part in a file name and mapper, all 
other items.
Sort it in inverse order when clicks the same place again. In addition, the 
activation back is always sorted with incrase order of a file name, and the 
place that selected becomes display last.
A launcher list saves it by a file name to call Launcher.lst in a folder with 
EXE.
When there is a database file, display a supplement item of header conformity 
by it.
Support movement with full-screen for the time being.
Save size in the end and a position.

Note) Because shortcut doesn't work, launcher please pay attention at the time 
      of active window.

Note) When an archive file exists, a file except a format to meet is listed.
      In addition, update of a list has a situation to take time very much in 
      order to do thawing of an archive by all means.

Note) In case of archive file, NES header editing isn't finished.

-Launcher Menu-

Edit(E)
        Nes header edit(E)      Can do work to revise a mapper number or a 
                                mirror of NES header editing NES.

Note) Because renews a file directly, take backup, please pay attention.
Note) In case of archive file, NES header editing isn't finished.

Option(O)
        Folder list(F)          Register a folder to let a list of launcher 
                                display it.
                                Can register itself to a maximum 16 folder, 
                                and become change a folder to register with a 
                                list with ON/OFF of check box of a list.

Note) Update a file list automatically that changes a folder.

        Display column(D)       Can replace an item to show launcher.
                                What turn an item without need into 
                                non-indication do it here.
                                An indication item part of launcher does drag 
                                with a mouse, and can replace it.

Refresh(R)                      When replaces a file and added it, please click 
                                it.
                                Do restructuring of contents of a list.

Note) Time depends on list update to some extent, but, meanwhile, there is 
      activation for the time being.
      But had better wait till it ended up being heavy.

=====================
= File of extension =
=====================

Battery backup SRAM     *.sav
State                   *.st?           (a number of 0-9 enters "?")
Disk save               *.dsv
Movie file              *.vmv

Netplay state           *.stn

Note) Because a save file and a state file of a disk include a disk image in 
      one part of a file, do it with distribution prohibition.
Note) Contents of battery backup SRAM are lost so that a state save includes 
      contents of battery backup SRAM when loads it. Please pay attention.
Note) Movie replay, contents of battery backup SRAM are lost in order to do a 
      state save inside when replays it. Please pay attention.

Note) Weren't able to load the state data and the movie data besides a disk 
      image or the same ROM image.
Note) Because turned a save of a disk into a difference minute form from 0.30, 
      think that gets possible to distribute it again. Save it by new fashion 
      type automatically when executes former data, and be got over.
Note) Battery backup SRAM, contents of a save of a disk are lost so that a 
      state save includes battery backup SRAM, contents of a save of a disk 
      when loads it. Please pay attention.
Note) Movie playback, battery backup SRAM, contents of a save of a disk are 
      lost in order to do state load inside when replays it. Please pay attention.

=================
= Archive files =
=================

There is you for the correspondence to the following archive forms.

Type    Needed DLL
---------------------------------
LHA     UNLHA.DLL
ZIP     UNZIP32.DLL(Isn't Info-Zip UNZIP32.DLL)
RAR     UNRAR32.DLL
CAB     CAB32.DLL

Think that can each download it from a WEB page of an Common Archivers Library
Project.
URL: http://www.csdinc.co.jp/archiver/

Note) Even if there wasn't UNZIP32.DLL, were able to defrost only the ZIP file 
      from v0.65.

Note) UNRAR32.DLL needs DLL of WinRAR.

============
= Database =
============

Please rename it in nesromdb.dat.
Rename it, and please put nesdbase.dat and NesToy to like with what can use 
either of Famicom.dat of NNNesterJ with a folder the same as EXE.

Note) When a header of a database is wrong, there is it to some extent.
      There is a thing revising a header in the VirtuaNES inside, but please 
      approve it beforehand because can't cope with all things.

=========
= Movie =
=========

Note)Get impossible to load the movie before v0.60 after v0.60.

Please do it with movie setting DIALOG when wants to prohibit the time when 
wants to change the player number that wants to record and a rerecord function.

Record information of a hard & software reset / disk change / expansion controller
(remove a FamilyBasic keyboard).

A append record function originates from a point in time that let you finish.
Because action games begin without notice, please pay attention.

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
In particular please pay attention!

Movie playback, battery backup SRAM, contents of a disk save are lost a state 
inside in order to load when plays back. Please pay attention.
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

Note) Checked versions of VirtuaNES which recorded from v0.60.
Note) As for the movie, confirmation DIALOG goes besides a disk image or the same 
      ROM image. When DIALOG appeared, please execute in responsibility of each 
      person.
Note) The reason is indistinct, but there seems to be the thing which can't 
      replay well even if records it partly.

-----------------
Rerecord gains it
-----------------
Do a state save during the movie record inside and playback, and a rerecord 
function is the function that can repeat a record from a point in time that 
loaded it.

Please use it when wants to take a long piece being perfect movie and a super 
play.

Load it during playback
        Take it from a point in time of the state data, and get over, and record 
        it.
Load it during records
        Come back until a point in time of the state data, and record it.

Note) Can't load the state data which wants to load besides the thing which 
      saved a state during the thing which was the back and movie playback and 
      records than length of the movie.
Note) There isn't a guarantee at having changed an expansion controller on the 
      way when grinds rerecord when uses an expansion controller.

------------------------------------------------
Accompany you when wants to record it from reset
------------------------------------------------

Because arranged an option starting a record from hardware reset in movie setting 
from v0.60, please use it.

==================
= Cheat function =
==================

Please refer to Cheat_E.txt.

==========
= Thanks =
==========

Referred to Unofficial nester on mapper and sound.

A Namco106 source part improves a thing of NEZplug (Mamiya product) by oneself, 
and use it.

The VRC7 source part used an emu2413 (Mitsutaka Okazaki product).

An archiver operation code changed a code of NesterJ, and used it. An original 
is Mikami Kana product arc.cpp,arc.h.

A zlib operation code changed a code of NNNesterJ, and used.

Use zlib. Can acquire a source code from http://www.zlib.org.

Thank people engaged in code making.

Had Mr. GIGO, cooperation of Mr. T.Aoyama on a disk sound source.

In addition, be held up to a lot of people, and this software holds water.

Thank all of you!!

=========================
= Request to all of you =
=========================

Stick to a ROM, and refer to an author, and please do not send it.

A thing and the character who don't work draw out a funny thing well, and it 
isn't possible.

A check of NESToy is soft, and please try to check it.

When even it is funny, please report it.

There is relation to use a CRC database, but don't support it about remodeling 
product basically.

Trash of a completely screen without a hindrance please forgive degree 
including influence elsewhere in a game.

A hindrance wants to revise one thing in a game if possible.

===========
= Contact =
===========

I am a native Japanese, and you seem to be hard to understand Japanese, and 
English is hard to understand me, too. :D

Please do not use slang and a net term if possible when has you send an email.

--------------------------------------------------------
    Put out the email address for virus measures.
--------------------------------------------------------

The official site moved to 09/07/2001. There is hard to be it that a link or 
bookmark have the following addresses change it.

URL:    http://virtuanes.s1.xrea.com:8080/

