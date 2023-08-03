What does CSS stand for?
Answers:CSS stands for "Cascading Style Sheets." CSS

How is CSS used within a webpage?
Answers:CSS within a webpage allows you to define styles for various HTML elements, classes, and IDs, giving you control over the visual aspects of your website. With CSS, you can set colors, fonts, spacing, borders, background images, and more, enabling you to create a visually appealing and consistent design for your web pages. Additionally, CSS provides responsiveness, allowing your website to adapt to different screen sizes and devices.

Can CSS work without HTML?
Answers:CSS cannot work without HTML.

What does CSS consist of?
Answers:Selectors Properties Values Declaration Blocks Stylesheets

Is the goal to learn all of the CSS properties? If not, what is the goal for learning CSS?
Answers: my goal is to learn all css properties

What is the syntax for CSS?
Answers:The syntax for CSS consists of rules, selectors, properties, and values. CSS rules are applied to HTML elements to control their appearance and layout.

What is a selector?
Answers: CSS selectors can be based on various criteria, such as the element's tag name, class, ID, attributes, or relationship to other elements. The rules defined for a selector will be applied to all matching elements in the HTML document.

What are Declaration(s)?
Answers:CSS a declaration is a combination of one or more property-value pairs that define the styles to be applied to a specific group of HTML elements selected by a CSS selector. A declaration is enclosed within curly braces {} and forms part of a CSS rule.

What is a Declaration Property?
Answers:CSS a declaration property is the first part of a declaration within a CSS rule. It represents a specific aspect of an HTML element's style that you want to control. Properties define the visual appearance, layout, and behavior of the targeted HTML elements.

What is a Declaration Value?
Answers:CSS a declaration value is the second part of a declaration within a CSS rule. It represents the specific setting you want to apply to the corresponding CSS property for the targeted HTML elements.

What is a Declaration Block?
Answers:Declaration values allow you to define the specific style settings for CSS properties, determining how the selected HTML elements will appear on your web page. By customizing the declaration values, you can create visually appealing and consistent designs across your website.
Video 2:

What are the 3 ways to connect CSS to HTML?
Answers: Inline CSS Internal CSS (Embedded CSS) External CSS (Linked CSS)

What is inline CSS?
Answers:Inline CSS is a method of applying CSS styles directly to individual HTML elements using the style attribute. With inline CSS, you define the styles within the HTML tags themselves, allowing you to customize the appearance of specific elements on the page.

What is internal CSS?
Answers:Internal CSS, also known as embedded CSS, is a method of including CSS styles directly within an HTML document. With internal CSS, you define the styles in the <head> section of the HTML file, using the <style> element. The styles specified inside the <style> element apply to the entire HTML document or specific sections of it.

What is external CSS?
Answers:External CSS is a method of linking a separate CSS file to an HTML document to apply styles to its content. Instead of defining styles directly within the HTML document, external CSS keeps the styles in a separate .css file, promoting better organization, maintainability, and reusability of styles across multiple web pages.

Which CSS approach uses an attribute to add style
Answers:Attribute selectors provide a powerful and flexible way to apply styles to elements based on their attributes, giving you more control over the presentation of your HTML content. They are particularly useful when you want to style specific elements without adding extra classes or IDs to the HTML structure.

Which of the 3 ways to add CSS is the best approach and why? Which is the worst and why?
Answers:External CSS (Linked CSS): Best approach for most projects, external CSS is considered the best approach. It promotes separation of concerns, making it easier to manage and maintain both HTML and CSS code. It allows for reusability of styles across multiple web pages, resulting in cleaner and more organized code. External CSS also allows for easy collaboration among developers, as the styles are stored in a separate file and can be version-controlled using tools like Git.

inline CSS is the worst Violates separation of concerns, mixing content with presentation.
Hard to maintain and update, as styles are directly embedded in HTML elements.
Difficult to reuse styles across multiple elements or pages.
Decreases readability and makes the HTML code cluttered.

Should CSS code be contained within an HTML file? Why or Why not?
Answers: xternal CSS, where CSS code is contained within separate .css files and linked to HTML documents using the <link> element, is the preferred and recommended approach for web development. It provides better organization, reusability, maintenance, and scalability, making it easier to create and maintain professional and consistent websites.

Do we use the link element to hyperlink to another page?
Answers:No, the <link> element in HTML is not used to create hyperlinks to another page. The <link> element is used specifically to link external resources, such as external CSS stylesheets, favicons, or alternate versions of the same web page for different devices or languages.

Which CSS approach utilizes the link element?
Answers:the "External CSS" method. The <link> element is specifically used in the HTML document to link an external CSS file to the webpage. This allows the styles defined in the external CSS file to be applied to the content of the HTML page.

Video 3: (Use W3schools to support answers)

What does the font-size property do?
Answers:The font-size property in CSS is used to set the size of the font for text content within HTML elements. It specifies the desired height of the font characters and is measured in various units, such as pixels (px), em, rem, percentages (%), or keywords like small, medium, large, etc.

<!DOCTYPE html>

<html>
<head>
    <title>Font Size Example</title>
    <style>
        p {
            font-size: 18px;
        }
    </style>
</head>
<body>
    <p>This is a paragraph with a font size of 18 pixels.</p>
</body>
</html>

What does the font-family property do?
Answers:provide web-safe fonts in the font-family property to ensure that your text displays correctly across different devices and browsers.

What does the text-transform property do?
Answers:The text-transform property is useful for adjusting the appearance of text and can be handy for styling headings, buttons, or other text elements in different ways based on the design requirements.

What does the font-style property do?
Answers:The font-style property is useful for adding emphasis or variations to text styles, especially when you want to create distinctions between different parts of your content.

What does the line-height property do?
Answers:The line-height property is commonly used for adjusting the spacing between lines of text, particularly in cases where you want to improve the readability and overall aesthetics of the text content.

What are CSS units and how are they different? (ex. px, em, %, etc.)
What
Answers:CSS units are used to specify measurements for various properties in CSS. They define the size, spacing, and positioning of elements on a web page. CSS provides several types of units, each with its specific use case and behavior.
