## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[1] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Verify that family names in the name table are consistent across all fonts in the family. Checks Typographic Family name (nameID 16) if present, otherwise uses Font Family name (nameID 1) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.adobe.fonts/check/family/consistent_family_name">com.adobe.fonts/check/family/consistent_family_name</a>)</summary><div>


* 🔥 **FAIL** 2 different Font Family names were found:

* 'Noto Sans Thai Looped' was found in:
  - NotoSansThaiLooped-Black.ttf (nameID 16)
  - NotoSansThaiLooped-Bold.ttf (nameID 1)
  - NotoSansThaiLooped-ExtraLight.ttf (nameID 16)
  - NotoSansThaiLooped-Light.ttf (nameID 16)
  - NotoSansThaiLooped-Medium.ttf (nameID 16)
  - NotoSansThaiLooped-Regular.ttf (nameID 1)
  - NotoSansThaiLooped-SemiBold.ttf (nameID 16)
  - NotoSansThaiLooped-Thin.ttf (nameID 16)

* 'Noto Sans Thai Looped Extrabold' was found in:
  - NotoSansThaiLooped-ExtraBold.ttf (nameID 1) [code: inconsistent-family-name]
</div></details><br></div></details><details><summary><b>[15] NotoSansThaiLooped-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 The Noto Project Authors" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts.
* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts GitHub repo.
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: OS/2 sTypoAscender is 1192 when it should be 1250 [code: bad-typo-ascender]
* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: hhea Ascender is 1192 when it should be 1250 [code: bad-hhea-ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, syriac, math, canadian-aboriginal, tifinagh, coptic, malayalam, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, caucasian-albanian, tifinagh, gothic, cherokee
 * U+035E COMBINING DOUBLE MACRON: try adding coptic
 * U+2010 HYPHEN: try adding one of: sundanese, kharoshthi, kaithi, lisu, coptic, syloti-nagri, cham, yi, kayah-li, sora-sompeng
 * U+2012 FIGURE DASH: not included in any glyphset definition
 * U+2015 HORIZONTAL BAR: try adding adlam
 * U+2060 WORD JOINER: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thai` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0E06
	* uni0E060331
	* uni0E09
	* uni0E0E.short
	* uni0E0F.short
	* uni0E10
	* uni0E10.less
	* uni0E12
	* uni0E14
	* uni0E140331
	* uni0E15
	* uni0E1B
	* uni0E24
	* uni0E240E45
	* uni0E260E45
	* uni0E28
	* uni0E2C
	* uni0E2C.short
	* uni0E2E
	* uni0E2F
	* uni0E31
	* uni0E32
	* uni0E320331
	* uni0E33
	* uni0E36
	* uni0E37
	* uni0E37.narrow
	* uni0E39
	* uni0E45
	* uni0E46
	* uni0E47
	* uni0E47.narrow
	* uni0E47.small
	* uni0E48
	* uni0E48.narrow
	* uni0E49
	* uni0E49.narrow
	* uni0E49.small
	* uni0E4A
	* uni0E4A.small
	* uni0E4B.small
	* uni0E4C
	* uni0E4C.narrow
	* uni0E4C.small
	* uni0E4E
	* uni0E4F
	* uni0E51
	* uni0E53
	* uni0E54
	* uni0E55
	* uni0E56
	* uni0E58
	* uni0E59 and uni0E5B
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0331.alt

	- uni035E.wide

	- uni0E29.BRACKET.varAlt01
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0E04	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E05	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E10	Contours detected: 6	Expected: 1 or 5

	- Glyph name: uni0E14	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E28	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E29	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni0E04	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E05	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E10	Contours detected: 6	Expected: 1 or 5

	- Glyph name: uni0E14	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E28	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E29	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 586 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 318:
minus
 [code: width-outliers]
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

	* g (U+0067): X=577.0,Y=-1.0 (should be at baseline 0?)

	* g (U+0067): X=386.0,Y=1.0 (should be at baseline 0?)

	* s (U+0073): X=373.0,Y=551.0 (should be at x-height 553?)

	* t (U+0074): X=363.0,Y=-1.0 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=506.0,Y=712.0 (should be at cap-height 714?)

	* agrave (U+00E0): X=282.0,Y=-1.5 (should be at baseline 0?)

	* aacute (U+00E1): X=282.0,Y=-1.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=282.0,Y=-1.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=447.5,Y=715.5 (should be at cap-height 714?)

	* acircumflex (U+00E2): X=179.5,Y=716.0 (should be at cap-height 714?)

	* atilde (U+00E3): X=282.0,Y=-1.5 (should be at baseline 0?)

	* adieresis (U+00E4): X=282.0,Y=-1.5 (should be at baseline 0?)

	* aring (U+00E5): X=282.0,Y=-1.5 (should be at baseline 0?)

	* ae (U+00E6): X=311.0,Y=-1.5 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=444.5,Y=715.5 (should be at cap-height 714?)

	* ecircumflex (U+00EA): X=176.5,Y=716.0 (should be at cap-height 714?)

	* icircumflex (U+00EE): X=298.5,Y=715.5 (should be at cap-height 714?)

	* icircumflex (U+00EE): X=30.5,Y=716.0 (should be at cap-height 714?)

	* ocircumflex (U+00F4): X=454.5,Y=715.5 (should be at cap-height 714?)

	* ocircumflex (U+00F4): X=186.5,Y=716.0 (should be at cap-height 714?)

	* ucircumflex (U+00FB): X=470.5,Y=715.5 (should be at cap-height 714?)

	* ucircumflex (U+00FB): X=202.5,Y=716.0 (should be at cap-height 714?)

	* amacron (U+0101): X=282.0,Y=-1.5 (should be at baseline 0?)

	* abreve (U+0103): X=282.0,Y=-1.5 (should be at baseline 0?)

	* aogonek (U+0105): X=282.0,Y=-1.5 (should be at baseline 0?)

	* Cacute (U+0106): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Cacute (U+0106): X=506.0,Y=712.0 (should be at cap-height 714?)

	* Cdotaccent (U+010A): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=506.0,Y=712.0 (should be at cap-height 714?)

	* Ccaron (U+010C): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=506.0,Y=712.0 (should be at cap-height 714?)

	* Gbreve (U+011E): X=545.5,Y=2.0 (should be at baseline 0?)

	* gbreve (U+011F): X=577.0,Y=-1.0 (should be at baseline 0?)

	* gbreve (U+011F): X=386.0,Y=1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=545.5,Y=2.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=577.0,Y=-1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=386.0,Y=1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=545.5,Y=2.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=577.0,Y=-1.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=386.0,Y=1.0 (should be at baseline 0?)

	* tcaron (U+0165): X=363.0,Y=-1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=590.5,Y=715.5 (should be at cap-height 714?)

	* wcircumflex (U+0175): X=322.5,Y=716.0 (should be at cap-height 714?)

	* ycircumflex (U+0177): X=440.5,Y=715.5 (should be at cap-height 714?)

	* ycircumflex (U+0177): X=172.5,Y=716.0 (should be at cap-height 714?)

	* uni021B (U+021B): X=363.0,Y=-1.0 (should be at baseline 0?)

	* circumflex (U+02C6): X=396.5,Y=715.5 (should be at cap-height 714?)

	* circumflex (U+02C6): X=128.5,Y=716.0 (should be at cap-height 714?)

	* uni0302 (U+0302): X=129.5,Y=715.5 (should be at cap-height 714?)

	* uni0302 (U+0302): X=-138.5,Y=716.0 (should be at cap-height 714?)

	* uni0312 (U+0312): X=-23.0,Y=713.0 (should be at cap-height 714?)

	* uni0312 (U+0312): X=113.0,Y=713.0 (should be at cap-height 714?)

	* uni0E2C (U+0E2C): X=344.5,Y=713.0 (should be at cap-height 714?)

	* uni0E31 (U+0E31): X=-319.0,Y=713.0 (should be at cap-height 714?)

	* uni0E31 (U+0E31): X=-319.0,Y=713.0 (should be at cap-height 714?)

	* uni0E4B (U+0E4B): X=-335.0,Y=716.0 (should be at cap-height 714?)

	* uni0E4B (U+0E4B): X=-2.0,Y=716.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-317.0,Y=716.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-190.0,Y=713.5 (should be at cap-height 714?)

	* uni0E54 (U+0E54): X=610.0,Y=1.5 (should be at baseline 0?)

	* uni0E54 (U+0E54): X=448.5,Y=-1.5 (should be at baseline 0?)

	* uni0E55 (U+0E55): X=610.0,Y=1.5 (should be at baseline 0?)

	* uni0E55 (U+0E55): X=448.5,Y=-1.5 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=401.0,Y=-1.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=96.0,Y=713.0 (should be at cap-height 714?)

	* quoteleft (U+2018): X=232.0,Y=713.0 (should be at cap-height 714?)

	* quoteright (U+2019): X=66.0,Y=713.0 (should be at cap-height 714?)

	* quoteright (U+2019): X=233.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=481.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=345.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=232.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=96.0,Y=713.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=315.0,Y=713.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=482.0,Y=713.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=66.0,Y=713.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=233.0,Y=713.0 (should be at cap-height 714?)

	* uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
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

	* Wdieresis (U+1E84): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wdieresis (U+1E84): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wdieresis (U+1E84): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wgrave (U+1E80): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wgrave (U+1E80): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wgrave (U+1E80): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* uni0E14 (U+0E14): B<<338.0,361.0>-<429.0,361.0>-<447.0,289.0>>/L<<447.0,289.0>--<447.0,324.0>> = 14.036243467926484

	* uni0E14 (U+0E14): L<<447.0,0.0>--<447.0,220.0>>/B<<447.0,220.0>-<433.0,158.0>-<366.0,91.0>> = 12.724355685422363 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Navajo (Latn, 166,319 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Kom (Latn, 360,685 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers), Ejagham (Latn, 120,000 speakers), Basaa (Latn, 332,940 speakers), Koonzime (Latn, 40,000 speakers), Avokaya (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[14] NotoSansThaiLooped-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 The Noto Project Authors" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts.
* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts GitHub repo.
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: OS/2 sTypoAscender is 1192 when it should be 1250 [code: bad-typo-ascender]
* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: hhea Ascender is 1192 when it should be 1250 [code: bad-hhea-ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, syriac, math, canadian-aboriginal, tifinagh, coptic, malayalam, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, caucasian-albanian, tifinagh, gothic, cherokee
 * U+035E COMBINING DOUBLE MACRON: try adding coptic
 * U+2010 HYPHEN: try adding one of: sundanese, kharoshthi, kaithi, lisu, coptic, syloti-nagri, cham, yi, kayah-li, sora-sompeng
 * U+2012 FIGURE DASH: not included in any glyphset definition
 * U+2015 HORIZONTAL BAR: try adding adlam
 * U+2060 WORD JOINER: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thai` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0E06
	* uni0E060331
	* uni0E09
	* uni0E10
	* uni0E12
	* uni0E1A
	* uni0E1B
	* uni0E240E45
	* uni0E260E45
	* uni0E29
	* uni0E2C
	* uni0E2F
	* uni0E30
	* uni0E31
	* uni0E320331
	* uni0E33
	* uni0E36
	* uni0E36.narrow
	* uni0E37
	* uni0E37.narrow
	* uni0E45
	* uni0E46
	* uni0E47
	* uni0E47.narrow
	* uni0E47.small
	* uni0E49
	* uni0E49.small
	* uni0E4A
	* uni0E4A.small
	* uni0E4C
	* uni0E4C.narrow
	* uni0E4C.small
	* uni0E4E
	* uni0E4F
	* uni0E53
	* uni0E54
	* uni0E55
	* uni0E56
	* uni0E58
	* uni0E59 and uni0E5B
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0331.alt

	- uni035E.wide

	- uni0E29.BRACKET.varAlt01
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0E10	Contours detected: 6	Expected: 1 or 5

	- Glyph name: uni0E29	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni0E10	Contours detected: 6	Expected: 1 or 5

	- Glyph name: uni0E29	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 581 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 320:
minus
 [code: width-outliers]
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

	* t (U+0074): X=104.0,Y=547.0 (should be at x-height 546?)

	* w (U+0077): X=12.0,Y=547.0 (should be at x-height 546?)

	* w (U+0077): X=162.0,Y=547.0 (should be at x-height 546?)

	* w (U+0077): X=349.0,Y=547.0 (should be at x-height 546?)

	* w (U+0077): X=515.0,Y=547.0 (should be at x-height 546?)

	* w (U+0077): X=703.0,Y=547.0 (should be at x-height 546?)

	* w (U+0077): X=850.0,Y=547.0 (should be at x-height 546?)

	* sterling (U+00A3): X=447.5,Y=713.0 (should be at cap-height 714?)

	* section (U+00A7): X=134.0,Y=0.5 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=114.5,Y=712.5 (should be at cap-height 714?)

	* Ccedilla (U+00C7): X=507.5,Y=712.5 (should be at cap-height 714?)

	* Oslash (U+00D8): X=487.0,Y=716.0 (should be at cap-height 714?)

	* acircumflex (U+00E2): X=413.0,Y=715.5 (should be at cap-height 714?)

	* acircumflex (U+00E2): X=187.5,Y=716.0 (should be at cap-height 714?)

	* ae (U+00E6): X=748.0,Y=-0.5 (should be at baseline 0?)

	* ae (U+00E6): X=308.5,Y=0.5 (should be at baseline 0?)

	* ccedilla (U+00E7): X=402.5,Y=1.0 (should be at baseline 0?)

	* egrave (U+00E8): X=435.0,Y=-0.5 (should be at baseline 0?)

	* eacute (U+00E9): X=435.0,Y=-0.5 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=435.0,Y=-0.5 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=413.0,Y=715.5 (should be at cap-height 714?)

	* ecircumflex (U+00EA): X=187.5,Y=716.0 (should be at cap-height 714?)

	* edieresis (U+00EB): X=435.0,Y=-0.5 (should be at baseline 0?)

	* icircumflex (U+00EE): X=263.0,Y=715.5 (should be at cap-height 714?)

	* icircumflex (U+00EE): X=37.5,Y=716.0 (should be at cap-height 714?)

	* ocircumflex (U+00F4): X=426.0,Y=715.5 (should be at cap-height 714?)

	* ocircumflex (U+00F4): X=200.5,Y=716.0 (should be at cap-height 714?)

	* oslash (U+00F8): X=87.0,Y=-1.0 (should be at baseline 0?)

	* ucircumflex (U+00FB): X=438.0,Y=715.5 (should be at cap-height 714?)

	* ucircumflex (U+00FB): X=212.5,Y=716.0 (should be at cap-height 714?)

	* abreve (U+0103): X=232.5,Y=716.0 (should be at cap-height 714?)

	* Cacute (U+0106): X=507.5,Y=712.5 (should be at cap-height 714?)

	* cacute (U+0107): X=402.5,Y=1.0 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=507.5,Y=712.5 (should be at cap-height 714?)

	* cdotaccent (U+010B): X=402.5,Y=1.0 (should be at baseline 0?)

	* Ccaron (U+010C): X=507.5,Y=712.5 (should be at cap-height 714?)

	* ccaron (U+010D): X=402.5,Y=1.0 (should be at baseline 0?)

	* emacron (U+0113): X=435.0,Y=-0.5 (should be at baseline 0?)

	* edotaccent (U+0117): X=435.0,Y=-0.5 (should be at baseline 0?)

	* ecaron (U+011B): X=435.0,Y=-0.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=542.5,Y=1.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=549.5,Y=712.0 (should be at cap-height 714?)

	* gbreve (U+011F): X=240.5,Y=716.0 (should be at cap-height 714?)

	* Gdotaccent (U+0120): X=542.5,Y=1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=549.5,Y=712.0 (should be at cap-height 714?)

	* uni0122 (U+0122): X=542.5,Y=1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=549.5,Y=712.0 (should be at cap-height 714?)

	* oe (U+0153): X=807.0,Y=-0.5 (should be at baseline 0?)

	* ubreve (U+016D): X=257.5,Y=716.0 (should be at cap-height 714?)

	* wcircumflex (U+0175): X=544.0,Y=715.5 (should be at cap-height 714?)

	* wcircumflex (U+0175): X=318.5,Y=716.0 (should be at cap-height 714?)

	* ycircumflex (U+0177): X=399.0,Y=715.5 (should be at cap-height 714?)

	* ycircumflex (U+0177): X=173.5,Y=716.0 (should be at cap-height 714?)

	* circumflex (U+02C6): X=354.0,Y=715.5 (should be at cap-height 714?)

	* circumflex (U+02C6): X=128.5,Y=716.0 (should be at cap-height 714?)

	* breve (U+02D8): X=154.5,Y=716.0 (should be at cap-height 714?)

	* uni0302 (U+0302): X=110.0,Y=715.5 (should be at cap-height 714?)

	* uni0302 (U+0302): X=-115.5,Y=716.0 (should be at cap-height 714?)

	* uni0306 (U+0306): X=-66.5,Y=716.0 (should be at cap-height 714?)

	* uni0312 (U+0312): X=-11.0,Y=713.0 (should be at cap-height 714?)

	* uni0312 (U+0312): X=97.0,Y=713.0 (should be at cap-height 714?)

	* uni0E31 (U+0E31): X=-8.0,Y=716.0 (should be at cap-height 714?)

	* uni0E36 (U+0E36): X=-125.0,Y=715.0 (should be at cap-height 714?)

	* uni0E36 (U+0E36): X=-186.5,Y=715.0 (should be at cap-height 714?)

	* uni0E4A (U+0E4A): X=-168.0,Y=715.0 (should be at cap-height 714?)

	* uni0E4A (U+0E4A): X=-165.0,Y=713.0 (should be at cap-height 714?)

	* uni0E4A (U+0E4A): X=-251.5,Y=716.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-299.0,Y=712.0 (should be at cap-height 714?)

	* uni0E51 (U+0E51): X=553.0,Y=2.0 (should be at baseline 0?)

	* uni0E54 (U+0E54): X=604.5,Y=1.0 (should be at baseline 0?)

	* uni0E54 (U+0E54): X=450.0,Y=-2.0 (should be at baseline 0?)

	* uni0E55 (U+0E55): X=604.5,Y=1.0 (should be at baseline 0?)

	* uni0E55 (U+0E55): X=450.0,Y=-2.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=371.5,Y=-1.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=97.0,Y=713.0 (should be at cap-height 714?)

	* quoteleft (U+2018): X=205.0,Y=713.0 (should be at cap-height 714?)

	* quoteright (U+2019): X=64.0,Y=713.0 (should be at cap-height 714?)

	* quoteright (U+2019): X=203.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=429.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=320.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=205.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=97.0,Y=713.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=288.0,Y=713.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=427.0,Y=713.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=64.0,Y=713.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=203.0,Y=713.0 (should be at cap-height 714?)

	* uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?)

	* uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
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

	* Wdieresis (U+1E84): B<<506.0,484.5>-<500.0,516.0>-<498.0,534.0>>/B<<498.0,534.0>-<496.0,516.0>-<490.0,484.5>> = 12.680383491819825

	* Wdieresis (U+1E84): B<<693.5,221.0>-<702.0,177.0>-<706.0,144.0>>/B<<706.0,144.0>-<709.0,168.0>-<715.0,202.0>> = 14.03624346792643

	* Wgrave (U+1E80): B<<280.5,202.0>-<287.0,168.0>-<290.0,144.0>>/B<<290.0,144.0>-<294.0,179.0>-<302.5,223.0>> = 13.644818100558723

	* Wgrave (U+1E80): B<<506.0,484.5>-<500.0,516.0>-<498.0,534.0>>/B<<498.0,534.0>-<496.0,516.0>-<490.0,484.5>> = 12.680383491819825

	* Wgrave (U+1E80): B<<693.5,221.0>-<702.0,177.0>-<706.0,144.0>>/B<<706.0,144.0>-<709.0,168.0>-<715.0,202.0>> = 14.03624346792643

	* uni0E10 (U+0E10): B<<82.0,312.5>-<113.0,339.0>-<160.0,341.0>>/L<<160.0,341.0>--<33.0,358.0>> = 10.060840751261908

	* uni0E10 (U+0E10): L<<293.0,324.0>--<222.0,333.0>>/B<<222.0,333.0>-<255.0,322.0>-<273.5,295.0>> = 11.210633128876657 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Navajo (Latn, 166,319 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Kom (Latn, 360,685 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers), Ejagham (Latn, 120,000 speakers), Basaa (Latn, 332,940 speakers), Koonzime (Latn, 40,000 speakers), Avokaya (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[17] NotoSansThaiLooped-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Expected "NotoSansThaiLoopedExtrabold-Regular.ttf. Got NotoSansThaiLooped-ExtraBold.ttf. [code: bad-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 The Noto Project Authors" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts.
* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts GitHub repo.
</div></details><details><summary>🔥 <b>FAIL:</b> Font has all mandatory 'name' table entries? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/mandatory_entries">com.google.fonts/check/name/mandatory_entries</a>)</summary><div>


* 🔥 **FAIL** Font lacks entry with nameId=16 (TYPOGRAPHIC_FAMILY_NAME) [code: missing-entry]
* 🔥 **FAIL** Font lacks entry with nameId=17 (TYPOGRAPHIC_SUBFAMILY_NAME) [code: missing-entry]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: OS/2 sTypoAscender is 1192 when it should be 1250 [code: bad-typo-ascender]
* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: hhea Ascender is 1192 when it should be 1250 [code: bad-hhea-ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, syriac, math, canadian-aboriginal, tifinagh, coptic, malayalam, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, caucasian-albanian, tifinagh, gothic, cherokee
 * U+035E COMBINING DOUBLE MACRON: try adding coptic
 * U+2010 HYPHEN: try adding one of: sundanese, kharoshthi, kaithi, lisu, coptic, syloti-nagri, cham, yi, kayah-li, sora-sompeng
 * U+2012 FIGURE DASH: not included in any glyphset definition
 * U+2015 HORIZONTAL BAR: try adding adlam
 * U+2060 WORD JOINER: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thai` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0E06
	* uni0E060331
	* uni0E09
	* uni0E0E.short
	* uni0E10
	* uni0E12
	* uni0E14
	* uni0E140331
	* uni0E15
	* uni0E1A
	* uni0E1B
	* uni0E240E45
	* uni0E260E45
	* uni0E28
	* uni0E29
	* uni0E2C
	* uni0E2F
	* uni0E30
	* uni0E31
	* uni0E320331
	* uni0E33
	* uni0E36
	* uni0E37
	* uni0E37.narrow
	* uni0E45
	* uni0E46
	* uni0E47
	* uni0E47.narrow
	* uni0E47.small
	* uni0E49
	* uni0E49.small
	* uni0E4A
	* uni0E4A.small
	* uni0E4C
	* uni0E4C.narrow
	* uni0E4C.small
	* uni0E4E
	* uni0E4F
	* uni0E53
	* uni0E54
	* uni0E55
	* uni0E56
	* uni0E58
	* uni0E59 and uni0E5B
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped Extrabold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0331.alt

	- uni035E.wide

	- uni0E29.BRACKET.varAlt01
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0E04	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E05	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E10	Contours detected: 6	Expected: 1 or 5

	- Glyph name: uni0E28	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E29	Contours detected: 5	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni0E04	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E05	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E10	Contours detected: 6	Expected: 1 or 5

	- Glyph name: uni0E28	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E29	Contours detected: 5	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 583 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 319:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E2D (U+0E2D): L<<220.0,183.0>--<220.0,182.0>> -> L<<220.0,182.0>--<220.0,140.0>> [code: found-colinear-vectors]
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

	* Wgrave (U+1E80): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981

	* uni0E04 (U+0E04): B<<339.0,363.0>-<430.0,363.0>-<446.0,287.0>>/L<<446.0,287.0>--<446.0,334.0>> = 11.888658039627968

	* uni0E04 (U+0E04): L<<446.0,0.0>--<446.0,230.0>>/B<<446.0,230.0>-<438.0,194.0>-<410.5,173.5>> = 12.528807709151492

	* uni0E05 (U+0E05): B<<338.0,358.0>-<430.0,358.0>-<445.0,279.0>>/L<<445.0,279.0>--<445.0,377.0>> = 10.750966993188039

	* uni0E05 (U+0E05): L<<445.0,0.0>--<445.0,227.0>>/B<<445.0,227.0>-<437.0,189.0>-<409.5,168.0>> = 11.888658039627968

	* uni0E28 (U+0E28): B<<339.0,363.0>-<430.0,363.0>-<446.0,287.0>>/L<<446.0,287.0>--<446.0,336.0>> = 11.888658039627968

	* uni0E28 (U+0E28): L<<446.0,0.0>--<446.0,230.0>>/B<<446.0,230.0>-<438.0,194.0>-<410.5,173.5>> = 12.528807709151492 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Navajo (Latn, 166,319 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Kom (Latn, 360,685 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers), Ejagham (Latn, 120,000 speakers), Basaa (Latn, 332,940 speakers), Koonzime (Latn, 40,000 speakers), Avokaya (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[16] NotoSansThaiLooped-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 The Noto Project Authors" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts.
* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts GitHub repo.
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: OS/2 sTypoAscender is 1192 when it should be 1250 [code: bad-typo-ascender]
* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: hhea Ascender is 1192 when it should be 1250 [code: bad-hhea-ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, syriac, math, canadian-aboriginal, tifinagh, coptic, malayalam, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, caucasian-albanian, tifinagh, gothic, cherokee
 * U+035E COMBINING DOUBLE MACRON: try adding coptic
 * U+2010 HYPHEN: try adding one of: sundanese, kharoshthi, kaithi, lisu, coptic, syloti-nagri, cham, yi, kayah-li, sora-sompeng
 * U+2012 FIGURE DASH: not included in any glyphset definition
 * U+2015 HORIZONTAL BAR: try adding adlam
 * U+2060 WORD JOINER: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thai` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0E2E
	* uni0E4A.small
	* uni0E4F
	* uni0E53 and uni0E5B
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0331.alt

	- uni035E.wide

	- uni0E29.BRACKET.varAlt01
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 570 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<-134.0,644.0>--<-138.0,761.0>> -> L<<-138.0,761.0>--<-138.0,821.0>>

	* uni0E48 (U+0E48): L<<-98.0,821.0>--<-98.0,761.0>> -> L<<-98.0,761.0>--<-102.0,644.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0E0D (U+0E0D): B<<541.5,-171.0>-<527.0,-189.0>-<502.0,-195.0>>/B<<502.0,-195.0>-<506.0,-195.0>-<511.0,-195.0>> = 13.495733280795811 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni0E5B (U+0E5B): L<<906.0,257.0>--<1045.0,256.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Navajo (Latn, 166,319 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Kom (Latn, 360,685 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers), Ejagham (Latn, 120,000 speakers), Basaa (Latn, 332,940 speakers), Koonzime (Latn, 40,000 speakers), Avokaya (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[15] NotoSansThaiLooped-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 The Noto Project Authors" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts.
* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts GitHub repo.
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: OS/2 sTypoAscender is 1192 when it should be 1250 [code: bad-typo-ascender]
* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: hhea Ascender is 1192 when it should be 1250 [code: bad-hhea-ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, syriac, math, canadian-aboriginal, tifinagh, coptic, malayalam, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, caucasian-albanian, tifinagh, gothic, cherokee
 * U+035E COMBINING DOUBLE MACRON: try adding coptic
 * U+2010 HYPHEN: try adding one of: sundanese, kharoshthi, kaithi, lisu, coptic, syloti-nagri, cham, yi, kayah-li, sora-sompeng
 * U+2012 FIGURE DASH: not included in any glyphset definition
 * U+2015 HORIZONTAL BAR: try adding adlam
 * U+2060 WORD JOINER: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thai` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0E2E
	* uni0E36.narrow
	* uni0E37
	* uni0E37.narrow
	* uni0E46
	* uni0E47
	* uni0E47.narrow
	* uni0E47.small
	* uni0E4A.small
	* uni0E4F
	* uni0E53 and uni0E5B
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0331.alt

	- uni035E.wide

	- uni0E29.BRACKET.varAlt01
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 571 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<-147.0,643.0>--<-153.0,765.0>> -> L<<-153.0,765.0>--<-153.0,834.0>>

	* uni0E48 (U+0E48): L<<-94.0,834.0>--<-94.0,765.0>> -> L<<-94.0,765.0>--<-100.0,643.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni0E09 (U+0E09): L<<168.0,0.0>--<167.0,169.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Navajo (Latn, 166,319 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Kom (Latn, 360,685 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers), Ejagham (Latn, 120,000 speakers), Basaa (Latn, 332,940 speakers), Koonzime (Latn, 40,000 speakers), Avokaya (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[15] NotoSansThaiLooped-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 The Noto Project Authors" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts.
* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts GitHub repo.
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: OS/2 sTypoAscender is 1192 when it should be 1250 [code: bad-typo-ascender]
* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: hhea Ascender is 1192 when it should be 1250 [code: bad-hhea-ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, syriac, math, canadian-aboriginal, tifinagh, coptic, malayalam, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, caucasian-albanian, tifinagh, gothic, cherokee
 * U+035E COMBINING DOUBLE MACRON: try adding coptic
 * U+2010 HYPHEN: try adding one of: sundanese, kharoshthi, kaithi, lisu, coptic, syloti-nagri, cham, yi, kayah-li, sora-sompeng
 * U+2012 FIGURE DASH: not included in any glyphset definition
 * U+2015 HORIZONTAL BAR: try adding adlam
 * U+2060 WORD JOINER: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thai` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0E06
	* uni0E060331
	* uni0E0D.less
	* uni0E12
	* uni0E1A
	* uni0E1A0331
	* uni0E1B
	* uni0E2C
	* uni0E2E
	* uni0E30
	* uni0E31
	* uni0E31.narrow
	* uni0E33
	* uni0E36
	* uni0E36.narrow
	* uni0E37
	* uni0E37.narrow
	* uni0E46
	* uni0E47
	* uni0E47.narrow
	* uni0E47.small
	* uni0E49.small
	* uni0E4A
	* uni0E4A.small
	* uni0E4C
	* uni0E4C.narrow
	* uni0E4C.small
	* uni0E4E
	* uni0E53
	* uni0E54
	* uni0E58
	* uni0E59 and uni0E5B
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0331.alt

	- uni035E.wide

	- uni0E29.BRACKET.varAlt01
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0E29	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni0E29	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 575 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 321:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<-184.0,640.0>--<-194.0,774.0>> -> L<<-194.0,774.0>--<-194.0,861.0>>

	* uni0E48 (U+0E48): L<<-86.0,861.0>--<-86.0,774.0>> -> L<<-86.0,774.0>--<-97.0,640.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* Wacute (U+1E82): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* Wcircumflex (U+0174): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* Wdieresis (U+1E84): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* Wgrave (U+1E80): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Navajo (Latn, 166,319 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Kom (Latn, 360,685 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers), Ejagham (Latn, 120,000 speakers), Basaa (Latn, 332,940 speakers), Koonzime (Latn, 40,000 speakers), Avokaya (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[14] NotoSansThaiLooped-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 The Noto Project Authors" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts.
* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts GitHub repo.
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: OS/2 sTypoAscender is 1192 when it should be 1250 [code: bad-typo-ascender]
* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: hhea Ascender is 1192 when it should be 1250 [code: bad-hhea-ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, syriac, math, canadian-aboriginal, tifinagh, coptic, malayalam, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, caucasian-albanian, tifinagh, gothic, cherokee
 * U+035E COMBINING DOUBLE MACRON: try adding coptic
 * U+2010 HYPHEN: try adding one of: sundanese, kharoshthi, kaithi, lisu, coptic, syloti-nagri, cham, yi, kayah-li, sora-sompeng
 * U+2012 FIGURE DASH: not included in any glyphset definition
 * U+2015 HORIZONTAL BAR: try adding adlam
 * U+2060 WORD JOINER: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thai` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0E06
	* uni0E060331
	* uni0E0D
	* uni0E0D.less
	* uni0E0D0331
	* uni0E1A
	* uni0E1A0331
	* uni0E1B
	* uni0E2C
	* uni0E2E
	* uni0E30
	* uni0E31
	* uni0E31.narrow
	* uni0E33
	* uni0E34
	* uni0E34.narrow
	* uni0E36
	* uni0E36.narrow
	* uni0E37
	* uni0E37.narrow
	* uni0E3A
	* uni0E46
	* uni0E47
	* uni0E47.narrow
	* uni0E47.small
	* uni0E49.small
	* uni0E4A
	* uni0E4A.small
	* uni0E4E
	* uni0E53
	* uni0E54 and uni0E5B
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0331.alt

	- uni035E.wide

	- uni0E29.BRACKET.varAlt01
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0E29	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni0E29	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<-171.0,641.0>--<-180.0,771.0>> -> L<<-180.0,771.0>--<-180.0,855.0>>

	* uni0E48 (U+0E48): L<<-89.0,855.0>--<-89.0,771.0>> -> L<<-89.0,771.0>--<-98.0,641.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Navajo (Latn, 166,319 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Kom (Latn, 360,685 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers), Ejagham (Latn, 120,000 speakers), Basaa (Latn, 332,940 speakers), Koonzime (Latn, 40,000 speakers), Avokaya (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[15] NotoSansThaiLooped-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 The Noto Project Authors" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts.
* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts GitHub repo.
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: OS/2 sTypoAscender is 1192 when it should be 1250 [code: bad-typo-ascender]
* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: hhea Ascender is 1192 when it should be 1250 [code: bad-hhea-ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, syriac, math, canadian-aboriginal, tifinagh, coptic, malayalam, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, caucasian-albanian, tifinagh, gothic, cherokee
 * U+035E COMBINING DOUBLE MACRON: try adding coptic
 * U+2010 HYPHEN: try adding one of: sundanese, kharoshthi, kaithi, lisu, coptic, syloti-nagri, cham, yi, kayah-li, sora-sompeng
 * U+2012 FIGURE DASH: not included in any glyphset definition
 * U+2015 HORIZONTAL BAR: try adding adlam
 * U+2060 WORD JOINER: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thai` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0E06
	* uni0E060331
	* uni0E12
	* uni0E1A
	* uni0E1A0331
	* uni0E1B
	* uni0E29
	* uni0E2C
	* uni0E2F
	* uni0E30
	* uni0E31
	* uni0E31.narrow
	* uni0E33
	* uni0E36
	* uni0E36.narrow
	* uni0E37
	* uni0E37.narrow
	* uni0E46
	* uni0E47
	* uni0E47.narrow
	* uni0E47.small
	* uni0E49.small
	* uni0E4A
	* uni0E4A.small
	* uni0E4C
	* uni0E4C.narrow
	* uni0E4C.small
	* uni0E4E
	* uni0E4F
	* uni0E53
	* uni0E54
	* uni0E55
	* uni0E58
	* uni0E59 and uni0E5B
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0331.alt

	- uni035E.wide

	- uni0E29.BRACKET.varAlt01
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0E29	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni0E29	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 577 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 320:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<-198.0,639.0>--<-210.0,777.0>> -> L<<-210.0,777.0>--<-210.0,868.0>>

	* uni0E48 (U+0E48): L<<-83.0,868.0>--<-83.0,777.0>> -> L<<-83.0,777.0>--<-96.0,639.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wacute (U+1E82): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wcircumflex (U+0174): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wdieresis (U+1E84): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wgrave (U+1E80): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Navajo (Latn, 166,319 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Kom (Latn, 360,685 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers), Ejagham (Latn, 120,000 speakers), Basaa (Latn, 332,940 speakers), Koonzime (Latn, 40,000 speakers), Avokaya (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[16] NotoSansThaiLooped-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 The Noto Project Authors" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts.
* 🔥 **FAIL** Version number 1.001007080078125 is equal to version on Google Fonts GitHub repo.
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: OS/2 sTypoAscender is 1192 when it should be 1250 [code: bad-typo-ascender]
* 🔥 **FAIL** Noto Sans Thai Looped Extrabold Regular: hhea Ascender is 1192 when it should be 1250 [code: bad-hhea-ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, syriac, math, canadian-aboriginal, tifinagh, coptic, malayalam, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, caucasian-albanian, tifinagh, gothic, cherokee
 * U+035E COMBINING DOUBLE MACRON: try adding coptic
 * U+2010 HYPHEN: try adding one of: sundanese, kharoshthi, kaithi, lisu, coptic, syloti-nagri, cham, yi, kayah-li, sora-sompeng
 * U+2012 FIGURE DASH: not included in any glyphset definition
 * U+2015 HORIZONTAL BAR: try adding adlam
 * U+2060 WORD JOINER: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `thai` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0E2E and uni0E4F
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0331.alt

	- uni035E.wide

	- uni0E29.BRACKET.varAlt01
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 570 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<-100.0,812.0>--<-100.0,758.0>> -> L<<-100.0,758.0>--<-103.0,645.0>>

	* uni0E48 (U+0E48): L<<-124.0,645.0>--<-127.0,758.0>> -> L<<-127.0,758.0>--<-127.0,812.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0E0D (U+0E0D): B<<531.5,-172.5>-<515.0,-191.0>-<487.0,-195.0>>/B<<487.0,-195.0>-<497.0,-196.0>-<509.0,-196.0>> = 13.840695491655614

	* uni0E2F (U+0E2F): B<<151.5,430.5>-<135.0,412.0>-<107.0,408.0>>/B<<107.0,408.0>-<117.0,407.0>-<129.0,407.0>> = 13.840695491655614

	* uni0E30 (U+0E30): B<<190.5,398.5>-<173.0,380.0>-<143.0,375.0>>/B<<143.0,375.0>-<147.0,375.0>-<150.0,375.0>> = 9.462322208025613

	* uni0E30 (U+0E30): B<<190.5,78.5>-<173.0,60.0>-<143.0,55.0>>/B<<143.0,55.0>-<147.0,55.0>-<150.0,55.0>> = 9.462322208025613

	* uni0E31 (U+0E31): B<<-194.5,681.0>-<-210.0,663.0>-<-237.0,657.0>>/L<<-237.0,657.0>--<-237.0,657.0>> = 12.528807709151492

	* uni0E5A (U+0E5A): B<<151.5,430.5>-<135.0,412.0>-<107.0,408.0>>/B<<107.0,408.0>-<117.0,407.0>-<129.0,407.0>> = 13.840695491655614 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<100.0,174.0>--<98.0,714.0>>

	* exclam (U+0021): L<<127.0,714.0>--<125.0,174.0>>

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>>

	* exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Navajo (Latn, 166,319 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Kom (Latn, 360,685 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers), Ejagham (Latn, 120,000 speakers), Basaa (Latn, 332,940 speakers), Koonzime (Latn, 40,000 speakers), Avokaya (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 48 | 90 | 1064 | 56 | 847 | 0 |
| 0% | 2% | 4% | 51% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
