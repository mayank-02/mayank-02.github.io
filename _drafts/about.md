---
layout: post
title:  "About"
tagline: "A behind-the-scenes look into the website (and myself, for good measure)"
card_color: "#4990E2"
ending:
  tagline: The source code of the entire site is available on GitHub.
  link: https://github.com/mayank-02/mayank-02.github.io
  link_text: View GitHub repo
permalink: /about/
---

# About Me

I was born and brought up in Pune. Right now, I'm in La Jolla, San Diego, where I'm studying computer science at UCSD.

<aside class="post-aside">
  Did you know? Pune is also known as the 'Oxford of the East'.
</aside>

If I'm not doing anything Computer Science-related, you might find me reading literature or playing badminton.

# About This Site

Hosted on [GitHub Pages][github-pages], this site is built on [Jekyll][jekyll], a static site generator built in Ruby. The site's theme was borrowed from Zachary Espiritu's [personal website][zachary-espiritu] (kudos for all the work here!), and the source code for it (licensed under the MIT license) can be found in GitHub [here][source-code].

For the automatically sorting "cards" seen on the front page, I use [Isotope][isotope].

If you've viewed some of the articles or project writeups, you'll notice that the images only load after the page has rendered. I'm using [Lazysizes][lazysizes] to lazily load the images in for faster response times.

Finally, in order to make sure all the necessary, visual-based Javascript is loaded before the page renders, I use [PleaseWait][please-wait] to display a brief interstitial with a humorous loading message until the page is ready to display.

[github-pages]: https://pages.github.com
[jekyll]: https://jekyllrb.com
[zachary-espiritu]: https://zacharyespiritu.github.io
[source-code]: https://github.com/mayank-02/mayank-02.github.io
[isotope]: http://isotope.metafizzy.co
[lazysizes]: http://afarkas.github.io/lazysizes
[please-wait]: http://pathgather.github.io/please-wait
