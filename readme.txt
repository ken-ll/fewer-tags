=== Fewer tags ===
Contributors: joostdevalk
Tags: tag, tags, seo
Requires at least: 6.2
Tested up to: 6.3
Requires PHP: 7.4
Stable tag: trunk
License: GPL3+
License URI: https://www.gnu.org/licenses/gpl-3.0.en.html

This plugin minimizes the effect of having too many tags by setting a minimum number of posts needed for a tag to be “live” on your site.

== Description ==
One of the most common SEO problems on WordPress sites is that people add too many tags to posts. The WordPress interface makes it incredibly easy to do so, and with every tag you add, you add another URL to your site for search engines to crawl and index. This plugin minimizes that effect by setting a minimum number of posts needed for a tag to be “live” on your site.

Tags that have less than the configured number of posts:
 * don\'t work on your site, and are redirected to your homepage.
 * no longer show up in tag listings.
 * are no longer linked in WordPress core's or Yoast SEO generated XML sitemaps.

This positively affects your site\'s SEO and also leads to less crawling, as you have less useless tag pages.

== Frequently Asked Questions ==

=== Can I safely install this on an existing site? ===

So you have a site with a lot of tags that don't add any value? Yes, you can safely add this plugin. It will redirect the useless tag pages to your site's homepage.

=== Should I also noindex my tag pages? ===

No, you should not noindex your tag pages. If your tag pages have more than 10 posts in them, they are valuable ways of getting your site crawled and of combining related content. There's no reason to noindex those pages at that point. What you could (and should) do is add descriptions to those tag pages.

=== How can I report security bugs? ===

You can report security bugs through the Patchstack Vulnerability Disclosure Program. The Patchstack team help validate, triage and handle any security vulnerabilities. [Report a security vulnerability.](https://patchstack.com/database/vdp/fewer-tags)

== Installation ==
1. Search for Fewer tags on the repository
2. Install the plugin
3. Optionally: go to Settings -> Reading and adjust the default minimum number of posts (the default is 10).
4. You\'re done

== Screenshots ==
1. The Fewer tags settings
