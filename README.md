# HTML-CSS

# INTRODUCTION-TO-HTML 101

# HTML SYNTAX ---------------------------------------------------------------------------------------------------------------------------------------------------------------
1. **HTML Structure:**
   - HTML is a language used to structure web pages.
   - Tags, enclosed in less-than and greater-than symbols, mark different elements.
   - Two types of tags: opening tags (<tag>) and closing tags (</tag>).


2. **HTML Elements:**
   - Elements are defined by tags and contain content.
   - Some elements require both opening and closing tags, while others do not.

3. **Markup Purpose:**
   - HTML markup gives meaning to content and helps computers understand it.
   - Acts as a bridge between the human and computer worlds.


4. **Nested HTML Elements:**
   - HTML elements can be nested within one another.
   - Entire HTML documents form a tree structure (DOM tree) with parents, children, and siblings.
   - DOM tree is important for CSS, JavaScript, and accessibility.


5. **Practical Example of Nesting:**
   - An article is an example of nested HTML elements.
   - Opening and closing tags define the article, headline, paragraphs, and emphasized text.
   - Proper nesting conveys meaning and affects the user experience.

6. **Closing Tags Importance:**
   - Forgetting to include closing tags is a common mistake in HTML.
   - Proper opening and closing of tags are crucial to conveying content meaning.


# HTML HEADLINES ----------------------------------------------------------------------------------------------------------------------------------------------------------

1. **Role of Headlines:**
   - Headlines, titles, and subheadings are crucial for dividing content into digestible chunks and conveying the page's structure.
   - On landing pages, headlines often serve as clickable titles leading to further information.

2. **HTML Headline Elements (h1 - h6):**
   - There are six headline elements in HTML: h1, h2, h3, h4, h5, and h6.
   - Each element has a distinct visual effect, conveying hierarchy and importance.
     
3. **Visual Hierarchy:**
   - h1 is the largest and most prominent, while h6 is the smallest and least attention-grabbing.
   - The visual presentation helps communicate the importance and hierarchy of the content.

4. **Choosing Headline Levels:**
   - Choosing the appropriate headline level is typically straightforward, starting with the opening tag and ending with the closing tag.
   - The challenge may arise in determining the most suitable level for a headline.

6. **Semantic Importance:**
   - Headline levels provide semantic meaning to browsers, distinguishing importance.
   - Consistent use of headline levels is crucial for accessibility, especially for screen reader users.


7. **Design Systems and Consistency:**
   - Design systems promote consistency and semantic success.
   - Teams may have predefined use cases for each headline level, contributing to a cohesive structure.


8. **Flexibility and Enhancement:**
   - No strict formula for using headline levels; flexibility is provided.
   - Leveraging all six levels can significantly enhance content structure and coherence.


# HTML LISTS ---------------------------------------------------------------------------------------------------------------------------------------------------------------

# Types of HTML Lists:
HTML supports three types of lists: unordered lists, ordered lists, and definition lists.

# Unordered Lists:
-Most commonly used type of list.
-Represented by the <ul> element.
-List items are enclosed in <li> elements.
-Each item in the list typically displays with a dot or marker.

# Ordered Lists:
-Similar to unordered lists but with a specific order to the items.
-Represented by the <ol> element.
-List items are also enclosed in <li> elements.
-Displays with numbered steps, indicating the order.

# Definition Lists:
-Used for creating lists resembling key-value pairs.
-Represented by the <dl> element.
-Terms or keys are enclosed in <dt> tags (definition term).
-Descriptions or values are enclosed in <dd> tags (definition description).
-Multiple descriptions for each term can be included.
-Terms and descriptions are placed side by side without additional wrapping.

# Styling and Structure:
-Indentation of list items for better code readability, although it doesn't affect webpage appearance.
-Default appearance of list markers determined by the browser, but can be styled using CSS

# HTML QUOTES -------------------------------------------------------------------------------------------------------------------------------------------------------------

