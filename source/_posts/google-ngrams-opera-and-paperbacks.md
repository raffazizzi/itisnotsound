---
title: Google Ngrams, Opera and Paperbacks
thumb: /images/operangram.png
tags:
  - music
  - opera
categories:
  - Music
comments: true
date: 2011-11-09 11:31:10
---

<div class="alert alert-warning" role="alert">This post was migrated from an old wordpress blog related to my PhD research.</div>

The <strong>Google Ngram Viewer</strong> is old news by now, and several have blogged about it. A few blogs were quick to identify the main issue around its reliability: OCR errors. <a href="http://searchengineland.com/when-ocr-goes-bad-googles-ngram-viewer-the-f-word-59181" target="_blank">This famous post</a> about the <strong>medial (or long) s</strong> is particular amusing. Nonetheless, I'd like to go back on the topic after a discussion I had with my supervisor some time ago.

In brief, the Google Ngram Viewer allows one to plot occurrences of a search query on the vast collection of books that Google scanned and OCR'd for Google Books. To have a better idea of what it does, have a look at this <a href="http://ngrams.tumblr.com/" target="_blank">Tumblr</a> that collects interesting Ngrams, or <a href="http://ngrams.googlelabs.com/" target="_blank">try it out</a> for yourself.

While looking at the Viewer with my supervisor, we tried to look for a few composers, <strong>particularly opera composers</strong>. We started by confirming our most obvious assumptions, like <strong>Beethoven being utterly dominant</strong> (in most corpora, and surely for a lot more than just Fidelio), closely followed by Purcell (in the English corpus) and Mozart. What baffled us for a bit was the fact that most of the composers seemed to experience <strong>a big drop around the 1950s and 1960s.</strong>

Once at home, I looked up in the English corpus <a href="http://books.google.com/ngrams/graph?content=Ludwig+van+Beethoven%2CWolfgang+Amadeus+Mozart%2CGeorge+Frideric+Handel%2CCharles+Gounod%2CGioachino+Rossini%2CVincenzo+Bellini%2CGaetano+Donizetti%2CGiacomo+Puccini%2CGeorges+Bizet%2CLeos+Jan%C3%A1cek%2CHenry+Purcell&amp;year_start=1900&amp;year_end=2000&amp;corpus=0&amp;smoothing=3" target="_blank">some notorious opera composers</a> between the 17<sup>th</sup> and early 20<sup>th</sup> century and confirmed this trend (N.B. this selection is not at all representative of the full landscape of opera composers, just first names that came to mind).

<figure class="figure">
  <img class="size-full wp-image-30" title="Google Ngram for some notorious opera composers" src="/images/operangram.png" alt="Google Ngram for some notorious opera composers" width="595" height="274" />
  <figcaption class="figure-caption">Google Ngram for some notorious opera composers</figcaption>
</figure>

Now, what made us perplexed was the fact that academic and non-academic literature about composers probably grew after the 1950s rather than diminish. But in fact, the Ngram Viewer <strong>normalizes the occurrences by the number of books published every year</strong>.  This is why on the Y axis we see percentages rather than number of occurrences. So why is the drop there?

After some head scratching, we got to the approximate conclusion that starting in the 1950s, book publishing begins targeting a larger and growing audience, resulting in a wider range of topics and genres. Notwithstanding the normalization, <strong>composers get submerged</strong> -in percentage of total published words per year- by many other printed words.

My knowledge of history of book publishing is very limited, but after doing some digging around I stumbled upon<em> A history of British Publishing</em> by John Feather that seems to confirm this idea. Specifically, the increase of adult literacy determined the success of <strong>paperback editions</strong> that "made [their] way into the British publishing scene in the 1950s..." and <strong>were ubiquitous by the 1970s</strong>. Assuming that a similar phenomenon took place in other English-speaking countries around the same years, we can tentatively take this as a plausible explanation for the drop.

It goes without saying that because of the noise caused by OCR, one should look with some suspicion to any information inferred from the Google Ngram Viewer. However, because of the corpus size, it is a unique tool and it shows the potential -and risks- of using numeric "evidence" to formulate and discuss theories about text-based culture.

I also find somewhat amusing that Google, by means of relevance rather than complexity, finally <strong>brought some computational linguistics on <a href="http://www.sciencemag.org/content/early/2010/12/15/science.1199644" target="_blank">Science Magazine</a></strong>.

<em>Trivia</em>: apparently, the Ngram Viewer, or some components of it, is <strong>written in Python</strong>, as I could see from one error message that I got during one of my tests ;)

<em>Why do you think the drop may be there? Leave your thoughts in the comments!</em>

## Comments

<div class="alert alert-warning" role="alert">These comments were migrated from an old wordpress blog related to my PhD research.</div>

**John Lavagnino (2011-11-09 17:31:08):** It's a great problem, and I think the paperback phenomenon may well be the explanation. A possible difficulty, though, is that Google Books is mostly based on the contents of academic libraries, and 1950s paperbacks may not be that well represented in their collections: they aren't usually academic material, and are often reprints of books libraries might already have. I wonder if there is also or instead a change in the profile of academic publishing in this period, especially because in the USA funding for the hard sciences greatly increased in the postwar era.

**Raff Viglianti (2011-11-10 10:16:03):** Hello John, thanks for your comment! Yes, that makes sense. It would be interesting to test for other humanities topics to see whether there is a general drop that might have been caused by more publications in the hard sciences. Though I wonder how well represented academic publications are on the Google books corpus? Would a change within academic publications be sufficient to cause the drop?
