## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[14] NotoSerifGeorgian-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 1068 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, math, canadian-aboriginal, tifinagh, coptic, syriac, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: kaithi, cham, syloti-nagri, kharoshthi, sora-sompeng, kayah-li, lisu, yi, coptic, sundanese
 * U+2116 NUMERO SIGN: try adding cyrillic

Or you can add the above codepoints to one of the subsets supported by the font: `georgian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni1CAD
	* uni1CAF and uni20BE
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Georgian Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 569 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 gravecomb (U+0300), tildecomb (U+0303), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni0312 (U+0312), uni0326 (U+0326), uni0327 (U+0327) and uni0328 (U+0328) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* at (U+0040): X=765.0,Y=-2.0 (should be at baseline 0?)

	* J (U+004A): X=117.0,Y=1.0 (should be at baseline 0?)

	* J (U+004A): X=317.0,Y=2.0 (should be at baseline 0?)

	* Q (U+0051): X=317.0,Y=-1.0 (should be at baseline 0?)

	* c (U+0063): X=431.0,Y=535.0 (should be at x-height 536?)

	* f (U+0066): X=155.0,Y=713.5 (should be at cap-height 714?)

	* p (U+0070): X=337.5,Y=1.5 (should be at baseline 0?)

	* q (U+0071): X=386.0,Y=1.0 (should be at baseline 0?)

	* s (U+0073): X=376.5,Y=535.5 (should be at x-height 536?)

	* t (U+0074): X=93.0,Y=535.5 (should be at x-height 536?)

	* t (U+0074): X=367.0,Y=1.5 (should be at baseline 0?)

	* sterling (U+00A3): X=329.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=469.0,Y=2.0 (should be at baseline 0?)

	* thorn (U+00FE): X=281.0,Y=-1.0 (should be at baseline 0?)

	* dcaron (U+010F): X=666.5,Y=712.5 (should be at cap-height 714?)

	* lcaron (U+013E): X=376.5,Y=712.5 (should be at cap-height 714?)

	* tcaron (U+0165): X=371.0,Y=1.5 (should be at baseline 0?)

	* tcaron (U+0165): X=378.5,Y=712.5 (should be at cap-height 714?)

	* uni021B (U+021B): X=367.0,Y=1.5 (should be at baseline 0?)

	* uni0312 (U+0312): X=98.0,Y=713.0 (should be at cap-height 714?)

	* uni10A1 (U+10A1): X=311.0,Y=713.5 (should be at cap-height 714?)

	* uni10AD (U+10AD): X=846.5,Y=0.5 (should be at baseline 0?)

	* uni10AD (U+10AD): X=526.0,Y=2.0 (should be at baseline 0?)

	* uni10B7 (U+10B7): X=311.0,Y=713.5 (should be at cap-height 714?)

	* uni10BD (U+10BD): X=152.0,Y=1.0 (should be at baseline 0?)

	* uni10C7 (U+10C7): X=440.0,Y=1.0 (should be at baseline 0?)

	* uni10D6 (U+10D6): X=205.0,Y=712.0 (should be at cap-height 714?)

	* uni10F2 (U+10F2): X=562.5,Y=-0.5 (should be at baseline 0?)

	* uni10F2 (U+10F2): X=428.5,Y=0.5 (should be at baseline 0?)

	* uni10F2 (U+10F2): X=209.0,Y=0.5 (should be at baseline 0?)

	* uni10F6 (U+10F6): X=833.5,Y=715.5 (should be at cap-height 714?)

	* uni1C92 (U+1C92): X=434.0,Y=712.0 (should be at cap-height 714?)

	* uni1C97 (U+1C97): X=413.5,Y=712.5 (should be at cap-height 714?)

	* uni1C97 (U+1C97): X=625.5,Y=713.0 (should be at cap-height 714?)

	* uni1C9A (U+1C9A): X=766.0,Y=-2.0 (should be at baseline 0?)

	* uni1C9C (U+1C9C): X=409.0,Y=713.5 (should be at cap-height 714?)

	* uni1CB2 (U+1CB2): X=462.0,Y=-2.0 (should be at baseline 0?)

	* uni1CB2 (U+1CB2): X=228.0,Y=-2.0 (should be at baseline 0?)

	* uni1CB9 (U+1CB9): X=229.5,Y=2.0 (should be at baseline 0?)

	* uni1CBE (U+1CBE): X=228.0,Y=716.0 (should be at cap-height 714?)

	* uni1CBE (U+1CBE): X=462.0,Y=716.0 (should be at cap-height 714?)

	* quoteleft (U+2018): X=246.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=462.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=246.0,Y=713.0 (should be at cap-height 714?)

	* uni2D23 (U+2D23): X=330.0,Y=715.0 (should be at cap-height 714?)

	* uni2D23 (U+2D23): X=582.0,Y=715.0 (should be at cap-height 714?)

	* uni2D24 (U+2D24): X=224.0,Y=-2.0 (should be at baseline 0?)

	* uni2D27 (U+2D27): X=429.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<402.5,227.0>-<406.0,208.0>-<407.0,194.0>>/B<<407.0,194.0>-<409.0,211.0>-<416.0,238.5>> = 10.79545358773178

	* eogonek (U+0119): B<<282.5,-58.0>-<309.0,-25.0>-<346.0,-9.0>>/B<<346.0,-9.0>-<340.0,-10.0>-<333.5,-10.0>> = 13.922898849188117

	* uni10A0 (U+10A0): B<<64.0,279.0>-<64.0,468.0>-<207.0,564.0>>/B<<207.0,564.0>-<173.0,549.0>-<145.0,549.0>> = 10.068650839783517

	* y (U+0079): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* yacute (U+00FD): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ycircumflex (U+0177): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ydieresis (U+00FF): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ygrave (U+1EF3): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<454.0,335.0>--<295.0,336.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆

Your font does *not* cover the following languages that require the soft-dotted feature: Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Dutch (Latn, 31,709,104 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lithuanian (Latn, 2,357,094 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] NotoSerifGeorgian-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 1068 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, math, canadian-aboriginal, tifinagh, coptic, syriac, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: kaithi, cham, syloti-nagri, kharoshthi, sora-sompeng, kayah-li, lisu, yi, coptic, sundanese
 * U+2116 NUMERO SIGN: try adding cyrillic

Or you can add the above codepoints to one of the subsets supported by the font: `georgian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni1CAD
	* uni1CAF and uni20BE
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 gravecomb (U+0300), tildecomb (U+0303), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni0312 (U+0312), uni0326 (U+0326), uni0327 (U+0327) and uni0328 (U+0328) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=343.0,Y=1.0 (should be at baseline 0?)

	* five (U+0035): X=336.0,Y=2.0 (should be at baseline 0?)

	* J (U+004A): X=281.0,Y=-2.0 (should be at baseline 0?)

	* a (U+0061): X=265.0,Y=-1.5 (should be at baseline 0?)

	* f (U+0066): X=310.0,Y=712.0 (should be at cap-height 714?)

	* s (U+0073): X=356.5,Y=534.5 (should be at x-height 536?)

	* t (U+0074): X=332.5,Y=-1.0 (should be at baseline 0?)

	* agrave (U+00E0): X=265.0,Y=-1.5 (should be at baseline 0?)

	* aacute (U+00E1): X=265.0,Y=-1.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=265.0,Y=-1.5 (should be at baseline 0?)

	* atilde (U+00E3): X=265.0,Y=-1.5 (should be at baseline 0?)

	* adieresis (U+00E4): X=265.0,Y=-1.5 (should be at baseline 0?)

	* aring (U+00E5): X=265.0,Y=-1.5 (should be at baseline 0?)

	* amacron (U+0101): X=265.0,Y=-1.5 (should be at baseline 0?)

	* abreve (U+0103): X=265.0,Y=-1.5 (should be at baseline 0?)

	* aogonek (U+0105): X=265.0,Y=-1.5 (should be at baseline 0?)

	* tcaron (U+0165): X=332.5,Y=-1.0 (should be at baseline 0?)

	* uni021B (U+021B): X=332.5,Y=-1.0 (should be at baseline 0?)

	* uni10A0 (U+10A0): X=478.5,Y=713.5 (should be at cap-height 714?)

	* uni10AD (U+10AD): X=814.5,Y=1.5 (should be at baseline 0?)

	* uni10B3 (U+10B3): X=498.5,Y=1.5 (should be at baseline 0?)

	* uni10B6 (U+10B6): X=737.0,Y=-1.0 (should be at baseline 0?)

	* uni10B6 (U+10B6): X=448.0,Y=-1.0 (should be at baseline 0?)

	* uni10B6 (U+10B6): X=318.0,Y=-1.0 (should be at baseline 0?)

	* uni10B6 (U+10B6): X=29.0,Y=-1.0 (should be at baseline 0?)

	* uni10B7 (U+10B7): X=384.0,Y=-1.0 (should be at baseline 0?)

	* uni10B7 (U+10B7): X=673.0,Y=-1.0 (should be at baseline 0?)

	* uni10B9 (U+10B9): X=761.0,Y=-1.0 (should be at baseline 0?)

	* uni10B9 (U+10B9): X=510.0,Y=-1.0 (should be at baseline 0?)

	* uni10B9 (U+10B9): X=373.0,Y=-1.0 (should be at baseline 0?)

	* uni10B9 (U+10B9): X=38.0,Y=-1.0 (should be at baseline 0?)

	* uni10BA (U+10BA): X=471.5,Y=1.5 (should be at baseline 0?)

	* uni10BA (U+10BA): X=601.5,Y=1.5 (should be at baseline 0?)

	* uni10BB (U+10BB): X=968.0,Y=-1.0 (should be at baseline 0?)

	* uni10BB (U+10BB): X=717.0,Y=-1.0 (should be at baseline 0?)

	* uni10D8 (U+10D8): X=346.5,Y=1.5 (should be at baseline 0?)

	* uni10D8 (U+10D8): X=254.5,Y=1.5 (should be at baseline 0?)

	* uni10DB (U+10DB): X=300.0,Y=712.0 (should be at cap-height 714?)

	* uni10DB (U+10DB): X=101.5,Y=714.5 (should be at cap-height 714?)

	* uni10DB (U+10DB): X=483.5,Y=716.0 (should be at cap-height 714?)

	* uni10E8 (U+10E8): X=381.0,Y=713.0 (should be at cap-height 714?)

	* uni10E8 (U+10E8): X=166.0,Y=716.0 (should be at cap-height 714?)

	* uni10EC (U+10EC): X=434.0,Y=716.0 (should be at cap-height 714?)

	* uni10F0 (U+10F0): X=177.0,Y=713.0 (should be at cap-height 714?)

	* uni10F4 (U+10F4): X=202.5,Y=-1.0 (should be at baseline 0?)

	* uni10F6 (U+10F6): X=247.0,Y=-1.0 (should be at baseline 0?)

	* uni10F6 (U+10F6): X=697.0,Y=-1.0 (should be at baseline 0?)

	* uni10FD (U+10FD): X=278.0,Y=716.0 (should be at cap-height 714?)

	* uni1C9C (U+1C9C): X=381.0,Y=715.0 (should be at cap-height 714?)

	* uni1CA9 (U+1CA9): X=413.5,Y=713.5 (should be at cap-height 714?)

	* uni1CB0 (U+1CB0): X=330.0,Y=712.0 (should be at cap-height 714?)

	* uni2D24 (U+2D24): X=245.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* y (U+0079): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* yacute (U+00FD): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ycircumflex (U+0177): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ydieresis (U+00FF): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ygrave (U+1EF3): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<101.0,122.0>--<100.0,646.0>>

	* h (U+0068): L<<252.0,309.0>--<253.0,118.0>>

	* sterling (U+00A3): L<<428.0,346.0>--<270.0,347.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆

