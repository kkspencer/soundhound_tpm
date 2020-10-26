# iPhone Web Browser Infringment Analysis [2009]

## Background Information
The iPhone is an internet and multimedia-enabled Smartphone designed and marketed by Apple Inc.
It functions as a camera phone, a portable media player, and an Internet client (with email, web
browsing and Wi-Fi connectivity) using the phone's Multi-Touch interface.

Apple Inc. announced the iPhone on January 9, 2007 after months of rumors and speculation. It was introduced in the United States on June 29, 2007 before being marketed worldwide. By the end of the year, it was named the Invention of the Year by Time magazine.

The first-generation iPhone featured a quad-band GSM with EDGE. The second generation addedUMTS technology with 3.6Mbps HSDPA, while the third generation adds support for 7.2 Mbps HSDPA downloading technology.

On March 17, 2009, Apple announced version 3.0 of the iPhone operating system, featuring improved system performance. The new iPhones also come with a 3 megapixel camera and video capability, and voice control.Over 33.75 million iPhones have been sold to date (December 2009).

The iPhone uses fast 3G and Wi-Fi wireless connections to deliver rich HTML email, maps with GPS,and Safari, the iPhone's native web browser, which displays pages similar to its Mac and Windows counterpart.

WebPages may be viewed in either portrait or landscape mode on the iPhone, with support for automatic zooming by pinching together or spreading apart one's fingertips on the screen, or by double tapping text or images.

Safari, iPhone's web browser, is based on the open-source WebKit rendering engine, which allows the iPhone to display normal WebPages just as you would see on a normal desktop computer, without having to apply any special formatting on the webpage (such as converting HTML to XML) and then optimizing it for display.

WebKit is an open source rendering engine, under the GNU Lesser General Public License. A rendering engine is software that takes marked up content (such as HTML, XML, image files, etc) and formatting information (such as CSS, XSL, etc) and displays the formatted content on a display. It is typically used for web browsers, e-mail clients or other applications that require the displaying (and editing) of web content.

In addition to Safari, WebKit is used in Google'sAndroid mobile phone platform and by Google's new Chrome browser as well as on some of Nokia's Symbian-based mobile devices.

Before WebKit became open source, it was originally derived by Apple Inc. from the open source Konqueror browser's KHTML software library for use as the engine of Mac OS X's Safari web browser,and has now been further developed by individuals from the KDE project, Google, Torch Mobile and others.

## Infringement Analysis
Since its release, the iPhone has had its fair share of infringement claims. One recent infringement claim against Apple Inc.'s iPhone is filed by a small holding company named EMG Technology. EMG Technology claims it was the first to invent an “apparatus and method of manipulating a region on a wireless device screen for viewing, zooming and controlling internet content. The lawsuit accuses Apple Inc of infringing **U.S. Patent No. 7,441,196** (henceforth referred to as the '196
patent) which covers the display of internet content reformatted from HTML to XML on mobile devices. The '196 patent was filed on March 13, 2006 and issued on October 21, 2008.

According to United States Patent Law Statute, a patent owner need only prove infringement of a single claim to establish patent infringement. To determine whether the iPhone infringes the'196 patent, we will first need to interpret the relevant claims, and then compare the interpreted claims with the features of the iPhone.

The '196 patent describes viewing websites on a variety of devices, including mobile devices. The patent is described as:

> A method and apparatus of a simplified navigation. A web page is provided having a link to a sister site. The sister site facilitates simplified navigation. Pages from the sister site are served responsive to actuations of the sister site link. In one embodiment, the sister site includes matrix pages to permit matrix navigation

This patent contains 76 claims that hold legal bearing.
After interpreting and considering each of the claims, claims 1 and 58 seem relevant to the iPhone's web browser.

**Claim 1 of the'196 patent describes:**

> A method of navigating the Internet, comprising: displaying on-line content accessed via the Internet, the on-line content reformatted from a webpage in a hypertext markup language(HTML) format into an extensible markup language (XML) format to generate a sister site, the sister site including a portion or a while of content of the web page reformatted to be displayed and navigable through a simplified navigation interface on any one of a television, web appliance, console device, handheld device, wireless device or cellular phone, the simplified navigation interface displayed in a form of a two-dimensional layer in a form of a navigation matrix, each cell is a division of a screen and exclusive to a separate single navigation option associated with a specific unique input, the online-
content formatted to be displayed in one or more of the plurality of cells and formatted to be selected for navigation by one or more of the unique inputs, navigation options to change between layers of the simplified navigation interface from general to more specific in each deeper layer; receiving a user selection of one of the navigation options; forwarding the selected navigation options across the internet to a server providing the simplified navigation interface; receiving a next deeper navigation layer of the simplified navigation interface corresponding to the selected navigation option; and manipulating a region of the screen for viewing and zooming and/or scrolling of the displayed on-line content.