1. **Block Quotes:**
   - Represented by the `<blockquote>` element.
   - Used for enclosing longer quotes, providing semantic meaning.
   - Typically includes the `<p>` element for paragraphs and the `<cite>` element for attribution.
   - Custom styling can be applied using CSS.

2. **Inline Quotes:**
   - Enclosed with the `<q>` element.
   - Used for shorter, inline quotes within text.
   - Automatically provides appropriate quote marks based on language conventions.
   - Comparable to other inline elements like `<strong>`, `<b>`, `<i>`, and `<em>`.

3. **Block vs. Inline Context:**
   - Block-level elements (e.g., blockquotes) create separate blocks on the page.
   - Inline elements (e.g., `<q>`) are meant to wrap around inline text, serving a similar purpose.
   - Understanding the inherent nature of HTML elements is crucial before diving into layout and CSS considerations.

4. **Cite Element:**
   - Used to provide the source or reference of a quote.
   - Typically placed within or after the `<blockquote>` element.
   - Offers semantic value and aids in styling.

5. **Datetime Attribute:**
   - Used to specify dates and times in a machine-readable format.
   - Example: `<time datetime="2025-05-08">May 8, 2025</time>`.
   - Follows a specific format (YYYY-MM-DD for dates, 24-hour clock format for times).
   
6. **Time Element:**
   - Used for indicating time in a standardized format.
   - Can include hours, minutes, seconds, fractions of a second, and time zone.
   - Combining date and time is possible using the `datetime` attribute.

7. **Machine-Readable Time:**
   - Preferred format includes the 24-hour clock, optional seconds, and time zone indication.
   - Example: `15:45 -05:00` represents 3:45 PM in a time zone five hours behind GMT.

8. **Combining Date and Time:**
   - Achieved using the `datetime` attribute with options to separate date and time using 'T' or space.
   - Various acceptable and correct formats exist, applicable to many programming languages.

9. **HTML Attributes and Datetime:**
   - Introduction to HTML attributes, specifically the `datetime` attribute.
   - Precise timing communication to computers facilitated by using the `datetime` attribute.
   - A more in-depth exploration of HTML attributes promised in a later section.


# HTML Code, `pre`, and `br` Elements: -----------------------------------------------------------------------------------------------------------------

1. **Using `<code>` Element:**
   - Utilized to showcase code on a webpage.
   - Opening `<code>` tag before the code snippet and closing `</code>` tag afterward.
   - Results in styling changes with a monospaced font.
   - Default behavior is inline, remaining part of the sentence it's in.

2. **HTML Entities:**
   - Used to display reserved characters in HTML code.
   - Example: `&lt;` for less than sign (`<`), `&gt;` for greater than sign (`>`).
   - Prevents the browser from interpreting code as actual HTML tags.

3. **Using `<br>` Element:**
   - Addresses the need for line breaks in specific scenarios.
   - Unlike regular spaces and line breaks, `<br>` element forces the browser to display them.
   - Simple tag without opening or closing tags, indicating where a line break should occur.

4. **Using `<pre>` Element:**
   - Maintains formatting and spacing, displaying irregular spacing as intended.
   - Useful when precise spacing and line breaks are integral to the content's meaning.
   - Wrapping content in `<pre>` tags allows the browser to respect the spacing and line breaks.

5. **Combining `<pre>` and `<code>` Elements:**
   - Often combined to display a code block with proper indentation.
   - Useful for conveying the structure and appearance of code.
   - Example: Wrapping HTML and CSS code in `<code>` element and further in `<pre>` element to preserve formatting and spacing.

6. **Integration of `<code>`, `<pre>`, and `<br>`:**
   - Illustrative example of combining these elements for effective content presentation.
   - Demonstrates their utility in conveying the structure and appearance of code and other content types.

