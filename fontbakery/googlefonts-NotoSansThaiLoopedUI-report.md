## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[1] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Fonts have consistent underline thickness? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/family/underline_thickness">com.google.fonts/check/family/underline_thickness</a>)</summary><div>


* 🔥 **FAIL** Thickness of the underline is not the same across this family. In order to fix this, please make sure that the underlineThickness value is the same in the 'post' table of all of this family font files.
Detected underlineThickness values are:
	fonts/NotoSansThaiLoopedUI/googlefonts/ttf/NotoSansThaiLoopedUI-Black.ttf: 130
	fonts/NotoSansThaiLoopedUI/googlefonts/ttf/NotoSansThaiLoopedUI-Bold.ttf: 107
	fonts/NotoSansThaiLoopedUI/googlefonts/ttf/NotoSansThaiLoopedUI-ExtraBold.ttf: 117
	fonts/NotoSansThaiLoopedUI/googlefonts/ttf/NotoSansThaiLoopedUI-ExtraLight.ttf: 33
	fonts/NotoSansThaiLoopedUI/googlefonts/ttf/NotoSansThaiLoopedUI-Light.ttf: 47
	fonts/NotoSansThaiLoopedUI/googlefonts/ttf/NotoSansThaiLoopedUI-Medium.ttf: 81
	fonts/NotoSansThaiLoopedUI/googlefonts/ttf/NotoSansThaiLoopedUI-Regular.ttf: 70
	fonts/NotoSansThaiLoopedUI/googlefonts/ttf/NotoSansThaiLoopedUI-SemiBold.ttf: 93
	fonts/NotoSansThaiLoopedUI/googlefonts/ttf/NotoSansThaiLoopedUI-Thin.ttf: 24
 [code: inconsistent-underline-thickness]