From the patent descriptions, when a user accesses a home page, they have the option of linking to a sister site, where the sister site is the reformatted site that provides for navigation of the site using the matrix navigation system. The sister site converts the original HTML page to an XML page with a matrix format to permit matrix navigation. The webpage is divided into regions which are not necessarily, but may be, of equal size, and the individual regions may be brought into focus independently. By “brought into focus”, the selected region is brought to the front of the screen. This division /segmentation facilitates tab, scroll and zoom features.


**Claim 58 of the '196 patent describes:**

> A machine readable medium having instructions stored therein, which when executed cause a machine to perform a set of operations comprising: displaying on-line content accessed via the Internet, the on-line content reformatted from a webpage in a hypertext markup language (HTML) format into an extensible markup
language (XML) format to generate a sister site, the sister site including a portion or a whole of content of the web page reformatted to be displayed and navigable through a simplified navigation interface on any one of a television, web appliance, console device, handheld device, wireless device or cellular phone, the simplified navigation interface displayed in a form of a two-dimensional layer of cells from a plurality of layers and a plurality of cells, the two-dimensional layer in a form of a navigation matrix, each cell is a division of a screen and exclusive to a separate single navigation option associated with a
specific unique input, the on-line content formatted to be displayed in one or more of the plurality of cells and formatted to beselected for navigation by one or more of the unique inputs, navigation options to change between layers of the simplifiednavigation interface from general to more specific in each deeper layer; receiving a user selection of one of the navigation options; forwarding the selected navigation option across the internet to a server providing the simplified navigation interface; receiving a next deeper navigation layer of the simplified navigation interface corresponding to the selected navigation option; and manipulating a region of the screen for viewing and zooming and/or scrolling of the displayed on-line content.

This claim specifically outlines the medium that enables the navigation method previously described in Claim 1. The medium could be a piece of software or computer program that reformats a webpage from HTML format into XML format for viewing on display.

As mentioned previously, Safari is the native web browser for the iPhone. It displays webpages similar to its Mac and Windows counterpart, and in addition, allows webpages to be viewed in portrait or landscape mode and supports automatic zooming by pinching together or spreading apart fingertips on the screen, or by double- tapping text or images. The zoom feature on the iPhone lets you magnify the entire screen, with the ability to zoom up to five times the normal size, and move left, right, up, and down to view any portion of the screen close up. To access the internet, a user simply enters a url into an address bar on the screen and taps on “go”. Once the page is loaded, the user can use a flip or dragfinger gesture on the multi-touch screen to scroll through the whole webpage. To help determine if the iPhone does indeed infringe on the '196 patent, we will compare the way the iPhone accesses webpageswith the claims in the '196 patent. Then we will determine if there is either literal infringement or infringement under the doctrine of equivalence or both.

From the claims in the '196 patent, mobile devices accesses a webpage by following this procedure: first, access the server containing the webpage, which is typically an HTML file; then reformat the HTML file into an XML file; after this, generate a sister webpage on the server using this new XML file in a format
that allows for matrix navigation, and then send the reformatted webpage to the mobile device. The iPhone on the other hand renders the HTML file directly as you would normally see it on a desktopbrowser without having to first reformat the HTML file into an XML file, generate a sister webpage, and
then display this new webpage on the screen.

This is because Safari is built on the WebKit rendering engine which allows any webpage to be viewed directly without the need for any special formatting for the display on mobile devices. Apart from being stripped of a few features, the web browser used in the iPhone is essentially the same as the web browser used on a normal desktop. Comparing the iPhone's features to Claim 58 of the '196 patent is a little tricky. Claim 58 is mostly concerned with the medium that allows for navigating websites. According to the claim, when a user accesses a webpage, the medium reformats the webpage from HTML to XML, and generates a sister site on the server, that is reformatted to be displayed on a mobile device. This sister site is formatted for the display in the form of a 2- D matrix layer. Each cell of the
matrix is a division of the screen, exclusive to a single navigation feature. To perform simple navigation features like zooming in, the user selects a cell on the screen, and the cell is brought to the front of the screen.
The iPhone on the other hand displays the whole webpage on its screen, allowing the user to view certain portions of the webpage by double tapping at the specific location on the screen, or spreading one's fingers apart on the desired location to zoom in.

According to United States Patent Law Statute, there are two main types of infringement namely: literal infringement and infringement under the doctrine of equivalents. The literal infringement of a claim exists when every element or limitation recited in the claim is found in the accused device or method.

Infringement under the doctrine of equivalence on the other hand occurs when the difference between the accused product or method and the claimed invention are insubstantial. Comparing the relevantclaims of the '196 patent with the features of the iPhone, we determine that theiPhone's Safari web browser does not literally infringe the '196 patent because it uses a completely different method to render webpages on its display.

