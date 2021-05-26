- **System Hardware** [`genesis_plus_gx_wide_system_hw`] (**auto**, sg-1000, sg-1000 II, mark-III, master system, master system II, game gear, mega drive / genesis)  
  Runs loaded content with a specific emulated console. 'Auto' will select the most appropriate system for the current game.
- **System Region** [`genesis_plus_gx_wide_region_detect`] (**auto**, ntsc-u, pal, ntsc-j)  
  Specify which region the system is from. For consoles other than the Game Gear, 'PAL' is 50hz while 'NTSC' is 60hz. Games may run faster or slower than normal if the incorrect region is selected.
- **System Lock-Ups** [`genesis_plus_gx_wide_force_dtack`] (**enabled**, disabled)  
  Emulate system lock-ups that occur on real hardware when performing illegal address access. This should only be disabled when playing certain demos and homebrew that rely on illegal behaviour for correct operation.
- **System Boot ROM** [`genesis_plus_gx_wide_bios`] (**disabled**, enabled)  
  Use official BIOS/bootloader for emulated hardware, if present in RetroArch's system directory. Displays console-specific start-up sequence/animation, then runs loaded content.
- **CD System BRAM** [`genesis_plus_gx_wide_bram`] (**per bios**, per game)  
  When running Sega CD content, specifies whether to share a single save file between all games from a specific region (Per-BIOS) or to create a separate save file for each game (Per-Game). Note that the Sega CD has limited internal storage, sufficient only for a handful of titles. To avoid running out of space, the 'Per-Game' setting is recommended.
- **68K Address Error** [`genesis_plus_gx_wide_addr_error`] (**enabled**, disabled)  
  The Genesis CPU (Motorola 68000) produces an Address Error (crash) when attempting to perform unaligned memory access. Enabling '68K Address Error' simulates this behaviour. It should only be disabled when playing ROM hacks, since these are typically developed using less accurate emulators and may rely on invalid RAM access for correct operation.
- **Cartridge Lock-On** [`genesis_plus_gx_wide_lock_on`] (**disabled**, game genie, action replay (pro), sonic & knuckles)  
  Lock-On Technology is a Genesis feature that allowed an older game to connect to the pass-through port of a special cartridge for extended or altered gameplay. This option specifies which type of special 'lock-on' cartridge to emulate. A corresponding bios file must be present in RetroArch's system directory.
- **Master System FM (YM2413)** [`genesis_plus_gx_wide_ym2413`] (**auto**, disabled, enabled)  
  Enable emulation of the FM Sound Unit used by certain Sega Mark III/Master System games for enhanced audio output.
- **Mega Drive / Genesis FM** [`genesis_plus_gx_wide_ym2612`] (**mame (ym2612)**, mame (asic ym3438), mame (enhanced ym3438))  
  Select method used to emulate the FM synthesizer (main sound generator) of the Mega Drive/Genesis. The 'YM2612' chip is used by the original Model 1 Genesis. The 'YM3438' is used in later Genesis revisions.
- **Sound Output** [`genesis_plus_gx_wide_sound_output`] (**stereo**, mono)  
  Select stereo or mono sound reproduction.
- **PSG Preamp Level** [`genesis_plus_gx_wide_psg_preamp`] (0, 5, 10, 15, 20, 25, 30, 35, 40, 45, 50, 55, 60, 65, 70, 75, 80, 85, 90, 95, 100, 105, 110, 115, 120, 125, 130, 135, 140, 145, **150**, 155, 160, 165, 170, 175, 180, 185, 190, 195, 200)  
  Set the audio preamplifier level of the emulated SN76496 4-channel Programmable Sound Generator found in the Master System, Game Gear and Genesis.
- **FM Preamp Level** [`genesis_plus_gx_wide_fm_preamp`] (0, 5, 10, 15, 20, 25, 30, 35, 40, 45, 50, 55, 60, 65, 70, 75, 80, 85, 90, 95, **100**, 105, 110, 115, 120, 125, 130, 135, 140, 145, 150, 155, 160, 165, 170, 175, 180, 185, 190, 195, 200)  
  Set the audio preamplifier level of the emulated Sega Mark III/Master System FM Sound Unit.
- **Audio Filter** [`genesis_plus_gx_wide_audio_filter`] (**disabled**, low-pass)  
  Enable a low pass audio filter to better simulate the characteristic sound of a Model 1 Genesis.
