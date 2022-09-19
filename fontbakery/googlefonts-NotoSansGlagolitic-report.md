## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[6] NotoSansGlagolitic-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


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



<pre>Got     : uni2C46=0+738|uniFE2E=0+0|uni2C03=2+958|uniFE2F=2+0</pre>



<pre>                                 +++++++++                          +++++++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1696 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M175.0,0.0Q131.0,0.0 110.0,16.5Q89.0,33.0 83.5,57.0Q78.0,81.0 78.0,104.0Q78.0,158.0 110.0,202.5Q142.0,247.0 196.0,275.0Q142.0,298.0 110.0,338.0Q78.0,378.0 78.0,432.0Q78.0,455.0 84.5,479.0Q91.0,503.0 110.0,519.5Q129.0,536.0 166.0,536.0L583.0,536.0Q627.0,536.0 638.5,516.0Q650.0,496.0 650.0,448.0L650.0,88.0Q650.0,40.0 638.5,20.0Q627.0,0.0 583.0,0.0L175.0,0.0ZM332.0,313.0L332.0,465.0L205.0,465.0Q174.0,465.0 168.5,452.5Q163.0,440.0 163.0,420.0Q163.0,372.0 205.0,344.5Q247.0,317.0 332.0,313.0ZM418.0,312.0L564.0,312.0L564.0,426.0Q564.0,452.0 556.5,458.5Q549.0,465.0 530.0,465.0L418.0,465.0L418.0,312.0ZM193.0,71.0L332.0,71.0L332.0,243.0Q250.0,237.0 206.5,200.5Q163.0,164.0 163.0,116.0Q163.0,97.0 168.0,84.0Q173.0,71.0 193.0,71.0ZM418.0,71.0L530.0,71.0Q549.0,71.0 556.5,78.0Q564.0,85.0 564.0,110.0L564.0,242.0L418.0,242.0L418.0,71.0Z"  transform="translate(0, 793)"/>
<path d="M-60.0,605.0L653.0,605.0L653.0,540.0L-97.0,540.0Q-154.0,540.0 -154.0,592.0Q-154.0,643.0 -107.0,643.0Q-86.0,643.0 -75.0,634.5Q-64.0,626.0 -60.0,605.0Z"  transform="translate(738, 793)"/>
<path d="M180.0,0.0L289.0,292.0Q225.0,312.0 177.5,353.0Q130.0,394.0 104.0,451.0Q78.0,508.0 78.0,575.0L78.0,636.0Q78.0,685.0 96.5,699.5Q115.0,714.0 146.0,714.0L532.0,714.0L399.0,355.0L488.0,355.0Q494.0,389.0 515.5,401.0Q537.0,413.0 583.0,413.0L782.0,413.0Q821.0,413.0 842.0,405.0Q863.0,397.0 871.0,376.0Q879.0,355.0 879.0,315.0L879.0,0.0L583.0,0.0Q544.0,0.0 523.0,8.5Q502.0,17.0 494.0,38.0Q486.0,59.0 486.0,98.0L486.0,276.0L392.0,276.0Q386.0,276.0 380.5,276.0Q375.0,276.0 370.0,277.0L267.0,0.0L180.0,0.0ZM316.0,365.0L417.0,635.0L204.0,635.0Q180.0,635.0 174.0,622.5Q168.0,610.0 168.0,563.0Q168.0,524.0 183.0,483.5Q198.0,443.0 231.0,411.5Q264.0,380.0 316.0,365.0ZM625.0,79.0L790.0,79.0L790.0,285.0Q790.0,314.0 780.0,324.0Q770.0,334.0 741.0,334.0L625.0,334.0Q595.0,334.0 585.5,324.0Q576.0,314.0 576.0,285.0L576.0,128.0Q576.0,99.0 585.5,89.0Q595.0,79.0 625.0,79.0Z"  transform="translate(738, 793)"/>
<path d="M-653.0,605.0L96.0,605.0Q130.0,605.0 142.0,591.0Q154.0,577.0 154.0,552.0Q154.0,502.0 107.0,502.0Q66.0,502.0 60.0,540.0L-653.0,540.0L-653.0,605.0Z"  transform="translate(1696, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1696 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M175.0,0.0Q131.0,0.0 110.0,16.5Q89.0,33.0 83.5,57.0Q78.0,81.0 78.0,104.0Q78.0,158.0 110.0,202.5Q142.0,247.0 196.0,275.0Q142.0,298.0 110.0,338.0Q78.0,378.0 78.0,432.0Q78.0,455.0 84.5,479.0Q91.0,503.0 110.0,519.5Q129.0,536.0 166.0,536.0L583.0,536.0Q627.0,536.0 638.5,516.0Q650.0,496.0 650.0,448.0L650.0,88.0Q650.0,40.0 638.5,20.0Q627.0,0.0 583.0,0.0L175.0,0.0ZM332.0,313.0L332.0,465.0L205.0,465.0Q174.0,465.0 168.5,452.5Q163.0,440.0 163.0,420.0Q163.0,372.0 205.0,344.5Q247.0,317.0 332.0,313.0ZM418.0,312.0L564.0,312.0L564.0,426.0Q564.0,452.0 556.5,458.5Q549.0,465.0 530.0,465.0L418.0,465.0L418.0,312.0ZM193.0,71.0L332.0,71.0L332.0,243.0Q250.0,237.0 206.5,200.5Q163.0,164.0 163.0,116.0Q163.0,97.0 168.0,84.0Q173.0,71.0 193.0,71.0ZM418.0,71.0L530.0,71.0Q549.0,71.0 556.5,78.0Q564.0,85.0 564.0,110.0L564.0,242.0L418.0,242.0L418.0,71.0Z"  transform="translate(0, 793)"/>
<path d="M-60.0,605.0L653.0,605.0L653.0,540.0L-97.0,540.0Q-154.0,540.0 -154.0,592.0Q-154.0,643.0 -107.0,643.0Q-86.0,643.0 -75.0,634.5Q-64.0,626.0 -60.0,605.0Z"  transform="translate(347, 1184)"/>
<path d="M180.0,0.0L289.0,292.0Q225.0,312.0 177.5,353.0Q130.0,394.0 104.0,451.0Q78.0,508.0 78.0,575.0L78.0,636.0Q78.0,685.0 96.5,699.5Q115.0,714.0 146.0,714.0L532.0,714.0L399.0,355.0L488.0,355.0Q494.0,389.0 515.5,401.0Q537.0,413.0 583.0,413.0L782.0,413.0Q821.0,413.0 842.0,405.0Q863.0,397.0 871.0,376.0Q879.0,355.0 879.0,315.0L879.0,0.0L583.0,0.0Q544.0,0.0 523.0,8.5Q502.0,17.0 494.0,38.0Q486.0,59.0 486.0,98.0L486.0,276.0L392.0,276.0Q386.0,276.0 380.5,276.0Q375.0,276.0 370.0,277.0L267.0,0.0L180.0,0.0ZM316.0,365.0L417.0,635.0L204.0,635.0Q180.0,635.0 174.0,622.5Q168.0,610.0 168.0,563.0Q168.0,524.0 183.0,483.5Q198.0,443.0 231.0,411.5Q264.0,380.0 316.0,365.0ZM625.0,79.0L790.0,79.0L790.0,285.0Q790.0,314.0 780.0,324.0Q770.0,334.0 741.0,334.0L625.0,334.0Q595.0,334.0 585.5,324.0Q576.0,314.0 576.0,285.0L576.0,128.0Q576.0,99.0 585.5,89.0Q595.0,79.0 625.0,79.0Z"  transform="translate(738, 793)"/>
<path d="M-653.0,605.0L96.0,605.0Q130.0,605.0 142.0,591.0Q154.0,577.0 154.0,552.0Q154.0,502.0 107.0,502.0Q66.0,502.0 60.0,540.0L-653.0,540.0L-653.0,605.0Z"  transform="translate(1238, 1182)"/>
</svg>


</div> [code: shaping-regression]
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

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 tildecomb (U+0303), u1E000 (U+1E000), u1E001 (U+1E001), u1E002 (U+1E002), u1E003 (U+1E003), u1E004 (U+1E004), u1E005 (U+1E005), u1E006 (U+1E006), u1E008 (U+1E008), u1E009 (U+1E009) and 39 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 5 | 110 | 7 | 104 | 0 |
| 0% | 0% | 2% | 48% | 3% | 46% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