Further, the method described in the '196 patent does not yield the same result as that of the iPhone. The method claimed in the '196 patent results in the generation of an XML file that is optimized to be viewed on a mobile device, while the iPhone's browser does not reformat the original HTML page, but rather renders it directly on the display.

Moreover, the reformatted HTML webpage as described in the claims of the '196 patent is a simplified version of the original HTML site for devices that cannot render the full HTML site, whereas the site that is rendered on the iPhone is the original HTML site.

The iPhone does not infringe the '196 patent under the doctrine of equivalence either. It stipulates that the iPhone must perform substantially the same function in substantially the same way, to obtain the same result. Both the iPhone's browser, and the method described in the '196 patent perform substantially the same function, which is enabling a mobile device to view and navigate a webpage.

However the method employed by the iPhone is substantially different from the method described in the patent, and further, the results obtained using the iPhone's
browser is substantially different from the results obtained using the method described in the '196 patent. The method in the '196 patent results in the generation of a simplified sister site with matrix navigation whereas the iPhone's method results in the rendering of the original page with the ability to zoom and scroll through the page.

## Conclusion
The iPhone's browser does not infringe the '196 patent under the United States Patent Law Statutes of Literal Infringement, and Infringement by Doctrine of Equivalence. Should EMG Technology proceed with this lawsuit, the result will most likely be in favor of Apple Inc. The United States Patent Law Statute allows for Apple Inc to defend itself in two main ways. It could prove that the relevant claims of the '196 patent is invalid on any ground specified as a condition for patentability [including the utility, novelty, and non-obviousness requirements], or failure of the '196 patent to comply with any requirements of section 112 [including the written description and enablement requirements].

Performing several patent searches on the United States Patent and Trademark Office (USPTO) website reveals a plethora of patents and prior art that could render the claims of the '196 patent invalid ongrounds of the novelty, and non-obviousness requirements. 

Some of these relevant patents are:
- [US6574620B](https://patentimages.storage.googleapis.com/34/f2/86/34414480505bc2/US6574620.pdf) 
- [US5621876A](https://patentimages.storage.googleapis.com/4f/b2/21/3547a52acb7632/US5621876.pdf) 
- [US6686927B](https://patentimages.storage.googleapis.com/42/34/bb/aea2ea348fbe3e/US6686927.pdf)
- [US6535896B](https://patentimages.storage.googleapis.com/f4/f2/aa/ed484fd0874981/US6535896.pdf)

Apple Inc, is the assignee of the [US6574620B](https://patentimages.storage.googleapis.com/34/f2/86/34414480505bc2/US6574620.pdf) patent, issued on June 3, 2003. It describes a portable browsing interface for information retrieval. The [US5621876A](https://patentimages.storage.googleapis.com/4f/b2/21/3547a52acb7632/US5621876.pdf) patent, issued on April 15, 1997 is also assigned to Apple Inc. and it describes a method and apparatus for modifying a display matrix in a matrix display area in a window on a computer display screen. Apple Inc. also owns the
[US6686927B](https://patentimages.storage.googleapis.com/42/34/bb/aea2ea348fbe3e/US6686927.pdf) patent issued on February 3, 2004 which describes a method and apparatus for intelligent scrolling. Patent [US6535896B](https://patentimages.storage.googleapis.com/f4/f2/aa/ed484fd0874981/US6535896.pdf), issued on March 18, 2003 to IBM, describes systems, methods and computer program products for utilizing XML-based tools to tailor HTML-based web page content for display within various client devices.

In light of these prior arts, the '196 patent could be rendered invalid on the grounds of novelty and possiblynon-obviousness. Apple has the option of pursuing to have the '196 patent re-examined by arguing that it does not meet the requirements for patentability, based on the prior art. Further EMG Technology risks being sued by Apple Inc, IBM and other companies, all of which have patented technologies that predate the '196 patent. Overall, it will be very difficult for EMG Technology to prove that the iPhone infringes on its '196 patent without mitigating the risk of its patent being reexamined and invalidated.

## References
- Schox, Jeffery. Patent Law and Strategy for Inventors and Entrepreneurs. 
- [Electronic Rough Draft United States Patent and Trademark Office from December 2, 2009](http://www.uspto.gov)
- [Wikipedia: “iPhone” entry from December 2, 2009](http://en.wikipedia.org/wiki/IPhone)
- [Wikipedia: “WebKit” entry from December 2, 2009](http://en.wikipedia.org/wiki/WebKit)
- [Apple Inc. website from December 3, 2009](http://www.apple.com)
- [MacDailyNews article on November 24, 2008: "EMG Technology files patent infringement lawsuit against Apple over iPhone Internet Navigation."](https://macdailynews.com/2008/11/24/emg_technology_files_patent_infringement_lawsuit_against_apple_over_iphone/)