- **Low-Pass Filter %** [`genesis_plus_gx_wide_lowpass_range`] (5, 10, 15, 20, 25, 30, 35, 40, 45, 50, 55, **60**, 65, 70, 75, 80, 85, 90, 95)  
  Specify the cut-off frequency of the audio low pass filter. A higher value increases the perceived 'strength' of the filter, since a wider range of the high frequency spectrum is attenuated.
- **Frameskip** [`genesis_plus_gx_wide_frameskip`] (**disabled**, auto, manual)  
  Skip frames to avoid audio buffer under-run (crackling). Improves performance at the expense of visual smoothness. 'Auto' skips frames when advised by the frontend. 'Manual' utilises the 'Frameskip Threshold (%)' setting.
- **Frameskip Threshold (%)** [`genesis_plus_gx_wide_frameskip_threshold`] (15, 18, 21, 24, 27, 30, **33**, 36, 39, 42, 45, 48, 51, 54, 57, 60)  
  When 'Frameskip' is set to 'Manual', specifies the audio buffer occupancy threshold (percentage) below which frames will be skipped. Higher values reduce the risk of crackling by causing frames to be dropped more frequently.
- **Blargg NTSC Filter** [`genesis_plus_gx_wide_blargg_ntsc_filter`] (**disabled**, monochrome, composite, svideo, rgb)  
  Apply a video filter to mimic various NTSC TV signals.
- **LCD Ghosting Filter** [`genesis_plus_gx_wide_lcd_filter`] (**disabled**, enabled)  
  Apply an image 'ghosting' filter to mimic the display characteristics of the Game Gear and 'Genesis Nomad' LCD panels.
- **Borders** [`genesis_plus_gx_wide_overscan`] (**disabled**, top/bottom, left/right, full)  
  Enable this to display the overscan regions at the top/bottom and/or left/right of the screen. These would normally be hidden by the bezel around the edge of a standard-definition television.
- **Game Gear Extended Screen** [`genesis_plus_gx_wide_gg_extra`] (**disabled**, enabled)  
  Forces Game Gear titles to run in 'SMS' mode, with an increased resolution of 256x192. May show additional content, but typically displays a border of corrupt/unwanted image data.
- **Hide Master System Left Border** [`genesis_plus_gx_wide_left_border`] (**disabled**, enabled)  
  Cuts off 8 pixels from both the left and right side of the screen when running Master System games, thereby hiding the border seen on the left side of the screen
- **Extra columns to draw in H40 for widescreen** [`genesis_plus_gx_wide_h40_extra_columns`] (10, **0**, 2, 4, 6, 8, 12, 14, 16, 18, 20, 22, 24)  
  Set the amount of extra colums to draw for widescreen
- **Fix VDP DMA boundary bug** [`genesis_plus_gx_wide_vdp_fix_dma_boundary_bug`] (**disabled**, enabled)  
  Enable this to fix the VDP DMA boundary bug
- **Core-Provided Aspect Ratio** [`genesis_plus_gx_wide_aspect_ratio`] (**auto**, NTSC PAR, PAL PAR)  
  Choose the preferred content aspect ratio. This will only apply when RetroArch's aspect ratio is set to 'Core provided' in the Video settings.
- **Interlaced Mode 2 Output** [`genesis_plus_gx_wide_render`] (**single field**, double field)  
  Interlaced Mode 2 allows the Genesis to output a double height (high resolution) 320x448 image by drawing alternate scanlines each frame (this is used by 'Sonic the Hedgehog 2' and 'Combat Cars' multiplayer modes). 'Double Field' mimics original hardware, producing a sharp image with flickering/interlacing artefacts. 'Single Field' apples a de-interlacing filter, which stabilises the image but causes mild blurring.
- **Show Light Gun Crosshair** [`genesis_plus_gx_wide_gun_cursor`] (**disabled**, enabled)  
  Display light gun crosshairs when using the 'MD Menacer', 'MD Justifiers' and 'MS Light Phaser' input device types.
- **Light Gun Input** [`genesis_plus_gx_wide_gun_input`] (**lightgun**, touchscreen)  
  Use a mouse-controlled 'Light Gun' or 'Touchscreen' input.
- **Invert Mouse Y-Axis** [`genesis_plus_gx_wide_invert_mouse`] (**disabled**, enabled)  
  Inverts the Y-axis of the 'MD Mouse' input device type.
- **Remove Per-Line Sprite Limit** [`genesis_plus_gx_wide_no_sprite_limit`] (**disabled**, enabled)  
  Removes the 8 (Master System) or 20 (Genesis) sprite-per-scanline hardware limit. This reduces flickering but can cause visual glitches, as some games exploit the hardware limit to generate special effects.

