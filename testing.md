# Apex Athletics - Testing 
I primarily used Chrome DevTools to test how my code would function, experimenting with different inputs through trial and error to find better solutions. This process helped me troubleshoot obvious issues I wasn’t initially sure how to fix. It was also an effective way to assess how responsive my webpage was.

I applied this method to all three pages. During the process, I discovered several bugs that I hadn’t noticed while writing the code.

Using the W3C Validator was particularly helpful in identifying these issues. Some errors were consistent across all pages since I had copied the generic layout into each one.

# AUTOMATED TESTING
## WC3 HTML Validator
The most consistenst issues i found amongst all my pages are as follows :
- Trailing slash on void elements
- Bad value for attribute src on element img: Illegal character in path segment: space is not allowed.
![Index.html Fixes]()Passed
## WC3 CSS Validator
![style.css Fixes]() 1 Warning :Imported style sheets are not checked in direct input and file upload modes
Passed
![style-2.css Fixes]()1 Warning :Imported style sheets are not checked in direct input and file upload modes
![style-3.css Fixes]() 1 Error Found : baseline is not a justify-content value : baseline
Fix - Removed entire line from css form styling.