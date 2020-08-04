<includeonly><div style="padding: 0.5em; {{#if:{{{float|}}}|float: {{{float}}};|}}{{#if:{{{width|}}}|width: {{{width}}};|}}"><table style="border: 1px solid lightgray; border-radius: 1em; padding: 0.5em 1em 0.5em 1em; width: 100%">
<tr>
{{#if:{{{gravatar|}}}|<td rowspan=2 style="padding-right: 1em; vertical-align: top; padding-top: 1em"><img style="border-radius: 50%" src="http://gravatar.com/avatar/{{{gravatar}}}"></td>|}}
<td colspan=2 style="font-family: Times, Helvetica, sans-serif; font-size: 17px">&ldquo;{{{quote}}}&rdquo;</td>
</tr>
<tr>
<td style="font-family: Times, Helvetica, sans-serif; font-size: 15px; padding-left: 1em">—{{{person}}}</td>
<td style="font-size: 10px; text-align: center; white-space: nowrap">[ [{{{source}}} source] ]</td>
</tr>
</table></div></includeonly><noinclude>This template generates a testimonial box with quote and attribution.
== Usage ==
<pre>
{{Testimonial
| quote = If this is coffee, please bring me some tea; but if this is tea, please bring me some coffee.
| person = Abraham Lincoln
| gravatar = 7194e8d48fa1d2b689f99443b767316c
| source = http://www.brainyquote.com/quotes/quotes/a/abrahamlin100275.html
| width = 30%
| float = right
}}
</pre>
{{Testimonial
| quote = If this is coffee, please bring me some tea; but if this is tea, please bring me some coffee.
| person = Abraham Lincoln
| gravatar = 7194e8d48fa1d2b689f99443b767316c
| source = http://www.brainyquote.com/quotes/quotes/a/abrahamlin100275.html
| width = 30%
| float = right
}}
</noinclude>