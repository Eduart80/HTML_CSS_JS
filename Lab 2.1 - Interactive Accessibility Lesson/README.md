# Lab 2.1 - Interactive Accessibility Lesson

Review: Accessibility Enhancements Checklist

Semantic HTML: Ensure that all elements have semantic meaning. Replace <div> and <span> tags where appropriate with semantic elements like <header>, <main>, <section>, <article>, <nav>, and <footer>.

ARIA Roles and Attributes:

Use ARIA attributes to improve accessibility for screen readers.
For example, use role="navigation" for navigation menus or aria-live="polite" for dynamically updated content.
Color Contrast:

Check and adjust the color contrast to ensure text is readable against the background.
Use tools like the WebAIM Contrast Checker  to validate color contrast ratios.
Alternative Text for Images:

Add meaningful alt attributes to all images. If an image is decorative, use alt="" to hide it from screen readers.
Keyboard Navigation:

Ensure all interactive elements (like buttons and links) are accessible using the keyboard.
Use the :focus pseudo-class to provide visual feedback when elements are focused.
Accessible Forms:

Add label elements to form controls and associate them using the for attribute.
Use aria-describedby for additional instructions or error messages.