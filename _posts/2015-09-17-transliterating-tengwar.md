---
layout: post
title: "Transliterating Tengwar"
date: 2015-09-17
categories: projects
hieroglyph: "&#x133DF;"
---
<h3 class="tengwar" style="text-align: center; margin-bottom: 25px;"><i>175#8j1T7F1Eb% 1b$y6E</i></h3>

<script>
$("<link />", {
    'rel': 'stylesheet',
    'href': '/assets/fonts.css'
  }).appendTo('head');
</script>

<p><a href="https://en.wikipedia.org/wiki/Tengwar"><b>Tengwar</b></a> is a writing system invented by J.R.R. Tolkien for use by the elves of Middle-Earth. Lately, I&#8217;ve learned how to write in Tengwar – not by learning any Elvish language, but by learning how to transliterate <i>English</i> into Tengwar using the instructions found in the <a href="http://www.starchamber.com/paracelsus/elvish/tengwar-textbook.pdf">Tengwar Textbook</a>.</p>
<p class="tengwar"><a href="https://en.wikipedia.org/wiki/Tengwar"><b>1b$y6E</b></a> iG `C y71Tb% 88Ú1t$ 5%r5$12$ w`Û s-6-6- 1j^z`B5$ e6Y iJO w`Û @ j$rO_ W t2%2jO\`V6E3- j1Ej$`Û· `Br`V j`V6E52$ 9yY 1`N y71TO 5% 1b$y6E  51Y w`Û j`V6E5b% 5#`Û j$rdT jb#`Ms#O· w1U w`Û j`V6E5b% 9yY 1`N 175#8j1T7F1EO b$jdT 5%1`N 1b$y6E iJb% @ 5%817zJ1`B5^_ e`N5&2 5% @ <a href="http://www.starchamber.com/paracelsus/elvish/tengwar-textbook.pdf">1b$y6E 1zFæ1w`NzH</a>-</p>

<p>I&#8217;ve found this writing system to be useful for writing down small notes-to-self, and I&#8217;ve become quite good at writing it.</p>
<p class="tengwar">`Br`V e`N5&2 4iG y71Tb% 88Ú1t$ 1`N w`V iJeFj& e6Y y71Tb% 2yY5 8tj#j 51YO_\1`N\8j$e· 5#2 `Br`V wzFt^O z`M1TO x`N2^ 1E y71Tb% 1T-
</p>

<p><img src="/images/elvish-stickies.png" style="display: block; margin: 0 auto;" alt="" height="434" /></p>

<p>Problem is, I&#8217;m still no good at <i>reading</i> Tengwar. Writing characters down on a piece of paper feels fluid and easy, but once I take a step back and look at the page, it&#8217;s incomprehensible at a glance. I have to sound the words out, character by character, if I want to read what I have written.</p>
<p class="tengwar">q7w^jt$ iG· `Bt 81j%j 5`N x`N2^ 1E <i>7`V2#b%</i> 1b$y6E- y71Tb% a7DzD16R_ 2yY5 5^ `C q`BiFO W qqE6R e`Vj$_ ej`M2% 5#2 `ViD`Û· w1U 5^iO `B 1zDO `C 81qR wzDz 5#2 j`NzH 1E @ qs#O· 1Ti 5%zt^q79V5$8w%jO 1E `C xj5#iO- `B 9r#O 1`N 8`N5&2 @ yuH_ `N1U· a7DzD16R w`Û a7DzD16R· eG `B y5#1 1`N 7`V2# o1E `B 9r#O y71T15$-</p>

