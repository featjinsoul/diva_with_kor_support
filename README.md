# diva_with_kor_support
Files for allowing Hatsune Miku: Project DIVA Arcade Future Tone (version 7.10) to display Korean characters properly.<br />
Fonts used:<br />
SeuratPro-M - For JP&EN<br />
SeuratPro-DB - For JP&EN<br />
Gulim - For KR<br />
This font is rendered using the custom size parameter in generate_font.py, with a size of 32pt.<br />
Bold and standard fonts are used as well.<br />

The files go in the directories:<br />
fontmap.farc: root of rom/<br />
spr_fnt_* : rom/2d/<br />


Fontmap created using https://github.com/somewhatlurker/diva_fontmap_tools.<br />
Required patches:<br />
proportional_main_font.p<br />
separate_fonts.p<br />
font_res_support.p<br />
