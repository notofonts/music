## Fontbakery report

Fontbakery version: 0.8.11

<details><summary><b>[11] NotoMusic-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 2.0019989013671875 is equal to version on Google Fonts.
* 🔥 **FAIL** Version number 2.0019989013671875 is equal to version on Google Fonts GitHub repo.
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĩ ĭ i̇ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĩ̧ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
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


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+1D165, U+1D166, U+1D16D, U+1D16E, U+1D16F, U+1D170, U+1D171 and U+1D172 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u1D06D (U+1D06D): L<<426.0,-7.0>--<408.0,-4.0>> -> L<<408.0,-4.0>--<391.0,0.0>>

	* u1D071 (U+1D071): L<<319.0,73.0>--<307.0,73.0>> -> L<<307.0,73.0>--<266.0,74.0>>

	* u1D075 (U+1D075): L<<163.0,50.0>--<149.0,47.0>> -> L<<149.0,47.0>--<128.0,44.0>>

	* u1D077 (U+1D077): L<<185.0,121.0>--<133.0,121.0>> -> L<<133.0,121.0>--<103.0,122.0>>

	* u1D077 (U+1D077): L<<322.0,114.0>--<185.0,121.0>> -> L<<185.0,121.0>--<133.0,121.0>>

	* u1D09F (U+1D09F): L<<215.0,360.0>--<216.0,349.0>> -> L<<216.0,349.0>--<216.0,346.0>>

	* u1D0AA (U+1D0AA): L<<325.0,276.0>--<355.0,273.0>> -> L<<355.0,273.0>--<452.0,258.0>>

	* u1D0AA (U+1D0AA): L<<452.0,258.0>--<469.0,258.0>> -> L<<469.0,258.0>--<491.0,260.0>>

	* u1D0B5 (U+1D0B5): L<<106.0,131.0>--<106.0,134.0>> -> L<<106.0,134.0>--<110.0,226.0>>

	* u1D1E9 (U+1D1E9): L<<226.0,216.0>--<275.0,179.0>> -> L<<275.0,179.0>--<314.0,150.0>> 

	* u1D1E9 (U+1D1E9): L<<314.0,150.0>--<275.0,121.0>> -> L<<275.0,121.0>--<226.0,84.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* u1D050 (U+1D050): B<<315.5,514.0>-<262.0,490.0>-<197.0,485.0>>/B<<197.0,485.0>-<228.0,485.0>-<253.0,474.5>> = 4.398705354995508

	* u1D05E (U+1D05E): B<<311.0,496.0>-<311.0,518.0>-<331.0,521.0>>/L<<331.0,521.0>--<113.0,521.0>> = 8.530765609948139

	* u1D061 (U+1D061): B<<287.0,137.0>-<287.0,117.0>-<274.0,107.0>>/B<<274.0,107.0>-<356.0,156.0>-<456.0,156.0>> = 6.707700340478021

	* u1D06B (U+1D06B): L<<144.0,108.0>--<103.0,110.0>>/B<<103.0,110.0>-<193.0,118.0>-<257.5,146.5>> = 7.87231022572785

	* u1D078 (U+1D078): B<<371.0,114.5>-<380.0,123.0>-<388.0,124.0>>/L<<388.0,124.0>--<322.0,124.0>> = 7.125016348901757

	* u1D079 (U+1D079): B<<336.0,101.0>-<336.0,120.0>-<360.0,124.0>>/L<<360.0,124.0>--<288.0,124.0>> = 9.462322208025613

	* u1D09E (U+1D09E): B<<310.0,331.0>-<277.0,331.0>-<274.0,372.0>>/B<<274.0,372.0>-<270.0,338.0>-<240.0,338.0>> = 10.894752932875335

	* u1D0A3 (U+1D0A3): L<<212.0,210.0>--<215.0,222.0>>/B<<215.0,222.0>-<196.0,180.0>-<142.0,180.0>> = 10.304846468766044

	* u1D0AE (U+1D0AE): B<<266.5,445.0>-<253.0,438.0>-<226.0,434.0>>/B<<226.0,434.0>-<237.0,433.0>-<244.5,430.0>> = 13.621397929215435

	* u1D0B2 (U+1D0B2): B<<409.0,203.0>-<409.0,217.0>-<416.0,242.0>>/B<<416.0,242.0>-<403.0,206.0>-<355.0,206.0>> = 4.212967912112212 

	* 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* u1D096 (U+1D096): L<<485.0,581.0>--<362.0,582.0>> 

	* u1D0A1 (U+1D0A1): L<<518.0,484.0>--<396.0,485.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 3 | 8 | 116 | 7 | 108 | 0 |
| 0% | 1% | 3% | 48% | 3% | 45% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
