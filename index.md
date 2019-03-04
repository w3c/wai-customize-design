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
footer: > # Text in footer in HTML
  <p><strong>Date:</strong> Updated 4 March 2019</p>
  <p><strong>Editor:</strong> Robert Jolly. Previous editor: Shawn Lawton Henry.</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>).</p>
style: |
  .wai-larger {
    font-size: 2rem;
  }
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

## Change Text Size with Zoom

  <p>Most web browsers let you increase and decrease the size of text, images, and other web page content with "zoom" features. Some browsers let you choose to change only the text size.</p>
  <div style="font-size:1.4rem;">
  <p>To change the zoom in most browsers, press the following two keys at the same time:</p>
  <ul>
    <li>In Windows, Linux, and Chrome OS:
      <ul>
        <li>To zoom bigger: "Ctrl" and "+" keys</li>
        <li>To zoom smaller: "Ctrl" and "-" keys</li>
      </ul>
    </li>
    <li>Mac OS:
      <ul>
        <li>To zoom bigger: "⌘" and "+" keys</li>
        <li>To zoom smaller: "⌘" and "-" keys</li>
      </ul>
    </li>
  </ul>
</div>

Browsers provide specific guidance on diffferent ways to change the zoom and/or text size:

* [Google Chrome - Change text, image, and video sizes (zoom)](https://support.google.com/chrome/answer/96810?hl=en)
* [Mozilla Firefox - Font size and zoom](https://support.mozilla.org/en-US/kb/font-size-and-zoom-increase-size-of-web-pages)
* [Internet Explorer - Ease of access options](https://support.microsoft.com/en-us/help/17456/windows-internet-explorer-ease-of-access-options)
* [Microsoft Edge - Ease of Access in Microsoft Edge](https://support.microsoft.com/en-gb/help/4000734/windows-10-microsoft-edge-ease-of-access)
* [Safari - Zoom in on webpages](https://support.apple.com/guide/safari/zoom-in-on-webpages-ibrw1068/mac)
* [Opera - Zoom](https://help.opera.com/en/latest/browser-window/#zoom)
* [Vivaldi - Zooming options in Vivaldi](https://help.vivaldi.com/article/zooming-options-in-vivaldi/)

There are also browser extensions and add-ons that provide additional control over text size.

### Why doesn't this work with some other websites?

The browser settings on this page should work when browsers and websites
meet [WAI guidelines]({{ "/standards-guidelines/" | relative_url }}) and are designed for accessibility, flexibility, and user control. However, some browsers do not provide as
much user control, and some websites are designed to defeat browser
settings. Text resizing and browser zoom may not work consistently on websites that
do not meet accessibility guidelines.

## For a Plain Layout View

Turning off the style sheet gives a plain layout view, which:

-   makes text black on a white background (or however your browser is
    set)
-   puts all the information in one column (called "linearized")
-   leaves content images
-   removes background images

Note: Not all browsers allow users to directly disable styles. However, some broswers offer a built-in “Reading Mode” which allows a page to be altered visually to enhance readability. Additionally, there are browser plugins and/or extensions from third-party developers which allow styles to be disabled or reading enhancements to be applied to web pages.

<table summary="Instructions for removing styles from or enhancing the reading layout in browser">
  <tbody>
    <tr>
      <th scope="col">Browser</th>
      <th scope="col">Example</th>
      <th scope="col">Menu Items</th>
    </tr>
    <tr>
      <th scope="row">Firefox</th>
      <td><img src="{{ '/assets/img/firefox-view-page-style.png' | relative_url }}" alt="Firefox screen capture as described in the page"></td>
      <td>View ▶<br>
        Page Style ▶<br>
        No Style</td>
    </tr>
    <tr>
      <th scope="row">Safari</th>
      <td><img src="{{ '/assets/img/safari-developer-no-styles.png' | relative_url }}" alt="Safari screen capture as described in the page"></td>
      <td><p><em>Note: This requires the Develop menu to be enabled under:</em><br>Preferences ▶ Advanced.</p>
        <p>
        Develop ▶<br>
        Disable Styles</p></td>
    </tr>
    <!-- Opera no longer has a built-in way to diable styles, like Chrome.
    <tr>
      <th scope="row">Opera</th>
      <td><img src="https://www.w3.org/WAI/about/plainlayout-opera-mac.png" alt="Opera screen capture as described in the page"></td>
      <td>View ▶<br>
        Style ▶<br>
        User Mode</td>
    </tr>
    -->
  </tbody>
</table>

## Other Text and Color Changes

Many browsers provide functionality to set different aspects of font and
color, including offering a “Reading View” for web pages. Below are links to instructions of how to access this functionality.

* [Mozilla Firefox - Change the fonts and colors websites use](https://support.mozilla.org/en-US/kb/change-fonts-and-colors-websites-use)
* [Mozilla Firefox - Reader View for clutter-free web pages](https://support.mozilla.org/en-US/kb/firefox-reader-view-clutter-free-web-pages)
* [Google Chrome - Set page or font size for all webpages](https://support.google.com/chrome/answer/96810?hl=en&ref_topic=7439724#fontsize)
* [Microsoft Edge - Change font style and size for Reading view in Microsoft Edge](https://support.microsoft.com/en-us/help/4028023/microsoft-edge-change-font-style-and-size-for-reading-view)
* [Microsoft Internet Explorer - Ease of Access Options](https://support.microsoft.com/en-us/help/17456/windows-internet-explorer-ease-of-access-options)
* [Apple Safari - Hide ads when reading articles](https://support.apple.com/en-ca/guide/safari/hide-ads-when-reading-articles-sfri32632/mac)
  * Note: This article has instructions titled "Change how your webpages look in Reader" which highlights how to customize fonts and colors for easier reading.
* [Opera - Look and feel > Fonts](https://help.opera.com/en/presto/look-and-feel/#fonts)
* [Vivaldi - Reader View](https://help.vivaldi.com/article/reader-view/)

<!--
<table summary="Instructions for changing font and colors in browser">
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
-->

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
