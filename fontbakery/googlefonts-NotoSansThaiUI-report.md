## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[2] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansThaiUI/googlefonts/ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><br></div></details><details><summary><b>[12] NotoSansThaiUI-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI Black [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni02BC (U+02BC): X=237.0,Y=713.0 (should be at cap-height 714?)

	* uni02BC (U+02BC): X=65.0,Y=713.0 (should be at cap-height 714?)

	* uni0E0E (U+0E0E): X=126.0,Y=1.0 (should be at baseline 0?)

	* uni0E0F (U+0E0F): X=126.0,Y=1.0 (should be at baseline 0?)

	* uni0E1D (U+0E1D): X=449.0,Y=715.0 (should be at cap-height 714?)

	* uni0E1D (U+0E1D): X=624.0,Y=715.0 (should be at cap-height 714?)

	* uni0E23 (U+0E23): X=143.5,Y=-1.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=117.0,Y=-1.0 (should be at baseline 0?)

	* uni0E49 (U+0E49): X=-322.0,Y=715.0 (should be at cap-height 714?)

	* uni0E4A (U+0E4A): X=-225.0,Y=713.0 (should be at cap-height 714?) 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E03 (U+0E03) contains a short segment B<<131.5,366.5>-<123.0,365.0>-<115.0,365.0>>

	* uni0E03 (U+0E03) contains a short segment B<<184.0,472.0>-<190.0,472.0>-<198.0,474.0>>

	* uni0E04 (U+0E04) contains a short segment L<<244.0,228.0>--<248.0,227.0>>

	* uni0E05 (U+0E05) contains a short segment L<<244.0,228.0>--<248.0,227.0>>

	* uni0E05 (U+0E05) contains a short segment L<<375.0,149.0>--<358.0,149.0>>

	* uni0E06 (U+0E06) contains a short segment B<<155.0,369.0>-<146.0,368.0>-<137.5,366.5>>

	* uni0E06 (U+0E06) contains a short segment B<<137.5,366.5>-<129.0,365.0>-<121.0,365.0>>

	* uni0E06 (U+0E06) contains a short segment B<<191.0,472.0>-<197.0,472.0>-<205.0,474.0>>

	* uni0E06 (U+0E06) contains a short segment B<<205.0,474.0>-<213.0,476.0>-<220.0,483.0>>

	* uni0E07 (U+0E07) contains a short segment L<<293.0,152.0>--<296.0,152.0>> 

	* And 76 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[11] NotoSansThaiUI-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E23 (U+0E23): X=138.0,Y=-0.5 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=120.0,Y=-1.5 (should be at baseline 0?)

	* uni0E47 (U+0E47): X=-372.0,Y=715.0 (should be at cap-height 714?)

	* uni0E47 (U+0E47): X=-293.0,Y=716.0 (should be at cap-height 714?)

	* uni0E47 (U+0E47): X=-273.0,Y=716.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-203.0,Y=713.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-21.0,Y=716.0 (should be at cap-height 714?) 

	* And uni0E4E (U+0E4E): X=-85.5,Y=713.5 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<218.0,227.0>--<221.0,226.0>>

	* uni0E05 (U+0E05) contains a short segment L<<217.0,227.0>--<220.0,226.0>>

	* uni0E06 (U+0E06) contains a short segment B<<179.0,469.0>-<187.0,469.0>-<197.0,471.5>>

	* uni0E07 (U+0E07) contains a short segment L<<277.0,121.0>--<283.0,121.0>>

	* uni0E08 (U+0E08) contains a short segment L<<250.0,114.0>--<257.0,114.0>>

	* uni0E09 (U+0E09) contains a short segment L<<423.0,77.0>--<415.0,77.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<319.0,408.0>--<325.0,408.0>>

	* uni0E0B (U+0E0B) contains a short segment B<<175.0,469.0>-<183.0,469.0>-<193.0,471.5>>

	* uni0E0B (U+0E0B) contains a short segment L<<330.0,408.0>--<334.0,408.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<55.0,333.0>--<55.0,357.0>> 

	* And 51 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-Condensed.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI Condensed [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI Condensed' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* tildecomb (U+0303): X=-291.0,Y=715.0 (should be at cap-height 714?)

	* uni0E0D (U+0E0D): X=462.0,Y=1.0 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=138.0,Y=1.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=110.5,Y=1.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=100.5,Y=-2.0 (should be at baseline 0?)

	* uni0E36 (U+0E36): X=-115.5,Y=715.0 (should be at cap-height 714?)

	* uni0E36 (U+0E36): X=-165.5,Y=715.5 (should be at cap-height 714?)

	* uni0E42 (U+0E42): X=18.0,Y=715.0 (should be at cap-height 714?)

	* uni0E42 (U+0E42): X=293.0,Y=715.0 (should be at cap-height 714?)

	* uni0E42 (U+0E42): X=139.0,Y=715.0 (should be at cap-height 714?) 

	* And 14 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<153.0,226.0>--<156.0,225.0>>

	* uni0E05 (U+0E05) contains a short segment L<<152.0,226.0>--<154.0,225.0>>

	* uni0E07 (U+0E07) contains a short segment L<<204.0,74.0>--<212.0,74.0>>

	* uni0E08 (U+0E08) contains a short segment L<<196.0,69.0>--<205.0,69.0>>

	* uni0E09 (U+0E09) contains a short segment L<<357.0,76.0>--<353.0,76.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<251.0,408.0>--<255.0,408.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<257.0,408.0>--<260.0,408.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<587.0,70.0>--<583.0,70.0>>

	* uni0E0D (U+0E0D) contains a short segment B<<161.0,69.0>-<169.0,60.0>-<185.0,60.0>>

	* uni0E0E (U+0E0E) contains a short segment L<<87.0,-190.0>--<87.0,-174.0>> 

	* And 48 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-CondensedBlack.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI Condensed Black [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI Condensed Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E0E (U+0E0E): X=115.0,Y=-1.0 (should be at baseline 0?)

	* uni0E0F (U+0E0F): X=115.0,Y=-1.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=128.0,Y=-1.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=104.0,Y=-1.5 (should be at baseline 0?)

	* uni0E49 (U+0E49): X=-250.0,Y=713.0 (should be at cap-height 714?)

	* uni0E4A (U+0E4A): X=-408.0,Y=713.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-180.0,Y=715.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-7.0,Y=715.0 (should be at cap-height 714?) 

	* And uni0E4E (U+0E4E): X=-60.0,Y=713.0 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<220.0,236.0>--<224.0,235.0>>

	* uni0E04 (U+0E04) contains a short segment L<<319.0,155.0>--<305.0,155.0>>

	* uni0E05 (U+0E05) contains a short segment L<<221.0,236.0>--<224.0,235.0>>

	* uni0E05 (U+0E05) contains a short segment L<<330.0,155.0>--<316.0,155.0>>

	* uni0E07 (U+0E07) contains a short segment L<<254.0,135.0>--<255.0,135.0>>

	* uni0E07 (U+0E07) contains a short segment B<<255.0,135.0>-<261.0,135.0>-<267.0,140.5>>

	* uni0E07 (U+0E07) contains a short segment B<<250.0,392.0>-<246.0,392.0>-<241.5,392.0>>

	* uni0E07 (U+0E07) contains a short segment B<<241.5,392.0>-<237.0,392.0>-<233.0,390.0>>

	* uni0E08 (U+0E08) contains a short segment L<<227.0,127.0>--<228.0,127.0>>

	* uni0E09 (U+0E09) contains a short segment L<<346.0,76.0>--<336.0,76.0>> 

	* And 79 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-CondensedBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI Condensed [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI Condensed' / SUBFAMILY_NAME = 'Bold'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E0E (U+0E0E): X=57.5,Y=1.5 (should be at baseline 0?)

	* uni0E0F (U+0E0F): X=57.5,Y=1.5 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=147.5,Y=-2.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=123.5,Y=-0.5 (should be at baseline 0?)

	* uni0E47 (U+0E47): X=-179.0,Y=712.0 (should be at cap-height 714?)

	* uni0E47 (U+0E47): X=-88.0,Y=712.0 (should be at cap-height 714?)

	* uni0E49 (U+0E49): X=-262.0,Y=713.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-179.0,Y=712.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-19.0,Y=715.0 (should be at cap-height 714?) 

	* And uni0E4E (U+0E4E): X=-74.0,Y=712.5 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E03 (U+0E03) contains a short segment B<<155.0,468.0>-<162.0,468.0>-<170.0,471.0>>

	* uni0E04 (U+0E04) contains a short segment L<<196.0,228.0>--<199.0,227.0>>

	* uni0E05 (U+0E05) contains a short segment L<<196.0,228.0>--<198.0,227.0>>

	* uni0E06 (U+0E06) contains a short segment B<<159.0,468.0>-<167.0,468.0>-<175.0,471.0>>

	* uni0E07 (U+0E07) contains a short segment L<<243.0,115.0>--<247.0,115.0>>

	* uni0E08 (U+0E08) contains a short segment L<<221.0,108.0>--<226.0,108.0>>

	* uni0E09 (U+0E09) contains a short segment L<<364.0,76.0>--<357.0,76.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<280.0,407.0>--<285.0,407.0>>

	* uni0E0B (U+0E0B) contains a short segment B<<155.0,468.0>-<163.0,468.0>-<171.0,471.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<289.0,407.0>--<293.0,407.0>> 

	* And 59 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-CondensedExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI Condensed ExtraBold [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI Condensed ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* tildecomb (U+0303): X=-229.0,Y=713.0 (should be at cap-height 714?)

	* uni0E0E (U+0E0E): X=109.0,Y=-2.0 (should be at baseline 0?)

	* uni0E0F (U+0E0F): X=109.0,Y=-2.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=125.5,Y=-1.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=105.0,Y=-2.0 (should be at baseline 0?)

	* uni0E34 (U+0E34): X=-374.0,Y=712.0 (should be at cap-height 714?)

	* uni0E34 (U+0E34): X=-65.0,Y=712.0 (should be at cap-height 714?)

	* uni0E35 (U+0E35): X=-374.0,Y=712.0 (should be at cap-height 714?)

	* uni0E35 (U+0E35): X=-192.0,Y=712.0 (should be at cap-height 714?)

	* uni0E36 (U+0E36): X=-374.0,Y=712.0 (should be at cap-height 714?) 

	* And 14 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<207.0,232.0>--<211.0,231.0>>

	* uni0E05 (U+0E05) contains a short segment L<<207.0,232.0>--<210.0,231.0>>

	* uni0E05 (U+0E05) contains a short segment L<<327.0,167.0>--<310.0,167.0>>

	* uni0E07 (U+0E07) contains a short segment L<<248.0,124.0>--<251.0,124.0>>

	* uni0E07 (U+0E07) contains a short segment B<<248.0,402.0>-<242.0,402.0>-<236.5,401.5>>

	* uni0E07 (U+0E07) contains a short segment B<<236.5,401.5>-<231.0,401.0>-<227.0,399.0>>

	* uni0E08 (U+0E08) contains a short segment L<<224.0,117.0>--<227.0,117.0>>

	* uni0E09 (U+0E09) contains a short segment L<<356.0,76.0>--<347.0,76.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<283.0,408.0>--<288.0,408.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<293.0,408.0>--<297.0,408.0>> 

	* And 72 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-CondensedExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI Condensed ExtraLight [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI Condensed ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* tildecomb (U+0303): X=-120.0,Y=713.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-321.0,Y=713.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-148.0,Y=713.0 (should be at cap-height 714?)

	* uni0E12 (U+0E12): X=259.0,Y=1.0 (should be at baseline 0?)

	* uni0E15 (U+0E15): X=271.0,Y=1.0 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=132.5,Y=-0.5 (should be at baseline 0?)

	* uni0E20 (U+0E20): X=23.0,Y=2.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=106.0,Y=1.5 (should be at baseline 0?)

	* uni0E25 (U+0E25): X=238.0,Y=1.0 (should be at baseline 0?)

	* uni0E26 (U+0E26): X=23.0,Y=2.0 (should be at baseline 0?) 

	* And 22 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<110.0,216.0>--<112.0,215.0>>

	* uni0E05 (U+0E05) contains a short segment L<<109.0,216.0>--<112.0,215.0>>

	* uni0E07 (U+0E07) contains a short segment L<<177.0,35.0>--<189.0,35.0>>

	* uni0E08 (U+0E08) contains a short segment L<<166.0,34.0>--<177.0,34.0>>

	* uni0E09 (U+0E09) contains a short segment L<<370.0,85.0>--<366.0,85.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<243.0,400.0>--<253.0,400.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<247.0,400.0>--<258.0,400.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<60.0,359.0>--<60.0,380.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<159.0,26.0>-<170.0,26.0>-<180.5,28.5>>

	* uni0E0C (U+0E0C) contains a short segment B<<180.5,28.5>-<191.0,31.0>-<199.0,35.0>> 

	* And 49 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-CondensedLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI Condensed Light [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI Condensed Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E0D (U+0E0D): X=462.0,Y=1.0 (should be at baseline 0?)

	* uni0E12 (U+0E12): X=269.0,Y=2.0 (should be at baseline 0?)

	* uni0E14 (U+0E14): X=269.0,Y=1.0 (should be at baseline 0?)

	* uni0E15 (U+0E15): X=278.0,Y=2.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=107.5,Y=1.5 (should be at baseline 0?)

	* uni0E25 (U+0E25): X=247.0,Y=2.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=97.5,Y=-1.5 (should be at baseline 0?)

	* uni0E2A (U+0E2A): X=247.0,Y=2.0 (should be at baseline 0?)

	* uni0E31 (U+0E31): X=-205.0,Y=716.0 (should be at cap-height 714?)

	* uni0E49 (U+0E49): X=-209.0,Y=715.0 (should be at cap-height 714?) 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<126.0,220.0>--<128.0,219.0>>

	* uni0E05 (U+0E05) contains a short segment L<<125.0,220.0>--<127.0,219.0>>

	* uni0E07 (U+0E07) contains a short segment L<<187.0,49.0>--<198.0,49.0>>

	* uni0E08 (U+0E08) contains a short segment L<<178.0,47.0>--<188.0,47.0>>

	* uni0E09 (U+0E09) contains a short segment L<<365.0,81.0>--<361.0,81.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<246.0,403.0>--<254.0,403.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<251.0,403.0>--<259.0,403.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<59.0,354.0>--<59.0,379.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<169.0,38.0>-<178.0,38.0>-<188.0,40.5>>

	* uni0E0C (U+0E0C) contains a short segment B<<188.0,40.5>-<198.0,43.0>-<205.0,47.0>> 

	* And 49 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-CondensedMedium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI Condensed Medium [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI Condensed Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E23 (U+0E23): X=114.5,Y=0.5 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=102.5,Y=-2.0 (should be at baseline 0?)

	* uni0E33 (U+0E33): X=-147.0,Y=716.0 (should be at cap-height 714?)

	* uni0E49 (U+0E49): X=-242.0,Y=712.0 (should be at cap-height 714?)

	* uni0E4D (U+0E4D): X=-147.0,Y=716.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-43.5,Y=715.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-57.0,Y=716.0 (should be at cap-height 714?)

	* uni0E51 (U+0E51): X=153.0,Y=1.0 (should be at baseline 0?)

	* uni0E53 (U+0E53): X=240.0,Y=2.0 (should be at baseline 0?)

	* uni0E57 (U+0E57): X=240.0,Y=2.0 (should be at baseline 0?) 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<166.0,227.0>--<168.0,226.0>>

	* uni0E05 (U+0E05) contains a short segment L<<165.0,227.0>--<167.0,226.0>>

	* uni0E07 (U+0E07) contains a short segment L<<216.0,86.0>--<223.0,86.0>>

	* uni0E08 (U+0E08) contains a short segment L<<203.0,80.0>--<211.0,80.0>>

	* uni0E09 (U+0E09) contains a short segment L<<359.0,76.0>--<354.0,76.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<259.0,408.0>--<264.0,408.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<266.0,408.0>--<270.0,408.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<595.0,70.0>--<590.0,70.0>>

	* uni0E0D (U+0E0D) contains a short segment B<<171.0,77.0>-<179.0,68.0>-<196.0,68.0>>

	* uni0E0E (U+0E0E) contains a short segment L<<85.0,-193.0>--<85.0,-177.0>> 

	* And 51 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-CondensedSemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI Condensed SemiBold [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI Condensed SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E0E (U+0E0E): X=55.5,Y=-1.0 (should be at baseline 0?)

	* uni0E0F (U+0E0F): X=55.5,Y=-1.0 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=144.0,Y=-1.0 (should be at baseline 0?)

	* uni0E49 (U+0E49): X=-251.0,Y=713.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-24.0,Y=713.0 (should be at cap-height 714?)

	* uni0E53 (U+0E53): X=249.0,Y=2.0 (should be at baseline 0?)

	* uni0E57 (U+0E57): X=249.0,Y=2.0 (should be at baseline 0?) 

	* And uni0E59 (U+0E59): X=249.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<180.0,227.0>--<183.0,226.0>>

	* uni0E05 (U+0E05) contains a short segment L<<179.0,227.0>--<182.0,226.0>>

	* uni0E07 (U+0E07) contains a short segment L<<228.0,99.0>--<234.0,99.0>>

	* uni0E08 (U+0E08) contains a short segment L<<211.0,93.0>--<218.0,93.0>>

	* uni0E09 (U+0E09) contains a short segment L<<361.0,76.0>--<355.0,76.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<269.0,408.0>--<274.0,408.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<277.0,408.0>--<280.0,408.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<604.0,71.0>--<598.0,71.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<52.0,339.0>--<52.0,366.0>>

	* uni0E0E (U+0E0E) contains a short segment L<<82.0,-196.0>--<82.0,-180.0>> 

	* And 46 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSansThaiUI-CondensedThin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI Condensed Thin [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI Condensed Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E0E (U+0E0E): X=23.0,Y=2.0 (should be at baseline 0?)

	* uni0E0F (U+0E0F): X=23.0,Y=2.0 (should be at baseline 0?)

	* uni0E12 (U+0E12): X=252.0,Y=1.0 (should be at baseline 0?)

	* uni0E14 (U+0E14): X=257.0,Y=-1.0 (should be at baseline 0?)

	* uni0E15 (U+0E15): X=266.0,Y=1.0 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=131.5,Y=-1.0 (should be at baseline 0?)

	* uni0E20 (U+0E20): X=23.0,Y=2.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=105.0,Y=2.0 (should be at baseline 0?)

	* uni0E26 (U+0E26): X=23.0,Y=2.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=95.0,Y=-1.5 (should be at baseline 0?) 

	* And 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<98.0,213.0>--<101.0,212.0>>

	* uni0E05 (U+0E05) contains a short segment L<<98.0,213.0>--<101.0,212.0>>

	* uni0E06 (U+0E06) contains a short segment L<<165.0,517.0>--<183.0,517.0>>

	* uni0E07 (U+0E07) contains a short segment L<<170.0,25.0>--<183.0,25.0>>

	* uni0E08 (U+0E08) contains a short segment L<<159.0,25.0>--<170.0,25.0>>

	* uni0E09 (U+0E09) contains a short segment L<<373.0,87.0>--<370.0,87.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<241.0,398.0>--<253.0,398.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<245.0,398.0>--<257.0,398.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<60.0,363.0>--<60.0,381.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<367.0,0.0>--<344.0,0.0>> 

	* And 75 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni0E2B (U+0E2B): L<<366.0,0.0>--<365.0,174.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NotoSansThaiUI-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI ExtraBold [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E0E (U+0E0E): X=120.0,Y=-1.0 (should be at baseline 0?)

	* uni0E0F (U+0E0F): X=120.0,Y=-1.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=140.5,Y=-1.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=118.5,Y=-1.5 (should be at baseline 0?)

	* uni0E31 (U+0E31): X=-209.5,Y=716.0 (should be at cap-height 714?)

	* uni0E33 (U+0E33): X=-150.0,Y=715.0 (should be at cap-height 714?)

	* uni0E33 (U+0E33): X=-215.5,Y=715.0 (should be at cap-height 714?)

	* uni0E47 (U+0E47): X=-371.0,Y=716.0 (should be at cap-height 714?)

	* uni0E4D (U+0E4D): X=-150.0,Y=715.0 (should be at cap-height 714?)

	* uni0E4D (U+0E4D): X=-215.5,Y=715.0 (should be at cap-height 714?) 

	* And 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E03 (U+0E03) contains a short segment B<<179.0,470.0>-<186.0,470.0>-<195.0,472.5>>

	* uni0E04 (U+0E04) contains a short segment L<<230.0,227.0>--<233.0,226.0>>

	* uni0E05 (U+0E05) contains a short segment L<<229.0,227.0>--<233.0,226.0>>

	* uni0E06 (U+0E06) contains a short segment B<<185.0,470.0>-<192.0,470.0>-<201.0,472.5>>

	* uni0E07 (U+0E07) contains a short segment L<<284.0,135.0>--<289.0,135.0>>

	* uni0E08 (U+0E08) contains a short segment L<<253.0,127.0>--<258.0,127.0>>

	* uni0E09 (U+0E09) contains a short segment L<<413.0,77.0>--<403.0,77.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<322.0,408.0>--<329.0,408.0>>

	* uni0E0B (U+0E0B) contains a short segment B<<180.0,470.0>-<187.0,470.0>-<196.0,472.5>>

	* uni0E0B (U+0E0B) contains a short segment L<<335.0,408.0>--<339.0,408.0>> 

	* And 59 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-ExtraCondensed.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI ExtraCondensed [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI ExtraCondensed' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* tildecomb (U+0303): X=-282.5,Y=712.5 (should be at cap-height 714?)

	* uni0E0D (U+0E0D): X=413.0,Y=1.0 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=127.5,Y=1.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=104.5,Y=1.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=94.5,Y=-2.0 (should be at baseline 0?)

	* uni0E36 (U+0E36): X=-105.5,Y=715.0 (should be at cap-height 714?)

	* uni0E36 (U+0E36): X=-150.0,Y=715.5 (should be at cap-height 714?)

	* uni0E49 (U+0E49): X=-214.0,Y=712.0 (should be at cap-height 714?)

	* uni0E4A (U+0E4A): X=-85.0,Y=716.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-43.5,Y=713.0 (should be at cap-height 714?) 

	* And 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<146.0,226.0>--<148.0,225.0>>

	* uni0E05 (U+0E05) contains a short segment L<<145.0,226.0>--<147.0,225.0>>

	* uni0E07 (U+0E07) contains a short segment L<<190.0,73.0>--<196.0,73.0>>

	* uni0E08 (U+0E08) contains a short segment L<<181.0,68.0>--<188.0,68.0>>

	* uni0E09 (U+0E09) contains a short segment L<<319.0,76.0>--<315.0,76.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<229.0,408.0>--<233.0,408.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<235.0,408.0>--<238.0,408.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<524.0,70.0>--<520.0,70.0>>

	* uni0E0D (U+0E0D) contains a short segment B<<151.0,68.5>-<158.0,59.0>-<173.0,59.0>>

	* uni0E0D (U+0E0D) contains a short segment B<<173.0,59.0>-<187.0,59.0>-<199.0,66.0>> 

	* And 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-ExtraCondensedBlack.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI ExtraCondensed Black [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI ExtraCondensed Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E0E (U+0E0E): X=110.0,Y=-2.0 (should be at baseline 0?)

	* uni0E0F (U+0E0F): X=110.0,Y=-2.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=121.5,Y=-1.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=99.0,Y=-1.5 (should be at baseline 0?)

	* uni0E47 (U+0E47): X=-292.0,Y=716.0 (should be at cap-height 714?)

	* uni0E49 (U+0E49): X=-219.0,Y=712.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-7.0,Y=715.0 (should be at cap-height 714?) 

	* And uni0E4E (U+0E4E): X=-55.5,Y=713.0 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<210.0,239.0>--<214.0,238.0>>

	* uni0E04 (U+0E04) contains a short segment L<<300.0,157.0>--<288.0,157.0>>

	* uni0E05 (U+0E05) contains a short segment L<<211.0,239.0>--<214.0,238.0>>

	* uni0E05 (U+0E05) contains a short segment L<<311.0,157.0>--<298.0,157.0>>

	* uni0E07 (U+0E07) contains a short segment L<<237.0,128.0>--<238.0,128.0>>

	* uni0E07 (U+0E07) contains a short segment B<<238.0,128.0>-<243.0,128.0>-<248.0,133.5>>

	* uni0E07 (U+0E07) contains a short segment B<<233.0,399.0>-<230.0,399.0>-<225.5,399.0>>

	* uni0E07 (U+0E07) contains a short segment B<<225.5,399.0>-<221.0,399.0>-<217.0,397.0>>

	* uni0E08 (U+0E08) contains a short segment L<<214.0,120.0>--<215.0,120.0>>

	* uni0E09 (U+0E09) contains a short segment L<<322.0,76.0>--<313.0,76.0>> 

	* And 79 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-ExtraCondensedBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI ExtraCondensed [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI ExtraCondensed' / SUBFAMILY_NAME = 'Bold'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* tildecomb (U+0303): X=-262.0,Y=715.5 (should be at cap-height 714?)

	* uni0E0E (U+0E0E): X=55.5,Y=1.5 (should be at baseline 0?)

	* uni0E0F (U+0E0F): X=55.5,Y=1.5 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=139.5,Y=-2.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=117.5,Y=-0.5 (should be at baseline 0?)

	* uni0E49 (U+0E49): X=-243.0,Y=713.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-18.0,Y=715.0 (should be at cap-height 714?) 

	* And uni0E4E (U+0E4E): X=-69.0,Y=712.5 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<187.0,229.0>--<190.0,228.0>>

	* uni0E05 (U+0E05) contains a short segment L<<187.0,229.0>--<189.0,228.0>>

	* uni0E05 (U+0E05) contains a short segment L<<304.0,180.0>--<286.0,180.0>>

	* uni0E07 (U+0E07) contains a short segment L<<228.0,112.0>--<232.0,112.0>>

	* uni0E08 (U+0E08) contains a short segment L<<208.0,105.0>--<213.0,105.0>>

	* uni0E09 (U+0E09) contains a short segment L<<339.0,76.0>--<332.0,76.0>>

	* uni0E0A (U+0E0A) contains a short segment B<<93.0,425.0>-<86.0,425.0>-<77.5,421.5>>

	* uni0E0A (U+0E0A) contains a short segment L<<263.0,407.0>--<268.0,407.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<272.0,407.0>--<275.0,407.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<46.0,336.0>--<46.0,360.0>> 

	* And 57 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-ExtraCondensedExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI ExtraCondensed ExtraBold [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI ExtraCondensed ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* tildecomb (U+0303): X=-225.0,Y=713.0 (should be at cap-height 714?)

	* uni0E23 (U+0E23): X=119.0,Y=-0.5 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=99.5,Y=-1.5 (should be at baseline 0?)

	* uni0E47 (U+0E47): X=-393.0,Y=712.0 (should be at cap-height 714?)

	* uni0E49 (U+0E49): X=-232.0,Y=713.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-168.0,Y=712.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-13.0,Y=715.0 (should be at cap-height 714?) 

	* And uni0E4E (U+0E4E): X=-63.0,Y=712.5 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<198.0,234.0>--<201.0,233.0>>

	* uni0E04 (U+0E04) contains a short segment L<<298.0,169.0>--<284.0,169.0>>

	* uni0E05 (U+0E05) contains a short segment L<<198.0,234.0>--<201.0,233.0>>

	* uni0E05 (U+0E05) contains a short segment L<<307.0,169.0>--<292.0,169.0>>

	* uni0E07 (U+0E07) contains a short segment L<<232.0,119.0>--<235.0,119.0>>

	* uni0E07 (U+0E07) contains a short segment B<<231.0,407.0>-<227.0,407.0>-<222.0,406.5>>

	* uni0E07 (U+0E07) contains a short segment B<<222.0,406.5>-<217.0,406.0>-<212.0,404.0>>

	* uni0E08 (U+0E08) contains a short segment L<<211.0,112.0>--<214.0,112.0>>

	* uni0E09 (U+0E09) contains a short segment L<<331.0,76.0>--<323.0,76.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<266.0,407.0>--<271.0,407.0>> 

	* And 69 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-ExtraCondensedExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI ExtraCondensed ExtraLight [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI ExtraCondensed ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E12 (U+0E12): X=232.0,Y=1.0 (should be at baseline 0?)

	* uni0E15 (U+0E15): X=242.0,Y=1.0 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=118.5,Y=-0.5 (should be at baseline 0?)

	* uni0E20 (U+0E20): X=21.0,Y=2.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=95.0,Y=1.5 (should be at baseline 0?)

	* uni0E25 (U+0E25): X=213.0,Y=1.0 (should be at baseline 0?)

	* uni0E26 (U+0E26): X=21.0,Y=2.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=86.5,Y=-1.5 (should be at baseline 0?)

	* uni0E2A (U+0E2A): X=214.0,Y=1.0 (should be at baseline 0?)

	* uni0E2F (U+0E2F): X=250.0,Y=-1.0 (should be at baseline 0?) 

	* And 19 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<101.0,218.0>--<103.0,217.0>>

	* uni0E05 (U+0E05) contains a short segment L<<101.0,218.0>--<103.0,217.0>>

	* uni0E07 (U+0E07) contains a short segment L<<162.0,35.0>--<172.0,35.0>>

	* uni0E08 (U+0E08) contains a short segment L<<151.0,34.0>--<160.0,34.0>>

	* uni0E09 (U+0E09) contains a short segment L<<327.0,82.0>--<324.0,82.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<216.0,400.0>--<225.0,400.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<221.0,400.0>--<229.0,400.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<53.0,360.0>--<53.0,380.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<144.0,26.0>-<153.0,26.0>-<162.0,28.5>>

	* uni0E0C (U+0E0C) contains a short segment B<<162.0,28.5>-<171.0,31.0>-<178.0,35.0>> 

	* And 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-ExtraCondensedLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI ExtraCondensed Light [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI ExtraCondensed Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* tildecomb (U+0303): X=-317.0,Y=716.0 (should be at cap-height 714?)

	* uni0E0D (U+0E0D): X=411.0,Y=1.0 (should be at baseline 0?)

	* uni0E12 (U+0E12): X=242.0,Y=2.0 (should be at baseline 0?)

	* uni0E14 (U+0E14): X=242.0,Y=1.0 (should be at baseline 0?)

	* uni0E15 (U+0E15): X=249.0,Y=2.0 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=122.0,Y=0.5 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=98.5,Y=1.5 (should be at baseline 0?)

	* uni0E25 (U+0E25): X=222.0,Y=2.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=89.5,Y=-1.5 (should be at baseline 0?)

	* uni0E2A (U+0E2A): X=222.0,Y=2.0 (should be at baseline 0?) 

	* And 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<118.0,221.0>--<120.0,220.0>>

	* uni0E05 (U+0E05) contains a short segment L<<118.0,221.0>--<120.0,220.0>>

	* uni0E06 (U+0E06) contains a short segment B<<115.0,454.0>-<122.0,454.0>-<131.0,458.5>>

	* uni0E07 (U+0E07) contains a short segment L<<173.0,49.0>--<181.0,49.0>>

	* uni0E07 (U+0E07) contains a short segment B<<174.5,473.0>-<166.0,471.0>-<161.0,468.0>>

	* uni0E08 (U+0E08) contains a short segment L<<162.0,47.0>--<171.0,47.0>>

	* uni0E09 (U+0E09) contains a short segment L<<324.0,80.0>--<321.0,80.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<221.0,403.0>--<228.0,403.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<226.0,403.0>--<233.0,403.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<53.0,355.0>--<53.0,379.0>> 

	* And 46 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-ExtraCondensedMedium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI ExtraCondensed Medium [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI ExtraCondensed Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* tildecomb (U+0303): X=-383.0,Y=715.5 (should be at cap-height 714?)

	* uni0E0D (U+0E0D): X=424.0,Y=2.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=108.0,Y=0.5 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=96.0,Y=-2.0 (should be at baseline 0?)

	* uni0E33 (U+0E33): X=-139.0,Y=716.0 (should be at cap-height 714?)

	* uni0E49 (U+0E49): X=-223.0,Y=712.0 (should be at cap-height 714?)

	* uni0E4D (U+0E4D): X=-139.0,Y=716.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-134.0,Y=713.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-40.0,Y=715.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-52.0,Y=716.0 (should be at cap-height 714?) 

	* And 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<158.0,227.0>--<160.0,226.0>>

	* uni0E05 (U+0E05) contains a short segment L<<157.0,227.0>--<159.0,226.0>>

	* uni0E07 (U+0E07) contains a short segment L<<201.0,85.0>--<207.0,85.0>>

	* uni0E08 (U+0E08) contains a short segment L<<189.0,79.0>--<195.0,79.0>>

	* uni0E09 (U+0E09) contains a short segment L<<325.0,76.0>--<320.0,76.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<239.0,408.0>--<243.0,408.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<246.0,408.0>--<249.0,408.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<538.0,70.0>--<533.0,70.0>>

	* uni0E0D (U+0E0D) contains a short segment B<<161.5,76.0>-<169.0,67.0>-<184.0,67.0>>

	* uni0E0E (U+0E0E) contains a short segment L<<79.0,-193.0>--<79.0,-177.0>> 

	* And 50 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-ExtraCondensedSemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI ExtraCondensed SemiBold [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI ExtraCondensed SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E0E (U+0E0E): X=54.0,Y=-1.5 (should be at baseline 0?)

	* uni0E0F (U+0E0F): X=54.0,Y=-1.5 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=134.5,Y=-1.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=98.0,Y=-2.0 (should be at baseline 0?)

	* uni0E49 (U+0E49): X=-232.0,Y=713.0 (should be at cap-height 714?)

	* uni0E4C (U+0E4C): X=-203.0,Y=715.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-23.0,Y=713.0 (should be at cap-height 714?)

	* uni0E53 (U+0E53): X=232.0,Y=2.0 (should be at baseline 0?)

	* uni0E57 (U+0E57): X=232.0,Y=2.0 (should be at baseline 0?) 

	* And uni0E59 (U+0E59): X=232.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<172.0,228.0>--<174.0,227.0>>

	* uni0E05 (U+0E05) contains a short segment L<<171.0,228.0>--<173.0,227.0>>

	* uni0E07 (U+0E07) contains a short segment L<<214.0,97.0>--<218.0,97.0>>

	* uni0E08 (U+0E08) contains a short segment L<<198.0,91.0>--<204.0,91.0>>

	* uni0E09 (U+0E09) contains a short segment L<<331.0,76.0>--<326.0,76.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<250.0,407.0>--<255.0,407.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<258.0,407.0>--<261.0,407.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<553.0,71.0>--<548.0,71.0>>

	* uni0E0D (U+0E0D) contains a short segment B<<197.0,76.0>-<210.0,76.0>-<223.0,82.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<49.0,340.0>--<49.0,366.0>> 

	* And 52 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-ExtraCondensedThin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI ExtraCondensed Thin [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI ExtraCondensed Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E0E (U+0E0E): X=20.0,Y=2.0 (should be at baseline 0?)

	* uni0E0F (U+0E0F): X=20.0,Y=2.0 (should be at baseline 0?)

	* uni0E12 (U+0E12): X=225.0,Y=1.0 (should be at baseline 0?)

	* uni0E14 (U+0E14): X=229.0,Y=-1.0 (should be at baseline 0?)

	* uni0E15 (U+0E15): X=237.0,Y=1.0 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=116.5,Y=-1.0 (should be at baseline 0?)

	* uni0E20 (U+0E20): X=20.0,Y=2.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=93.0,Y=2.0 (should be at baseline 0?)

	* uni0E26 (U+0E26): X=20.0,Y=2.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=84.5,Y=-1.5 (should be at baseline 0?) 

	* And 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<90.0,216.0>--<92.0,215.0>>

	* uni0E05 (U+0E05) contains a short segment L<<90.0,216.0>--<92.0,215.0>>

	* uni0E06 (U+0E06) contains a short segment L<<147.0,517.0>--<164.0,517.0>>

	* uni0E07 (U+0E07) contains a short segment L<<155.0,25.0>--<166.0,25.0>>

	* uni0E08 (U+0E08) contains a short segment L<<143.0,25.0>--<153.0,25.0>>

	* uni0E09 (U+0E09) contains a short segment L<<329.0,84.0>--<326.0,84.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<213.0,398.0>--<223.0,398.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<217.0,398.0>--<227.0,398.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<53.0,363.0>--<53.0,381.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<326.0,0.0>--<303.0,0.0>> 

	* And 79 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI ExtraLight [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E12 (U+0E12): X=323.0,Y=1.0 (should be at baseline 0?)

	* uni0E15 (U+0E15): X=339.0,Y=1.0 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=165.5,Y=-0.5 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=131.5,Y=1.5 (should be at baseline 0?)

	* uni0E25 (U+0E25): X=297.0,Y=1.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=119.0,Y=-1.5 (should be at baseline 0?)

	* uni0E2A (U+0E2A): X=297.0,Y=1.0 (should be at baseline 0?)

	* uni0E2F (U+0E2F): X=359.0,Y=-1.0 (should be at baseline 0?)

	* uni0E2F (U+0E2F): X=398.0,Y=-1.0 (should be at baseline 0?)

	* uni0E36 (U+0E36): X=-165.0,Y=713.0 (should be at cap-height 714?) 

	* And 17 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<129.0,211.0>--<132.0,210.0>>

	* uni0E05 (U+0E05) contains a short segment L<<128.0,211.0>--<131.0,210.0>>

	* uni0E07 (U+0E07) contains a short segment L<<213.0,35.0>--<228.0,35.0>>

	* uni0E08 (U+0E08) contains a short segment L<<203.0,34.0>--<218.0,34.0>>

	* uni0E09 (U+0E09) contains a short segment L<<469.0,90.0>--<465.0,90.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<304.0,400.0>--<319.0,400.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<309.0,400.0>--<324.0,400.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<75.0,359.0>--<75.0,380.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<223.0,29.0>-<237.0,32.0>-<248.0,35.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<761.0,89.0>--<757.0,89.0>> 

	* And 45 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E4A (U+0E4A): L<<-155.0,636.0>--<-154.0,636.0>> -> L<<-154.0,636.0>--<-63.0,636.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[12] NotoSansThaiUI-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI Light [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* tildecomb (U+0303): X=-312.5,Y=715.0 (should be at cap-height 714?)

	* uni0E0D (U+0E0D): X=583.0,Y=1.0 (should be at baseline 0?)

	* uni0E12 (U+0E12): X=332.0,Y=2.0 (should be at baseline 0?)

	* uni0E14 (U+0E14): X=334.0,Y=1.0 (should be at baseline 0?)

	* uni0E15 (U+0E15): X=344.0,Y=2.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=129.5,Y=1.5 (should be at baseline 0?)

	* uni0E25 (U+0E25): X=305.0,Y=2.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=118.0,Y=-1.5 (should be at baseline 0?)

	* uni0E2A (U+0E2A): X=306.0,Y=2.0 (should be at baseline 0?)

	* uni0E31 (U+0E31): X=-259.0,Y=716.0 (should be at cap-height 714?) 

	* And 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<144.0,217.0>--<147.0,216.0>>

	* uni0E05 (U+0E05) contains a short segment L<<143.0,217.0>--<146.0,216.0>>

	* uni0E07 (U+0E07) contains a short segment L<<222.0,51.0>--<236.0,51.0>>

	* uni0E08 (U+0E08) contains a short segment L<<214.0,48.0>--<228.0,48.0>>

	* uni0E09 (U+0E09) contains a short segment L<<460.0,85.0>--<456.0,85.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<303.0,403.0>--<314.0,403.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<309.0,403.0>--<320.0,403.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<72.0,354.0>--<72.0,378.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<203.0,40.0>-<215.0,40.0>-<227.5,42.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<227.5,42.0>-<240.0,44.0>-<250.0,48.0>> 

	* And 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansThaiUI-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI Medium [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E18 (U+0E18): X=164.0,Y=-0.5 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=129.0,Y=0.5 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=117.0,Y=-2.0 (should be at baseline 0?)

	* uni0E31 (U+0E31): X=-240.0,Y=712.0 (should be at cap-height 714?)

	* uni0E33 (U+0E33): X=-166.0,Y=716.0 (should be at cap-height 714?)

	* uni0E49 (U+0E49): X=-287.0,Y=712.0 (should be at cap-height 714?)

	* uni0E4D (U+0E4D): X=-166.0,Y=716.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-50.5,Y=715.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-67.0,Y=716.0 (should be at cap-height 714?)

	* uni0E51 (U+0E51): X=189.0,Y=1.0 (should be at baseline 0?) 

	* And 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<184.0,226.0>--<187.0,225.0>>

	* uni0E05 (U+0E05) contains a short segment L<<182.0,226.0>--<185.0,225.0>>

	* uni0E07 (U+0E07) contains a short segment L<<250.0,89.0>--<260.0,89.0>>

	* uni0E08 (U+0E08) contains a short segment L<<237.0,84.0>--<249.0,84.0>>

	* uni0E09 (U+0E09) contains a short segment L<<439.0,76.0>--<433.0,76.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<306.0,408.0>--<312.0,408.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<314.0,408.0>--<318.0,408.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<728.0,70.0>--<723.0,70.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<63.0,341.0>--<63.0,370.0>>

	* uni0E0E (U+0E0E) contains a short segment L<<99.0,-194.0>--<99.0,-178.0>> 

	* And 43 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[11] NotoSansThaiUI-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E0D (U+0E0D): X=576.0,Y=1.0 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=162.5,Y=0.5 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=125.5,Y=1.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=115.5,Y=-2.0 (should be at baseline 0?)

	* uni0E36 (U+0E36): X=-138.5,Y=715.0 (should be at cap-height 714?)

	* uni0E36 (U+0E36): X=-201.0,Y=715.5 (should be at cap-height 714?)

	* uni0E42 (U+0E42): X=9.0,Y=716.0 (should be at cap-height 714?)

	* uni0E42 (U+0E42): X=350.0,Y=716.0 (should be at cap-height 714?)

	* uni0E42 (U+0E42): X=147.0,Y=716.0 (should be at cap-height 714?)

	* uni0E42 (U+0E42): X=146.0,Y=712.0 (should be at cap-height 714?) 

	* And 14 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<170.0,226.0>--<173.0,225.0>>

	* uni0E05 (U+0E05) contains a short segment L<<168.0,226.0>--<171.0,225.0>>

	* uni0E07 (U+0E07) contains a short segment L<<238.0,76.0>--<250.0,76.0>>

	* uni0E08 (U+0E08) contains a short segment L<<232.0,71.0>--<245.0,71.0>>

	* uni0E09 (U+0E09) contains a short segment L<<445.0,76.0>--<441.0,76.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<301.0,408.0>--<306.0,408.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<307.0,408.0>--<312.0,408.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<734.0,70.0>--<730.0,70.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<66.0,344.0>--<66.0,375.0>>

	* uni0E0E (U+0E0E) contains a short segment L<<103.0,-191.0>--<103.0,-175.0>> 

	* And 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansThaiUI-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI SemiBold [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* tildecomb (U+0303): X=-454.0,Y=712.0 (should be at cap-height 714?)

	* uni0E18 (U+0E18): X=166.0,Y=-1.5 (should be at baseline 0?)

	* uni0E47 (U+0E47): X=-465.0,Y=712.0 (should be at cap-height 714?)

	* uni0E47 (U+0E47): X=-187.0,Y=713.0 (should be at cap-height 714?)

	* uni0E47 (U+0E47): X=-100.0,Y=713.0 (should be at cap-height 714?)

	* uni0E49 (U+0E49): X=-296.0,Y=713.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-27.0,Y=713.0 (should be at cap-height 714?)

	* uni0E53 (U+0E53): X=289.0,Y=2.0 (should be at baseline 0?)

	* uni0E57 (U+0E57): X=289.0,Y=2.0 (should be at baseline 0?) 

	* And uni0E59 (U+0E59): X=289.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<200.0,227.0>--<203.0,226.0>>

	* uni0E05 (U+0E05) contains a short segment L<<199.0,227.0>--<202.0,226.0>>

	* uni0E07 (U+0E07) contains a short segment L<<262.0,104.0>--<271.0,104.0>>

	* uni0E08 (U+0E08) contains a short segment L<<243.0,98.0>--<252.0,98.0>>

	* uni0E09 (U+0E09) contains a short segment L<<431.0,77.0>--<425.0,77.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<312.0,408.0>--<318.0,408.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<321.0,408.0>--<326.0,408.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<721.0,71.0>--<715.0,71.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<59.0,337.0>--<59.0,364.0>>

	* uni0E0E (U+0E0E) contains a short segment L<<96.0,-198.0>--<96.0,-181.0>> 

	* And 42 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-SemiCondensed.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI SemiCondensed [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI SemiCondensed' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E0D (U+0E0D): X=516.0,Y=1.0 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=149.5,Y=1.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=118.0,Y=1.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=107.5,Y=-2.0 (should be at baseline 0?)

	* uni0E36 (U+0E36): X=-126.5,Y=715.0 (should be at cap-height 714?)

	* uni0E36 (U+0E36): X=-182.5,Y=715.5 (should be at cap-height 714?)

	* uni0E42 (U+0E42): X=14.0,Y=715.0 (should be at cap-height 714?)

	* uni0E42 (U+0E42): X=320.0,Y=715.0 (should be at cap-height 714?)

	* uni0E42 (U+0E42): X=143.0,Y=715.0 (should be at cap-height 714?)

	* uni0E44 (U+0E44): X=148.0,Y=715.0 (should be at cap-height 714?) 

	* And 11 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<161.0,226.0>--<164.0,225.0>>

	* uni0E05 (U+0E05) contains a short segment L<<160.0,226.0>--<162.0,225.0>>

	* uni0E07 (U+0E07) contains a short segment L<<220.0,75.0>--<230.0,75.0>>

	* uni0E08 (U+0E08) contains a short segment L<<213.0,70.0>--<224.0,70.0>>

	* uni0E09 (U+0E09) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<275.0,408.0>--<279.0,408.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<281.0,408.0>--<285.0,408.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<657.0,70.0>--<653.0,70.0>>

	* uni0E0E (U+0E0E) contains a short segment L<<95.0,-191.0>--<95.0,-175.0>>

	* uni0E0E (U+0E0E) contains a short segment B<<31.0,66.0>-<37.0,64.0>-<44.5,62.0>> 

	* And 47 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-SemiCondensedBlack.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI SemiCondensed Black [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI SemiCondensed Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni02BC (U+02BC): X=232.0,Y=713.0 (should be at cap-height 714?)

	* uni02BC (U+02BC): X=65.0,Y=713.0 (should be at cap-height 714?)

	* uni0E23 (U+0E23): X=135.5,Y=-1.5 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=110.0,Y=-1.5 (should be at baseline 0?)

	* uni0E49 (U+0E49): X=-163.0,Y=712.0 (should be at cap-height 714?)

	* uni0E49 (U+0E49): X=-46.0,Y=712.0 (should be at cap-height 714?)

	* uni0E4A (U+0E4A): X=-439.0,Y=715.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-64.5,Y=712.5 (should be at cap-height 714?)

	* uni0E51 (U+0E51): X=131.0,Y=-1.0 (should be at baseline 0?) 

	* And uni0E58 (U+0E58): X=286.5,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E03 (U+0E03) contains a short segment B<<139.0,376.0>-<131.0,373.0>-<123.5,371.5>>

	* uni0E03 (U+0E03) contains a short segment B<<123.5,371.5>-<116.0,370.0>-<108.0,370.0>>

	* uni0E03 (U+0E03) contains a short segment B<<173.0,471.0>-<179.0,471.0>-<186.0,473.5>>

	* uni0E03 (U+0E03) contains a short segment B<<186.0,473.5>-<193.0,476.0>-<200.0,483.0>>

	* uni0E04 (U+0E04) contains a short segment L<<232.0,232.0>--<236.0,231.0>>

	* uni0E04 (U+0E04) contains a short segment L<<340.0,152.0>--<324.0,152.0>>

	* uni0E05 (U+0E05) contains a short segment L<<232.0,232.0>--<236.0,231.0>>

	* uni0E05 (U+0E05) contains a short segment L<<352.0,152.0>--<336.0,152.0>>

	* uni0E06 (U+0E06) contains a short segment B<<145.0,376.0>-<137.0,373.0>-<129.5,371.5>>

	* uni0E06 (U+0E06) contains a short segment B<<129.5,371.5>-<122.0,370.0>-<114.0,370.0>> 

	* And 84 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-SemiCondensedBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI SemiCondensed [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI SemiCondensed' / SUBFAMILY_NAME = 'Bold'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* tildecomb (U+0303): X=-450.0,Y=713.0 (should be at cap-height 714?)

	* uni0E18 (U+0E18): X=157.0,Y=-2.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=130.5,Y=-0.5 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=113.0,Y=-2.0 (should be at baseline 0?)

	* uni0E47 (U+0E47): X=-444.0,Y=713.0 (should be at cap-height 714?)

	* uni0E47 (U+0E47): X=-274.0,Y=712.0 (should be at cap-height 714?)

	* uni0E47 (U+0E47): X=-255.0,Y=712.0 (should be at cap-height 714?)

	* uni0E47 (U+0E47): X=-190.0,Y=716.0 (should be at cap-height 714?)

	* uni0E47 (U+0E47): X=-94.0,Y=716.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-190.0,Y=712.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-20.0,Y=716.0 (should be at cap-height 714?) 

	* And uni0E4E (U+0E4E): X=-79.5,Y=713.0 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E03 (U+0E03) contains a short segment B<<165.0,468.0>-<172.0,468.0>-<180.5,471.0>>

	* uni0E04 (U+0E04) contains a short segment L<<207.0,228.0>--<210.0,227.0>>

	* uni0E05 (U+0E05) contains a short segment L<<206.0,228.0>--<209.0,227.0>>

	* uni0E06 (U+0E06) contains a short segment B<<169.0,468.0>-<176.0,468.0>-<185.0,471.0>>

	* uni0E07 (U+0E07) contains a short segment L<<259.0,118.0>--<264.0,118.0>>

	* uni0E08 (U+0E08) contains a short segment L<<235.0,111.0>--<241.0,111.0>>

	* uni0E09 (U+0E09) contains a short segment L<<392.0,77.0>--<385.0,77.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<298.0,408.0>--<304.0,408.0>>

	* uni0E0B (U+0E0B) contains a short segment B<<165.0,468.0>-<172.0,468.0>-<181.0,471.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<309.0,408.0>--<312.0,408.0>> 

	* And 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-SemiCondensedExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI SemiCondensed ExtraBold [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI SemiCondensed ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* tildecomb (U+0303): X=-233.0,Y=713.0 (should be at cap-height 714?)

	* uni0E0E (U+0E0E): X=114.0,Y=-2.0 (should be at baseline 0?)

	* uni0E0F (U+0E0F): X=114.0,Y=-2.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=132.5,Y=-1.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=111.5,Y=-1.5 (should be at baseline 0?)

	* uni0E31 (U+0E31): X=-194.0,Y=713.0 (should be at cap-height 714?)

	* uni0E33 (U+0E33): X=-201.0,Y=713.0 (should be at cap-height 714?)

	* uni0E34 (U+0E34): X=-403.0,Y=716.0 (should be at cap-height 714?)

	* uni0E34 (U+0E34): X=-69.0,Y=716.0 (should be at cap-height 714?)

	* uni0E35 (U+0E35): X=-403.0,Y=716.0 (should be at cap-height 714?) 

	* And 14 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E03 (U+0E03) contains a short segment B<<169.0,470.0>-<175.0,470.0>-<183.0,472.5>>

	* uni0E04 (U+0E04) contains a short segment L<<218.0,230.0>--<222.0,229.0>>

	* uni0E05 (U+0E05) contains a short segment L<<218.0,230.0>--<221.0,229.0>>

	* uni0E05 (U+0E05) contains a short segment L<<348.0,165.0>--<330.0,165.0>>

	* uni0E06 (U+0E06) contains a short segment B<<174.0,470.0>-<181.0,470.0>-<189.0,472.5>>

	* uni0E06 (U+0E06) contains a short segment B<<189.0,472.5>-<197.0,475.0>-<204.0,482.0>>

	* uni0E07 (U+0E07) contains a short segment L<<265.0,129.0>--<269.0,129.0>>

	* uni0E08 (U+0E08) contains a short segment L<<238.0,122.0>--<242.0,122.0>>

	* uni0E09 (U+0E09) contains a short segment L<<383.0,77.0>--<374.0,77.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<302.0,408.0>--<308.0,408.0>> 

	* And 70 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSansThaiUI-SemiCondensedExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI SemiCondensed ExtraLight [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI SemiCondensed ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* tildecomb (U+0303): X=-120.0,Y=716.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-333.0,Y=716.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-149.0,Y=716.0 (should be at cap-height 714?)

	* uni0E12 (U+0E12): X=289.0,Y=1.0 (should be at baseline 0?)

	* uni0E15 (U+0E15): X=303.0,Y=1.0 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=148.5,Y=-0.5 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=117.5,Y=1.5 (should be at baseline 0?)

	* uni0E25 (U+0E25): X=266.0,Y=1.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=107.0,Y=-1.5 (should be at baseline 0?)

	* uni0E2A (U+0E2A): X=267.0,Y=1.0 (should be at baseline 0?) 

	* And 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<119.0,213.0>--<121.0,212.0>>

	* uni0E05 (U+0E05) contains a short segment L<<118.0,213.0>--<121.0,212.0>>

	* uni0E07 (U+0E07) contains a short segment L<<194.0,35.0>--<207.0,35.0>>

	* uni0E08 (U+0E08) contains a short segment L<<184.0,34.0>--<197.0,34.0>>

	* uni0E09 (U+0E09) contains a short segment L<<417.0,87.0>--<413.0,87.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<272.0,400.0>--<284.0,400.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<277.0,400.0>--<289.0,400.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<67.0,359.0>--<67.0,380.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<176.0,26.0>-<188.0,26.0>-<200.5,29.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<200.5,29.0>-<213.0,32.0>-<222.0,35.0>> 

	* And 48 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0E4A (U+0E4A): L<<-138.0,636.0>--<-138.0,636.0>> -> L<<-138.0,636.0>--<-56.0,636.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-SemiCondensedLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI SemiCondensed Light [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI SemiCondensed Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* tildecomb (U+0303): X=-301.5,Y=712.0 (should be at cap-height 714?)

	* uni0E0D (U+0E0D): X=520.0,Y=1.0 (should be at baseline 0?)

	* uni0E12 (U+0E12): X=299.0,Y=2.0 (should be at baseline 0?)

	* uni0E14 (U+0E14): X=300.0,Y=1.0 (should be at baseline 0?)

	* uni0E15 (U+0E15): X=309.0,Y=2.0 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=118.0,Y=1.5 (should be at baseline 0?)

	* uni0E25 (U+0E25): X=274.0,Y=2.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=107.5,Y=-1.5 (should be at baseline 0?)

	* uni0E2A (U+0E2A): X=275.0,Y=2.0 (should be at baseline 0?)

	* uni0E31 (U+0E31): X=-231.0,Y=716.0 (should be at cap-height 714?) 

	* And 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<134.0,218.0>--<137.0,217.0>>

	* uni0E05 (U+0E05) contains a short segment L<<134.0,218.0>--<136.0,217.0>>

	* uni0E07 (U+0E07) contains a short segment L<<204.0,50.0>--<216.0,50.0>>

	* uni0E08 (U+0E08) contains a short segment L<<195.0,47.0>--<207.0,47.0>>

	* uni0E09 (U+0E09) contains a short segment L<<410.0,83.0>--<406.0,83.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<273.0,403.0>--<282.0,403.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<278.0,403.0>--<288.0,403.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<65.0,354.0>--<65.0,378.0>>

	* uni0E0C (U+0E0C) contains a short segment B<<185.0,39.0>-<196.0,39.0>-<207.0,41.5>>

	* uni0E0C (U+0E0C) contains a short segment B<<207.0,41.5>-<218.0,44.0>-<226.0,47.0>> 

	* And 47 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-SemiCondensedMedium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI SemiCondensed Medium [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI SemiCondensed Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E23 (U+0E23): X=121.5,Y=0.5 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=109.0,Y=-2.0 (should be at baseline 0?)

	* uni0E31 (U+0E31): X=-217.0,Y=712.0 (should be at cap-height 714?)

	* uni0E33 (U+0E33): X=-156.0,Y=716.0 (should be at cap-height 714?)

	* uni0E49 (U+0E49): X=-263.0,Y=712.0 (should be at cap-height 714?)

	* uni0E4D (U+0E4D): X=-156.0,Y=716.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-46.5,Y=715.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-61.0,Y=716.0 (should be at cap-height 714?)

	* uni0E51 (U+0E51): X=170.0,Y=1.0 (should be at baseline 0?)

	* uni0E53 (U+0E53): X=261.0,Y=2.0 (should be at baseline 0?) 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<175.0,227.0>--<177.0,226.0>>

	* uni0E05 (U+0E05) contains a short segment L<<173.0,227.0>--<176.0,226.0>>

	* uni0E07 (U+0E07) contains a short segment L<<232.0,88.0>--<240.0,88.0>>

	* uni0E08 (U+0E08) contains a short segment L<<220.0,82.0>--<229.0,82.0>>

	* uni0E09 (U+0E09) contains a short segment L<<397.0,76.0>--<392.0,76.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<282.0,408.0>--<287.0,408.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<289.0,408.0>--<293.0,408.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<658.0,70.0>--<653.0,70.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<58.0,342.0>--<58.0,371.0>>

	* uni0E0E (U+0E0E) contains a short segment L<<92.0,-194.0>--<92.0,-177.0>> 

	* And 49 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-SemiCondensedSemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI SemiCondensed SemiBold [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI SemiCondensed SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E0E (U+0E0E): X=57.5,Y=-0.5 (should be at baseline 0?)

	* uni0E0F (U+0E0F): X=57.5,Y=-0.5 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=154.0,Y=-1.0 (should be at baseline 0?)

	* uni0E49 (U+0E49): X=-273.0,Y=713.0 (should be at cap-height 714?)

	* uni0E4E (U+0E4E): X=-25.0,Y=713.0 (should be at cap-height 714?)

	* uni0E53 (U+0E53): X=268.0,Y=2.0 (should be at baseline 0?)

	* uni0E57 (U+0E57): X=268.0,Y=2.0 (should be at baseline 0?) 

	* And uni0E59 (U+0E59): X=268.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<190.0,227.0>--<192.0,226.0>>

	* uni0E05 (U+0E05) contains a short segment L<<188.0,227.0>--<191.0,226.0>>

	* uni0E07 (U+0E07) contains a short segment L<<244.0,102.0>--<251.0,102.0>>

	* uni0E08 (U+0E08) contains a short segment L<<227.0,95.0>--<235.0,95.0>>

	* uni0E09 (U+0E09) contains a short segment L<<395.0,76.0>--<388.0,76.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<289.0,408.0>--<295.0,408.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<298.0,408.0>--<302.0,408.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<659.0,71.0>--<654.0,71.0>>

	* uni0E0D (U+0E0D) contains a short segment L<<55.0,338.0>--<55.0,365.0>>

	* uni0E0E (U+0E0E) contains a short segment L<<89.0,-197.0>--<89.0,-181.0>> 

	* And 43 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansThaiUI-SemiCondensedThin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** Style name used in "fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf" is not canonical. You should rebuild the font using any of the following style names: "Thin", "ExtraLight", "Light", "Regular", "Medium", "SemiBold", "Bold", "ExtraBold", "Black", "Thin Italic", "ExtraLight Italic", "Light Italic", "Italic", "Medium Italic", "SemiBold Italic", "Bold Italic", "ExtraBold Italic", "Black Italic". [code: bad-static-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI SemiCondensed Thin [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI SemiCondensed Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* tildecomb (U+0303): X=-120.0,Y=712.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-329.0,Y=712.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-143.0,Y=712.0 (should be at cap-height 714?)

	* uni0E0E (U+0E0E): X=26.0,Y=2.0 (should be at baseline 0?)

	* uni0E0F (U+0E0F): X=26.0,Y=2.0 (should be at baseline 0?)

	* uni0E12 (U+0E12): X=283.0,Y=1.0 (should be at baseline 0?)

	* uni0E14 (U+0E14): X=289.0,Y=-1.0 (should be at baseline 0?)

	* uni0E15 (U+0E15): X=299.0,Y=1.0 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=148.0,Y=-1.0 (should be at baseline 0?)

	* uni0E20 (U+0E20): X=26.0,Y=2.0 (should be at baseline 0?) 

	* And 23 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<108.0,210.0>--<110.0,209.0>>

	* uni0E05 (U+0E05) contains a short segment L<<108.0,210.0>--<110.0,209.0>>

	* uni0E06 (U+0E06) contains a short segment L<<185.0,517.0>--<203.0,517.0>>

	* uni0E07 (U+0E07) contains a short segment L<<187.0,25.0>--<201.0,25.0>>

	* uni0E08 (U+0E08) contains a short segment L<<177.0,25.0>--<190.0,25.0>>

	* uni0E09 (U+0E09) contains a short segment L<<421.0,90.0>--<418.0,90.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<271.0,398.0>--<286.0,398.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<180.0,517.0>--<198.0,517.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<276.0,398.0>--<290.0,398.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<68.0,363.0>--<68.0,381.0>> 

	* And 75 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansThaiUI-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI Thin [code: render-own-name]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Thai UI Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4

	- Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni0E10	Contours detected: 2	Expected: 1 or 5

	- Glyph name: uni0E3F	Contours detected: 5	Expected: 3

	- Glyph name: uni0E4F	Contours detected: 3	Expected: 4 

	- And Glyph name: uni0E55	Contours detected: 2	Expected: 1 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* tildecomb (U+0303): X=-120.0,Y=716.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-342.0,Y=716.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-144.0,Y=716.0 (should be at cap-height 714?)

	* uni0E0E (U+0E0E): X=30.0,Y=2.0 (should be at baseline 0?)

	* uni0E0F (U+0E0F): X=30.0,Y=2.0 (should be at baseline 0?)

	* uni0E12 (U+0E12): X=316.0,Y=1.0 (should be at baseline 0?)

	* uni0E14 (U+0E14): X=323.0,Y=-1.0 (should be at baseline 0?)

	* uni0E15 (U+0E15): X=335.0,Y=1.0 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=166.5,Y=-1.0 (should be at baseline 0?)

	* uni0E20 (U+0E20): X=30.0,Y=2.0 (should be at baseline 0?) 

	* And 24 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* uni0E04 (U+0E04) contains a short segment L<<118.0,207.0>--<121.0,206.0>>

	* uni0E05 (U+0E05) contains a short segment L<<118.0,207.0>--<121.0,206.0>>

	* uni0E06 (U+0E06) contains a short segment L<<207.0,517.0>--<226.0,517.0>>

	* uni0E07 (U+0E07) contains a short segment L<<206.0,25.0>--<222.0,25.0>>

	* uni0E08 (U+0E08) contains a short segment L<<196.0,25.0>--<211.0,25.0>>

	* uni0E09 (U+0E09) contains a short segment L<<475.0,93.0>--<471.0,93.0>>

	* uni0E0A (U+0E0A) contains a short segment L<<305.0,398.0>--<322.0,398.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<201.0,517.0>--<220.0,517.0>>

	* uni0E0B (U+0E0B) contains a short segment L<<310.0,398.0>--<327.0,398.0>>

	* uni0E0C (U+0E0C) contains a short segment L<<77.0,363.0>--<77.0,381.0>> 

	* And 76 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[10] NotoSansThaiUI[wdth,wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


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
 

	- And 318 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2016 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Black.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Bold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Condensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-CondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-ExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Light.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Medium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Regular.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensed.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBlack.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedExtraLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedLight.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedMedium.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedSemiBold.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-SemiCondensedThin.ttf', 'fonts/NotoSansThaiUI/googlefonts/ttf/NotoSansThaiUI-Thin.ttf', 'fonts/NotoSansThaiUI/googlefonts/variable-ttf/NotoSansThaiUI[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Thai UI [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 334. [code: invalid-default-instance-subfamily-nameid:334]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0E26 + uni0E45 

	- And uni0E24 + uni0E45 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* uni0E0D (U+0E0D): X=576.0,Y=1.0 (should be at baseline 0?)

	* uni0E18 (U+0E18): X=162.5,Y=0.5 (should be at baseline 0?)

	* uni0E23 (U+0E23): X=125.5,Y=1.0 (should be at baseline 0?)

	* uni0E27 (U+0E27): X=115.5,Y=-2.0 (should be at baseline 0?)

	* uni0E36 (U+0E36): X=-138.5,Y=715.0 (should be at cap-height 714?)

	* uni0E36 (U+0E36): X=-201.0,Y=715.5 (should be at cap-height 714?)

	* uni0E42 (U+0E42): X=9.0,Y=716.0 (should be at cap-height 714?)

	* uni0E42 (U+0E42): X=350.0,Y=716.0 (should be at cap-height 714?)

	* uni0E42 (U+0E42): X=147.0,Y=716.0 (should be at cap-height 714?)

	* uni0E42 (U+0E42): X=146.0,Y=712.0 (should be at cap-height 714?) 

	* And 14 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 215 | 257 | 4386 | 247 | 3050 | 0 |
| 0% | 3% | 3% | 54% | 3% | 37% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
