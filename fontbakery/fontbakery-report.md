## FontBakery report

fontbakery version: 0.13.0







## Check results



<details><summary>[19] Martel[wght].ttf</summary>
<div>
<details>
    <summary>💥 <b>ERROR</b> Check METADATA.pb includes production subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-includes-production-subsets">googlefonts/metadata/includes_production_subsets</a></summary>
    <div>







* 💥 **ERROR** <p>Expecting value: line 1 column 1 (char 0)</p>
 [code: error]



</div>
</details>

<details>
    <summary>💥 <b>ERROR</b> Check if the axes match between the font and the Google Fonts version. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-axes-match">googlefonts/axes_match</a></summary>
    <div>







* 💥 **ERROR** <p>Expecting value: line 1 column 1 (char 0)</p>
 [code: error]



</div>
</details>

<details>
    <summary>💥 <b>ERROR</b> Check font follows the Google Fonts CJK vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-cjk-vertical-metrics">googlefonts/cjk_vertical_metrics</a></summary>
    <div>







* 💥 **ERROR** <p>Expecting value: line 1 column 1 (char 0)</p>
 [code: error]



</div>
</details>

<details>
    <summary>💥 <b>ERROR</b> Check if the vertical metrics of a CJK family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-cjk-vertical-metrics-regressions">googlefonts/cjk_vertical_metrics_regressions</a></summary>
    <div>







* 💥 **ERROR** <p>Expecting value: line 1 column 1 (char 0)</p>
 [code: error]



</div>
</details>

<details>
    <summary>💥 <b>ERROR</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics">googlefonts/vertical_metrics</a></summary>
    <div>







* 💥 **ERROR** <p>Expecting value: line 1 column 1 (char 0)</p>
 [code: error]



</div>
</details>

<details>
    <summary>💥 <b>ERROR</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics-regressions">googlefonts/vertical_metrics_regressions</a></summary>
    <div>







* 💥 **ERROR** <p>Expecting value: line 1 column 1 (char 0)</p>
 [code: error]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Validates subfamilyNameID and postScriptNameID for the default instance record <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-varfont-valid-default-instance-nameids">opentype/varfont/valid_default_instance_nameids</a></summary>
    <div>







* 🔥 **FAIL** <p>'Medium' instance has the same coordinates as the default instance; its subfamily name should be 'Regular'.</p>
<p>Note: If the default instance really is meant to be called 'Medium', the problem may be that the font lacks NameID 17, which should probably be present and set to 'Medium'.</p>
 [code: invalid-default-instance-subfamily-name]



* 🔥 **FAIL** <p>'Medium' instance has the same coordinates as the default instance; its postscript name should be 'Martel-Regular', instead of 'Martel-Medium'.</p>
 [code: invalid-default-instance-postscript-name]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#case-mapping">case_mapping</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+1E0C: LATIN CAPITAL LETTER D WITH DOT BELOW</td>
<td align="left">U+1E0D: LATIN SMALL LETTER D WITH DOT BELOW</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-copyright">googlefonts/font_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright (c) 2015 Dan Reynolds. Copyright (c) 2010-2015, Sorkin Type Co (<a href="http://www.sorkintype.com">www.sorkintype.com</a>) with Reserved Font Name 'Merriweather'&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-license-OFL-copyright">googlefonts/license/OFL_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-names">googlefonts/font_names</a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left"><strong>Martel</strong></td>
<td align="left"><strong>Martel Medium</strong></td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Regular</td>
<td align="left">Regular</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left"><strong>Martel Regular</strong></td>
<td align="left"><strong>Martel Medium</strong></td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left"><strong>Martel-Regular</strong></td>
<td align="left"><strong>Martel-Medium</strong></td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left"><strong>N/A</strong></td>
<td align="left"><strong>Martel</strong></td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left"><strong>N/A</strong></td>
<td align="left"><strong>Medium</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#interpolation-issues">interpolation_issues</a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 point 6 in glyph 'uni0925094D0930' has a kink between location wght=200 and location wght=900

- Contour 3 start point differs in glyph 'uni091B' between location wght=500 and location wght=200

- Contour 3 in glyph 'uni091B': becomes underweight between wght=500 and wght=200.

- Contour 2 point 13 in glyph 'oe' has a kink between location wght=200 and location wght=900

