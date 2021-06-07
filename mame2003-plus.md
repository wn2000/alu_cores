| Core Option         | Description |
| ------------------- | --- |
| 4-way joystick emulation on 8-way joysticks | `mame2003-plus_four_way_emulation` = "enabled\|disabled" |
| Mouse Device | Set mouse device input to be read either from a mouse, a pointer (pointer, trackpad, touchscreen), or to be disabled. `mame2003-plus_mouse_device` = "mouse\|pointer\|disabled" |
| Show Lightgun crosshair | Toggle crosshair visibilty for lightgun games. `mame2003-plus_crosshair_enabled` = "enabled\|disabled" |
| Skip Disclaimer | Skip the copyright disclaimer message. `mame2003-plus_skip_disclaimer` = "disabled\|enabled" |
| Skip Warnings | Advanced feature: changing from the default is not recommended in most cases. Skip any driver warnings about emulation quality. `mame2003-plus_skip_warnings` = "disabled\|enabled" |
| Display MAME menu | Enable this core option to display the core's MAME Menu and then disable it when you have finished using the MAME Menu. `mame2003-plus_display_setup` = "disabled\|enabled" |
| Specify Neo Geo BIOS (Restart core) | Manually specify your choice of Neo Geo BIOS from among those supported. `mame2003-plus_neogeo_bios` = "default\|euro\|euro-s1\|us\|us-e\|asia\|japan\|japan-s2\|unibios33\|unibios20\|unibios13\|unibios11\|unibios10\|debug\|asia-aes" |
| Specify Sega ST-V BIOS (Restart core) | Manually specify your choice of ST-V BIOS from among those supported. `mame2003-plus_stv_bios` = "default\|japan\|japana\|us\|japan\_b\|taiwan\|europe" |
| Use CD soundtrack (Restart core) | See Alternate CD soundtrack support in the Audio samples section of this doc. `mame2003-plus_use_alt_sound` = "enabled\|disabled" |
| Share 2 player dial controls across one X/Y device | See the 2-player dial and spinner devices section of this doc. `mame2003-plus_dialsharexy` = "disabled\|enabled" |
| Vector resolution multiplier (Restart core) | Attempts to create a higher quality emulation of vector display hardware by upscaling the emulated display to a higher resolution. `mame2003-plus_vector_resolution` = "1024x768\|640x480\|1280x960\|1440x1080\|1600x1200\|original" |
| Vector antialiasing | Enables or disables the anti-aliasing for vector games. `mame2003-plus_vector_antialias` = "enabled\|disabled" |
| Vector beam width | Sets the emulated width of the vector beam in pixels. This setting is only effective when anti-aliasing is enabled. `mame2003-plus_vector_beam_width` = "2\|1\|1.2\|1.4\|1.6\|1.8\|2.5\|3\|4\|5\|6\|7\|8\|9\|10\|11\|12" |
| Vector translucency | Emulates the partial transparency of vector display hardware. |
| Vector flicker | Emulates the flicker of vector display hardware. `mame2003-plus_vector_flicker` = "20\|0\|10\|30\|40\|50\|60\|70\|80\|90\|100" |
| Vector intensity | Emulates the variable intensity of vector display hardware. `mame2003-plus_vector_intensity` = "1.5\|0.5\|1\|2\|2.5\|3" |
| DCS Speedhack | Advanced feature: changing from the default is not recommended in most cases. Use so-called "speed hacks" to improve the performance of DCS sound hardware. `mame2003-plus_dcs_speedhack` = "enabled\|disabled" |
| Locate system files within a subfolder | For historical reasons, MAME 2003-Plus reads system files within a subfolder named mame2003-plus even though this is not part of the libretro API. `mame2003-plus_core_sys_subfolder` = "enabled\|disabled" |
| Locate save files within a subfolder | For historical reasons, MAME 2003-Plus saves files within a subfolder named mame2003-plus even though this is not part of the libretro API. `mame2003-plus_core_save_subfolder` = "enabled\|disabled" |
| TATE Mode | From the Japanese 縦 (ta-te) meaning "vertical", TATE Mode renders vertical games lengthwise along the display. This mode is intended for use with rotating monitors and portable devices that can make the full use of their viewable area for games which used vertical monitors. `mame2003-plus_tate_mode` = "disabled\|enabled" |
| Brightness | Simple brightness adjustment. `mame2003-plus_brightness` = "1.0\|0.2\|0.3\|0.4\|0.5\|0.6\|0.7\|0.8\|0.9\|1.1\|1.2\|1.3\|1.4\|1.5\|1.6\|1.7\|1.8\|1.9\|2.0" |
| Gamma correction | Simple gamma adjustment. `mame2003-plus_gamma` = "1.0\|0.5\|0.6\|0.7\|0.8\|0.9\|1.1\|1.2\|1.3\|1.4\|1.5\|1.6\|1.7\|1.8\|1.9\|2.0" |
| Frameskip | Advanced feature: changing from the default is not recommended in most cases. `mame2003-plus_frameskip` = "0\|1\|2\|3\|4\|5" |
| Sample Rate (KHz) | Advanced feature: changing from the default is not recommended in most cases. `mame2003-plus_sample_rate` = "48000\|8000\|11025\|22050\|30000\|44100" |
| Input interface | Advanced feature: changing from the default is not recommended in most cases. retropad, the default option, processes input via the libretro retropad abstraction, including from any keyboard which are bound to the retropad. The keyboard setting only sends keyboard input directly to the core, ignoring the retropad. The simultaneous setting sends inputs both ways at the same time and is not recommended. This setting exists for historical reasons. `mame2003-plus_input_interface` = "retropad\|keyboard\|simultaneous" |
| Legacy Remapping | Note: Using the legacy MAME control remapper may affect stateless netplay between two users with their MAME remappings set differently. `mame2003-plus_mame_remapping` = "enabled\|disabled" |
| Display artwork (Restart core) | Display artwork packs from within the core, particularly "backdrop" artwork. `mame2003-plus_display_artwork` = "enabled\|disabled" |
| Artwork resolution multiplier (Restart core) | Upscales games with artwork backs so that the artwork can be displayed at a higher resolution. `mame2003-plus_art_resolution` = "1\|2" |
| NVRAM Bootstraps | Advanced feature: changing from the default is not recommended in most cases. `mame2003-plus_nvram_bootstraps` = "enabled\|disabled" |
| Dip switch/Cheat input ports | Advanced feature: changing from the default is not recommended in most cases. Activates a few specific cheats that manipulate the dipswitch input system. `mame2003-plus_cheat_input_ports` = "disabled\|enabled" |
| Bypass audio skew (Restart core) | Advanced feature: changing from the default is not recommended in most cases. Bypass the frontend's "audio skew" feature which attempts to adjust the audio for games which displayed at framerates not native to modern displays. `mame2003-plus_machine_timing` = "enabled\|disabled" |
| Center joystick axis for digital controls | Emulates the center position of an analog joystick to allow digital joysticks to play analog based games. This is only applied when the AD Stick type is used. `mame2003-plus_digital_joy_centering` = "enabled\|disabled" |