Your font does *not* cover the following languages that require the soft-dotted feature: Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Dutch (Latn, 31,709,104 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lithuanian (Latn, 2,357,094 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[14] NotoSerifGeorgian-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 1068 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, math, canadian-aboriginal, tifinagh, coptic, syriac, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: kaithi, cham, syloti-nagri, kharoshthi, sora-sompeng, kayah-li, lisu, yi, coptic, sundanese
 * U+2116 NUMERO SIGN: try adding cyrillic

Or you can add the above codepoints to one of the subsets supported by the font: `georgian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni1CAD
	* uni1CAF and uni20BE
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Georgian ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 564 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 gravecomb (U+0300), tildecomb (U+0303), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni0312 (U+0312), uni0326 (U+0326), uni0327 (U+0327) and uni0328 (U+0328) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=351.5,Y=1.0 (should be at baseline 0?)

	* J (U+004A): X=120.0,Y=-1.0 (should be at baseline 0?)

	* Q (U+0051): X=319.0,Y=-2.0 (should be at baseline 0?)

	* Q (U+0051): X=509.0,Y=2.0 (should be at baseline 0?)

	* bracketleft (U+005B): X=274.0,Y=1.0 (should be at baseline 0?)

	* bracketright (U+005D): X=162.0,Y=1.0 (should be at baseline 0?)

	* b (U+0062): X=269.5,Y=534.5 (should be at x-height 536?)

	* c (U+0063): X=417.0,Y=535.0 (should be at x-height 536?)

	* f (U+0066): X=157.5,Y=715.0 (should be at cap-height 714?)

	* p (U+0070): X=265.0,Y=-1.5 (should be at baseline 0?)

	* s (U+0073): X=367.0,Y=535.0 (should be at x-height 536?)

	* t (U+0074): X=86.5,Y=534.0 (should be at x-height 536?)

	* t (U+0074): X=351.0,Y=0.5 (should be at baseline 0?)

	* y (U+0079): X=353.0,Y=2.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=373.0,Y=712.0 (should be at cap-height 714?)

	* atilde (U+00E3): X=394.0,Y=713.0 (should be at cap-height 714?)

	* ntilde (U+00F1): X=411.0,Y=713.0 (should be at cap-height 714?)

	* otilde (U+00F5): X=395.0,Y=713.0 (should be at cap-height 714?)

	* yacute (U+00FD): X=353.0,Y=2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=353.0,Y=2.0 (should be at baseline 0?)

	* dcaron (U+010F): X=651.5,Y=712.0 (should be at cap-height 714?)

	* lcaron (U+013E): X=358.5,Y=712.0 (should be at cap-height 714?)

	* tcaron (U+0165): X=353.0,Y=0.5 (should be at baseline 0?)

	* tcaron (U+0165): X=359.5,Y=712.0 (should be at cap-height 714?)

	* ycircumflex (U+0177): X=353.0,Y=2.0 (should be at baseline 0?)

	* uni021B (U+021B): X=351.0,Y=0.5 (should be at baseline 0?)

	* tilde (U+02DC): X=330.0,Y=713.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-234.0,Y=713.0 (should be at cap-height 714?)

	* uni0312 (U+0312): X=95.0,Y=713.0 (should be at cap-height 714?)

	* uni10A0 (U+10A0): X=478.5,Y=715.5 (should be at cap-height 714?)

	* uni10A1 (U+10A1): X=306.0,Y=712.5 (should be at cap-height 714?)

	* uni10A3 (U+10A3): X=531.5,Y=712.5 (should be at cap-height 714?)

	* uni10AD (U+10AD): X=832.0,Y=0.5 (should be at baseline 0?)

	* uni10AD (U+10AD): X=516.0,Y=2.0 (should be at baseline 0?)

	* uni10B7 (U+10B7): X=306.0,Y=712.5 (should be at cap-height 714?)

	* uni10BA (U+10BA): X=485.5,Y=-1.0 (should be at baseline 0?)

	* uni10BA (U+10BA): X=619.5,Y=0.5 (should be at baseline 0?)

	* uni10D4 (U+10D4): X=551.0,Y=2.0 (should be at baseline 0?)

	* uni10DB (U+10DB): X=95.5,Y=713.0 (should be at cap-height 714?)

	* uni10DC (U+10DC): X=555.0,Y=716.0 (should be at cap-height 714?)

	* uni10E5 (U+10E5): X=552.0,Y=2.0 (should be at baseline 0?)

	* uni10E8 (U+10E8): X=169.0,Y=712.0 (should be at cap-height 714?)

	* uni10EC (U+10EC): X=449.0,Y=712.0 (should be at cap-height 714?)

	* uni10F2 (U+10F2): X=421.5,Y=2.0 (should be at baseline 0?)

	* uni10F2 (U+10F2): X=204.0,Y=2.0 (should be at baseline 0?)

	* uni10F6 (U+10F6): X=566.0,Y=-2.0 (should be at baseline 0?)

	* uni10F9 (U+10F9): X=216.0,Y=2.0 (should be at baseline 0?)

	* uni10FD (U+10FD): X=285.0,Y=712.0 (should be at cap-height 714?)

	* uni1C97 (U+1C97): X=409.0,Y=712.0 (should be at cap-height 714?)

	* uni1CA3 (U+1CA3): X=205.0,Y=715.0 (should be at cap-height 714?)

	* uni1CA9 (U+1CA9): X=438.0,Y=713.5 (should be at cap-height 714?)

	* ygrave (U+1EF3): X=353.0,Y=2.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=241.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=454.0,Y=713.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=241.0,Y=713.0 (should be at cap-height 714?)

	* uni2D22 (U+2D22): X=126.5,Y=2.0 (should be at baseline 0?)

	* uni2D24 (U+2D24): X=234.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eogonek (U+0119): B<<270.5,-58.5>-<297.0,-26.0>-<333.0,-9.0>>/B<<333.0,-9.0>-<329.0,-10.0>-<324.0,-10.0>> = 11.24147876762648

	* y (U+0079): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* yacute (U+00FD): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* ycircumflex (U+0177): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* ydieresis (U+00FF): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* ygrave (U+1EF3): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<442.0,340.0>--<284.0,341.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆

Your font does *not* cover the following languages that require the soft-dotted feature: Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Dutch (Latn, 31,709,104 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lithuanian (Latn, 2,357,094 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSerifGeorgian-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 1068 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, math, canadian-aboriginal, tifinagh, coptic, syriac, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: kaithi, cham, syloti-nagri, kharoshthi, sora-sompeng, kayah-li, lisu, yi, coptic, sundanese
 * U+2116 NUMERO SIGN: try adding cyrillic

Or you can add the above codepoints to one of the subsets supported by the font: `georgian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Georgian ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 gravecomb (U+0300), tildecomb (U+0303), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni0312 (U+0312), uni0326 (U+0326), uni0327 (U+0327) and uni0328 (U+0328) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* G (U+0047): X=486.5,Y=-1.0 (should be at baseline 0?)

	* W (U+0057): X=496.0,Y=713.0 (should be at cap-height 714?)

	* W (U+0057): X=533.0,Y=713.0 (should be at cap-height 714?)

	* f (U+0066): X=349.0,Y=716.0 (should be at cap-height 714?)

	* w (U+0077): X=411.0,Y=535.0 (should be at x-height 536?)

	* w (U+0077): X=452.0,Y=535.0 (should be at x-height 536?)

	* sterling (U+00A3): X=359.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=91.0,Y=2.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=486.5,Y=-1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=486.5,Y=-1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=486.5,Y=-1.0 (should be at baseline 0?)

	* Eng (U+014A): X=569.0,Y=1.0 (should be at baseline 0?)

	* Wcircumflex (U+0174): X=496.0,Y=713.0 (should be at cap-height 714?)

	* Wcircumflex (U+0174): X=533.0,Y=713.0 (should be at cap-height 714?)

	* uni0308 (U+0308): X=83.0,Y=712.0 (should be at cap-height 714?)

	* uni0308 (U+0308): X=-84.0,Y=712.0 (should be at cap-height 714?)

	* uni10A0 (U+10A0): X=516.5,Y=713.0 (should be at cap-height 714?)

	* uni10A1 (U+10A1): X=239.0,Y=712.0 (should be at cap-height 714?)

	* uni10A3 (U+10A3): X=123.0,Y=716.0 (should be at cap-height 714?)

	* uni10B7 (U+10B7): X=239.0,Y=712.0 (should be at cap-height 714?)

	* uni10DB (U+10DB): X=174.0,Y=712.5 (should be at cap-height 714?)

	* uni10DC (U+10DC): X=354.5,Y=715.0 (should be at cap-height 714?)

	* uni10E2 (U+10E2): X=429.0,Y=715.5 (should be at cap-height 714?)

	* uni10F4 (U+10F4): X=381.5,Y=713.5 (should be at cap-height 714?)

	* uni10F5 (U+10F5): X=342.0,Y=714.5 (should be at cap-height 714?)

	* uni10F9 (U+10F9): X=238.0,Y=-2.0 (should be at baseline 0?)

	* uni10FC (U+10FC): X=52.0,Y=713.0 (should be at cap-height 714?)

	* uni1C90 (U+1C90): X=309.0,Y=716.0 (should be at cap-height 714?)

	* uni1C91 (U+1C91): X=208.5,Y=712.0 (should be at cap-height 714?)

	* uni1C93 (U+1C93): X=637.0,Y=2.0 (should be at baseline 0?)

	* uni1C97 (U+1C97): X=661.5,Y=-2.0 (should be at baseline 0?)

	* uni1C9C (U+1C9C): X=364.0,Y=712.5 (should be at cap-height 714?)

	* uni1C9D (U+1C9D): X=612.5,Y=-2.0 (should be at baseline 0?)

	* uni1C9D (U+1C9D): X=260.5,Y=-2.0 (should be at baseline 0?)

	* uni1CA6 (U+1CA6): X=594.0,Y=0.5 (should be at baseline 0?)

	* uni1CB0 (U+1CB0): X=224.0,Y=715.0 (should be at cap-height 714?)

	* uni1CB2 (U+1CB2): X=107.5,Y=-0.5 (should be at baseline 0?)

	* uni1CB2 (U+1CB2): X=480.0,Y=-0.5 (should be at baseline 0?)

	* uni1CBE (U+1CBE): X=480.0,Y=714.5 (should be at cap-height 714?)

	* uni1CBE (U+1CBE): X=107.5,Y=714.5 (should be at cap-height 714?)

	* Wgrave (U+1E80): X=496.0,Y=713.0 (should be at cap-height 714?)

	* Wgrave (U+1E80): X=533.0,Y=713.0 (should be at cap-height 714?)

	* Wacute (U+1E82): X=496.0,Y=713.0 (should be at cap-height 714?)

	* Wacute (U+1E82): X=533.0,Y=713.0 (should be at cap-height 714?)

	* Wdieresis (U+1E84): X=496.0,Y=713.0 (should be at cap-height 714?)

	* Wdieresis (U+1E84): X=533.0,Y=713.0 (should be at cap-height 714?)

	* Euro (U+20AC): X=417.0,Y=1.5 (should be at baseline 0?)

	* uni2D09 (U+2D09): X=241.0,Y=1.0 (should be at baseline 0?)

	* uni2D0B (U+2D0B): X=400.5,Y=712.5 (should be at cap-height 714?)

	* uni2D0B (U+2D0B): X=341.5,Y=1.0 (should be at baseline 0?)

	* uni2D1D (U+2D1D): X=453.0,Y=-1.5 (should be at baseline 0?)

	* uni2D25 (U+2D25): X=714.0,Y=714.5 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<356.5,474.5>-<399.0,456.0>-<423.0,417.0>>/B<<423.0,417.0>-<401.0,487.0>-<370.5,540.5>> = 14.160313822966648 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆

Your font does *not* cover the following languages that require the soft-dotted feature: Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Dutch (Latn, 31,709,104 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lithuanian (Latn, 2,357,094 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[11] NotoSerifGeorgian-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 1068 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, math, canadian-aboriginal, tifinagh, coptic, syriac, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: kaithi, cham, syloti-nagri, kharoshthi, sora-sompeng, kayah-li, lisu, yi, coptic, sundanese
 * U+2116 NUMERO SIGN: try adding cyrillic

Or you can add the above codepoints to one of the subsets supported by the font: `georgian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Georgian Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 gravecomb (U+0300), tildecomb (U+0303), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni0312 (U+0312), uni0326 (U+0326), uni0327 (U+0327) and uni0328 (U+0328) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* nine (U+0039): X=147.0,Y=1.0 (should be at baseline 0?)

	* bracketleft (U+005B): X=183.5,Y=714.5 (should be at cap-height 714?)

	* bracketright (U+005D): X=145.5,Y=714.5 (should be at cap-height 714?)

	* t (U+0074): X=297.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=412.0,Y=534.0 (should be at x-height 536?)

	* w (U+0077): X=462.0,Y=534.0 (should be at x-height 536?)

	* y (U+0079): X=269.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=354.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=79.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=460.5,Y=1.0 (should be at baseline 0?)

	* paragraph (U+00B6): X=496.0,Y=715.5 (should be at cap-height 714?)

	* Oslash (U+00D8): X=446.5,Y=714.5 (should be at cap-height 714?)

	* atilde (U+00E3): X=398.0,Y=712.0 (should be at cap-height 714?)

	* atilde (U+00E3): X=432.0,Y=712.0 (should be at cap-height 714?)

	* eth (U+00F0): X=440.0,Y=715.0 (should be at cap-height 714?)

	* ntilde (U+00F1): X=455.0,Y=712.0 (should be at cap-height 714?)

	* ntilde (U+00F1): X=489.0,Y=712.0 (should be at cap-height 714?)

	* otilde (U+00F5): X=408.0,Y=712.0 (should be at cap-height 714?)

	* otilde (U+00F5): X=442.0,Y=712.0 (should be at cap-height 714?)

	* yacute (U+00FD): X=269.0,Y=-1.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=269.0,Y=-1.0 (should be at baseline 0?)

	* ccaron (U+010D): X=222.5,Y=713.5 (should be at cap-height 714?)

	* ccaron (U+010D): X=318.0,Y=713.5 (should be at cap-height 714?)

	* dcroat (U+0111): X=402.5,Y=716.0 (should be at cap-height 714?)

	* ecaron (U+011B): X=219.5,Y=713.5 (should be at cap-height 714?)

	* ecaron (U+011B): X=315.0,Y=713.5 (should be at cap-height 714?)

	* lslash (U+0142): X=98.0,Y=715.5 (should be at cap-height 714?)

	* ncaron (U+0148): X=279.5,Y=713.5 (should be at cap-height 714?)

	* ncaron (U+0148): X=375.0,Y=713.5 (should be at cap-height 714?)

	* rcaron (U+0159): X=176.5,Y=713.5 (should be at cap-height 714?)

	* rcaron (U+0159): X=272.0,Y=713.5 (should be at cap-height 714?)

	* scaron (U+0161): X=173.5,Y=713.5 (should be at cap-height 714?)

	* scaron (U+0161): X=269.0,Y=713.5 (should be at cap-height 714?)

	* tcaron (U+0165): X=297.0,Y=1.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=269.0,Y=-1.0 (should be at baseline 0?)

	* zcaron (U+017E): X=212.5,Y=713.5 (should be at cap-height 714?)

	* zcaron (U+017E): X=308.0,Y=713.5 (should be at cap-height 714?)

	* uni021B (U+021B): X=297.0,Y=1.0 (should be at baseline 0?)

	* caron (U+02C7): X=122.5,Y=713.5 (should be at cap-height 714?)

	* caron (U+02C7): X=218.0,Y=713.5 (should be at cap-height 714?)

	* tilde (U+02DC): X=339.0,Y=712.0 (should be at cap-height 714?)

	* tilde (U+02DC): X=373.0,Y=712.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-185.0,Y=712.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-151.0,Y=712.0 (should be at cap-height 714?)

	* uni030C (U+030C): X=-327.5,Y=713.5 (should be at cap-height 714?)

	* uni030C (U+030C): X=-232.0,Y=713.5 (should be at cap-height 714?)

	* uni0312 (U+0312): X=56.0,Y=715.0 (should be at cap-height 714?)

	* uni10BA (U+10BA): X=425.0,Y=1.0 (should be at baseline 0?)

	* uni10D4 (U+10D4): X=404.0,Y=1.0 (should be at baseline 0?)

	* uni10D4 (U+10D4): X=468.0,Y=1.0 (should be at baseline 0?)

	* uni10D7 (U+10D7): X=613.5,Y=-1.0 (should be at baseline 0?)

	* uni10DB (U+10DB): X=118.0,Y=713.5 (should be at cap-height 714?)

	* uni10DC (U+10DC): X=333.0,Y=712.0 (should be at cap-height 714?)

	* uni10E0 (U+10E0): X=358.0,Y=713.0 (should be at cap-height 714?)

	* uni10E1 (U+10E1): X=95.0,Y=713.0 (should be at cap-height 714?)

	* uni10E2 (U+10E2): X=481.0,Y=713.5 (should be at cap-height 714?)

	* uni10E5 (U+10E5): X=404.0,Y=1.0 (should be at baseline 0?)

	* uni10E5 (U+10E5): X=468.0,Y=1.0 (should be at baseline 0?)

	* uni10E8 (U+10E8): X=202.5,Y=712.5 (should be at cap-height 714?)

	* uni10E8 (U+10E8): X=100.5,Y=713.5 (should be at cap-height 714?)

	* uni10EC (U+10EC): X=434.0,Y=713.0 (should be at cap-height 714?)

	* uni10EC (U+10EC): X=327.5,Y=712.5 (should be at cap-height 714?)

	* uni10ED (U+10ED): X=259.5,Y=714.5 (should be at cap-height 714?)

	* uni10EE (U+10EE): X=98.0,Y=715.5 (should be at cap-height 714?)

	* uni10F2 (U+10F2): X=482.0,Y=0.5 (should be at baseline 0?)

	* uni10F4 (U+10F4): X=391.0,Y=715.0 (should be at cap-height 714?)

	* uni10F7 (U+10F7): X=440.5,Y=-1.0 (should be at baseline 0?)

	* uni1C90 (U+1C90): X=327.0,Y=713.0 (should be at cap-height 714?)

	* uni1C91 (U+1C91): X=267.0,Y=716.0 (should be at cap-height 714?)

	* uni1C97 (U+1C97): X=671.0,Y=-1.0 (should be at baseline 0?)

	* uni1C98 (U+1C98): X=354.0,Y=-2.0 (should be at baseline 0?)

	* uni1C98 (U+1C98): X=252.0,Y=-1.5 (should be at baseline 0?)

	* uni1C9C (U+1C9C): X=375.5,Y=713.0 (should be at cap-height 714?)

	* uni1C9C (U+1C9C): X=461.5,Y=712.0 (should be at cap-height 714?)

	* uni1C9D (U+1C9D): X=620.0,Y=-1.0 (should be at baseline 0?)

	* uni1C9D (U+1C9D): X=267.5,Y=-1.0 (should be at baseline 0?)

	* uni1C9E (U+1C9E): X=312.0,Y=715.0 (should be at cap-height 714?)

	* uni1CA6 (U+1CA6): X=600.5,Y=1.0 (should be at baseline 0?)

	* uni1CA7 (U+1CA7): X=180.0,Y=712.0 (should be at cap-height 714?)

	* uni1CA9 (U+1CA9): X=395.0,Y=1.0 (should be at baseline 0?)

	* uni1CAA (U+1CAA): X=463.0,Y=715.0 (should be at cap-height 714?)

	* uni1CB0 (U+1CB0): X=277.0,Y=715.0 (should be at cap-height 714?)

	* uni1CB1 (U+1CB1): X=394.0,Y=713.0 (should be at cap-height 714?)

	* uni1CB1 (U+1CB1): X=451.0,Y=715.0 (should be at cap-height 714?)

	* uni1CB2 (U+1CB2): X=387.0,Y=2.0 (should be at baseline 0?)

	* uni1CB2 (U+1CB2): X=218.5,Y=2.0 (should be at baseline 0?)

	* uni1CB8 (U+1CB8): X=418.0,Y=712.0 (should be at cap-height 714?)

	* uni1CBE (U+1CBE): X=218.5,Y=712.0 (should be at cap-height 714?)

	* uni1CBE (U+1CBE): X=387.0,Y=712.0 (should be at cap-height 714?)

	* ygrave (U+1EF3): X=269.0,Y=-1.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=198.0,Y=715.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=377.0,Y=715.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=198.0,Y=715.0 (should be at cap-height 714?)

	* uni2D09 (U+2D09): X=94.0,Y=715.5 (should be at cap-height 714?)

	* uni2D0B (U+2D0B): X=265.0,Y=712.0 (should be at cap-height 714?)

	* uni2D10 (U+2D10): X=433.0,Y=713.5 (should be at cap-height 714?)

	* uni2D15 (U+2D15): X=220.5,Y=713.5 (should be at cap-height 714?)

	* uni2D15 (U+2D15): X=313.5,Y=714.5 (should be at cap-height 714?)

	* uni2D1B (U+2D1B): X=395.0,Y=715.5 (should be at cap-height 714?)

	* uni2D22 (U+2D22): X=132.5,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆

Your font does *not* cover the following languages that require the soft-dotted feature: Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Dutch (Latn, 31,709,104 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lithuanian (Latn, 2,357,094 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSerifGeorgian-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 1068 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, math, canadian-aboriginal, tifinagh, coptic, syriac, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: kaithi, cham, syloti-nagri, kharoshthi, sora-sompeng, kayah-li, lisu, yi, coptic, sundanese
 * U+2116 NUMERO SIGN: try adding cyrillic

Or you can add the above codepoints to one of the subsets supported by the font: `georgian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Georgian Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 gravecomb (U+0300), tildecomb (U+0303), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni0312 (U+0312), uni0326 (U+0326), uni0327 (U+0327) and uni0328 (U+0328) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<408.0,339.0>--<251.0,340.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆

Your font does *not* cover the following languages that require the soft-dotted feature: Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Dutch (Latn, 31,709,104 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lithuanian (Latn, 2,357,094 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[11] NotoSerifGeorgian-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 1068 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, math, canadian-aboriginal, tifinagh, coptic, syriac, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: kaithi, cham, syloti-nagri, kharoshthi, sora-sompeng, kayah-li, lisu, yi, coptic, sundanese
 * U+2116 NUMERO SIGN: try adding cyrillic

Or you can add the above codepoints to one of the subsets supported by the font: `georgian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 gravecomb (U+0300), tildecomb (U+0303), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni0312 (U+0312), uni0326 (U+0326), uni0327 (U+0327) and uni0328 (U+0328) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft (U+0028): X=314.0,Y=715.0 (should be at cap-height 714?)

	* parenright (U+0029): X=32.0,Y=715.0 (should be at cap-height 714?)

	* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

	* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

	* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* a (U+0061): X=182.0,Y=536.5 (should be at x-height 536?)

	* c (U+0063): X=360.0,Y=535.0 (should be at x-height 536?)

	* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

	* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

	* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

	* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=454.5,Y=715.5 (should be at cap-height 714?)

	* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?)

	* gbreve (U+011F): X=161.0,Y=-0.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at baseline 0?)

	* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at baseline 0?)

	* uni0122 (U+0122): X=519.0,Y=1.5 (should be at baseline 0?)

	* uni0123 (U+0123): X=161.0,Y=-0.5 (should be at baseline 0?)

	* uni0312 (U+0312): X=82.0,Y=715.0 (should be at cap-height 714?)

	* uni10BD (U+10BD): X=368.0,Y=712.5 (should be at cap-height 714?)

	* uni10C2 (U+10C2): X=157.5,Y=0.5 (should be at baseline 0?)

	* uni10C7 (U+10C7): X=176.0,Y=713.0 (should be at cap-height 714?)

	* uni10D8 (U+10D8): X=348.5,Y=-2.0 (should be at baseline 0?)

	* uni10D8 (U+10D8): X=218.5,Y=-2.0 (should be at baseline 0?)

	* uni10DB (U+10DB): X=451.0,Y=716.0 (should be at cap-height 714?)

	* uni10DD (U+10DD): X=596.5,Y=-2.0 (should be at baseline 0?)

	* uni10DD (U+10DD): X=218.5,Y=-2.0 (should be at baseline 0?)

	* uni10E0 (U+10E0): X=593.5,Y=-2.0 (should be at baseline 0?)

	* uni10E0 (U+10E0): X=215.5,Y=-2.0 (should be at baseline 0?)

	* uni10E2 (U+10E2): X=255.0,Y=712.5 (should be at cap-height 714?)

	* uni10E2 (U+10E2): X=494.5,Y=712.0 (should be at cap-height 714?)

	* uni10E3 (U+10E3): X=541.0,Y=2.0 (should be at baseline 0?)

	* uni10E9 (U+10E9): X=233.5,Y=712.0 (should be at cap-height 714?)

	* uni10F0 (U+10F0): X=152.0,Y=1.5 (should be at baseline 0?)

	* uni10F2 (U+10F2): X=423.5,Y=-2.0 (should be at baseline 0?)

	* uni10F2 (U+10F2): X=153.5,Y=-2.0 (should be at baseline 0?)

	* uni10F6 (U+10F6): X=599.5,Y=712.0 (should be at cap-height 714?)

	* uni10FC (U+10FC): X=125.0,Y=712.0 (should be at cap-height 714?)

	* uni1C91 (U+1C91): X=286.0,Y=713.0 (should be at cap-height 714?)

	* uni1C97 (U+1C97): X=685.0,Y=0.5 (should be at baseline 0?)

	* uni1C98 (U+1C98): X=368.5,Y=-0.5 (should be at baseline 0?)

	* uni1C98 (U+1C98): X=262.0,Y=-0.5 (should be at baseline 0?)

	* uni1C9C (U+1C9C): X=390.5,Y=713.0 (should be at cap-height 714?)

	* uni1C9C (U+1C9C): X=481.5,Y=712.0 (should be at cap-height 714?)

	* uni1C9D (U+1C9D): X=630.0,Y=0.5 (should be at baseline 0?)

	* uni1C9D (U+1C9D): X=277.0,Y=0.5 (should be at baseline 0?)

	* uni1C9E (U+1C9E): X=329.0,Y=712.0 (should be at cap-height 714?)

	* uni1CA0 (U+1CA0): X=623.5,Y=-0.5 (should be at baseline 0?)

	* uni1CA0 (U+1CA0): X=234.0,Y=-0.5 (should be at baseline 0?)

	* uni1CA3 (U+1CA3): X=148.0,Y=712.0 (should be at cap-height 714?)

	* uni1CA6 (U+1CA6): X=609.5,Y=1.5 (should be at baseline 0?)

	* uni1CA9 (U+1CA9): X=381.5,Y=713.0 (should be at cap-height 714?)

	* uni1CAA (U+1CAA): X=480.0,Y=713.0 (should be at cap-height 714?)

	* uni1CB0 (U+1CB0): X=214.0,Y=712.0 (should be at cap-height 714?)

	* uni1CB0 (U+1CB0): X=293.0,Y=713.0 (should be at cap-height 714?)

	* uni1CB1 (U+1CB1): X=474.0,Y=712.0 (should be at cap-height 714?)

	* quoteleft (U+2018): X=220.0,Y=715.0 (should be at cap-height 714?)

	* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at baseline 0?)

	* quotedblleft (U+201C): X=420.0,Y=715.0 (should be at cap-height 714?)

	* quotedblleft (U+201C): X=220.0,Y=715.0 (should be at cap-height 714?)

	* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at baseline 0?)

	* uni2D03 (U+2D03): X=386.0,Y=712.0 (should be at cap-height 714?)

	* uni2D06 (U+2D06): X=-43.0,Y=715.0 (should be at cap-height 714?)

	* uni2D18 (U+2D18): X=438.0,Y=2.0 (should be at baseline 0?)

	* uni2D1E (U+2D1E): X=207.0,Y=2.0 (should be at baseline 0?)

	* uni2D22 (U+2D22): X=138.5,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆

Your font does *not* cover the following languages that require the soft-dotted feature: Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Dutch (Latn, 31,709,104 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lithuanian (Latn, 2,357,094 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] NotoSerifGeorgian-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 1068 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, math, canadian-aboriginal, tifinagh, coptic, syriac, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: kaithi, cham, syloti-nagri, kharoshthi, sora-sompeng, kayah-li, lisu, yi, coptic, sundanese
 * U+2116 NUMERO SIGN: try adding cyrillic

Or you can add the above codepoints to one of the subsets supported by the font: `georgian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni1CAD and uni1CAF
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Georgian SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 gravecomb (U+0300), tildecomb (U+0303), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni0312 (U+0312), uni0326 (U+0326), uni0327 (U+0327) and uni0328 (U+0328) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=119.0,Y=-1.0 (should be at baseline 0?)

	* three (U+0033): X=340.0,Y=1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=132.0,Y=-1.0 (should be at baseline 0?)

	* Q (U+0051): X=470.0,Y=-2.0 (should be at baseline 0?)

	* a (U+0061): X=186.5,Y=538.0 (should be at x-height 536?)

	* y (U+0079): X=254.0,Y=-2.0 (should be at baseline 0?)

	* y (U+0079): X=343.0,Y=-2.0 (should be at baseline 0?)

	* Aring (U+00C5): X=477.0,Y=715.5 (should be at cap-height 714?)

	* germandbls (U+00DF): X=352.0,Y=716.0 (should be at cap-height 714?)

	* atilde (U+00E3): X=135.5,Y=712.0 (should be at cap-height 714?)

	* ntilde (U+00F1): X=170.5,Y=712.0 (should be at cap-height 714?)

	* otilde (U+00F5): X=139.5,Y=712.0 (should be at cap-height 714?)

	* yacute (U+00FD): X=254.0,Y=-2.0 (should be at baseline 0?)

	* yacute (U+00FD): X=343.0,Y=-2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=254.0,Y=-2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=343.0,Y=-2.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=254.0,Y=-2.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=343.0,Y=-2.0 (should be at baseline 0?)

	* tilde (U+02DC): X=73.5,Y=712.0 (should be at cap-height 714?)

	* tildecomb (U+0303): X=-474.5,Y=712.0 (should be at cap-height 714?)

	* uni10A0 (U+10A0): X=457.5,Y=715.0 (should be at cap-height 714?)

	* uni10A1 (U+10A1): X=280.5,Y=713.5 (should be at cap-height 714?)

	* uni10A3 (U+10A3): X=513.0,Y=716.0 (should be at cap-height 714?)

	* uni10AD (U+10AD): X=790.5,Y=2.0 (should be at baseline 0?)

	* uni10B3 (U+10B3): X=489.5,Y=2.0 (should be at baseline 0?)

	* uni10B6 (U+10B6): X=726.0,Y=-1.0 (should be at baseline 0?)

	* uni10B6 (U+10B6): X=453.0,Y=-1.0 (should be at baseline 0?)

	* uni10B6 (U+10B6): X=309.0,Y=-1.0 (should be at baseline 0?)

	* uni10B6 (U+10B6): X=36.0,Y=-1.0 (should be at baseline 0?)

	* uni10B7 (U+10B7): X=391.0,Y=-1.0 (should be at baseline 0?)

	* uni10B7 (U+10B7): X=280.5,Y=713.5 (should be at cap-height 714?)

	* uni10B7 (U+10B7): X=664.0,Y=-1.0 (should be at baseline 0?)

	* uni10B9 (U+10B9): X=736.0,Y=-1.0 (should be at baseline 0?)

	* uni10B9 (U+10B9): X=506.0,Y=-1.0 (should be at baseline 0?)

	* uni10B9 (U+10B9): X=353.0,Y=-1.0 (should be at baseline 0?)

	* uni10B9 (U+10B9): X=38.0,Y=-1.0 (should be at baseline 0?)

	* uni10BA (U+10BA): X=456.0,Y=-0.5 (should be at baseline 0?)

	* uni10BB (U+10BB): X=948.0,Y=-1.0 (should be at baseline 0?)

	* uni10BB (U+10BB): X=718.0,Y=-1.0 (should be at baseline 0?)

	* uni10BD (U+10BD): X=393.5,Y=712.5 (should be at cap-height 714?)

	* uni10C7 (U+10C7): X=176.5,Y=712.0 (should be at cap-height 714?)

	* uni10D4 (U+10D4): X=515.0,Y=-2.0 (should be at baseline 0?)

	* uni10DB (U+10DB): X=297.0,Y=716.0 (should be at cap-height 714?)

	* uni10DB (U+10DB): X=107.5,Y=715.0 (should be at cap-height 714?)

	* uni10DB (U+10DB): X=471.0,Y=716.0 (should be at cap-height 714?)

	* uni10E5 (U+10E5): X=516.0,Y=-2.0 (should be at baseline 0?)

	* uni10E9 (U+10E9): X=290.0,Y=715.0 (should be at cap-height 714?)

	* uni10F6 (U+10F6): X=593.0,Y=715.0 (should be at cap-height 714?)

	* uni10F7 (U+10F7): X=167.5,Y=-2.0 (should be at baseline 0?)

	* uni10F9 (U+10F9): X=224.0,Y=1.0 (should be at baseline 0?)

	* uni1C98 (U+1C98): X=380.5,Y=2.0 (should be at baseline 0?)

	* uni1CA9 (U+1CA9): X=401.0,Y=713.5 (should be at cap-height 714?)

	* uni1CB0 (U+1CB0): X=316.0,Y=712.0 (should be at cap-height 714?)

	* ygrave (U+1EF3): X=254.0,Y=-2.0 (should be at baseline 0?)

	* ygrave (U+1EF3): X=343.0,Y=-2.0 (should be at baseline 0?)

	* quotesinglbase (U+201A): X=119.0,Y=-1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=324.5,Y=-1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=119.0,Y=-1.0 (should be at baseline 0?)

	* uni2D24 (U+2D24): X=255.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<104.0,119.0>--<103.0,648.0>>

	* h (U+0068): L<<233.0,313.0>--<234.0,115.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆

Your font does *not* cover the following languages that require the soft-dotted feature: Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Dutch (Latn, 31,709,104 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lithuanian (Latn, 2,357,094 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] NotoSerifGeorgian-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 1068 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, math, canadian-aboriginal, tifinagh, coptic, syriac, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: kaithi, cham, syloti-nagri, kharoshthi, sora-sompeng, kayah-li, lisu, yi, coptic, sundanese
 * U+2116 NUMERO SIGN: try adding cyrillic

Or you can add the above codepoints to one of the subsets supported by the font: `georgian`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Georgian Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 gravecomb (U+0300), tildecomb (U+0303), uni0306 (U+0306), uni0307 (U+0307), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni0312 (U+0312), uni0326 (U+0326), uni0327 (U+0327) and uni0328 (U+0328) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=99.5,Y=-1.5 (should be at baseline 0?)

	* semicolon (U+003B): X=111.5,Y=-1.5 (should be at baseline 0?)

	* C (U+0043): X=407.0,Y=1.5 (should be at baseline 0?)

	* G (U+0047): X=477.5,Y=-1.5 (should be at baseline 0?)

	* b (U+0062): X=114.0,Y=715.5 (should be at cap-height 714?)

	* d (U+0064): X=428.0,Y=715.5 (should be at cap-height 714?)

	* g (U+0067): X=394.0,Y=537.5 (should be at x-height 536?)

	* h (U+0068): X=114.0,Y=715.5 (should be at cap-height 714?)

	* k (U+006B): X=114.0,Y=715.5 (should be at cap-height 714?)

	* l (U+006C): X=110.0,Y=715.5 (should be at cap-height 714?)

	* t (U+0074): X=53.5,Y=536.5 (should be at x-height 536?)

	* sterling (U+00A3): X=362.5,Y=-1.5 (should be at baseline 0?)

	* sterling (U+00A3): X=464.5,Y=-0.5 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=407.0,Y=1.5 (should be at baseline 0?)

	* Oslash (U+00D8): X=437.5,Y=713.5 (should be at cap-height 714?)

	* thorn (U+00FE): X=117.5,Y=716.0 (should be at cap-height 714?)

	* Cacute (U+0106): X=407.0,Y=1.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=407.0,Y=1.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=407.0,Y=1.5 (should be at baseline 0?)

	* dcaron (U+010F): X=428.0,Y=715.5 (should be at cap-height 714?)

	* dcroat (U+0111): X=427.5,Y=715.5 (should be at cap-height 714?)

	* Gbreve (U+011E): X=477.5,Y=-1.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=477.5,Y=-1.5 (should be at baseline 0?)

	* uni0122 (U+0122): X=477.5,Y=-1.5 (should be at baseline 0?)

	* hbar (U+0127): X=113.5,Y=715.5 (should be at cap-height 714?)

	* uni0137 (U+0137): X=114.0,Y=715.5 (should be at cap-height 714?)

	* lacute (U+013A): X=110.0,Y=715.5 (should be at cap-height 714?)

	* uni013C (U+013C): X=110.0,Y=715.5 (should be at cap-height 714?)

	* lcaron (U+013E): X=110.0,Y=715.5 (should be at cap-height 714?)

	* Eng (U+014A): X=566.0,Y=1.0 (should be at baseline 0?)

	* uni10A0 (U+10A0): X=58.5,Y=712.5 (should be at cap-height 714?)

	* uni10A0 (U+10A0): X=501.0,Y=714.5 (should be at cap-height 714?)

	* uni10A1 (U+10A1): X=233.5,Y=713.5 (should be at cap-height 714?)

	* uni10B7 (U+10B7): X=233.5,Y=713.5 (should be at cap-height 714?)

	* uni10D3 (U+10D3): X=194.5,Y=1.5 (should be at baseline 0?)

	* uni10D6 (U+10D6): X=247.0,Y=716.0 (should be at cap-height 714?)

	* uni10D6 (U+10D6): X=89.0,Y=716.0 (should be at cap-height 714?)

	* uni10D8 (U+10D8): X=205.5,Y=-2.0 (should be at baseline 0?)

	* uni10E0 (U+10E0): X=423.5,Y=714.5 (should be at cap-height 714?)

	* uni10E1 (U+10E1): X=107.5,Y=715.5 (should be at cap-height 714?)

	* uni10E5 (U+10E5): X=412.0,Y=715.5 (should be at cap-height 714?)

	* uni10E8 (U+10E8): X=412.5,Y=712.5 (should be at cap-height 714?)

	* uni10EB (U+10EB): X=427.0,Y=715.5 (should be at cap-height 714?)

	* uni10ED (U+10ED): X=272.5,Y=712.5 (should be at cap-height 714?)

	* uni10EE (U+10EE): X=111.0,Y=715.5 (should be at cap-height 714?)

	* uni10F9 (U+10F9): X=240.0,Y=-1.0 (should be at baseline 0?)

	* uni10FB (U+10FB): X=108.5,Y=0.5 (should be at baseline 0?)

	* uni10FB (U+10FB): X=149.0,Y=0.5 (should be at baseline 0?)

	* uni10FD (U+10FD): X=148.0,Y=713.5 (should be at cap-height 714?)

	* uni1C91 (U+1C91): X=212.0,Y=712.0 (should be at cap-height 714?)

	* uni1C92 (U+1C92): X=201.5,Y=712.5 (should be at cap-height 714?)

	* uni1C93 (U+1C93): X=631.5,Y=0.5 (should be at baseline 0?)

	* uni1CA7 (U+1CA7): X=153.0,Y=715.0 (should be at cap-height 714?)

	* uni1CAF (U+1CAF): X=672.0,Y=712.0 (should be at cap-height 714?)

	* uni1CB0 (U+1CB0): X=227.5,Y=715.5 (should be at cap-height 714?)

	* uni1CB1 (U+1CB1): X=393.5,Y=715.0 (should be at cap-height 714?)

	* uni1CB8 (U+1CB8): X=417.0,Y=715.0 (should be at cap-height 714?)

	* uni1CB9 (U+1CB9): X=347.0,Y=1.5 (should be at baseline 0?)

	* Euro (U+20AC): X=406.0,Y=0.5 (should be at baseline 0?)

	* uni2D06 (U+2D06): X=244.5,Y=-0.5 (should be at baseline 0?)

	* uni2D06 (U+2D06): X=-33.5,Y=714.5 (should be at cap-height 714?)

	* uni2D09 (U+2D09): X=244.5,Y=-0.5 (should be at baseline 0?)

	* uni2D09 (U+2D09): X=114.0,Y=715.5 (should be at cap-height 714?)

	* uni2D0B (U+2D0B): X=206.0,Y=712.5 (should be at cap-height 714?)

	* uni2D0B (U+2D0B): X=326.0,Y=-0.5 (should be at baseline 0?)

	* uni2D10 (U+2D10): X=468.0,Y=715.5 (should be at cap-height 714?)

	* uni2D19 (U+2D19): X=104.0,Y=715.5 (should be at cap-height 714?)

	* uni2D1B (U+2D1B): X=420.0,Y=715.0 (should be at cap-height 714?)

	* uni2D21 (U+2D21): X=126.0,Y=715.5 (should be at cap-height 714?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<385.5,450.5>-<412.0,431.0>-<428.0,400.0>>/B<<428.0,400.0>-<403.0,480.0>-<371.5,537.5>> = 9.945547575071476

	* sterling (U+00A3): B<<192.0,89.0>-<173.0,58.0>-<145.0,40.0>>/L<<145.0,40.0>--<149.0,42.0>> = 6.170175095029526 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<123.0,167.0>--<120.0,714.0>>

	* exclam (U+0021): L<<149.0,714.0>--<148.0,167.0>>

	* exclamdown (U+00A1): L<<123.0,-177.0>--<124.0,370.0>>

	* exclamdown (U+00A1): L<<149.0,370.0>--<152.0,-177.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆

Your font does *not* cover the following languages that require the soft-dotted feature: Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Dutch (Latn, 31,709,104 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lithuanian (Latn, 2,357,094 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 18 | 95 | 1064 | 55 | 873 | 0 |
| 0% | 1% | 5% | 51% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
