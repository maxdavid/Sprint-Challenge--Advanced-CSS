# Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

1. What is the difference between an adaptive website and a fully responsive website?
A responsive website uses media queries to dynamically resize based on screen size, and can resize to fit *any* screen size. Adaptive websites have distinct layouts for each sized screens, which must be manually considered on a per-device basis.

2. Describe what it means to be mobile first vs desktop first.
The mobile first is designing a product's mobile design first, and expanding out to other formats from that. This can be important for today's mobile-focused technical lifestyle.

Desktop first is designing the desktop experience first, then the mobile and tablet designs afterwards.

The technical difference might be best explained in @media queries; mobile first designs usually call `max-width` while desktop first often uses `min-width`

3. What does `font-size: 62.5%` in the `html` tag do for us when using `rem` units?
Because `em` and `rem` are directly affected by their parent tag, changing the font size in the `html` tag will scale every other `rem` unit under it.

4. How would you describe preprocessing to someone new to CSS?
Preprocessing is a programming language that compiles to a valid CSS file that can be read by your browser.

5. What is your favorite concept in preprocessing? What is the concept that gives you the most trouble?
My favorite concept is the ability to nest selectors together. It makes for a much cleaner file.

The concept that's giving me the most trouble so far is the sheer number of options and features to learn!

