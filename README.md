Pootle bugs or feature requests:

**I. Important:**

1. Prevent accidental upload of wrong .po files

2. Preserve edit history per-string if a .po file is uploaded without either "merge with suggestions" or "merge with conflicts as suggestions"

**II. Less important:**

1. People should be able to edit their own suggestions, at least for the first 5-10 minutes since submissions, even if they have no other rights

2. Prevent suggestions to languages people are not registered with

3. Small but annoying bug: Uppercase letters with diacritics are not visible in the edit textbox: https://i.imgur.com/ipbG8eN.png (that should show the string ARATĂ )


**III. Feature requests:**

1. Comments to projects, folders, .po files and individual strings

2. Regex searches

3. Case-independent "exact" searches (I had to search the same word several times since it was present in lowercase and uppercase variants)

4. Search source and target strings simultaneously with different queries for each: for example "find the source string containing 'cat' where the target string contains 'pisică'"

5. Get the edit history between two points in time, at glance, in diff form at the project level and subfolders or individual .po or strings (either like Github's side-by-side diff: https://i.imgur.com/GfFkYVG.png or a raw diff format)

6. Search suggestion history as well as edit history.

7. Search individual people's suggestions, contributions and reviews and across time.

8. Add small textboxes next to suggestions to give reasons why certain suggestions are rejected and give contributers a view of those reasons along with the related string.

9. Add the ability to ignore formatting rules for specific strings (perhaps specifying why), on a string by string basis. For example, Romanian quotes are like „this” and sometimes we also have to put quotes around terms that are unquoted in English, this triggers the 'quotes matching' and the 'double-quote' rule.

10. Related to 9, per-language specific regexes or parsing rules for: common mistakes, terminology violations, style and tone, common formulas etc.
