# Day 03 Reflection

## 1. Which path was easiest to get wrong, and why?
The image path was easiest to get wrong because the folder name and image filename must match exactly. The file extension must also be correct.

## 2. How did you confirm a link points to the right destination?
I opened both HTML pages in a browser and clicked each navigation link. I checked that the Home and About links opened the correct pages and that the Projects link moved to the projects section.

## 3. What is the difference between a page link and a fragment link?
A page link opens another HTML page, such as `about.html`. A fragment link jumps to an element on a page using its ID, such as `index.html#projects`.

## 4. What would you improve before showing this mini-site to another student?
I would add CSS to improve the layout, check the pages on mobile screens, and make sure all links and images work.

## Bug tested: Broken image path
- **Issue:** The image did not appear when the filename in the `src` attribute was misspelled.
- **Cause:** The HTML path did not match the actual image filename.
- **Fix:** I restored the correct path: `images/profile.jpg`.
- **Result:** The image loaded after the correct filename and path were restored.

## Final note
The image path test was performed in the browser. The correct image path was restored, and the image loaded successfully.
