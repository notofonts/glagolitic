## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[9] NotoSansGlagolitic-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00301" while name version string (for platform 3, encoding 1) is "Version 2.002; ttfautohint (v1.8.4.7-5d5b)". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/glagolitic.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansGlagolitic/googlefonts/ttf/NotoSansGlagolitic-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/glagolitic.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ⱆ︮Ⰳ︯</span> (Issue #1)</li>


<pre>Expected: uni2C46=0+738|uniFE2E=0@-391,391+0|uni2C03=2+958|uniFE2F=2@-458,389+0</pre>



<pre>Got     : uni2C46=0+738|uniFE2E=0@-391,212+0|uni2C03=2+958|uniFE2F=2@-458,212+0</pre>



<pre>                                       ^^                                 ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1696 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M175.0,0.0Q131.0,0.0 110.0,16.5Q89.0,33.0 83.5,57.0Q78.0,81.0 78.0,104.0Q78.0,158.0 110.0,202.5Q142.0,247.0 196.0,275.0Q142.0,298.0 110.0,338.0Q78.0,378.0 78.0,432.0Q78.0,455.0 84.5,479.0Q91.0,503.0 110.0,519.5Q129.0,536.0 166.0,536.0L583.0,536.0Q627.0,536.0 638.5,516.0Q650.0,496.0 650.0,448.0L650.0,88.0Q650.0,40.0 638.5,20.0Q627.0,0.0 583.0,0.0L175.0,0.0ZM332.0,313.0L332.0,465.0L205.0,465.0Q174.0,465.0 168.5,452.5Q163.0,440.0 163.0,420.0Q163.0,372.0 205.0,344.5Q247.0,317.0 332.0,313.0ZM418.0,312.0L564.0,312.0L564.0,426.0Q564.0,452.0 556.5,458.5Q549.0,465.0 530.0,465.0L418.0,465.0L418.0,312.0ZM193.0,71.0L332.0,71.0L332.0,243.0Q250.0,237.0 206.5,200.5Q163.0,164.0 163.0,116.0Q163.0,97.0 168.0,84.0Q173.0,71.0 193.0,71.0ZM418.0,71.0L530.0,71.0Q549.0,71.0 556.5,78.0Q564.0,85.0 564.0,110.0L564.0,242.0L418.0,242.0L418.0,71.0Z" transform="translate(0, 793)"/>
<path d="M-60.0,775.0L653.0,775.0L653.0,710.0L-97.0,710.0Q-154.0,710.0 -154.0,762.0Q-154.0,813.0 -107.0,813.0Q-86.0,813.0 -75.0,804.5Q-64.0,796.0 -60.0,775.0Z" transform="translate(347, 1005)"/>
<path d="M180.0,0.0L289.0,292.0Q225.0,312.0 177.5,353.0Q130.0,394.0 104.0,451.0Q78.0,508.0 78.0,575.0L78.0,636.0Q78.0,685.0 96.5,699.5Q115.0,714.0 146.0,714.0L532.0,714.0L399.0,355.0L488.0,355.0Q494.0,389.0 515.5,401.0Q537.0,413.0 583.0,413.0L782.0,413.0Q821.0,413.0 842.0,405.0Q863.0,397.0 871.0,376.0Q879.0,355.0 879.0,315.0L879.0,0.0L583.0,0.0Q544.0,0.0 523.0,8.5Q502.0,17.0 494.0,38.0Q486.0,59.0 486.0,98.0L486.0,276.0L392.0,276.0Q386.0,276.0 380.5,276.0Q375.0,276.0 370.0,277.0L267.0,0.0L180.0,0.0ZM316.0,365.0L417.0,635.0L204.0,635.0Q180.0,635.0 174.0,622.5Q168.0,610.0 168.0,563.0Q168.0,524.0 183.0,483.5Q198.0,443.0 231.0,411.5Q264.0,380.0 316.0,365.0ZM625.0,79.0L790.0,79.0L790.0,285.0Q790.0,314.0 780.0,324.0Q770.0,334.0 741.0,334.0L625.0,334.0Q595.0,334.0 585.5,324.0Q576.0,314.0 576.0,285.0L576.0,128.0Q576.0,99.0 585.5,89.0Q595.0,79.0 625.0,79.0Z" transform="translate(738, 793)"/>
<path d="M-653.0,775.0L96.0,775.0Q130.0,775.0 142.0,761.0Q154.0,747.0 154.0,722.0Q154.0,672.0 107.0,672.0Q66.0,672.0 60.0,710.0L-653.0,710.0L-653.0,775.0Z" transform="translate(1238, 1005)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1696 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M175.0,0.0Q131.0,0.0 110.0,16.5Q89.0,33.0 83.5,57.0Q78.0,81.0 78.0,104.0Q78.0,158.0 110.0,202.5Q142.0,247.0 196.0,275.0Q142.0,298.0 110.0,338.0Q78.0,378.0 78.0,432.0Q78.0,455.0 84.5,479.0Q91.0,503.0 110.0,519.5Q129.0,536.0 166.0,536.0L583.0,536.0Q627.0,536.0 638.5,516.0Q650.0,496.0 650.0,448.0L650.0,88.0Q650.0,40.0 638.5,20.0Q627.0,0.0 583.0,0.0L175.0,0.0ZM332.0,313.0L332.0,465.0L205.0,465.0Q174.0,465.0 168.5,452.5Q163.0,440.0 163.0,420.0Q163.0,372.0 205.0,344.5Q247.0,317.0 332.0,313.0ZM418.0,312.0L564.0,312.0L564.0,426.0Q564.0,452.0 556.5,458.5Q549.0,465.0 530.0,465.0L418.0,465.0L418.0,312.0ZM193.0,71.0L332.0,71.0L332.0,243.0Q250.0,237.0 206.5,200.5Q163.0,164.0 163.0,116.0Q163.0,97.0 168.0,84.0Q173.0,71.0 193.0,71.0ZM418.0,71.0L530.0,71.0Q549.0,71.0 556.5,78.0Q564.0,85.0 564.0,110.0L564.0,242.0L418.0,242.0L418.0,71.0Z" transform="translate(0, 793)"/>
<path d="M-60.0,775.0L653.0,775.0L653.0,710.0L-97.0,710.0Q-154.0,710.0 -154.0,762.0Q-154.0,813.0 -107.0,813.0Q-86.0,813.0 -75.0,804.5Q-64.0,796.0 -60.0,775.0Z" transform="translate(347, 1184)"/>
<path d="M180.0,0.0L289.0,292.0Q225.0,312.0 177.5,353.0Q130.0,394.0 104.0,451.0Q78.0,508.0 78.0,575.0L78.0,636.0Q78.0,685.0 96.5,699.5Q115.0,714.0 146.0,714.0L532.0,714.0L399.0,355.0L488.0,355.0Q494.0,389.0 515.5,401.0Q537.0,413.0 583.0,413.0L782.0,413.0Q821.0,413.0 842.0,405.0Q863.0,397.0 871.0,376.0Q879.0,355.0 879.0,315.0L879.0,0.0L583.0,0.0Q544.0,0.0 523.0,8.5Q502.0,17.0 494.0,38.0Q486.0,59.0 486.0,98.0L486.0,276.0L392.0,276.0Q386.0,276.0 380.5,276.0Q375.0,276.0 370.0,277.0L267.0,0.0L180.0,0.0ZM316.0,365.0L417.0,635.0L204.0,635.0Q180.0,635.0 174.0,622.5Q168.0,610.0 168.0,563.0Q168.0,524.0 183.0,483.5Q198.0,443.0 231.0,411.5Q264.0,380.0 316.0,365.0ZM625.0,79.0L790.0,79.0L790.0,285.0Q790.0,314.0 780.0,324.0Q770.0,334.0 741.0,334.0L625.0,334.0Q595.0,334.0 585.5,324.0Q576.0,314.0 576.0,285.0L576.0,128.0Q576.0,99.0 585.5,89.0Q595.0,79.0 625.0,79.0Z" transform="translate(738, 793)"/>
<path d="M-653.0,775.0L96.0,775.0Q130.0,775.0 142.0,761.0Q154.0,747.0 154.0,722.0Q154.0,672.0 107.0,672.0Q66.0,672.0 60.0,710.0L-653.0,710.0L-653.0,775.0Z" transform="translate(1238, 1182)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- gravecomb

	- tildecomb

	- u1E000

	- u1E001

	- u1E002

	- u1E003

	- u1E004

	- u1E005

	- u1E006

	- u1E008

	- u1E009

	- u1E00A

	- u1E00B

	- u1E00C

	- u1E00D

	- u1E00E

	- u1E00F

	- u1E010

	- u1E011

	- u1E012

	- u1E013

	- u1E014

	- u1E015

	- u1E016

	- u1E017

	- u1E018

	- u1E01B

	- u1E01C

	- u1E01D

	- u1E01E

	- u1E01F

	- u1E020

	- u1E021

	- u1E023

	- u1E024

	- u1E026

	- u1E027

	- u1E028

	- u1E02A

	- uni0302

	- uni0304

	- uni0305

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni0312

	- uni0326

	- uni0327

	- uni0328

	- uni0483

	- uni0484

	- uni0487

	- uniA66F

	- uniFE24

	- uniFE25

	- uniFE26

	- uniFE2E

	- uniFE2F [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, cherokee, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: math, malayalam, tifinagh, old-permic, canadian-aboriginal, tai-le, coptic, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+25CC DOTTED CIRCLE: try adding one of: duployan, hebrew, javanese, batak, brahmi, thaana, tamil, coptic, syriac, mahajani, tagbanwa, chakma, lao, hanifi-rohingya, math, sinhala, myanmar, tai-le, kharoshthi, tirhuta, lepcha, mandaic, devanagari, psalter-pahlavi, tibetan, yi, khudawadi, hanunoo, gurmukhi, tagalog, oriya, sundanese, tai-viet, tifinagh, nko, music, dogra, elbasan, caucasian-albanian, bhaiksuki, bengali, buginese, phags-pa, wancho, khojki, zanabazar-square, buhid, syloti-nagri, modi, kaithi, manichaean, mende-kikakui, takri, old-permic, cham, khmer, marchen, pahawh-hmong, adlam, kannada, meetei-mayek, new-tai-lue, limbu, sogdian, balinese, telugu, thai, grantha, soyombo, bassa-vah, osage, symbols, rejang, miao, malayalam, sharada, siddham, newa, gunjala-gondi, masaram-gondi, ahom, gujarati, mongolian, kayah-li
 * U+FE24 COMBINING MACRON LEFT HALF: try adding one of: coptic, caucasian-albanian
 * U+FE25 COMBINING MACRON RIGHT HALF: try adding one of: coptic, caucasian-albanian
 * U+FE26 COMBINING CONJOINING MACRON: try adding one of: coptic, caucasian-albanian

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `glagolitic`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
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
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: i̅ i҄ i҇ i꙯ i̦̅ i̦҄ i̦҇ i̦꙯ i̧̅ i̧҄ i̧҇ i̧꙯ j̅ j҄ j҇ j꙯ j̦̅ j̦҄ j̦҇ j̦꙯

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Navajo (Latn, 166,319 speakers), Igbo (Latn, 27,823,640 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Basaa (Latn, 332,940 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 4 | 5 | 118 | 7 | 115 | 0 |
| 0% | 2% | 2% | 47% | 3% | 46% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
