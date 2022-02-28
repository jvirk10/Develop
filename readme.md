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
![snip3](https://user-images.githubusercontent.com/99306075/155905893-01734a84-8d5f-401e-810b-7dadb4be1286.png)
![snip2](https://user-images.githubusercontent.com/99306075/155905901-13dd528a-5ff9-43c3-8862-169342e4436c.png)

Page Published at  https://jvirk10.github.io/Develop/
