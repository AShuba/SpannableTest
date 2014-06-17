<h3><b>Spannable vs fromHtml</b></h3>
<br/>
There are different methods to format text inside Android TextView.<br/>
<ol>
<li>Simle HTML formatting</li>
<li>SpannableBuilder</li>
</ol>

Current test just makes <b>bold</b>, <i>italic</i>, green text and applies it to TextView.
<br/>
<br/>
My Nexus 4 shows next results
<br/>
<ol>
<li>HTML formatting - about 3000000 nsec</li>
<li>SpannableBuilder - about 600000 nsec</li>
</ol>

So use SpannableBuilder for text formatting instead of HTML tags where it possible :-)