7. **Versatility of Elements:**
   - `<code>`, `<pre>`, and `<br>` elements serve various purposes in enhancing the presentation and readability of content.
   - Handy for displaying code snippets, poems, and other formatted text on webpages.
  


  # HTML SUPERCRIPTS, SUBSCRIPTS, & SMALL TEXTX: -----------------------------------------------------------------------------------------------------------------------

1. **Subscripts and Superscripts:**
   - Subscripts are characters set below the normal baseline for text.
   - Superscripts are characters set above the normal baseline of text.
   - Commonly used in mathematical formulas, chemical equations, and footnotes.

2. **Using `<sub>` and `<sup>` Elements:**
   - To mark up subscripts, use the `<sub>` element.
   - To mark up superscripts, use the `<sup>` element.
   - Example: `<sub>2</sub>` for subscript and `<sup>2</sup>` for superscript.

3. **Handling Subscripts and Superscripts in HTML:**
   - Wrap the characters needing subscript or superscript in the respective `<sub>` or `<sup>` elements.
   - Adjusts the position and size of the characters accordingly.

4. **MathML for Complex Equations:**
   - For complex mathematical equations, consider using MathML, a specialized markup language for math.
   - More powerful than what HTML can provide for mathematical representation.

5. **Small Text with `<small>` Element:**
   - Used to mark text as fine print or less important but still necessary.
   - Example: Providing copyright information in the footer.
   - Not solely for adjusting text size; CSS can handle that aspect.

6. **Importance of `<small>` Element:**
   - `<small>` is used to convey that a certain passage of text has very little prominence.
   - Helpful for content like fine print at the bottom of a page regarding ownership or copyright information.
   - HTML element choice aligns with the semantic meaning of the content.

7. **HTML Elements for Typography:**
   - `<small>`, `<sub>`, and `<sup>` elements play a crucial role in refining typography and conveying the full meaning of content.
   - They aid in presenting details correctly, enhancing the overall visual and semantic aspects of the content.
  


   # TROUBLESHOOTING & DEBUGGING HTML CODE: ---------------------------------------------------------------------------------------------------------------------------

1. **Using Browser Developer Tools:**
   - Browsers like Firefox provide developer tools that offer insights into a website's code and performance.
   - Access developer tools by right-clicking and selecting "inspect element" or navigating through browser menus.
   - Three main sections in the developer tools: HTML (left), CSS (middle), and additional options (right).

2. **Document Object Model (DOM):**
   - The left pane in developer tools displays the Document Object Model (DOM) created by the browser.
   - Represents the structure of the HTML code, offering a tree-like view of elements.
   - Useful for understanding the hierarchy and relationships between elements.

3. **Inspecting HTML in Developer Tools:**
   - Use the HTML panel in developer tools to inspect HTML elements on a webpage.
   - Observe the DOM tree, identify elements, and understand how they are structured.

4. **Learning from Other Websites:**
   - Study how other developers use HTML by inspecting websites with similar content.
   - Developer tools help identify the HTML elements and structure used by other websites.
   - Learn from admired teams or websites to understand effective HTML structuring.

5. **Debugging HTML Mistakes:**
   - Developer tools are valuable for debugging HTML code.
   - Example scenario: Identifying and fixing a mistake in an unordered list that resulted in an extra, empty list item.
   - Browser's attempt to fix HTML issues may lead to unexpected results, understanding the DOM helps in debugging.

6. **Use of HTML Inspector:**
   - HTML inspector in developer tools aids in reviewing and debugging broken code.
   - Identify mistakes in the HTML code and understand how the browser interprets and modifies it.
   - Correct mistakes, such as missing closing tags, using insights from the HTML inspector.

7. **Developer Tools for Problem Solving:**
   - Whenever uncertainties arise in HTML code behavior, turn to developer tools to investigate and solve problems.
   - Helps in understanding how browsers interpret and process HTML, offering a practical debugging solution.


   # HTML ATTRIBUTES: ---------------------------------------------------------------------------------------------------------------------------

