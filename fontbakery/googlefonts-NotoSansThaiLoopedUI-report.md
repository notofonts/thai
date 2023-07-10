## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[13] NotoSansThaiLoopedUI-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- 276 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 The Noto Project Authors" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai Looped UI Black [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped UI Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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

	- Glyph name: uni0E04	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E05	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E0C	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E0D	Contours detected: 5	Expected: 1 or 4

	- Glyph name: uni0E10	Contours detected: 6	Expected: 1 or 5

	- Glyph name: uni0E13	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E14	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E15	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E28	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0E29	Contours detected: 4	Expected: 1 or 3 

	- 12 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 586 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 318:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=391.5,Y=-2.0 (should be at baseline 0?)

	* uni0E31 (U+0E31): X=-324.5,Y=712.5 (should be at cap-height 714?)

	* uni0E43 (U+0E43): X=207.0,Y=715.0 (should be at cap-height 714?)

	* uni0E51 (U+0E51): X=323.0,Y=-2.0 (should be at baseline 0?)

	* uni0E54 (U+0E54): X=558.0,Y=1.5 (should be at baseline 0?)

	* uni0E54 (U+0E54): X=407.5,Y=-1.5 (should be at baseline 0?)

	* uni0E55 (U+0E55): X=558.0,Y=1.5 (should be at baseline 0?)

	* uni0E55 (U+0E55): X=407.5,Y=-1.5 (should be at baseline 0?)

	* quoteleft (U+2018): X=96.0,Y=713.0 (should be at cap-height 714?)

	* quoteleft (U+2018): X=232.0,Y=713.0 (should be at cap-height 714?) 

	* 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E01 (U+0E01) contains a short segment L<<37.0,310.0>--<37.0,325.0>>

	* uni0E03 (U+0E03) contains a short segment B<<171.5,334.5>-<178.0,339.0>-<182.0,343.0>>

	* uni0E06 (U+0E06) contains a short segment B<<164.0,334.0>-<170.0,339.0>-<176.0,343.0>>

	* uni0E07 (U+0E07) contains a short segment L<<254.0,129.0>--<259.0,129.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<25.0,310.0>--<25.0,325.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<33.0,132.0>--<33.0,130.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<25.0,310.0>--<25.0,325.0>>

	* uni0E0E (U+0E0E) contains a short segment B<<107.0,217.0>-<105.0,226.0>-<105.0,231.0>>

	* uni0E0E (U+0E0E) contains a short segment L<<42.0,310.0>--<42.0,325.0>>

	* uni0E0F (U+0E0F) contains a short segment B<<183.0,-25.0>-<186.0,-9.0>-<187.0,0.0>> 

	* 54 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E0C (U+0E0C): L<<33.0,132.0>--<33.0,130.0>> -> L<<33.0,130.0>--<33.0,126.0>>

	* uni0E0D (U+0E0D): L<<38.0,132.0>--<38.0,129.0>> -> L<<38.0,129.0>--<38.0,126.0>> 

	* uni0E13 (U+0E13): L<<38.0,132.0>--<38.0,129.0>> -> L<<38.0,129.0>--<38.0,126.0>> [code: found-colinear-vectors]
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
 

	- 276 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 The Noto Project Authors" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai Looped UI [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped UI' / SUBFAMILY_NAME = 'Bold'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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

	- Glyph name: uni0E10	Contours detected: 6	Expected: 1 or 5

	- Glyph name: uni0E29	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 6	Expected: 1 or 5

	- Glyph name: uni0E29	Contours detected: 4	Expected: 1 or 3 

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 579 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 320:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E2C (U+0E2C): X=519.0,Y=713.0 (should be at cap-height 714?)

	* uni0E2C (U+0E2C): X=642.0,Y=713.0 (should be at cap-height 714?)

	* uni0E31 (U+0E31): X=-279.0,Y=715.0 (should be at cap-height 714?)

	* uni0E33 (U+0E33): X=-109.0,Y=712.5 (should be at cap-height 714?)

	* uni0E33 (U+0E33): X=-174.0,Y=712.5 (should be at cap-height 714?)

	* uni0E36 (U+0E36): X=-229.0,Y=715.0 (should be at cap-height 714?)

	* uni0E36 (U+0E36): X=-227.0,Y=715.0 (should be at cap-height 714?)

	* uni0E36 (U+0E36): X=-115.0,Y=715.0 (should be at cap-height 714?)

	* uni0E36 (U+0E36): X=-171.0,Y=715.0 (should be at cap-height 714?)

	* uni0E47 (U+0E47): X=-228.5,Y=715.5 (should be at cap-height 714?) 

	* 22 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E01 (U+0E01) contains a short segment L<<43.0,318.0>--<43.0,332.0>>

	* uni0E05 (U+0E05) contains a short segment L<<297.0,363.0>--<288.0,363.0>>

	* uni0E06 (U+0E06) contains a short segment B<<255.0,100.0>-<256.0,97.0>-<256.0,93.0>>

	* uni0E08 (U+0E08) contains a short segment B<<131.0,165.0>-<128.0,165.0>-<124.0,165.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<33.0,318.0>--<33.0,332.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<189.0,182.0>--<189.0,182.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<33.0,318.0>--<33.0,332.0>>

	* uni0E0E (U+0E0E) contains a short segment L<<115.0,197.0>--<115.0,197.0>>

	* uni0E0E (U+0E0E) contains a short segment B<<115.0,197.0>-<114.0,204.0>-<114.0,209.0>>

	* uni0E0E (U+0E0E) contains a short segment L<<52.0,318.0>--<52.0,332.0>> 

	* 52 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E2D (U+0E2D): L<<192.0,169.0>--<192.0,163.0>> -> L<<192.0,163.0>--<192.0,123.0>> 

	* uni0E2E (U+0E2E): L<<192.0,166.0>--<192.0,160.0>> -> L<<192.0,160.0>--<192.0,122.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0E10 (U+0E10): B<<72.5,282.0>-<98.0,306.0>-<138.0,310.0>>/L<<138.0,310.0>--<30.0,325.0>> = 13.617755840458111 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansThaiLoopedUI-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- 276 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 The Noto Project Authors" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai Looped UI Light [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped UI Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0331.alt

	- uni035E.wide 

	- uni0E29.BRACKET.varAlt01
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 571 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* semicolon (U+003B): X=66.5,Y=-1.5 (should be at baseline 0?)

	* question (U+003F): X=107.5,Y=713.5 (should be at cap-height 714?)

	* uni0E0E (U+0E0E): X=266.0,Y=1.0 (should be at baseline 0?)

	* uni0E0E (U+0E0E): X=103.0,Y=1.0 (should be at baseline 0?)

	* uni0E0F (U+0E0F): X=103.0,Y=1.0 (should be at baseline 0?)

	* uni0E34 (U+0E34): X=-378.0,Y=715.5 (should be at cap-height 714?)

	* uni0E34 (U+0E34): X=-174.0,Y=715.0 (should be at cap-height 714?)

	* uni0E36 (U+0E36): X=-166.5,Y=716.0 (should be at cap-height 714?)

	* uni0E36 (U+0E36): X=-58.5,Y=713.5 (should be at cap-height 714?)

	* uni0E44 (U+0E44): X=99.0,Y=715.0 (should be at cap-height 714?) 

	* 10 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E01 (U+0E01) contains a short segment L<<56.0,333.0>--<56.0,344.0>>

	* uni0E04 (U+0E04) contains a short segment B<<203.0,238.0>-<203.0,240.0>-<203.0,240.0>>

	* uni0E05 (U+0E05) contains a short segment L<<273.0,395.0>--<266.0,395.0>>

	* uni0E05 (U+0E05) contains a short segment B<<201.0,236.0>-<201.0,238.0>-<201.0,238.0>>

	* uni0E08 (U+0E08) contains a short segment L<<214.0,42.0>--<228.0,42.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<52.0,333.0>--<52.0,344.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<466.0,98.0>-<469.0,88.0>-<469.0,76.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<385.0,156.0>-<389.0,156.0>-<392.0,156.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<135.0,156.0>-<135.0,150.0>-<135.0,147.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<52.0,333.0>--<52.0,344.0>> 

	* 65 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<-138.0,585.0>--<-144.0,697.0>> -> L<<-144.0,697.0>--<-144.0,761.0>> 

	* uni0E48 (U+0E48): L<<-85.0,761.0>--<-85.0,697.0>> -> L<<-85.0,697.0>--<-91.0,585.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[14] NotoSansThaiLoopedUI-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- 276 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 The Noto Project Authors" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai Looped UI Medium [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped UI Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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

	- Glyph name: uni0E29	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E29	Contours detected: 4	Expected: 1 or 3 

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 576 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 321:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* braceleft (U+007B): X=150.0,Y=1.0 (should be at baseline 0?)

	* uni0E31 (U+0E31): X=-271.0,Y=712.0 (should be at cap-height 714?)

	* uni0E4A (U+0E4A): X=-340.0,Y=715.0 (should be at cap-height 714?)

	* uni0E54 (U+0E54): X=547.0,Y=1.0 (should be at baseline 0?)

	* uni0E54 (U+0E54): X=410.0,Y=-1.5 (should be at baseline 0?)

	* uni0E55 (U+0E55): X=547.0,Y=1.0 (should be at baseline 0?)

	* uni0E55 (U+0E55): X=410.0,Y=-1.5 (should be at baseline 0?)

	* uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?) 

	* uni25CC (U+25CC): X=326.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E01 (U+0E01) contains a short segment L<<46.0,322.0>--<46.0,335.0>>

	* uni0E03 (U+0E03) contains a short segment B<<197.0,433.0>-<197.0,431.0>-<196.0,429.0>>

	* uni0E05 (U+0E05) contains a short segment L<<290.0,371.0>--<281.0,371.0>>

	* uni0E06 (U+0E06) contains a short segment B<<206.0,433.0>-<206.0,431.0>-<206.0,429.0>>

	* uni0E06 (U+0E06) contains a short segment B<<243.0,102.0>-<244.0,96.0>-<244.0,89.0>>

	* uni0E08 (U+0E08) contains a short segment B<<139.0,170.0>-<132.0,169.0>-<125.0,169.0>>

	* uni0E08 (U+0E08) contains a short segment L<<243.0,79.0>--<247.0,79.0>>

	* uni0E09 (U+0E09) contains a short segment B<<335.0,89.0>-<335.0,91.0>-<335.0,94.0>>

	* uni0E0B (U+0E0B) contains a short segment B<<197.0,433.0>-<197.0,431.0>-<196.0,429.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<36.0,322.0>--<36.0,335.0>> 

	* 72 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<-182.0,581.0>--<-194.0,708.0>> -> L<<-194.0,708.0>--<-194.0,791.0>> 

	* uni0E48 (U+0E48): L<<-76.0,791.0>--<-76.0,708.0>> -> L<<-76.0,708.0>--<-88.0,581.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0E03 (U+0E03): B<<197.0,433.0>-<197.0,431.0>-<196.0,429.0>>/B<<196.0,429.0>-<217.0,466.0>-<223.0,508.0>> = 3.0127875041831653 

	* uni0E0B (U+0E0B): B<<197.0,433.0>-<197.0,431.0>-<196.0,429.0>>/B<<196.0,429.0>-<217.0,466.0>-<223.0,508.0>> = 3.0127875041831653 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiLoopedUI-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- 276 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 The Noto Project Authors" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai Looped UI [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped UI' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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

	- Glyph name: uni0E29	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3

	- Glyph name: uni0E29	Contours detected: 4	Expected: 1 or 3 

	- Glyph name: uni0E2E	Contours detected: 4	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
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

	* braceleft (U+007B): X=150.0,Y=1.0 (should be at baseline 0?)

	* uni0E0E (U+0E0E): X=257.0,Y=1.0 (should be at baseline 0?) 

	* 21 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E01 (U+0E01) contains a short segment L<<49.0,327.0>--<49.0,339.0>>

	* uni0E03 (U+0E03) contains a short segment B<<189.0,434.0>-<189.0,428.0>-<188.0,423.0>>

	* uni0E05 (U+0E05) contains a short segment L<<280.0,381.0>--<271.0,381.0>>

	* uni0E06 (U+0E06) contains a short segment B<<129.0,173.0>-<131.0,173.0>-<132.0,173.0>>

	* uni0E06 (U+0E06) contains a short segment B<<203.0,434.0>-<203.0,428.0>-<202.0,423.0>>

	* uni0E08 (U+0E08) contains a short segment L<<229.0,62.0>--<238.0,62.0>>

	* uni0E09 (U+0E09) contains a short segment B<<142.0,163.0>-<134.0,162.0>-<125.0,162.0>>

	* uni0E09 (U+0E09) contains a short segment B<<334.0,83.0>-<334.0,90.0>-<335.0,96.0>>

	* uni0E0B (U+0E0B) contains a short segment B<<189.0,434.0>-<189.0,428.0>-<188.0,423.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<41.0,327.0>--<41.0,339.0>> 

	* 87 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<-162.0,583.0>--<-171.0,703.0>> -> L<<-171.0,703.0>--<-171.0,781.0>> 

	* uni0E48 (U+0E48): L<<-80.0,781.0>--<-80.0,703.0>> -> L<<-80.0,703.0>--<-89.0,583.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiLoopedUI-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- 276 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2022 The Noto Project Authors" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai Looped UI Thin [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai Looped UI Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni0331.alt

	- uni035E.wide 

	- uni0E29.BRACKET.varAlt01
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 570 among a set of 4 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
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

	* 14 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E48 (U+0E48): L<<-115.0,587.0>--<-118.0,690.0>> -> L<<-118.0,690.0>--<-118.0,740.0>> 

	* uni0E48 (U+0E48): L<<-91.0,740.0>--<-91.0,690.0>> -> L<<-91.0,690.0>--<-94.0,587.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0E30 (U+0E30): B<<174.5,72.5>-<160.0,56.0>-<135.0,51.0>>/L<<135.0,51.0>--<137.0,51.0>> = 11.309932474020195

	* uni0E30 (U+0E30): B<<175.0,364.5>-<161.0,348.0>-<136.0,342.0>>/L<<136.0,342.0>--<137.0,342.0>> = 13.495733280795811 

	* uni0E31 (U+0E31): B<<-177.5,621.0>-<-191.0,605.0>-<-215.0,599.0>>/B<<-215.0,599.0>-<-148.0,599.0>-<-90.5,630.5>> = 14.036243467926457 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<100.0,174.0>--<98.0,714.0>> 

	* exclam (U+0021): L<<127.0,714.0>--<125.0,174.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 30 | 49 | 722 | 37 | 553 | 0 |
| 0% | 2% | 4% | 52% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