<p>However, Tengwar is incredibly <em>pretty</em>. I want to get more practice reading it. What if I could read <i>whatever I want</i> with this writing system? If I only had a script that could convert English text into readable Tengwar for me!</p>
<p class="tengwar">9yYr$6R· 1b$y6E iG 5%z72$w%j`Û <i>q71R1`Û</i>- `B y5#1 1`N s1R t7HO q7zD1iGO 7`V2#b% 1T- o1E eG `B z`Nm& 7`V2# <i>o1Er$6R `B y5#1</i> y3G 4iG y71Tb% 88Ú1t$À eG `B 5^j`Û 92# `C 8z7qT1 41E z`Nm& z5^r6R1 b$jdT 1zFæ1 5%1`N 7`V2#w#jO 1b$y6E e6Y t`VÁ
</p>

<p>As a glance through the Tengwar Textbook will demonstrate, Tengwar is pretty complicated. There isn&#8217;t a single standard way to write in English using Tengwar: there are a variety of &#8220;modes&#8221;, each of which has a different set of rules. I have my own personal way of writing in Tengwar that combines some features of each of those modes that I like.</p>
<p class="tengwar">iD `C xj5#iO 37`Nv& @ 1b$y6E 1zFæ1w`NzH yj%j 2t$5^8171EO· 1b$y6E iG q71R1`Û zt^qjzG1E2$- 47FO iG51 `C 8b%jO 815#2uD y`C`Û 1`N y71TO 5% b$jdT iJb% 1b$y6E- 47FO 7DO `C r7D`B1R`Û W t2^O_· `VaD W oaG 9iD `C 2eGe7F5$1 81R W 7j&O_- `B 9r#O t`Û yY5 q6R85^j# y`C`Û W y71Tb% 5% 1b$y6E 41E zt^w5%O_ 8t^O e`V1E7JO_ W `VaD W 4iHO t2^O_ 41E `B jzGO-</p>

<p>Even though there are already some scripts around the Internet that will claim to transliterate English to Tengwar, they don&#8217;t necessarily follow my mode of writing, or even a standard mode. Thus I decided, one evening, to write my own script.</p>
<p class="tengwar">r$5$ 4`Nv& 47FO 7DO j#7`V2#`Û 8t^O 8z7qT1_ 7D`N5&2 @ 5%16R51R 41E yj%j zj`Ct% 1`N 175#8j1T7F1EO b$jdT 1`N 1b$y6E· 4`V`Û 25^1 5iFiF87Dj%`Û ej^jyY t`Û t2^O W y71Tb%· 6Y r$5$ `C 815#2uD t2^O- 3iJ `B 2iF2%2$· 5^O r$5$b%· 1`N y71TO t`Û yY5 8z7qT1-</p>

<p>I like the look of the Tengwar Annatar font, so the script would convert English text to the characters needed to render Tengwar text in that font. Eventually, I may extend it so that I can also output Tengwar using <a href="http://get-software.net/macros/latex/contrib/tengwarscript/tengwarscript.pdf">TengwarScript</a>, a TeX package. Writing a script with Tengwar Annatar in mind is the more difficult task of the two because of the way it typesets vowels (tehtar), so adding support for TengwarScript onto the existing script would be easy.</p>
<p class="tengwar">`B jzGO @ j`NzH W @ 1b$y6E 5#51E6E e5^1· 8`N @ 8z7qT1 y`Nm& z5^r6R1 b$jdT 1zFæ1 1`N @ a7DzD16R_ 5`V2$2$ 1`N 75$26R 1b$y6E 1zFæ1 5% 41E e5^1- r$5$1`Mj#j`Û· `B t`C`Û zFæ15$2 1T 8`N 41E `B z5# j#8`N `N1Uq1U 1b$y6E iJb% <a href="http://get-software.net/macros/latex/contrib/tengwarscript/tengwarscript.pdf">1b$y6E8z7qT1</a>· `C 1zFæ qzDzs#O- y71Tb% `C 8z7qT1 y3G 1b$y6E 5#51E6E 5% t5%2 iG @ t7HO 2eGezGj&1 1iDz W @ 1y`N wzF`CiJO W @ y`C`Û 1T 1qÙiF1R_ ryYj$_ Œ19V16Eœ· 8`N 2#2b% 8qUq6Y1 e6Y 1b$y6E8z7qT1 5^1`N @ zFæiG1b% 8z7qT1 y`Nm& w`V `ViD`Û-</p>