1. **Introduction to HTML Attributes:**
   - HTML elements have a basic version but gain additional capabilities through attributes.
   - Some attributes are specific to certain elements, while others work with multiple elements.

2. **Global Attributes:**
   - Four key global attributes are highlighted: "class" (for styling with CSS), "id" (unique on the entire HTML page), "lang" (specifies language), and "dir" (indicates text flow direction).

3. **Practical Use of Class and ID Attributes:**
   - "Class" is commonly used for styling, while "ID" is unique and valuable for JavaScript and targeted links.

4. **"content editable" Attribute:**
   - Allows visitors to edit webpage content, but page refresh reverts changes.
   - Backend development, typically in JavaScript, is required to capture and save edited content.

5. **Attributes for User Interaction:**
   - HTML attributes, like "content editable," enhance user interaction with the screen, keyboard, and assistive devices.
   - Many attributes provide browser APIs to JavaScript, improving the user experience.

6. **Additional Attributes - "lang" and "dir":**
   - "Lang" specifies content language using a short code, and "dir" indicates text flow direction.
   - Both are Global Attributes usable on any HTML element.

7. **Key Takeaway:**
   - Four essential Global Attributes are "class," "id," "lang," and "dir."
   - Comprehensive lists of Global Attributes can be found on MDM web docs.
   - These attributes enhance web page elements and improve user interaction.

# HTML  ARIA Roles: --------------------------------------------------------------------------------------------------------------------------------------------------------

1. **Introduction to ARIA Roles:**
   - ARIA Roles are additional attributes added to HTML elements to enhance their meaning for assistive technologies like screen readers and braille displays.
   - The primary goal is to use proper HTML elements for content meaning, but compromises may be necessary for accessibility.

2. **Importance of ARIA Roles:**
   - ARIA Roles are crucial for making websites accessible to people with disabilities, ensuring compliance with laws in many places.
   - They play a vital role in providing essential information to assistive technologies, particularly in the context of complex interfaces in web applications.

3. **Example Demonstrating the Need for ARIA Roles:**
   - A CSS Grid experiment, placing each letter of the headline "hello world" in separate grid cells, creates a poor experience for screen reader users.
   - The accessibility tree treats each letter as a separate text container, spelling out the letters individually instead of reading the intended phrase.

4. **Using ARIA to Improve Accessibility:**
   - ARIA can be employed to enhance web accessibility by adding an ARIA label to specify the text that the screen reader should read.
   - Hiding individual letters using ARIA hidden attribute improves the screen reader experience without affecting the DOM tree.

5. **Understanding the Accessibility Tree:**
   - The accessibility tree, parallel to the DOM tree, is crucial for assistive devices like screen readers.
   - It represents the content structure, allowing assistive technologies to provide a better user experience.

6. **ARIA's Impact on Web Accessibility:**
   - ARIA is a powerful tool for improving web accessibility, especially in scenarios where semantic HTML is challenging or when building complex application interfaces.
   - ARIA Roles offer essential tools to ensure website accessibility for everyone.

7. **Key Takeaway:**
   - ARIA Roles are crucial for making websites accessible to people with disabilities.
   - They provide essential tools for conveying meaning to assistive technologies, improving the overall user experience.
   - ARIA is particularly valuable when working with complex interfaces or teams struggling with semantic HTML.


# FORMATTING HTML: ----------------------------------------------------------------------------------------------------------------------------------------------------

1. **Whitespace Handling in HTML:**
   - HTML generally ignores spaces, tabs, and line breaks, except in specific cases like `<pre>`, `<code>`, `<textarea>`, or when modified by CSS.
   - Extra spaces and indentations usually don't matter to browsers and are often ignored.

2. **Comments in HTML:**
   - Comments in HTML are added using `<!--` at the start and `-->` at the end.
   - Browsers disregard comments, but code editors may display them in a grayed-out fashion, enhancing code readability and identifying commented sections.