</div></details><br></div></details><details><summary><b>[14] NotoSansThaiLoopedUI-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 290 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai Looped UI Black [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1112, but got 1069 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hmtx.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 240 font units wide, non-breaking space named (uni00A0) is 260 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped UI Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.6x (1600) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E04	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E05	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E12	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E14	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E15	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E1E	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E1F	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E28	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E2C	Contours detected: 6	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3 

	- And 14 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=391.5,Y=-2.0 (should be at baseline 0?)

	* uni0E33 (U+0E33): X=-304.0,Y=715.0 (should be at cap-height 714?)

	* uni0E33 (U+0E33): X=-22.0,Y=715.0 (should be at cap-height 714?)

	* uni0E33 (U+0E33): X=-115.0,Y=715.0 (should be at cap-height 714?)

	* uni0E33 (U+0E33): X=-211.0,Y=715.0 (should be at cap-height 714?)

	* uni0E34 (U+0E34): X=261.0,Y=713.0 (should be at cap-height 714?)

	* uni0E35 (U+0E35): X=254.0,Y=713.0 (should be at cap-height 714?)

	* uni0E36 (U+0E36): X=246.0,Y=713.0 (should be at cap-height 714?)

	* uni0E37 (U+0E37): X=242.0,Y=713.0 (should be at cap-height 714?)

	* uni0E47 (U+0E47): X=460.0,Y=712.0 (should be at cap-height 714?) 

	* And 23 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E08 (U+0E08) contains a short segment L<<314.0,137.0>--<330.0,137.0>>

	* uni0E09 (U+0E09) contains a short segment L<<309.0,182.0>--<310.0,182.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<603.0,264.0>-<603.0,250.0>-<604.0,239.0>>

	* uni0E0F (U+0E0F) contains a short segment B<<416.0,-140.0>-<427.0,-140.0>-<430.5,-131.5>>

	* uni0E0F (U+0E0F) contains a short segment B<<430.5,-131.5>-<434.0,-123.0>-<434.0,-110.0>>

	* uni0E10 (U+0E10) contains a short segment L<<309.0,138.0>--<325.0,138.0>>

	* uni0E12 (U+0E12) contains a short segment L<<360.0,366.0>--<354.0,366.0>>

	* uni0E13 (U+0E13) contains a short segment L<<586.0,187.0>--<590.0,187.0>>

	* uni0E13 (U+0E13) contains a short segment B<<660.0,225.0>-<675.0,232.0>-<679.5,239.0>>

	* uni0E13 (U+0E13) contains a short segment B<<679.5,239.0>-<684.0,246.0>-<684.0,261.0>> 

	* And 41 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<219.0,818.0>--<219.0,725.0>> -> L<<219.0,725.0>--<210.0,593.0>> 

	* And uni0E48 (U+0E48): L<<59.0,593.0>--<50.0,725.0>> -> L<<50.0,725.0>--<50.0,818.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0E12 (U+0E12): B<<431.5,324.0>-<459.0,304.0>-<469.0,271.0>>/B<<469.0,271.0>-<468.0,282.0>-<468.0,295.0>> = 11.663969860003432 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSansThaiLoopedUI-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 290 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai Looped UI [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1112, but got 1069 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hmtx.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 248 font units wide, non-breaking space named (uni00A0) is 260 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped UI' / SUBFAMILY_NAME = 'Bold'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.6x (1600) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E12	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E1E	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E1F	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E2C	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E12	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E1E	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E1F	Contours detected: 3	Expected: 1 or 2 

	- And 4 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=386.0,Y=-0.5 (should be at baseline 0?)

	* uni0E31 (U+0E31): X=50.0,Y=716.0 (should be at cap-height 714?)

	* uni0E33 (U+0E33): X=-284.0,Y=712.0 (should be at cap-height 714?)

	* uni0E33 (U+0E33): X=-16.0,Y=712.0 (should be at cap-height 714?)

	* uni0E33 (U+0E33): X=-98.0,Y=712.0 (should be at cap-height 714?)

	* uni0E33 (U+0E33): X=-202.0,Y=712.0 (should be at cap-height 714?)

	* uni0E35 (U+0E35): X=416.0,Y=716.0 (should be at cap-height 714?)

	* uni0E44 (U+0E44): X=274.0,Y=713.0 (should be at cap-height 714?)

	* uni0E4D (U+0E4D): X=50.0,Y=712.0 (should be at cap-height 714?)

	* uni0E4D (U+0E4D): X=318.0,Y=712.0 (should be at cap-height 714?) 

	* And 16 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E05 (U+0E05) contains a short segment L<<342.0,379.0>--<336.0,379.0>>

	* uni0E07 (U+0E07) contains a short segment L<<355.0,340.0>--<353.0,340.0>>

	* uni0E08 (U+0E08) contains a short segment L<<152.0,154.0>--<150.0,154.0>>

	* uni0E08 (U+0E08) contains a short segment L<<296.0,112.0>--<309.0,112.0>>

	* uni0E09 (U+0E09) contains a short segment B<<372.0,100.0>-<372.0,102.0>-<372.0,102.0>>

	* uni0E09 (U+0E09) contains a short segment L<<141.0,152.0>--<140.0,152.0>>

	* uni0E09 (U+0E09) contains a short segment L<<288.0,159.0>--<288.0,159.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<573.0,248.0>-<573.0,236.0>-<574.0,225.0>>

	* uni0E0D (U+0E0D) contains a short segment B<<624.0,-166.0>-<627.0,-167.0>-<631.0,-167.0>>

	* uni0E0F (U+0E0F) contains a short segment B<<429.0,-165.0>-<442.0,-165.0>-<447.0,-155.0>> 

	* And 65 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<187.0,803.0>--<187.0,717.0>> -> L<<187.0,717.0>--<180.0,595.0>> 

	* And uni0E48 (U+0E48): L<<57.0,595.0>--<50.0,717.0>> -> L<<50.0,717.0>--<50.0,803.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0E10 (U+0E10): B<<368.0,-160.0>-<389.0,-190.0>-<429.0,-197.0>>/B<<429.0,-197.0>-<406.0,-187.0>-<391.0,-167.5>> = 13.572320169300394 

	* And uni0E10 (U+0E10): B<<534.0,433.0>-<513.0,433.0>-<491.0,437.0>>/L<<491.0,437.0>--<491.0,437.0>> = 10.304846468766044 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[21] NotoSansThaiLoopedUI-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 290 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWeightClass. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** OS/2 usWeightClass is '400' when it should be '800'. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has all mandatory 'name' table entries? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/mandatory_entries">com.google.fonts/check/name/mandatory_entries</a>)</summary><div>


* 🔥 **FAIL** Font lacks entry with nameId=16 (TYPOGRAPHIC_FAMILY_NAME) [code: missing-entry]
* 🔥 **FAIL** Font lacks entry with nameId=17 (TYPOGRAPHIC_SUBFAMILY_NAME) [code: missing-entry]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname">com.google.fonts/check/name/familyname</a>)</summary><div>


* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "Noto Sans Thai Looped UI ExtraBold" but got "Noto Sans Thai Looped UI Extrabold". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FULL_FONT_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/fullfontname">com.google.fonts/check/name/fullfontname</a>)</summary><div>


* 🔥 **FAIL** [FULL_FONT_NAME(4):WINDOWS(3)]
Expected: "Noto Sans Thai Looped UI ExtraBold"
But got:  "Noto Sans Thai Looped UI Extrabold Regular" [code: bad-entry]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: POSTSCRIPT_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/postscriptname">com.google.fonts/check/name/postscriptname</a>)</summary><div>


* 🔥 **FAIL** [POSTSCRIPT_NAME(6):WINDOWS(3)]
Expected: "NotoSansThaiLoopedUI-ExtraBold"
But got:  "NotoSansThaiLoopedUIExtrabold-Regular" [code: bad-entry]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicfamilyname">com.google.fonts/check/name/typographicfamilyname</a>)</summary><div>


* 🔥 **FAIL** Non-RIBBI fonts must have a TYPOGRAPHIC_FAMILY_NAME entry on the name table. [code: non-ribbi-lacks-entry]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: TYPOGRAPHIC_SUBFAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/typographicsubfamilyname">com.google.fonts/check/name/typographicsubfamilyname</a>)</summary><div>


* 🔥 **FAIL** TYPOGRAPHIC_SUBFAMILY_NAME for Win is missing. It must be "ExtraBold". [code: missing-typo-win]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai Looped UI Extrabold [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1112, but got 1069 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hmtx.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 244 font units wide, non-breaking space named (uni00A0) is 260 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped UI Extrabold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.6x (1600) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E12	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E14	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E15	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E1E	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E1F	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E2C	Contours detected: 5	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E12	Contours detected: 4	Expected: 1 or 3 

	- And 8 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=388.0,Y=-1.5 (should be at baseline 0?)

	* uni0E31 (U+0E31): X=352.5,Y=715.0 (should be at cap-height 714?)

	* uni0E43 (U+0E43): X=280.0,Y=715.0 (should be at cap-height 714?)

	* uni0E49 (U+0E49): X=75.5,Y=713.0 (should be at cap-height 714?)

	* uni0E4C (U+0E4C): X=202.0,Y=714.5 (should be at cap-height 714?)

	* uni0E4C (U+0E4C): X=142.0,Y=714.5 (should be at cap-height 714?)

	* quoteleft (U+2018): X=96.0,Y=713.0 (should be at cap-height 714?)

	* quoteleft (U+2018): X=218.0,Y=713.0 (should be at cap-height 714?)

	* quoteright (U+2019): X=65.0,Y=713.0 (should be at cap-height 714?)

	* quoteright (U+2019): X=217.0,Y=713.0 (should be at cap-height 714?) 

	* And 10 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E05 (U+0E05) contains a short segment L<<350.0,373.0>--<344.0,373.0>>

	* uni0E08 (U+0E08) contains a short segment L<<304.0,123.0>--<318.0,123.0>>

	* uni0E09 (U+0E09) contains a short segment L<<298.0,170.0>--<298.0,170.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<587.0,256.0>-<587.0,242.0>-<588.0,232.0>>

	* uni0E0F (U+0E0F) contains a short segment B<<423.0,-154.0>-<435.0,-154.0>-<439.5,-144.5>>

	* uni0E0F (U+0E0F) contains a short segment B<<439.5,-144.5>-<444.0,-135.0>-<444.0,-120.0>>

	* uni0E10 (U+0E10) contains a short segment L<<300.0,124.0>--<315.0,124.0>>

	* uni0E12 (U+0E12) contains a short segment B<<392.0,115.0>-<392.0,119.0>-<393.0,122.0>>

	* uni0E12 (U+0E12) contains a short segment L<<354.0,373.0>--<348.0,373.0>>

	* uni0E13 (U+0E13) contains a short segment L<<568.0,175.0>--<570.0,175.0>> 

	* And 47 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<202.0,810.0>--<202.0,721.0>> -> L<<202.0,721.0>--<194.0,594.0>> 

	* And uni0E48 (U+0E48): L<<58.0,594.0>--<50.0,721.0>> -> L<<50.0,721.0>--<50.0,810.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0E15 (U+0E15): B<<432.0,322.5>-<461.0,298.0>-<466.0,258.0>>/L<<466.0,258.0>--<466.0,364.0>> = 7.125016348901757 

	* And uni0E15 (U+0E15): L<<466.0,0.0>--<466.0,224.0>>/B<<466.0,224.0>-<462.0,194.0>-<446.0,169.0>> = 7.594643368591447 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSansThaiLoopedUI-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 290 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai Looped UI ExtraLight [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1112, but got 1069 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hmtx.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 270 font units wide, non-breaking space named (uni00A0) is 531 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped UI ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.6x (1600) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E1E	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E1F	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E2B	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E1E	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E1F	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E2B	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3 

	- And Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=141.5,Y=1.5 (should be at baseline 0?)

	* exclam (U+0021): X=90.0,Y=1.5 (should be at baseline 0?)

	* comma (U+002C): X=72.0,Y=0.5 (should be at baseline 0?)

	* period (U+002E): X=141.5,Y=1.5 (should be at baseline 0?)

	* period (U+002E): X=90.0,Y=1.5 (should be at baseline 0?)

	* colon (U+003A): X=141.5,Y=1.5 (should be at baseline 0?)

	* colon (U+003A): X=90.0,Y=1.5 (should be at baseline 0?)

	* question (U+003F): X=111.5,Y=715.0 (should be at cap-height 714?)

	* question (U+003F): X=189.0,Y=1.5 (should be at baseline 0?)

	* question (U+003F): X=137.5,Y=1.5 (should be at baseline 0?) 

	* And 21 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment B<<212.0,258.0>-<212.0,267.0>-<214.0,275.0>>

	* uni0E05 (U+0E05) contains a short segment L<<295.0,424.0>--<290.0,424.0>>

	* uni0E05 (U+0E05) contains a short segment B<<209.0,258.0>-<209.0,266.0>-<211.0,273.0>>

	* uni0E09 (U+0E09) contains a short segment L<<223.0,64.0>--<225.0,64.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<66.0,351.0>--<66.0,375.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<66.0,351.0>--<66.0,375.0>>

	* uni0E0E (U+0E0E) contains a short segment L<<131.0,351.0>--<131.0,374.0>>

	* uni0E0F (U+0E0F) contains a short segment L<<364.0,-114.0>--<390.0,-114.0>>

	* uni0E0F (U+0E0F) contains a short segment L<<131.0,351.0>--<131.0,374.0>>

	* uni0E0F (U+0E0F) contains a short segment L<<329.0,-270.0>--<309.0,-270.0>> 

	* And 55 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<53.0,604.0>--<50.0,712.0>> -> L<<50.0,712.0>--<50.0,775.0>> 

	* And uni0E48 (U+0E48): L<<89.0,775.0>--<89.0,712.0>> -> L<<89.0,712.0>--<86.0,604.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0E2A (U+0E2A): B<<418.0,491.0>-<408.0,492.0>-<398.0,494.0>>/L<<398.0,494.0>--<398.0,494.0>> = 11.309932474020195 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSansThaiLoopedUI-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 290 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai Looped UI Light [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1112, but got 1069 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hmtx.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 266 font units wide, non-breaking space named (uni00A0) is 430 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped UI Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.6x (1600) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E1E	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E1F	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E1E	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E1F	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3 

	- And Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* semicolon (U+003B): X=66.5,Y=-1.5 (should be at baseline 0?)

	* question (U+003F): X=107.5,Y=713.5 (should be at cap-height 714?)

	* uni0E4C (U+0E4C): X=133.0,Y=716.0 (should be at cap-height 714?)

	* uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?) 

	* And uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E03 (U+0E03) contains a short segment B<<222.0,452.0>-<222.0,441.0>-<220.0,433.0>>

	* uni0E05 (U+0E05) contains a short segment L<<304.0,415.0>--<299.0,415.0>>

	* uni0E06 (U+0E06) contains a short segment B<<239.0,452.0>-<239.0,441.0>-<237.0,433.0>>

	* uni0E06 (U+0E06) contains a short segment B<<257.0,132.0>-<259.0,122.0>-<260.0,112.0>>

	* uni0E06 (U+0E06) contains a short segment B<<260.0,112.0>-<261.0,102.0>-<261.0,92.0>>

	* uni0E09 (U+0E09) contains a short segment L<<235.0,87.0>--<237.0,87.0>>

	* uni0E0B (U+0E0B) contains a short segment B<<228.0,452.0>-<228.0,441.0>-<226.0,433.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<64.0,349.0>--<64.0,376.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<428.0,196.0>-<442.0,196.0>-<454.0,194.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<64.0,349.0>--<64.0,376.0>> 

	* And 41 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<108.0,777.0>--<108.0,709.0>> -> L<<108.0,709.0>--<104.0,602.0>> 

	* And uni0E48 (U+0E48): L<<54.0,602.0>--<50.0,709.0>> -> L<<50.0,709.0>--<50.0,777.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0E1E (U+0E1E): B<<227.0,89.0>-<227.0,86.0>-<226.0,84.0>>/L<<226.0,84.0>--<228.0,89.0>> = 4.763641690726143

	* uni0E1E (U+0E1E): L<<583.0,88.0>--<585.0,83.0>>/L<<585.0,83.0>--<584.0,88.0>> = 10.491477012331599

	* uni0E1F (U+0E1F): B<<227.0,89.0>-<227.0,87.0>-<226.0,84.0>>/L<<226.0,84.0>--<228.0,89.0>> = 3.3664606634297236 

	* And uni0E1F (U+0E1F): L<<583.0,88.0>--<585.0,83.0>>/L<<585.0,83.0>--<584.0,88.0>> = 10.491477012331599 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiLoopedUI-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 290 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai Looped UI Medium [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1112, but got 1069 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hmtx.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 256 font units wide, non-breaking space named (uni00A0) is 260 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped UI Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.6x (1600) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E1E	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E1F	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E1E	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E1F	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3 

	- And Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* slash (U+002F): X=376.0,Y=716.0 (should be at cap-height 714?)

	* slash (U+002F): X=110.0,Y=-2.0 (should be at baseline 0?)

	* slash (U+002F): X=9.0,Y=-2.0 (should be at baseline 0?)

	* slash (U+002F): X=275.0,Y=716.0 (should be at cap-height 714?)

	* uni0E31 (U+0E31): X=50.0,Y=715.0 (should be at cap-height 714?)

	* uni0E35 (U+0E35): X=416.0,Y=713.0 (should be at cap-height 714?)

	* uni0E46 (U+0E46): X=353.0,Y=-1.0 (should be at baseline 0?)

	* uni0E49 (U+0E49): X=310.0,Y=712.5 (should be at cap-height 714?)

	* uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?) 

	* And uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E03 (U+0E03) contains a short segment L<<237.0,447.0>--<237.0,447.0>>

	* uni0E05 (U+0E05) contains a short segment L<<325.0,393.0>--<319.0,393.0>>

	* uni0E06 (U+0E06) contains a short segment B<<177.0,221.0>-<176.0,227.0>-<176.0,235.0>>

	* uni0E06 (U+0E06) contains a short segment L<<259.0,447.0>--<259.0,447.0>>

	* uni0E06 (U+0E06) contains a short segment B<<281.0,225.0>-<281.0,218.0>-<282.0,212.0>>

	* uni0E06 (U+0E06) contains a short segment B<<299.0,122.0>-<300.0,113.0>-<300.0,105.0>>

	* uni0E08 (U+0E08) contains a short segment B<<173.0,161.0>-<166.0,160.0>-<159.0,160.0>>

	* uni0E08 (U+0E08) contains a short segment L<<276.0,84.0>--<285.0,84.0>>

	* uni0E09 (U+0E09) contains a short segment B<<161.0,157.0>-<154.0,157.0>-<147.0,157.0>>

	* uni0E09 (U+0E09) contains a short segment L<<265.0,134.0>--<266.0,134.0>> 

	* And 79 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E1E (U+0E1E): L<<255.0,149.0>--<255.0,149.0>> -> L<<255.0,149.0>--<255.0,149.0>>

	* uni0E1F (U+0E1F): L<<255.0,149.0>--<255.0,149.0>> -> L<<255.0,149.0>--<255.0,149.0>>

	* uni0E48 (U+0E48): L<<153.0,787.0>--<153.0,708.0>> -> L<<153.0,708.0>--<147.0,597.0>> 

	* And uni0E48 (U+0E48): L<<56.0,597.0>--<50.0,708.0>> -> L<<50.0,708.0>--<50.0,787.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[12] NotoSansThaiLoopedUI-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 290 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai Looped UI [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1112, but got 1069 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped UI' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.6x (1600) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E1E	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E1F	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E1E	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E1F	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3 

	- And Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=177.5,Y=2.0 (should be at baseline 0?)

	* exclam (U+0021): X=90.0,Y=2.0 (should be at baseline 0?)

	* period (U+002E): X=177.5,Y=2.0 (should be at baseline 0?)

	* period (U+002E): X=90.0,Y=2.0 (should be at baseline 0?)

	* colon (U+003A): X=177.5,Y=2.0 (should be at baseline 0?)

	* colon (U+003A): X=90.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=222.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=134.5,Y=2.0 (should be at baseline 0?)

	* uni0E35 (U+0E35): X=416.0,Y=712.0 (should be at cap-height 714?)

	* uni0E46 (U+0E46): X=358.0,Y=-0.5 (should be at baseline 0?) 

	* And 11 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E05 (U+0E05) contains a short segment L<<318.0,399.0>--<312.0,399.0>>

	* uni0E06 (U+0E06) contains a short segment B<<176.0,215.0>-<181.0,215.0>-<186.0,215.0>>

	* uni0E06 (U+0E06) contains a short segment B<<270.0,223.0>-<270.0,213.0>-<271.0,203.0>>

	* uni0E08 (U+0E08) contains a short segment L<<268.0,72.0>--<275.0,72.0>>

	* uni0E09 (U+0E09) contains a short segment L<<255.0,124.0>--<257.0,124.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<525.0,224.0>-<525.0,212.0>-<526.0,202.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<543.0,124.0>-<545.0,115.0>-<545.0,102.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<433.0,215.0>-<436.0,215.0>-<439.0,215.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<439.0,215.0>-<439.0,227.0>-<439.0,243.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<162.0,190.0>-<171.0,191.0>-<181.0,191.0>> 

	* And 63 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<138.0,780.0>--<138.0,704.0>> -> L<<138.0,704.0>--<133.0,598.0>> 

	* And uni0E48 (U+0E48): L<<55.0,598.0>--<50.0,704.0>> -> L<<50.0,704.0>--<50.0,780.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[14] NotoSansThaiLoopedUI-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 290 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai Looped UI SemiBold [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1112, but got 1069 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hmtx.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 252 font units wide, non-breaking space named (uni00A0) is 260 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped UI SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.6x (1600) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E12	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E1E	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E1F	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E12	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E1E	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E1F	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3 

	- And Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=382.5,Y=0.5 (should be at baseline 0?)

	* uni0E31 (U+0E31): X=50.0,Y=716.0 (should be at cap-height 714?)

	* uni0E44 (U+0E44): X=280.0,Y=716.0 (should be at cap-height 714?)

	* uni0E48 (U+0E48): X=50.0,Y=712.0 (should be at cap-height 714?)

	* uni0E48 (U+0E48): X=169.0,Y=712.0 (should be at cap-height 714?)

	* uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?) 

	* And uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E02 (U+0E02) contains a short segment B<<176.0,339.0>-<170.0,338.0>-<164.0,338.0>>

	* uni0E05 (U+0E05) contains a short segment L<<333.0,386.0>--<327.0,386.0>>

	* uni0E06 (U+0E06) contains a short segment B<<168.0,227.0>-<168.0,229.0>-<168.0,233.0>>

	* uni0E06 (U+0E06) contains a short segment B<<293.0,227.0>-<293.0,224.0>-<293.0,222.0>>

	* uni0E06 (U+0E06) contains a short segment B<<309.0,118.0>-<310.0,114.0>-<310.0,109.0>>

	* uni0E07 (U+0E07) contains a short segment B<<353.0,341.0>-<350.0,341.0>-<345.0,341.0>>

	* uni0E08 (U+0E08) contains a short segment B<<163.0,158.0>-<159.0,158.0>-<155.0,158.0>>

	* uni0E08 (U+0E08) contains a short segment L<<285.0,97.0>--<296.0,97.0>>

	* uni0E09 (U+0E09) contains a short segment B<<370.0,98.0>-<370.0,106.0>-<372.0,114.0>>

	* uni0E09 (U+0E09) contains a short segment B<<152.0,155.0>-<148.0,154.0>-<144.0,154.0>> 

	* And 79 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<169.0,794.0>--<169.0,712.0>> -> L<<169.0,712.0>--<162.0,596.0>> 

	* And uni0E48 (U+0E48): L<<57.0,596.0>--<50.0,712.0>> -> L<<50.0,712.0>--<50.0,794.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0E03 (U+0E03): B<<168.5,320.0>-<193.0,344.0>-<213.0,364.0>>/B<<213.0,364.0>-<198.0,355.0>-<181.0,350.0>> = 14.036243467926457

	* uni0E06 (U+0E06): B<<210.0,332.5>-<227.0,351.0>-<242.0,368.0>>/B<<242.0,368.0>-<226.0,357.0>-<207.5,351.0>> = 14.067811387328987

	* uni0E0B (U+0E0B): B<<170.5,320.0>-<195.0,344.0>-<215.0,364.0>>/B<<215.0,364.0>-<200.0,355.0>-<183.0,350.0>> = 14.036243467926457 

	* And uni0E10 (U+0E10): B<<442.0,-204.0>-<449.0,-204.0>-<454.0,-204.0>>/B<<454.0,-204.0>-<419.0,-200.0>-<395.5,-178.0>> = 6.5198017516569164 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] NotoSansThaiLoopedUI-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 290 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai Looped UI Thin [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1112, but got 1069 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hmtx.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 272 font units wide, non-breaking space named (uni00A0) is 600 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped UI Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.6x (1600) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E2B	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E2B	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3 

	- And Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=132.5,Y=1.0 (should be at baseline 0?)

	* exclam (U+0021): X=90.0,Y=1.0 (should be at baseline 0?)

	* comma (U+002C): X=73.0,Y=1.5 (should be at baseline 0?)

	* period (U+002E): X=132.5,Y=1.0 (should be at baseline 0?)

	* period (U+002E): X=90.0,Y=1.0 (should be at baseline 0?)

	* colon (U+003A): X=132.5,Y=1.0 (should be at baseline 0?)

	* colon (U+003A): X=90.0,Y=1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=73.0,Y=1.5 (should be at baseline 0?)

	* question (U+003F): X=180.5,Y=1.0 (should be at baseline 0?)

	* question (U+003F): X=138.0,Y=1.0 (should be at baseline 0?) 

	* And 19 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E03 (U+0E03) contains a short segment B<<255.0,441.0>-<255.0,445.0>-<255.0,448.5>>

	* uni0E03 (U+0E03) contains a short segment B<<255.0,448.5>-<255.0,452.0>-<255.0,455.0>>

	* uni0E05 (U+0E05) contains a short segment L<<289.0,430.0>--<285.0,430.0>>

	* uni0E06 (U+0E06) contains a short segment B<<153.0,176.0>-<164.0,176.0>-<174.5,174.5>>

	* uni0E06 (U+0E06) contains a short segment B<<269.0,441.0>-<269.0,447.0>-<269.0,454.0>>

	* uni0E09 (U+0E09) contains a short segment L<<215.0,49.0>--<217.0,49.0>>

	* uni0E0B (U+0E0B) contains a short segment B<<262.0,441.0>-<262.0,445.0>-<262.0,448.5>>

	* uni0E0B (U+0E0B) contains a short segment B<<262.0,448.5>-<262.0,452.0>-<262.0,455.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<68.0,353.0>--<68.0,374.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<721.0,530.0>--<746.0,530.0>> 

	* And 76 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<53.0,605.0>--<50.0,714.0>> -> L<<50.0,714.0>--<50.0,774.0>> 

	* And uni0E48 (U+0E48): L<<77.0,774.0>--<77.0,714.0>> -> L<<77.0,714.0>--<74.0,605.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0E11 (U+0E11): B<<205.5,386.5>-<219.0,413.0>-<225.0,439.0>>/B<<225.0,439.0>-<212.0,413.0>-<182.0,395.0>> = 13.570434385161475 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<100.0,174.0>--<98.0,714.0>> 

	* And exclam (U+0021): L<<127.0,714.0>--<125.0,174.0>> [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 52 | 80 | 1037 | 58 | 768 | 0 |
| 0% | 3% | 4% | 52% | 3% | 38% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
