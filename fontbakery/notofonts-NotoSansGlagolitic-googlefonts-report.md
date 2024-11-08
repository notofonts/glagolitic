## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[8] NotoSansGlagolitic-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 299, but got 293 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check that texts shape as per expectation <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>qa/shaping_tests/glagolitic.json: Expected and actual shaping not matching</p>
<ul>
<li>
<p>Shaping did not match: ⱆ︮Ⰳ︯ (Issue #1)</p>
<pre><code>Expected: uni2C46=0+738|uniFE2E=0@-391,391+0|uni2C03=2+958|uniFE2F=2@-458,389+0
Got     : uni2C46=0+738|uniFE2E=0@-391,212+0|uni2C03=2+958|uniFE2F=2@-458,212+0
                                       ^^                                 ^^^
</code></pre>
<p>Got: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -293 1696 1362" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g79" d="M175.0,0.0Q131.0,0.0 110.0,16.5Q89.0,33.0 83.5,57.0Q78.0,81.0 78.0,104.0Q78.0,158.0 110.0,202.5Q142.0,247.0 196.0,275.0Q142.0,298.0 110.0,338.0Q78.0,378.0 78.0,432.0Q78.0,455.0 84.5,479.0Q91.0,503.0 110.0,519.5Q129.0,536.0 166.0,536.0L583.0,536.0Q627.0,536.0 638.5,516.0Q650.0,496.0 650.0,448.0L650.0,88.0Q650.0,40.0 638.5,20.0Q627.0,0.0 583.0,0.0L175.0,0.0ZM332.0,313.0L332.0,465.0L205.0,465.0Q174.0,465.0 168.5,452.5Q163.0,440.0 163.0,420.0Q163.0,372.0 205.0,344.5Q247.0,317.0 332.0,313.0ZM418.0,312.0L564.0,312.0L564.0,426.0Q564.0,452.0 556.5,458.5Q549.0,465.0 530.0,465.0L418.0,465.0L418.0,312.0ZM193.0,71.0L332.0,71.0L332.0,243.0Q250.0,237.0 206.5,200.5Q163.0,164.0 163.0,116.0Q163.0,97.0 168.0,84.0Q173.0,71.0 193.0,71.0ZM418.0,71.0L530.0,71.0Q549.0,71.0 556.5,78.0Q564.0,85.0 564.0,110.0L564.0,242.0L418.0,242.0L418.0,71.0Z"/> <path id="g146" d="M-60.0,775.0L653.0,775.0L653.0,710.0L-97.0,710.0Q-154.0,710.0 -154.0,762.0Q-154.0,813.0 -107.0,813.0Q-86.0,813.0 -75.0,804.5Q-64.0,796.0 -60.0,775.0Z"/> <path id="g12" d="M180.0,0.0L289.0,292.0Q225.0,312.0 177.5,353.0Q130.0,394.0 104.0,451.0Q78.0,508.0 78.0,575.0L78.0,636.0Q78.0,685.0 96.5,699.5Q115.0,714.0 146.0,714.0L532.0,714.0L399.0,355.0L488.0,355.0Q494.0,389.0 515.5,401.0Q537.0,413.0 583.0,413.0L782.0,413.0Q821.0,413.0 842.0,405.0Q863.0,397.0 871.0,376.0Q879.0,355.0 879.0,315.0L879.0,0.0L583.0,0.0Q544.0,0.0 523.0,8.5Q502.0,17.0 494.0,38.0Q486.0,59.0 486.0,98.0L486.0,276.0L392.0,276.0Q386.0,276.0 380.5,276.0Q375.0,276.0 370.0,277.0L267.0,0.0L180.0,0.0ZM316.0,365.0L417.0,635.0L204.0,635.0Q180.0,635.0 174.0,622.5Q168.0,610.0 168.0,563.0Q168.0,524.0 183.0,483.5Q198.0,443.0 231.0,411.5Q264.0,380.0 316.0,365.0ZM625.0,79.0L790.0,79.0L790.0,285.0Q790.0,314.0 780.0,324.0Q770.0,334.0 741.0,334.0L625.0,334.0Q595.0,334.0 585.5,324.0Q576.0,314.0 576.0,285.0L576.0,128.0Q576.0,99.0 585.5,89.0Q595.0,79.0 625.0,79.0Z"/> <path id="g147" d="M-653.0,775.0L96.0,775.0Q130.0,775.0 142.0,761.0Q154.0,747.0 154.0,722.0Q154.0,672.0 107.0,672.0Q66.0,672.0 60.0,710.0L-653.0,710.0L-653.0,775.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g79"/> </g> <g transform="translate(347,212)"> <use href="#g146"/> </g> <g transform="translate(738,0)"> <use href="#g12"/> </g> <g transform="translate(1238,212)"> <use href="#g147"/> </g> </svg>  Expected: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -293 1696 1497" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g79" d="M175.0,0.0Q131.0,0.0 110.0,16.5Q89.0,33.0 83.5,57.0Q78.0,81.0 78.0,104.0Q78.0,158.0 110.0,202.5Q142.0,247.0 196.0,275.0Q142.0,298.0 110.0,338.0Q78.0,378.0 78.0,432.0Q78.0,455.0 84.5,479.0Q91.0,503.0 110.0,519.5Q129.0,536.0 166.0,536.0L583.0,536.0Q627.0,536.0 638.5,516.0Q650.0,496.0 650.0,448.0L650.0,88.0Q650.0,40.0 638.5,20.0Q627.0,0.0 583.0,0.0L175.0,0.0ZM332.0,313.0L332.0,465.0L205.0,465.0Q174.0,465.0 168.5,452.5Q163.0,440.0 163.0,420.0Q163.0,372.0 205.0,344.5Q247.0,317.0 332.0,313.0ZM418.0,312.0L564.0,312.0L564.0,426.0Q564.0,452.0 556.5,458.5Q549.0,465.0 530.0,465.0L418.0,465.0L418.0,312.0ZM193.0,71.0L332.0,71.0L332.0,243.0Q250.0,237.0 206.5,200.5Q163.0,164.0 163.0,116.0Q163.0,97.0 168.0,84.0Q173.0,71.0 193.0,71.0ZM418.0,71.0L530.0,71.0Q549.0,71.0 556.5,78.0Q564.0,85.0 564.0,110.0L564.0,242.0L418.0,242.0L418.0,71.0Z"/> <path id="g146" d="M-60.0,775.0L653.0,775.0L653.0,710.0L-97.0,710.0Q-154.0,710.0 -154.0,762.0Q-154.0,813.0 -107.0,813.0Q-86.0,813.0 -75.0,804.5Q-64.0,796.0 -60.0,775.0Z"/> <path id="g12" d="M180.0,0.0L289.0,292.0Q225.0,312.0 177.5,353.0Q130.0,394.0 104.0,451.0Q78.0,508.0 78.0,575.0L78.0,636.0Q78.0,685.0 96.5,699.5Q115.0,714.0 146.0,714.0L532.0,714.0L399.0,355.0L488.0,355.0Q494.0,389.0 515.5,401.0Q537.0,413.0 583.0,413.0L782.0,413.0Q821.0,413.0 842.0,405.0Q863.0,397.0 871.0,376.0Q879.0,355.0 879.0,315.0L879.0,0.0L583.0,0.0Q544.0,0.0 523.0,8.5Q502.0,17.0 494.0,38.0Q486.0,59.0 486.0,98.0L486.0,276.0L392.0,276.0Q386.0,276.0 380.5,276.0Q375.0,276.0 370.0,277.0L267.0,0.0L180.0,0.0ZM316.0,365.0L417.0,635.0L204.0,635.0Q180.0,635.0 174.0,622.5Q168.0,610.0 168.0,563.0Q168.0,524.0 183.0,483.5Q198.0,443.0 231.0,411.5Q264.0,380.0 316.0,365.0ZM625.0,79.0L790.0,79.0L790.0,285.0Q790.0,314.0 780.0,324.0Q770.0,334.0 741.0,334.0L625.0,334.0Q595.0,334.0 585.5,324.0Q576.0,314.0 576.0,285.0L576.0,128.0Q576.0,99.0 585.5,89.0Q595.0,79.0 625.0,79.0Z"/> <path id="g147" d="M-653.0,775.0L96.0,775.0Q130.0,775.0 142.0,761.0Q154.0,747.0 154.0,722.0Q154.0,672.0 107.0,672.0Q66.0,672.0 60.0,710.0L-653.0,710.0L-653.0,775.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g79"/> </g> <g transform="translate(347,391)"> <use href="#g146"/> </g> <g transform="translate(738,0)"> <use href="#g12"/> </g> <g transform="translate(1238,389)"> <use href="#g147"/> </g> </svg></p>
</li>
</ul>
 [code: shaping-regression]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansGlagolitic/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: syriac, math, duployan, todhri, tai-le, canadian-aboriginal, tifinagh, old-permic, coptic, hebrew, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: buginese, kannada, tai-tham, buhid, tai-le, batak, meetei-mayek, yi, masaram-gondi, kharoshthi, grantha, math, hanunoo, manichaean, new-tai-lue, devanagari, tirhuta, soyombo, adlam, warang-citi, tifinagh, symbols, psalter-pahlavi, balinese, mende-kikakui, duployan, marchen, dogra, sogdian, lepcha, siddham, myanmar, zanabazar-square, bhaiksuki, tagbanwa, sundanese, gurmukhi, wancho, mahajani, telugu, coptic, hanifi-rohingya, bengali, lao, mongolian, nko, ahom, cham, oriya, khmer, khudawadi, kayah-li, brahmi, newa, armenian, saurashtra, canadian-aboriginal, sinhala, miao, gunjala-gondi, syloti-nagri, thai, pahawh-hmong, syriac, thaana, khojki, tibetan, caucasian-albanian, gujarati, takri, hebrew, bassa-vah, osage, sharada, elbasan, music, tamil, tai-viet, limbu, chakma, old-permic, phags-pa, malayalam, mandaic, modi, tagalog, rejang, kaithi, javanese</li>
<li>U+FE24 COMBINING MACRON LEFT HALF: try adding one of: coptic, caucasian-albanian</li>
<li>U+FE25 COMBINING MACRON RIGHT HALF: try adding one of: coptic, caucasian-albanian</li>
<li>U+FE26 COMBINING CONJOINING MACRON: try adding one of: coptic, caucasian-albanian</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>glagolitic</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̅ i҄ i҇ i꙯ i̦̅ i̦҄ i̦҇ i̦꙯ i̧̅ i̧҄ i̧҇ i̧꙯ j̅ j҄ j҇ j꙯ j̦̅ j̦҄ j̦҇ j̦꙯</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ekpeye (Latn, 226,000 speakers), Ma’di (Latn, 584,000 speakers), Lugbara (Latn, 2,200,000 speakers), Makaa (Latn, 221,000 speakers), Yala (Latn, 200,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ejagham (Latn, 120,000 speakers), Mango (Latn, 77,000 speakers), Mfumte (Latn, 79,000 speakers), South Central Banda (Latn, 244,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Avokaya (Latn, 100,000 speakers), Dan (Latn, 1,099,244 speakers), Han (Latn, 6 speakers), Cicipu (Latn, 44,000 speakers), Nzakara (Latn, 50,000 speakers), Gulay (Latn, 250,478 speakers), Dii (Latn, 71,000 speakers), Aghem (Latn, 38,843 speakers), Fur (Latn, 1,230,163 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Igbo (Latn, 27,823,640 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Koonzime (Latn, 40,000 speakers), Sar (Latn, 500,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Basaa (Latn, 332,940 speakers), Ebira (Latn, 2,200,000 speakers), Heiltsuk (Latn, 300 speakers), Mundani (Latn, 34,000 speakers), Kom (Latn, 360,685 speakers), Nateni (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Southern Kisi (Latn, 360,000 speakers), Kaska (Latn, 125 speakers), Teke-Ebo (Latn, 260,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Vute (Latn, 21,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 3 | 5 | 116 | 6 | 121 | 0 | 
| 0% | 0% | 1% | 2% | 46% | 2% | 48% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
