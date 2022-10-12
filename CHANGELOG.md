# Undertale: UA translation Changelog (data.win)

2022-08-15

- 9:28 - Added support for ukrainian lng in "gml_Script_scr_gettext" line 1 (var ua_text), line 12 (if (global.language == "ua"){})

- 9:34 - Added script "textdata_ua"
	
- 9:39 - Added third language in settingMenu "gml_Object_obj_settingsmenu_Draw_0"
	
- 9:55 - Added lines "ds_map_add(global.text_data_ja, "settings_language_ua", "ウクライナ")" in "gml_Script_textdata_ja" line 16289 and "ds_map_add(global.text_data_en, "settings_language_ua", "UKRAINIAN")" in "gml_Script_textdata_en" line 15601
	
- 10:08 - Added urkainian keyboard for namingscreen in "gml_Script_scr_namingscreen_setup"
	
- 10:14 - Added support for ukrainian lng in "gml_Object_obj_time_Create_0" line 106 (if (!variable_global_exists("text_data_ua"))
    script_execute(textdata_ua)) and changed line 109 (added '|| global.language != "ua"')
	
- 10:54 - Added cyrillic symbols for all fonts (exept japanese's fonts)
	
- 11:55 - Note: I don't know why but if in "gml_Script_scr_namingscreen" change somthing, game will go in endless loop or something(?) after pressing "Begin game"(FIXED)
	
- 21:01 - Reworked sybols in fnt_plain
	
2022-08-16
	
- 00:41 - Fixed keyboard bug (empty symbol in name)
	
- 14:00 - Undertale now works with jsons
	
- 15:00 - Optimised jsonloader by change "file_text" to buffer
	
- 19:05 - Added if function that change "lv" to "рв" in scr_binfowrite if global.language == "ua"
	
- 19:45 - Added if function that change "lv" to "рв" in "gml_Object_obj_floweydraw_Draw_0" if (global.language == "ua")
	
	
- 20:02 - Added if function that change "lv" to "рв", "hp" to "рж" and "g" to "з"in "gml_Object_obj_overworldcontroller_Draw_0" if (global.language == "ua")

2022-08-17
	
- 16:15 - Added if function that change "hp" to "рж" in "gml_Object_obj_floweydraw_Draw_0" if (global.language == "ua")(Update: "рж" to "рз")
	
- 17:00 - Translated "fight", "act", "item" and "spare" buttons.
	
2022-08-19
	
- 10:45 - Translated all names and comments to them.
	
2022-09-04

- 15:40 - Added some if (global.language == "ua") to gml_Object_obj_overworldcontroller_Draw_0. (line 98 and 366)
	
- 23:15 - Reworked Font width in gml_Object_obj_base_writer_Draw_0 (line 422)

2022-09-07

- 15:03 - Added if (global.language == "ua") in gml_Script_scr_setsprite
	
2022-09-12

- 21:48 - Added snd_wonderfulidea_ua
	
2022-09-13

- 9:48 - Added draw_text_transformed(40, 130, scr_gettext("translate_title_by"), 1, 1, 0) in gml_Object_obj_undertaletitle_Draw_0	

2022-09-14

- 1:34 - Added "item_menub_header1" in gml_Script_SCR_TEXT (line 84)
	
- 1:39 - Note: Use japanese menub system
	
2022-09-16
	
- 17:48 - Note: Not without help, but I figured out what the problem was with "gml_Script_scr_namingscreen" and fixed it
	
- 19:06 - Centered instructions in game start
	
- 1:45 - Now game use menub system instead of classic system
	
				"gml_Object_obj_battlecontroller_Draw_0" Line 99
		
				"gml_Object_obj_battlecontroller_KeyPress_37" Line 24
				
				"gml_Object_obj_battlecontroller_KeyPress_38" Line 53
				
				"gml_Object_obj_battlecontroller_KeyPress_39" Line 44
				
				"gml_Object_obj_battlecontroller_KeyPress_39" Line 51
				
				"gml_Object_obj_battlecontroller_KeyPress_Step 0" Line 150
				
				"gml_Script_scr_battlemenu_cursor_y" Line 3
	
2022-09-19
	
- 12:48 - Moved "itembox_close" a little bit to the left in gml_Object_obj_itemswapper_Draw_0. Line 54

2022-10-02
	
- 13:00 - Added borders.
	
	
				Used "BorderEnabler" by krzys_h
	
				"gml_Object_obj_time_Create_0" Line 104
		
				"gml_Object_obj_time_Draw_76" Line 9
				
				"gml_Object_obj_time_Draw_77" Line 24
				
2022-10-12
	
- 10:53 - Added "\@@" thing for additional characters in the dialog box.
	
	
				"gml_Object_obj_base_writer_Draw_0" Line 7, 8, 59, 258
				
				"gml_Object_obj_base_writer_Alarm_0" Line 56