<p>As I built this thing and debugged the little errors and inconsistencies that I noticed here and there, I kept track of what it output as the result for the sentence (&#8220;This was a triumph. I&#8217;m making a note here: huge success!&#8221;) that I used for testing. Tengwar has various little complexities – the R-rule, a distinction between voiced and voiceless &#8216;th&#8217;, double consonants like &#8216;ch&#8217; and &#8216;ph&#8217; and &#8216;ng&#8217; and &#8216;rd&#8217;, and vowel carriers – that make correct transliteration more difficult. When put together, the history of my testing string provides a visualization of my progress against these complexities as I improved the script.</p>
<p class="tengwar">iD `B w`Mj%1 4iG 3b% 5#2 2w$x&s2$ @ j1T1jO 6R76Y_ 5#2 5%z5^8iG15$8`B`V_ 41E `B 51YiG2$ 97FO 5#2 47FO· `B zqR1 17zDz W o1E 1T `N1Uq1U iD @ 7iFj&1 e6Y @ 85$15$iO Œ4iG yiD `C 17`Bt&e- `Bt tzDb% `C 51YO 97FO- 9s&O 8zJ8iF_Áœ 41E `B iJ2$ e6Y 1iF1b%- 1b$y6E 9iD r7D`B`NiJ j1T1jO zt^qjzFæ1T`B`V_  @ 6\7j&O· `C 2iG15%z1`B5^ w1Ry`V5$ r`NiG2$ 5#2 r`NiGj$iF_ 3· 2`Nw&jO z5^85^5#1_ jzGO a 5#2 e 5#2 b 5#2 u· 5#2 ryYj$ z6E7`B6R_  41E tzDO z6Y7zF1 175#8j1T7F1E`B5^ t7HO 2eGezGj&1- o5$ q1U 1s^4$6R· @ 9iG17H`Û W t`Û 1iF1b% 817b% q7r^2%O_ `C riG`Mj#,G1E`B5^ W t`Û q7x^7iF_ x#`C5%81 4iFO zt^qjzFæ1T`B`V_ iD `B t%q7r^2$ @ 8z7qT1-</p>

<p><img src="/images/elvish-debugging.png" style="display: block; margin: 0 auto;" alt="" height="300" /></p>

<p>With the finished product, now I can take my favorite poems and stories, pass them through the transliterator, render the resulting text using the Tengwar Annatar font, and send that document to my Kindle! There are still some little details which could be improved upon, but I&#8217;m pleased with the result so far.</p>
<p class="tengwar">y3G @ e5%dT2$ q72^zJ1· 5yY `B z5# 1zDO t`Û er#7H1TO q`Nt$_ 5#2 817H`B`V_· qiD_ 4t$ 37`Nv& @ 175#8j1T7F1E6Y· 75$26R @ 7iFj&1b% 1zFæ1 iJb% @ 1b$y6E 5#51E6E e5^1· 5#2 85$2 41E 2zHt&5$1 1`N t`Û z5%2jOÁ 47FO 7DO 81j%j 8t^O j1T1jO 21R`Cj%_ oaG z`Nm& w`V t%q7r^2$ qU5^· w1U `Bt qj`ViD2$ y3G @ 7iFj&1 8`N e6E-</p>

<p><img src="/images/elvish-kindle-cropped.jpg" style="display: block; margin: 0 auto;" alt="" width="573" /></p>

<p>(<a href="https://gist.github.com/csvoss/e58302f7394a57860c46"><b>english_to_tengwar.py</b></a> on GitHub Gist)
&mdash;
<span class="tengwar">Œ<a href="https://gist.github.com/csvoss/e58302f7394a57860c46"><b>b$jdT·1`N·1b$y6E-q`Û</b></a> 5^ s3Gw& siG1œ</span></p>
