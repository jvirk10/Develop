Horiseon accessibility code refactor
Refactor of the Horiseon web page to follow accessibility standards and optimize for search engines.

User Story
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

Acceptance Criteria

GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

Changes made

Added a more descriptive title
Added semantic tags in comment form (header, nav, section, article, aside, footer) for better readability.
Added alt text for images
Consolidated repetitive css and made selectors more specific
Re-organized css to better match sections in html
Fixed missing id to make menu link work correctly
Commented HTML and CSS for readability and clarity


screenshot
<img width="1280" alt="Screen Shot 2022-02-27 at 6 45 52 PM" src="https://user-images.githubusercontent.com/99306075/155905152-8531ecdb-f5f9-4d67-b79d-2062ee6febc1.png">


