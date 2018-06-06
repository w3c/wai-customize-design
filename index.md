---
title: How to Change Text Size or Colors
layout: default
parent: "/"
permalink: /meta/customize/
github:
  repository: w3c/wai-customize-design
doc-note-type: draft
doc-note-message: >
  This page is in the process of getting a major rewrite and content update.
---
{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

The WAI website is designed to let you change the text size, text and
background colors, and other display settings **through standard browser
settings**.

This page shows you how to use some of these browser display settings.

-   "[Why doesn't this work with some other Web sites?](#notworky)"
    explains that these settings may not work on browsers and Web sites
    that do not meet [accessibility guidelines]({{ "/standards-guidelines/" | relative_url }}).
-   "[Should all sites include this?](#alldoit)" explains that including
    these instructions is not an accessibility requirement.

## To Zoom In or Out

Most web browsers include functionality that allows for an increase or decrease text and content in web pages via a feature called browser zoom. Some browsers also give control for text-only size adjustments. Additionally, there are a number of browser extensions or add-ons that provide users addtional control over the display of content.

Most commonly, the commands to increase or decrease zoom levels in browsers are:

<ul>
  <li>Windows, Linux, and Chrome OS: Ctrl and + or Ctrl and - (pressing Ctrl and the plus button or Ctrl and the minus button simultaneously)</li>
  <li>Mac OS: ⌘ and + or ⌘ and + (pressing command and the plus button or command and the minus button simultaneously)</li>
</ul>

Browser vendors have specific, detailed, and updated guides available for changing the zoom and/or text display sizes. We have collected links to some of these resources for your convenience.

<ul>
  <li><a href="https://support.mozilla.org/en-US/kb/font-size-and-zoom-increase-size-of-web-pages">Mozilla Firefox - Font size and zoom</a></li>
  <li><a href="https://support.google.com/chrome/answer/96810?hl=en">Google Chrome - Change text, image, and video sizes (zoom)</a></li>
  <li><a href="#">Microsoft Edge - is there an official MS page for Edge's zoom feature?</a></li>
  <li><a href="https://support.apple.com/guide/safari/zoom-in-on-webpages-ibrw1068/mac">Safari - Zoom in on webpages</a></li>
  <li><a href="https://support.microsoft.com/en-us/help/17456/windows-internet-explorer-ease-of-access-options">Internet Explorer - Ease of access options</a></li>
 
  <li><a href="http://help.opera.com/FreeBSD/12.00/en/zoom.html">Opera - Zoom</a></li>
  <li><a href="https://help.vivaldi.com/article/zooming-options-in-vivaldi/">Vivaldi - Zooming options in Vivaldi</a></li>
</ul>

### Why doesn't this work with some other websites?

The browser settings on this page should work when browsers and websites
meet [WAI guidelines]({{ "/standards-guidelines/" | relative_url }}) and are designed for accessibility,
flexibility, and user control. However, some browsers do not provide as
much user control, and some websites are designed to defeat browser
settings. Text resizing does not work well in browsers and websites that
do not meet accessibility guidelines.

-   In **Internet Explorer** Version 6 and earlier, the text may not
    resize because the Web site is designed with "hard-coded" or
    "absolute" text sizes. To override Web site setting:
    1.  *Menu items:* Tools ▶ Internet Options
    2.  *In Internet Options dialog box:* Accessibility button (bottom
        right)
    3.  *In Accessibility dialog box:*<br>
        \[/\] Ignore colors specified on Web pages<br>
        \[/\] Ignore font styles specified on Web pages<br>
        \[/\] Ignore font sizes specified on Web pages

-   In **Firefox** early versions, the text should resize even if the
    Web site text is not "coded" for flexibility. However the sections
    of the Web site may not resize, making it difficult to use the site
    with large text. This is because the Web site was designed with
    "hard-coded" or "absolute" sizes. Firefox does not resize images.

-   **Opera** resizes all aspects of a Web site, including font, images,
    and sections. **Resizing should work fairly well in Opera**, even if
    the Web site is not "coded" for flexibility.

## For a Plain Layout View

Turning off the style sheet gives a plain layout view, which:

-   makes text black on a white background (or however your browser is
    set)
-   puts all the information in one column (called "linearized")
-   leaves content images
-   removes background images

<table summary="Instructions for changing text size in browser">
  <tbody>
    <tr>
      <th scope="col">Browser</th>
      <th scope="col">Example</th>
      <th scope="col">Menu Items</th>
    </tr>
    <tr>
      <th scope="row">Firefox</th>
      <td><img src="https://www.w3.org/WAI/about/plainlayout-firefox-mac.png" alt="Firefox screen capture as described in the page"></td>
      <td>View ▶<br>
        Page Style ▶<br>
        No Style</td>
    </tr>
    <tr>
      <th scope="row">Opera</th>
      <td><img src="https://www.w3.org/WAI/about/plainlayout-opera-mac.png" alt="Opera screen capture as described in the page"></td>
      <td>View ▶<br>
        Style ▶<br>
        User Mode</td>
    </tr>
  </tbody>
</table>

## Other Text and Color Changes

Many browsers provide functionality to set different aspects of font and
color. Below are examples of how to access this functionality.

<table summary="Instructions for changing text size in browser">
  <tbody>
    <tr>
      <th scope="col">Browser</th>
      <th scope="col">Example</th>
      <th scope="col">To access functionality:</th>
    </tr>
    <tr>
      <th scope="row">Firefox</th>
      <td><img src="https://www.w3.org/WAI/about/other-firefox-mac.png" alt="Firefox screen capture as described in the page"></td>
      <td><p><em>Windows Menu items:</em>Tools ▶ Options<br>
        <em>Macintosh Menu items:</em> Firefox ▶ Preferences</p>

        <p><em>In dialog box:</em> General (in the left pane), Fonts &amp;
        Colors (button)</p>
      </td>
    </tr>
    <tr>
      <th scope="row">Opera</th>
      <td></td>
      <td><p><em>Windows Menu items:</em> Tools ▶ Preferences<br>
        <em>Macintosh Menu items:</em> Opera ▶ Preferences</p>

        <p><em>In dialog box:</em> Fonts and Page Style (in the left pane)</p>
      </td>
    </tr>
  </tbody>
</table>

## Should all websites include instructions like this?

It is not an accessibility requirement that websites include information
on changing text sizes and colors like this page. WAI chose to include
this information to help people who want to know how to change their
browser settings and may not know how.

Web browsers and websites **should** be designed following [WAI
guidelines]({{ "/standards-guidelines/" | relative_url }}) so that people can easily change text sizes and
colors.

## Note: No Browser Endorsement

W3C WAI does not endorse specific Web browsers and does not recommend
one browser over another. While some common browsers are included in
this page, mention of a specific browser does not imply endorsement or
recommendation.

## Related Pages

-   [Help with the WAI Web Site](https://www.w3.org/WAI/sitehelp) includes instructions on
    navigating the WAI Web site and other topics