3. **Uppercase vs. Lowercase in HTML:**
   - In the early days, HTML elements were often capitalized, but modern practices favor lowercase for consistency.
   - Browser support is not affected by the case, and either uppercase or lowercase HTML is handled well.

4. **Length of HTML Elements:**
   - Early HTML elements were often abbreviated to optimize file size due to limited computer resources.
   - As technology advanced, newer elements favored complete words for improved readability and understandability.
   - The length of an HTML element can provide a clue about its historical context and age.

5. **Self-Closing Elements in HTML:**
   - While most HTML elements have both opening and closing tags, newer elements always include both.
   - Older elements, like `<img>`, lacked closing tags initially. Adding a slash at the end (`<img />`) became a best practice, but it is less emphasized in recent years.
   - Browsers accommodate various formatting options for self-closing elements, allowing flexibility in writing HTML. The choice of using a closing slash is up to personal preference.
  

# UNUSUAL CHARACTERS: -------------------------------------------------------------------------------------------------------------------------------------------------------

1. **Handling <, >, and &:**
   - In HTML, the symbols `<`, `>`, and `&` are significant characters.
   - If written with spaces around them, they appear as regular content; however, if resembling an HTML element, they might disappear as the browser assumes they are part of HTML code.

2. **Character Entities in HTML:**
   - Character entities in HTML are represented as an ampersand, a short code, and a semicolon.
   - These entities replace symbols like `<` and `>` to ensure proper display in HTML content.
   - The W3C provides a reference chart for character entities, useful for typing characters not available on the keyboard.

3. **Non-Breaking Spaces in HTML:**
   - Non-breaking spaces have a unique role in preventing line breaks between words.
   - Using `&nbsp;` in HTML ensures that the browser keeps words together on the same line, useful for names like "Lebron James."
   - Non-breaking spaces also enable creating multiple spaces between words, unlike regular spaces that may be ignored by the browser.

4. **Usefulness of Character Entities:**
   - Character entities, including non-breaking spaces, ensure specific characters are displayed as intended on webpages.
   - They offer a solution for handling characters not easily accessible on the keyboard, providing an alternative to copying and pasting or learning keyboard commands.
     
  
# HTML LINKS: ----------------------------------------------------------------------------------------------------------------------------------------------------------------

1. **Introduction to Web Links:**
   - Web links are now commonplace, encountered throughout online experiences in navigation bars, menus, teaser cards, and clickable article titles.
   - The concept of linking, hypertext, and hypermedia has been integral to computing innovation since the 1960s, leading to the birth of the web.

2. **Creating Links with the A Element:**
   - To create a link, the HTML A element (anchor) is used.
   - The A element requires an href attribute containing a URL enclosed in quotes, specifying the destination of the link.
   - Text, images, or both can be placed between the opening and closing A tags to make them clickable.

3. **Linking Text, Images, or Complex Elements:**
   - The A element, by default, is inline and can be placed within paragraphs or any other text.
   - Links are not limited to text; they can also wrap around images or more complex elements, enabling the creation of linked groups of elements.

4. **Absolute URLs for Linking:**
   - URLs for linking can be versatile, including the entire URL when linking to another website or specific web page.
   - Absolute URLs point precisely to a location on the web and must include the HTTP or HTTPS part, which stands for Hypertext Transport Protocol.

5. **Importance of HTTPS in URLs:**
   - HTTPS, where the "S" stands for Secure, is recommended for enhanced security in modern web addresses.
   - While modern browsers automatically add HTTPS://, developers and content creators need to include it when manually creating links.

6. **Significance of HTTP and HTTPS:**
   - HTTP and HTTPS are protocols defining rules for web communication.
   - HTTPS is considered more secure, and its inclusion in URLs is crucial when creating links.