- Contour 0 point 6 in glyph 'uni0935094D0930' has a kink between location wght=200 and location wght=900

- Contour 0 start point differs in glyph 'dotaccent.cap' between location wght=500 and location wght=200

- Contour 0 in glyph 'dotaccent.cap': becomes underweight between wght=500 and wght=200.

- Contour 0 start point differs in glyph 'dotaccent.cap' between location wght=200 and location wght=900

- Contour 0 in glyph 'dotaccent.cap': becomes underweight between wght=200 and wght=900.

- Contour 4 start point differs in glyph 'uni091B094D0930' between location wght=500 and location wght=200

- Contour 4 in glyph 'uni091B094D0930': becomes underweight between wght=500 and wght=200.

- Contour 0 point 44 in glyph 'y' has a kink between location wght=200 and location wght=900
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 606 among a set of 4 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 620:
plus, plusminus</p>
<p>Width = 647:
less, greater</p>
<p>Width = 602:
logicalnot</p>
<p>Width = 625:
divide</p>
<p>Width = 626:
approxequal</p>
<p>Width = 646:
greaterequal, lessequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- DC1

- DC2

- DC3

- DC4

- DLE

- HT

- LF

- NULL

- RS

- US

- acute.cap

- breve.cap

- caron.cap

- circumflex.cap

- dieresis.cap

- dotaccent.cap

- grave.cap

- i.loclTRK

- ring.cap

- space.copy_one

- tilde.cap

- uni004A0301

- uni006A0301

- uni013B.loclMAH

- uni013C.loclMAH

- uni0145.loclMAH

- uni0146.loclMAH

- uni030C.alt

- uni0941.alt

- uni0942.alt
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+007F : try adding symbols</li>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, cherokee, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, syriac, hebrew, old-permic, canadian-aboriginal, duployan, malayalam, math, tai-le, todhri, tifinagh</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0313 COMBINING COMMA ABOVE: try adding one of: old-permic, todhri</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>devanagari</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ, Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ŋ, ŋ, Ŧ, ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̓ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ị̓ i̦̓ i̧̓ j̓ j̣̓ j̦̓ j̧̓ j̨̓ į̆ į̇ į̈ į̊ į̋ į̒ į̓ į̣̀ į̣́ į̣̂ į̣̃ į̣̄</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Teke-Ebo (Latn, 260,000 speakers), Aghem (Latn, 38,843 speakers), Mundani (Latn, 34,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Basaa (Latn, 332,940 speakers), Mfumte (Latn, 79,000 speakers), Mango (Latn, 77,000 speakers), Ejagham (Latn, 120,000 speakers), Keliko (Latn, 63,000 speakers), Nateni (Latn, 100,000 speakers), Han (Latn, 6 speakers), Ekpeye (Latn, 226,000 speakers), Southern Kisi (Latn, 360,000 speakers), Yala (Latn, 200,000 speakers), Lugbara (Latn, 2,200,000 speakers), Heiltsuk (Latn, 300 speakers), Dan (Latn, 1,099,244 speakers), Kaska (Latn, 125 speakers), Gulay (Latn, 250,478 speakers), Western Krahn (Latn, 97,800 speakers), Koonzime (Latn, 40,000 speakers), Longto (Latn, 5,000 speakers), Vute (Latn, 21,000 speakers), Igbo (Latn, 27,823,640 speakers), Southern Tutchone (Latn, 65 speakers), Ma’di (Latn, 584,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Northern Tutchone (Latn, 85 speakers), Bafut (Latn, 158,146 speakers), Fur (Latn, 1,230,163 speakers), Cicipu (Latn, 44,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), South Central Banda (Latn, 244,000 speakers), Abua (Latn, 25,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Dii (Latn, 71,000 speakers), Makaa (Latn, 221,000 speakers), Ebira (Latn, 2,200,000 speakers), Avokaya (Latn, 100,000 speakers), Nzakara (Latn, 50,000 speakers), Kom (Latn, 360,685 speakers), Ikwere (Latn, 717,000 speakers), Navajo (Latn, 166,319 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Zapotec (Latn, 490,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'toff' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 6 | 0 | 5 | 8 | 83 | 9 | 127 | 0 | 
| 3% | 0% | 2% | 3% | 35% | 4% | 53% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
