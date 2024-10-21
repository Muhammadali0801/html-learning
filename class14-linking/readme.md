# HTML Links and Linking Techniques

This document covers the various ways of creating and managing links in HTML. It includes explanations for linking to other websites, understanding directory structure, email links, opening links in a new window, and linking to specific parts of the same page.

---

### 1. Basic Links

In HTML, links are created using the `<a>` (anchor) tag. Links can point to other web pages, parts of the same page, files, email addresses, and more. The `href` attribute of the `<a>` tag specifies the destination of the link.

### 2. Linking to Other Websites
To link to external websites, simply use the full URL as the value of the href attribute.

**Explanation**: This link points to wikipedia.org. By clicking it, the user will be taken to that external website. Always use the full URL (https:// or http://) when linking to other sites.

### 3. Directory Structure (Relative Links)
When linking to files within the same website, you can use relative URLs instead of absolute URLs. Relative URLs depend on the current directory structure and file location.

**Explanation**:  If about-us.html is located in the same directory as the current page, this link will work. For files in other directories, you need to adjust the relative path:

**Same Directory**: <a href="page.html">Link</a>
**Parent Directory**: <a href="../page.html">Link</a>
**Subdirectory**: <a href="folder/page.html">Link</a>

**Understanding Relative Paths**:
. (dot) refers to the current directory.
.. (double dot) refers to the parent directory.

### 4. Email Links
You can create a link that opens the user’s default email client to send an email using the mailto: protocol.

### 5. Opening Links in a New Window/Tab
To open a link in a new browser window or tab, use the target="_blank" attribute in the `<a>` tag.

**Explanation**: When the user clicks this link, example.com will open in a new tab or window, leaving the current page intact. For security reasons, it's a good practice to also add rel="noopener noreferrer" when opening links in new windows, as it prevents the new page from accessing your original page:

### 6. Linking to Specific Parts of the Same Page
You can link to a specific section within the same page using anchor links. To do this, you need to assign an id to the target element and then link to that id using a hash symbol (#).

### 7. Linking to Specific Sections on Other Pages
You can also link to a specific section of a different page by combining the page URL with the section’s id.

## Key Points to Remember:

**Absolute Links**: Use the full URL (including https://) to link to external sites.

**Relative Links**: Use directory structure and relative paths to link within the same website.

**Email Links: Use mailto**: to create a link that opens an email client.

**Open in New Window**: Use target="_blank" to open links in a new tab or window.

**Anchor Links**: Use id attributes and hash links (#) to link to specific sections of a page.


