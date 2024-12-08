---
Title: About
Description: This is our about page
---

<p>
  Sidan nu använder SCSS genererad mallar. Jag har uppdaterat SCSS koden så den använder sig av import, variablar och nestlande regler. 
</p>

<p>
  För att göra innerhållet på sidan responsivt användar jag av ett wrapper element (<i>.main</i>) med 100% bredd som innerhåller ett barn element (<i>.main-content</i>) med max-bredd och är centrerad med margin auto. De stora elementen som header, content och footer har flex layout för att underlätta strukturering av barn-elementen.
</p>

<p>
  Text fonter är importerad från Google Fonts. 
</p>

<p>
  FontAwesome är också importerad för symboler. Den är den patchad versionen och jag hade i början lite problem att få den att fungera. På FontAwesome sidan vill de ha lite olika klassnman än det som den patchad versionen använder ("<i>fa-brands</i>" vs "<i>fab</i>").
</p>

<p>
  Länk-element är stylad så de följer med båda temas huvud- och ascent färg. Det gäller för alla lägen (normal, hover, visited).
</p>
                
<p>
  "npm run style" klagar mycket och jag tystade ned den lite med "<i>--silence-deprecation=import,global-builtin</i>" i package.json. I framtiden kommer jag nog att konvertera alla dessa funktioner till nya standard.
</p>

                