7. **Historical Perspective on Link Creation:**
   - The creation of links, utilizing absolute URLs and protocols like HTTP and HTTPS, was one of the most significant inventions in the early days of the web.
  

   # HTML URL PATHWAYS:----------------------------------------------------------------------------------------------------------------------------------------------------

1. **Absolute and Relative URLs:**
   - Absolute URLs point to a specific location on the web and include the full domain, while relative URLs are based on the current file's location.
   - When working locally or on different servers, using relative URLs allows flexibility in directing links to local copies or testing servers.

2. **Creating Relative URLs:**
   - Relative URLs are essential not just for linking (A element) but also for referencing image files, video files, CSS, JavaScript files, or any other files with specified paths.
   - Understanding file organization is crucial; slashes in a URL indicate navigating the file structure.

3. **Forming Relative URLs:**
   - To create a relative URL, omit the domain name and include the initial slash at the beginning to start from the root level.
   - Alternatively, write the path relative to the file where the link is written.

4. **Example of Relative URL Creation:**
   - Given the file styles.css in a directory named CSS, to link to logo.gif in the images folder, two options are available:
     - /images/logo.gif (relative to the root level)
     - ../images/logo.gif (relative to the current file's location, going up one level).

5. **Understanding URLs with Folders:**
   - In web development, a URL like http://www.awesomedogs.com/people looks for an index.html file inside the people folder.
   - Creating folders and using index.html allows for a clean URL structure but applies only to HTML files, not images or CSS.

6. **Trailing Slash in URLs:**
   - Whether a trailing slash is included or not in a URL doesn't matter; both versions lead to the same destination.

7. **Considerations for Well-Structured URLs:**
   - Crafting well-structured and elegant URLs is essential for user experience and search engine results.
   - Careful consideration of URL impact, especially when using relative URLs, is crucial for projects that move from server to server.

8. **Summary of URL Types:**
   - URLs can be either relative or absolute.
   - Relative URLs are based on the current file's location, while absolute URLs start from the root of the website.
   - Using folders and index.html files can help create clean and user-friendly URLs in web development.
  

# HTML NAVIGATION: ---------------------------------------------------------------------------------------------------------------------------------------------------

1. **Creating Main Navigation:**
   - Main navigation bars or menus can be created by wrapping each link in an "li" element, enclosing the list of links in a "ul" element, and then encompassing the entire menu in a "nav" element.
   - Applying CSS styling enhances the visual appearance of the menu.

2. **Semantic Markup for Navigation:**
   - To convey the purpose of the menu to screen readers and assistive devices, attributes can be added.
   - Assign the role "navigation" to the "nav" element, indicating that it represents the main navigation of the page.
   - Include an "aria label" for the main menu to provide a descriptive label for screen readers.

3. **Breadcrumb Trail Navigation:**
   - Breadcrumb trails are another type of menu where links are wrapped in a "nav" element, and an ordered list ("ol") is used since the order of links matters.
   - Instead of assigning the role "navigation," an "aria label" of "breadcrumb" is added to provide context when read aloud.

4. **Footer Links Representation:**
   - Links typically found in the footer of a page, which are not part of the site's main navigation, can be marked individually as links and wrapped in a "footer" element.
   - No "nav" element or unordered list is necessary for footer links.

5. **Accessibility Considerations:**
   - Semantic markup and attributes like "role" and "aria label" help convey meaning to assistive devices and screen readers.
   - There are various approaches to marking up navigation elements, and the choice depends on specific circumstances and preferences.

6. **Combining HTML Elements for Semantic Meaning:**
   - As HTML elements are combined, there are numerous options to consider for creating menus and navigation bars.
   - Careful consideration of actions and the layering of semantic meaning into content guides the selection of the right approach for each project.
   - There is no one-size-fits-all approach, and choices depend on specific circumstances and desired rendering.
  
   # HTML Working with Graphics and Images--------------------------------------------------------------------------------------------------------------------
      
   - The choice of image file format is crucial for webpages to ensure compatibility with web browsers.
   - There are various file formats available, and new ones are continuously being developed to find the ideal balance between small file sizes and visually stunning images.
   - The goal is to achieve high image quality with the smallest possible file size to ensure faster downloads and minimize data usage for users.
   - Different file formats employ distinct approaches and compression techniques to address the challenge of balancing image quality and file size.


# RESPONSIVE IMAGES

-CSS provides a solution for displaying images in various sizes to cater to both large and small screens.
- Dealing with large, high-resolution images poses a challenge due to their large file sizes, impacting users with slow network connections or limited data plans.
- The traditional approach of reducing image size universally may result in low-quality, enlarged images on larger screens.
  - HTML's responsive image features enable the delivery of different image files to screens of various sizes, considering device capabilities and network speed.
- Basic code for loading an image includes the source attribute pointing to the image file, along with ALT text, width, and height.
  - To support different screens, create multiple copies of an image with varying resolutions and use the source set attribute to inform the browser about these options.
- The source set attribute lists images with resolutions (e.g., 2X, 3X) to allow the browser to choose the appropriate version based on screen density, network connection, and user settings.
  - This technique is useful for handling different image sizes for retina and high DPI screens.
- The next step involves adjusting image sizes based on page layout or width, addressing further customization for responsive design.


# Responsive Width: 

- Building on the previous section, the focus is on making images responsive based on both screen pixel density and viewport width.
- The example involves using the image element and the src set attribute, similar to the previous section.
  - Instead of specifying pixel density (1x, 2x, etc.), now the width of each file is indicated in the src set attribute (e.g., 480w for 480 pixels wide, 960w for 960 pixels wide).
-The browser decides which image to display based on both device density and viewport width.
- A potential issue arises when the chosen image does not fit the desired layout, as the browser makes this decision early in the loading process before knowing CSS or layout details.
- To address this, the sizes attribute in HTML is introduced, allowing specification of which image to use at different breakpoints.
- The sizes attribute enables the browser to download the right-sized image for the layout by indicating how much of the viewport's width the image will take up at each breakpoint.
- Providing information in the HTML through attributes like src set and sizes helps the browser make intelligent decisions, taking into account network conditions and user preferences.

  # Responsive Pictures:

- Source set and sizes attributes enable multiple image files for the browser to determine which one to load based on device characteristics and viewport width.
- Responsive images go beyond resolution replacement, involving displaying different images on small and large screens or using entirely different photos.
- The "picture" element acts as a wrapper, allowing alternative options using the "source" element for various scenarios.
- Example scenario: displaying a photo differently on big screens (showing the whole field and person's body) and small screens (focusing only on the face).
- "Source set" attribute is used in the "source" element to point to different image files for various screen sizes.
- Media queries within the "source" element specify which image to load based on viewport width.
- Browser intelligently switches between files, considering viewport size and retina screens.
- In typical web browsing, only the appropriate image file is downloaded, optimizing webpage performance.
- The main purpose is sending the smallest file while delivering visually appealing images.
- Despite complexity, publishing images is often automated on websites with server robots.
- Effort is justified by significant data savings; optimizing six photos could save three megabytes of data if each photo saves 500k.

# Figcaption and Figures:

- When adding an image to a web page, it's essential to consider captions, and for this purpose, two additional elements are introduced: "figure" and "figcaption."
- An illustration (Figure 58) demonstrates the use of the "figure" and "figcaption" elements.
- To add a caption to a picture of a dog, use the "figcaption" element to wrap the text and specify it as a caption.
- Combine the image and the caption within a "figure" element, providing the browser with more information about the content and the relationship between the image and the caption.
- The use of "figure" and "figcaption" elements goes beyond a regular paragraph or a generic div, helping search engines and AI understand the connection between these content pieces.
- Figures are versatile and not limited to images; they can be used for various visual elements, such as interactive graphics or any content that requires a caption for illustration or concept demonstration.

  
