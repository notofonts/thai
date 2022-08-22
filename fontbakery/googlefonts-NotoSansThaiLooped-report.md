## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[9] NotoSansThaiLooped-Black.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0E0D
	* tripleKhan
	* uni0E260E45
	* uni0E240E45
	* pikKaa
	* uni0E0D0331 and uni0E0C0331
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110 

	- And fonThongthai
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0E04	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E05	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E12	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E14	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E15	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E28	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3 

	- And 14 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=391.5,Y=-2.0 (should be at baseline 0?)

	* three (U+0033): X=129.0,Y=0.5 (should be at baseline 0?)

	* six (U+0036): X=510.0,Y=716.0 (should be at cap-height 714?)

	* C (U+0043): X=490.5,Y=-0.5 (should be at baseline 0?)

	* C (U+0043): X=506.0,Y=712.0 (should be at cap-height 714?)

	* G (U+0047): X=545.5,Y=2.0 (should be at baseline 0?)

	* a (U+0061): X=282.0,Y=-1.5 (should be at baseline 0?)

	* c (U+0063): X=429.5,Y=552.0 (should be at x-height 553?)

	* f (U+0066): X=99.0,Y=551.0 (should be at x-height 553?)

	* f (U+0066): X=143.0,Y=716.0 (should be at cap-height 714?) 

	* And 75 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<219.0,860.0>--<219.0,767.0>> -> L<<219.0,767.0>--<210.0,635.0>> 

	* And uni0E48 (U+0E48): L<<59.0,635.0>--<50.0,767.0>> -> L<<50.0,767.0>--<50.0,860.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<339.5,236.0>-<346.0,204.0>-<347.0,184.0>>/B<<347.0,184.0>-<349.0,204.0>-<354.5,235.5>> = 8.57299836361137

	* W (U+0057): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* W (U+0057): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* W (U+0057): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wacute (U+1E82): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wacute (U+1E82): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wacute (U+1E82): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wcircumflex (U+0174): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wcircumflex (U+0174): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[8] NotoSansThaiLooped-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110 

	- And fonThongthai
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0E12	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni0E12	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3 

	- And 4 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=386.0,Y=-0.5 (should be at baseline 0?)

	* four (U+0034): X=331.0,Y=716.0 (should be at cap-height 714?)

	* four (U+0034): X=475.0,Y=716.0 (should be at cap-height 714?)

	* six (U+0036): X=494.0,Y=716.0 (should be at cap-height 714?)

	* C (U+0043): X=507.5,Y=712.5 (should be at cap-height 714?)

	* G (U+0047): X=542.5,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=549.5,Y=712.0 (should be at cap-height 714?)

	* c (U+0063): X=402.5,Y=1.0 (should be at baseline 0?)

	* e (U+0065): X=435.0,Y=-0.5 (should be at baseline 0?)

	* s (U+0073): X=361.0,Y=545.0 (should be at x-height 546?) 

	* And 88 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* fongDan (U+EC0A): L<<131.0,637.0>--<120.0,759.0>> -> L<<120.0,759.0>--<120.0,845.0>>

	* fongDan (U+EC0A): L<<247.0,845.0>--<247.0,759.0>> -> L<<247.0,759.0>--<236.0,637.0>>

	* fongDan (U+EC0A): L<<314.0,637.0>--<303.0,759.0>> -> L<<303.0,759.0>--<303.0,845.0>>

	* fongDan (U+EC0A): L<<430.0,845.0>--<430.0,759.0>> -> L<<430.0,759.0>--<419.0,637.0>>

	* fongmanFanNu (U+EC09): L<<131.0,637.0>--<120.0,759.0>> -> L<<120.0,759.0>--<120.0,845.0>>

	* fongmanFanNu (U+EC09): L<<247.0,845.0>--<247.0,759.0>> -> L<<247.0,759.0>--<236.0,637.0>>

	* fongmanFanNu (U+EC09): L<<315.0,637.0>--<303.0,759.0>> -> L<<303.0,759.0>--<303.0,845.0>>

	* fongmanFanNu (U+EC09): L<<431.0,845.0>--<431.0,759.0>> -> L<<431.0,759.0>--<419.0,637.0>>

	* uni0E12 (U+0E12): L<<393.0,146.0>--<390.0,143.0>> -> L<<390.0,143.0>--<256.0,0.0>>

	* uni0E48 (U+0E48): L<<187.0,845.0>--<187.0,759.0>> -> L<<187.0,759.0>--<180.0,637.0>> 

	* And 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<280.5,202.0>-<287.0,168.0>-<290.0,144.0>>/B<<290.0,144.0>-<294.0,179.0>-<302.5,223.0>> = 13.644818100558723

	* W (U+0057): B<<506.0,484.5>-<500.0,516.0>-<498.0,534.0>>/B<<498.0,534.0>-<496.0,516.0>-<490.0,484.5>> = 12.680383491819825

	* W (U+0057): B<<693.5,221.0>-<702.0,177.0>-<706.0,144.0>>/B<<706.0,144.0>-<709.0,168.0>-<715.0,202.0>> = 14.03624346792643

	* Wacute (U+1E82): B<<280.5,202.0>-<287.0,168.0>-<290.0,144.0>>/B<<290.0,144.0>-<294.0,179.0>-<302.5,223.0>> = 13.644818100558723

	* Wacute (U+1E82): B<<506.0,484.5>-<500.0,516.0>-<498.0,534.0>>/B<<498.0,534.0>-<496.0,516.0>-<490.0,484.5>> = 12.680383491819825

	* Wacute (U+1E82): B<<693.5,221.0>-<702.0,177.0>-<706.0,144.0>>/B<<706.0,144.0>-<709.0,168.0>-<715.0,202.0>> = 14.03624346792643

	* Wcircumflex (U+0174): B<<280.5,202.0>-<287.0,168.0>-<290.0,144.0>>/B<<290.0,144.0>-<294.0,179.0>-<302.5,223.0>> = 13.644818100558723

	* Wcircumflex (U+0174): B<<506.0,484.5>-<500.0,516.0>-<498.0,534.0>>/B<<498.0,534.0>-<496.0,516.0>-<490.0,484.5>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<693.5,221.0>-<702.0,177.0>-<706.0,144.0>>/B<<706.0,144.0>-<709.0,168.0>-<715.0,202.0>> = 14.03624346792643

	* Wdieresis (U+1E84): B<<280.5,202.0>-<287.0,168.0>-<290.0,144.0>>/B<<290.0,144.0>-<294.0,179.0>-<302.5,223.0>> = 13.644818100558723 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni0E05 (U+0E05): L<<466.0,0.0>--<465.0,382.0>> 

	* And uni0E1B (U+0E1B): L<<283.0,114.0>--<398.0,115.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] NotoSansThaiLooped-ExtraBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110 

	- And fonThongthai
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0E12	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E14	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E15	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And 8 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* fongDan (U+EC0A): L<<116.0,636.0>--<104.0,763.0>> -> L<<104.0,763.0>--<104.0,852.0>>

	* fongDan (U+EC0A): L<<312.0,636.0>--<300.0,763.0>> -> L<<300.0,763.0>--<300.0,852.0>>

	* fongmanFanNu (U+EC09): L<<244.0,852.0>--<244.0,763.0>> -> L<<244.0,763.0>--<232.0,636.0>>

	* fongmanFanNu (U+EC09): L<<440.0,852.0>--<440.0,763.0>> -> L<<440.0,763.0>--<428.0,636.0>>

	* unalome (U+EC0B): L<<287.0,615.0>--<287.0,615.0>> -> L<<287.0,615.0>--<287.0,615.0>>

	* uni0E48 (U+0E48): L<<202.0,852.0>--<202.0,763.0>> -> L<<202.0,763.0>--<194.0,636.0>>

	* uni0E48 (U+0E48): L<<58.0,636.0>--<50.0,763.0>> -> L<<50.0,763.0>--<50.0,852.0>>

	* uni17C9 (U+17C9): L<<190.0,852.0>--<190.0,763.0>> -> L<<190.0,763.0>--<178.0,636.0>>

	* uni17C9 (U+17C9): L<<386.0,852.0>--<386.0,763.0>> -> L<<386.0,763.0>--<374.0,636.0>>

	* uni17CB (U+17CB): L<<202.0,852.0>--<202.0,763.0>> -> L<<202.0,763.0>--<190.0,636.0>> 

	* And uni17CB (U+17CB): L<<62.0,636.0>--<50.0,763.0>> -> L<<50.0,763.0>--<50.0,852.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<329.0,217.5>-<335.0,187.0>-<337.0,166.0>>/B<<337.0,166.0>-<340.0,187.0>-<345.5,217.0>> = 13.570434385161475

	* W (U+0057): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475

	* W (U+0057): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981

	* Wacute (U+1E82): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475

	* Wacute (U+1E82): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981

	* Wcircumflex (U+0174): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475

	* Wcircumflex (U+0174): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981

	* Wdieresis (U+1E84): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475

	* Wdieresis (U+1E84): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981

	* Wgrave (U+1E80): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475 

	* And 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni0E05 (U+0E05): L<<464.0,0.0>--<463.0,379.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[7] NotoSansThaiLooped-ExtraLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110 

	- And fonThongthai
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0E1E	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E1F	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E2B	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And 8 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* fongDan (U+EC0A): L<<218.0,644.0>--<213.0,752.0>> -> L<<213.0,752.0>--<213.0,816.0>>

	* fongDan (U+EC0A): L<<252.0,816.0>--<252.0,752.0>> -> L<<252.0,752.0>--<247.0,644.0>>

	* fongDan (U+EC0A): L<<333.0,644.0>--<328.0,752.0>> -> L<<328.0,752.0>--<328.0,816.0>>

	* fongDan (U+EC0A): L<<367.0,816.0>--<367.0,752.0>> -> L<<367.0,752.0>--<362.0,644.0>>

	* fongmanFanNu (U+EC09): L<<218.0,644.0>--<213.0,752.0>> -> L<<213.0,752.0>--<213.0,816.0>>

	* fongmanFanNu (U+EC09): L<<252.0,816.0>--<252.0,752.0>> -> L<<252.0,752.0>--<247.0,644.0>>

	* fongmanFanNu (U+EC09): L<<333.0,644.0>--<328.0,752.0>> -> L<<328.0,752.0>--<328.0,816.0>>

	* fongmanFanNu (U+EC09): L<<367.0,816.0>--<367.0,752.0>> -> L<<367.0,752.0>--<362.0,644.0>>

	* uni0E1E (U+0E1E): L<<217.0,60.0>--<217.0,60.0>> -> L<<217.0,60.0>--<217.0,60.0>>

	* uni0E48 (U+0E48): L<<53.0,644.0>--<50.0,752.0>> -> L<<50.0,752.0>--<50.0,816.0>> 

	* And 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0E2A (U+0E2A): B<<418.0,511.0>-<408.0,512.0>-<398.0,514.0>>/L<<398.0,514.0>--<398.0,514.0>> = 11.309932474020195 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[8] NotoSansThaiLooped-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110 

	- And fonThongthai
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0E1E	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E1F	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni0E1E	Contours detected: 4	Expected: 1 or 2 

	- And 6 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* fongDan (U+EC0A): L<<204.0,643.0>--<199.0,750.0>> -> L<<199.0,750.0>--<199.0,818.0>>

	* fongDan (U+EC0A): L<<254.0,818.0>--<254.0,750.0>> -> L<<254.0,750.0>--<249.0,643.0>>

	* fongDan (U+EC0A): L<<329.0,643.0>--<323.0,750.0>> -> L<<323.0,750.0>--<323.0,818.0>>

	* fongDan (U+EC0A): L<<379.0,818.0>--<379.0,750.0>> -> L<<379.0,750.0>--<373.0,643.0>>

	* fongmanFanNu (U+EC09): L<<205.0,643.0>--<199.0,750.0>> -> L<<199.0,750.0>--<199.0,818.0>>

	* fongmanFanNu (U+EC09): L<<255.0,818.0>--<255.0,750.0>> -> L<<255.0,750.0>--<249.0,643.0>>

	* fongmanFanNu (U+EC09): L<<329.0,643.0>--<324.0,750.0>> -> L<<324.0,750.0>--<324.0,818.0>>

	* fongmanFanNu (U+EC09): L<<379.0,818.0>--<379.0,750.0>> -> L<<379.0,750.0>--<374.0,643.0>>

	* uni0E48 (U+0E48): L<<108.0,818.0>--<108.0,750.0>> -> L<<108.0,750.0>--<104.0,643.0>>

	* uni0E48 (U+0E48): L<<54.0,643.0>--<50.0,750.0>> -> L<<50.0,750.0>--<50.0,818.0>> 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0E10 (U+0E10): B<<442.0,497.0>-<425.0,497.0>-<409.0,500.0>>/L<<409.0,500.0>--<409.0,500.0>> = 10.61965527615514 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni0E05 (U+0E05): L<<475.0,0.0>--<474.0,389.0>> 

	* And uni0E1B (U+0E1B): L<<234.0,47.0>--<417.0,48.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] NotoSansThaiLooped-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110 

	- And fonThongthai
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* fongDan (U+EC0A): L<<166.0,639.0>--<158.0,750.0>> -> L<<158.0,750.0>--<158.0,829.0>>

	* fongDan (U+EC0A): L<<255.0,829.0>--<255.0,750.0>> -> L<<255.0,750.0>--<247.0,639.0>>

	* fongDan (U+EC0A): L<<319.0,639.0>--<311.0,750.0>> -> L<<311.0,750.0>--<311.0,829.0>>

	* fongDan (U+EC0A): L<<408.0,829.0>--<408.0,750.0>> -> L<<408.0,750.0>--<399.0,639.0>>

	* fongmanFanNu (U+EC09): L<<166.0,639.0>--<158.0,750.0>> -> L<<158.0,750.0>--<158.0,829.0>>

	* fongmanFanNu (U+EC09): L<<255.0,829.0>--<255.0,750.0>> -> L<<255.0,750.0>--<247.0,639.0>>

	* fongmanFanNu (U+EC09): L<<319.0,639.0>--<311.0,750.0>> -> L<<311.0,750.0>--<311.0,829.0>>

	* fongmanFanNu (U+EC09): L<<408.0,829.0>--<408.0,750.0>> -> L<<408.0,750.0>--<399.0,639.0>>

	* uni0E48 (U+0E48): L<<153.0,829.0>--<153.0,750.0>> -> L<<153.0,750.0>--<147.0,639.0>>

	* uni0E48 (U+0E48): L<<56.0,639.0>--<50.0,750.0>> -> L<<50.0,750.0>--<50.0,829.0>> 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* Wacute (U+1E82): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* Wcircumflex (U+0174): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* Wdieresis (U+1E84): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328 

	* And Wgrave (U+1E80): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni0E05 (U+0E05): L<<471.0,0.0>--<470.0,388.0>> 

	* And uni0E1B (U+0E1B): L<<263.0,84.0>--<402.0,85.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] NotoSansThaiLooped-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* unalome
	* uni0E52
	* uni0E0D
	* uni0E0C
	* khomutReversed
	* uni0E5B
	* tripleKhan
	* uni0E260E45
	* uni0E240E45
	* uni0E0D0331 and 4 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110 

	- And fonThongthai
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* fongDan (U+EC0A): L<<181.0,640.0>--<174.0,746.0>> -> L<<174.0,746.0>--<174.0,822.0>>

	* fongDan (U+EC0A): L<<258.0,822.0>--<258.0,746.0>> -> L<<258.0,746.0>--<251.0,640.0>>

	* fongDan (U+EC0A): L<<321.0,640.0>--<314.0,746.0>> -> L<<314.0,746.0>--<314.0,822.0>>

	* fongDan (U+EC0A): L<<398.0,822.0>--<398.0,746.0>> -> L<<398.0,746.0>--<391.0,640.0>>

	* fongmanFanNu (U+EC09): L<<181.0,640.0>--<174.0,746.0>> -> L<<174.0,746.0>--<174.0,822.0>>

	* fongmanFanNu (U+EC09): L<<258.0,822.0>--<258.0,746.0>> -> L<<258.0,746.0>--<251.0,640.0>>

	* fongmanFanNu (U+EC09): L<<321.0,640.0>--<314.0,746.0>> -> L<<314.0,746.0>--<314.0,822.0>>

	* fongmanFanNu (U+EC09): L<<398.0,822.0>--<398.0,746.0>> -> L<<398.0,746.0>--<391.0,640.0>>

	* uni0E48 (U+0E48): L<<138.0,822.0>--<138.0,746.0>> -> L<<138.0,746.0>--<133.0,640.0>>

	* uni0E48 (U+0E48): L<<55.0,640.0>--<50.0,746.0>> -> L<<50.0,746.0>--<50.0,822.0>> 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni0E05 (U+0E05): L<<473.0,0.0>--<472.0,391.0>> 

	* And uni0E1B (U+0E1B): L<<254.0,71.0>--<404.0,72.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] NotoSansThaiLooped-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110 

	- And fonThongthai
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* fongDan (U+EC0A): L<<150.0,638.0>--<140.0,754.0>> -> L<<140.0,754.0>--<140.0,836.0>>

	* fongDan (U+EC0A): L<<251.0,836.0>--<251.0,754.0>> -> L<<251.0,754.0>--<242.0,638.0>>

	* fongDan (U+EC0A): L<<317.0,638.0>--<307.0,754.0>> -> L<<307.0,754.0>--<307.0,836.0>>

	* fongDan (U+EC0A): L<<418.0,836.0>--<418.0,754.0>> -> L<<418.0,754.0>--<408.0,638.0>>

	* fongmanFanNu (U+EC09): L<<150.0,638.0>--<140.0,754.0>> -> L<<140.0,754.0>--<140.0,836.0>>

	* fongmanFanNu (U+EC09): L<<251.0,836.0>--<251.0,754.0>> -> L<<251.0,754.0>--<241.0,638.0>>

	* fongmanFanNu (U+EC09): L<<317.0,638.0>--<307.0,754.0>> -> L<<307.0,754.0>--<307.0,836.0>>

	* fongmanFanNu (U+EC09): L<<418.0,836.0>--<418.0,754.0>> -> L<<418.0,754.0>--<408.0,638.0>>

	* uni0E48 (U+0E48): L<<169.0,836.0>--<169.0,754.0>> -> L<<169.0,754.0>--<162.0,638.0>>

	* uni0E48 (U+0E48): L<<57.0,638.0>--<50.0,754.0>> -> L<<50.0,754.0>--<50.0,836.0>> 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wacute (U+1E82): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wcircumflex (U+0174): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wdieresis (U+1E84): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wgrave (U+1E80): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216 

	* And uni0E10 (U+0E10): B<<442.0,-204.0>-<449.0,-204.0>-<454.0,-204.0>>/B<<454.0,-204.0>-<419.0,-200.0>-<395.5,-178.0>> = 6.5198017516569164 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni0E1B (U+0E1B): L<<272.0,98.0>--<400.0,99.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] NotoSansThaiLooped-Thin.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0E29.BRACKET.110 

	- And fonThongthai
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0E2B	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E5A	Contours detected: 3	Expected: 1 or 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni0E2B	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 2	Expected: 1 or 3 

	- And 4 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* fongDan (U+EC0A): L<<227.0,645.0>--<223.0,754.0>> -> L<<223.0,754.0>--<223.0,814.0>>

	* fongDan (U+EC0A): L<<250.0,814.0>--<250.0,754.0>> -> L<<250.0,754.0>--<246.0,645.0>>

	* fongDan (U+EC0A): L<<336.0,645.0>--<332.0,754.0>> -> L<<332.0,754.0>--<332.0,814.0>>

	* fongDan (U+EC0A): L<<359.0,814.0>--<359.0,754.0>> -> L<<359.0,754.0>--<355.0,645.0>>

	* fongmanFanNu (U+EC09): L<<227.0,645.0>--<223.0,754.0>> -> L<<223.0,754.0>--<223.0,814.0>>

	* fongmanFanNu (U+EC09): L<<250.0,814.0>--<250.0,754.0>> -> L<<250.0,754.0>--<246.0,645.0>>

	* fongmanFanNu (U+EC09): L<<336.0,645.0>--<332.0,754.0>> -> L<<332.0,754.0>--<332.0,814.0>>

	* fongmanFanNu (U+EC09): L<<359.0,814.0>--<359.0,754.0>> -> L<<359.0,754.0>--<355.0,645.0>>

	* uni0E48 (U+0E48): L<<53.0,645.0>--<50.0,754.0>> -> L<<50.0,754.0>--<50.0,814.0>>

	* uni0E48 (U+0E48): L<<77.0,814.0>--<77.0,754.0>> -> L<<77.0,754.0>--<74.0,645.0>> 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0E11 (U+0E11): B<<205.5,406.5>-<219.0,433.0>-<225.0,459.0>>/B<<225.0,459.0>-<212.0,433.0>-<182.0,415.0>> = 13.570434385161475 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<100.0,174.0>--<98.0,714.0>>

	* exclam (U+0021): L<<127.0,714.0>--<125.0,174.0>>

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>> 

	* And exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>> [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 9 | 0 | 63 | 1010 | 56 | 857 | 0 |
| 0% | 0% | 3% | 51% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
