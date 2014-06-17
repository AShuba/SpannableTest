Spannable vs fromHtml
====================

There are different methods to format text inside Android TextView.<br/>

* [Simle HTML formatting](http://developer.android.com/intl/ru/reference/android/text/Html.html)
* [SpannableBuilder](http://developer.android.com/intl/ru/reference/android/text/Spannable.html)


Current test just makes <b>bold</b>, <i>italic</i>, green text and applies it to TextView.

My Nexus 4 shows next results

* HTML formatting - about 3000000 nsec</li>
* SpannableBuilder - about 600000 nsec</li>

So use SpannableBuilder for text formatting instead of HTML tags where it possible :-)
