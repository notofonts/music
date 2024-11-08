## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[10] NotoMusic-Regular.ttf</summary>
<div>
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
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+1D165, U+1D166, U+1D16D, U+1D16E, U+1D16F, U+1D170, U+1D171 and U+1D172</p>
 [code: non-mark-chars]



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







* ⚠️ **WARN** <p>Family metadata at fonts/NotoMusic/googlefonts/ttf does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, malayalam, hebrew, tai-le, canadian-aboriginal, syriac, coptic, duployan, tifinagh, math, todhri</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>music</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Kpelle, Guinea (Latn, 622,000 speakers), Avokaya (Latn, 100,000 speakers), Nzakara (Latn, 50,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Ejagham (Latn, 120,000 speakers), Kaska (Latn, 125 speakers), Mango (Latn, 77,000 speakers), Kom (Latn, 360,685 speakers), Nateni (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ekpeye (Latn, 226,000 speakers), Bafut (Latn, 158,146 speakers), Ebira (Latn, 2,200,000 speakers), Fur (Latn, 1,230,163 speakers), Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Makaa (Latn, 221,000 speakers), Igbo (Latn, 27,823,640 speakers), Mfumte (Latn, 79,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Heiltsuk (Latn, 300 speakers), Dii (Latn, 71,000 speakers), Koonzime (Latn, 40,000 speakers), Han (Latn, 6 speakers), Basaa (Latn, 332,940 speakers), Bete-Bendi (Latn, 100,000 speakers), Mundani (Latn, 34,000 speakers), Lugbara (Latn, 2,200,000 speakers), Vute (Latn, 21,000 speakers), Zapotec (Latn, 490,000 speakers), Cicipu (Latn, 44,000 speakers), Aghem (Latn, 38,843 speakers), Dan (Latn, 1,099,244 speakers), Ma’di (Latn, 584,000 speakers), South Central Banda (Latn, 244,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* u1D06D (U+1D06D): L&lt;&lt;426.0,-7.0&gt;--&lt;408.0,-4.0&gt;&gt; -&gt; L&lt;&lt;408.0,-4.0&gt;--&lt;391.0,0.0&gt;&gt;

* u1D071 (U+1D071): L&lt;&lt;319.0,73.0&gt;--&lt;307.0,73.0&gt;&gt; -&gt; L&lt;&lt;307.0,73.0&gt;--&lt;266.0,74.0&gt;&gt;

* u1D075 (U+1D075): L&lt;&lt;163.0,50.0&gt;--&lt;149.0,47.0&gt;&gt; -&gt; L&lt;&lt;149.0,47.0&gt;--&lt;128.0,44.0&gt;&gt;

* u1D077 (U+1D077): L&lt;&lt;185.0,121.0&gt;--&lt;133.0,121.0&gt;&gt; -&gt; L&lt;&lt;133.0,121.0&gt;--&lt;103.0,122.0&gt;&gt;

* u1D077 (U+1D077): L&lt;&lt;322.0,114.0&gt;--&lt;185.0,121.0&gt;&gt; -&gt; L&lt;&lt;185.0,121.0&gt;--&lt;133.0,121.0&gt;&gt;

* u1D09F (U+1D09F): L&lt;&lt;215.0,360.0&gt;--&lt;216.0,349.0&gt;&gt; -&gt; L&lt;&lt;216.0,349.0&gt;--&lt;216.0,346.0&gt;&gt;

* u1D0AA (U+1D0AA): L&lt;&lt;325.0,276.0&gt;--&lt;355.0,273.0&gt;&gt; -&gt; L&lt;&lt;355.0,273.0&gt;--&lt;452.0,258.0&gt;&gt;

* u1D0AA (U+1D0AA): L&lt;&lt;452.0,258.0&gt;--&lt;469.0,258.0&gt;&gt; -&gt; L&lt;&lt;469.0,258.0&gt;--&lt;491.0,260.0&gt;&gt;

* u1D0B5 (U+1D0B5): L&lt;&lt;106.0,131.0&gt;--&lt;106.0,134.0&gt;&gt; -&gt; L&lt;&lt;106.0,134.0&gt;--&lt;110.0,226.0&gt;&gt;

* u1D1E9 (U+1D1E9): L&lt;&lt;226.0,216.0&gt;--&lt;275.0,179.0&gt;&gt; -&gt; L&lt;&lt;275.0,179.0&gt;--&lt;314.0,150.0&gt;&gt;

* u1D1E9 (U+1D1E9): L&lt;&lt;314.0,150.0&gt;--&lt;275.0,121.0&gt;&gt; -&gt; L&lt;&lt;275.0,121.0&gt;--&lt;226.0,84.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* u1D050 (U+1D050): B&lt;&lt;315.5,514.0&gt;-&lt;262.0,490.0&gt;-&lt;197.0,485.0&gt;&gt;/B&lt;&lt;197.0,485.0&gt;-&lt;228.0,485.0&gt;-&lt;253.0,474.5&gt;&gt; = 4.398705354995508

* u1D05E (U+1D05E): B&lt;&lt;311.0,496.0&gt;-&lt;311.0,518.0&gt;-&lt;331.0,521.0&gt;&gt;/L&lt;&lt;331.0,521.0&gt;--&lt;113.0,521.0&gt;&gt; = 8.530765609948139

* u1D061 (U+1D061): B&lt;&lt;287.0,137.0&gt;-&lt;287.0,117.0&gt;-&lt;274.0,107.0&gt;&gt;/B&lt;&lt;274.0,107.0&gt;-&lt;356.0,156.0&gt;-&lt;456.0,156.0&gt;&gt; = 6.707700340478021

* u1D06B (U+1D06B): L&lt;&lt;144.0,108.0&gt;--&lt;103.0,110.0&gt;&gt;/B&lt;&lt;103.0,110.0&gt;-&lt;193.0,118.0&gt;-&lt;257.5,146.5&gt;&gt; = 7.87231022572785

* u1D078 (U+1D078): B&lt;&lt;371.0,114.5&gt;-&lt;380.0,123.0&gt;-&lt;388.0,124.0&gt;&gt;/L&lt;&lt;388.0,124.0&gt;--&lt;322.0,124.0&gt;&gt; = 7.125016348901757

* u1D079 (U+1D079): B&lt;&lt;336.0,101.0&gt;-&lt;336.0,120.0&gt;-&lt;360.0,124.0&gt;&gt;/L&lt;&lt;360.0,124.0&gt;--&lt;288.0,124.0&gt;&gt; = 9.462322208025613

* u1D09E (U+1D09E): B&lt;&lt;310.0,331.0&gt;-&lt;277.0,331.0&gt;-&lt;274.0,372.0&gt;&gt;/B&lt;&lt;274.0,372.0&gt;-&lt;270.0,338.0&gt;-&lt;240.0,338.0&gt;&gt; = 10.894752932875335

* u1D0A3 (U+1D0A3): L&lt;&lt;212.0,210.0&gt;--&lt;215.0,222.0&gt;&gt;/B&lt;&lt;215.0,222.0&gt;-&lt;196.0,180.0&gt;-&lt;142.0,180.0&gt;&gt; = 10.304846468766044

* u1D0AE (U+1D0AE): B&lt;&lt;266.5,445.0&gt;-&lt;253.0,438.0&gt;-&lt;226.0,434.0&gt;&gt;/B&lt;&lt;226.0,434.0&gt;-&lt;237.0,433.0&gt;-&lt;244.5,430.0&gt;&gt; = 13.621397929215435

* u1D0B2 (U+1D0B2): B&lt;&lt;409.0,203.0&gt;-&lt;409.0,217.0&gt;-&lt;416.0,242.0&gt;&gt;/B&lt;&lt;416.0,242.0&gt;-&lt;403.0,206.0&gt;-&lt;355.0,206.0&gt;&gt; = 4.212967912112212

* u1D0B6 (U+1D0B6): B&lt;&lt;162.0,578.0&gt;-&lt;184.0,590.0&gt;-&lt;196.0,593.0&gt;&gt;/L&lt;&lt;196.0,593.0&gt;--&lt;185.0,593.0&gt;&gt; = 14.036243467926457

* u1D0BC (U+1D0BC): B&lt;&lt;334.0,95.0&gt;-&lt;334.0,118.0&gt;-&lt;360.0,124.0&gt;&gt;/L&lt;&lt;360.0,124.0&gt;--&lt;288.0,124.0&gt;&gt; = 12.994616791916512

* u1D0C0 (U+1D0C0): B&lt;&lt;162.0,578.0&gt;-&lt;184.0,590.0&gt;-&lt;196.0,593.0&gt;&gt;/L&lt;&lt;196.0,593.0&gt;--&lt;185.0,593.0&gt;&gt; = 14.036243467926457

* u1D15C (U+1D15C): B&lt;&lt;180.0,66.5&gt;-&lt;151.0,95.0&gt;-&lt;150.0,135.0&gt;&gt;/L&lt;&lt;150.0,135.0&gt;--&lt;150.0,-31.0&gt;&gt; = 1.4320961841645452

* u1D15C (U+1D15C): B&lt;&lt;534.0,202.0&gt;-&lt;563.0,174.0&gt;-&lt;564.0,135.0&gt;&gt;/L&lt;&lt;564.0,135.0&gt;--&lt;564.0,301.0&gt;&gt; = 1.4688007143857

* u1D15C (U+1D15C): L&lt;&lt;150.0,301.0&gt;--&lt;150.0,141.0&gt;&gt;/B&lt;&lt;150.0,141.0&gt;-&lt;152.0,178.0&gt;-&lt;180.5,204.5&gt;&gt; = 3.094058058917113

* u1D15C (U+1D15C): L&lt;&lt;564.0,-31.0&gt;--&lt;564.0,128.0&gt;&gt;/B&lt;&lt;564.0,128.0&gt;-&lt;562.0,90.0&gt;-&lt;532.5,63.0&gt;&gt; = 3.012787504183286
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* u1D096 (U+1D096): L&lt;&lt;485.0,581.0&gt;--&lt;362.0,582.0&gt;&gt;

* u1D0A1 (U+1D0A1): L&lt;&lt;518.0,484.0&gt;--&lt;396.0,485.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



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
| 0 | 0 | 1 | 9 | 117 | 6 | 118 | 0 | 
| 0% | 0% | 0% | 4% | 47% | 2% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
