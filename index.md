---
title: How to Change Text Size or Colors
layout: default
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
    that do not meet [accessibility guidelines](guid-tech).
-   "[Should all sites include this?](#alldoit)" explains that including
    these instructions is not an accessibility requirement.

## To Change Text Size

Most Web browsers include functionality to let you increase or decrease
the text in a Web page. For example, to increase text size:

<table summary="Instructions for changing text size in browser">
  <tbody>
    <tr>
      <th scope="col">Browser</th>
      <th scope="col">Example</th>
      <th scope="col">Menu Items</th>
      <th scope="col">Macintosh Shortcut</th>
      <th scope="col">Windows Shortcut</th>
    </tr>
    <tr>
      <th scope="row">Internet Explorer</th>
      <td><p><img src="https://www.w3.org/WAI/about/textsize-ie.png" alt="Internet Explorer screen capture as described in the page"><br>
        </p>
      </td>
      <td>View ▶
        Text Size ▶
        Largest</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th scope="row">Firefox,<br>
        Netscape</th>
      <td><img src="https://www.w3.org/WAI/about/textsize-mozilla.png" alt="Firefox/Netscape screen capture as described in the page"><br>
      </td>
      <td>View ▶
        Text Size ▶
        Increase</td>
      <td><kbd>Command</kbd>+<kbd>+</kbd></td>
      <td><kbd>Ctrl</kbd>+<kbd>+</kbd></td>
    </tr>
    <tr>
      <th scope="row">Opera</th>
      <td><img src="https://www.w3.org/WAI/about/textsize-opera.png" alt="Opera screen capture as described in the page"><br>
      </td>
      <td>View ▶
        Zoom ▶
        %</td>
      <td><kbd>Command</kbd>+<kbd>+</kbd>
      </td>
      <td><p><kbd>+</kbd></p>

        <p><em>or</em></p>

        <p><kbd>0</kbd></p>
      </td>
    </tr>
    <tr>
      <th scope="row">Safari</th>
      <td><img src="https://www.w3.org/WAI/about/textsize-safari.png" alt="Safari screen capture as described in the page"></td>
      <td>View ▶
        Make Text Bigger</td>
      <td><kbd>Command</kbd>+<kbd>+</kbd></td>
      <td></td>
    </tr>
  </tbody>
</table>

### Why doesn't this work with some other websites?

The browser settings on this page should work when browsers and websites
meet [WAI guidelines](guid-tech) and are designed for accessibility,
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
guidelines](guid-tech) so that people can easily change text sizes and
colors.

## Note: No Browser Endorsement

W3C WAI does not endorse specific Web browsers and does not recommend
one browser over another. While some common browsers are included in
this page, mention of a specific browser does not imply endorsement or
recommendation.

## Related Pages

-   [Help with the WAI Web Site](sitehelp) includes instructions on
    navigating the WAI Web site and other topics