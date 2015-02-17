GitHub Wiki Search Functionality for Chrome
===========================================

This workaround is based on the awesome extension, [github-wiki-search](https://github.com/linyows/github-wiki-search) which can be downloaded as a [Google Chrome extension](https://chrome.google.com/webstore/detail/github-wiki-search/gdifdhnjmjaidbajhapmbcbnoocoeooc).

The only downfail of the original extension itself is the lack of GitHub Enterprise support. This is mostly due to security features of Chrome extensions. This workaround will enable search functionality on any GitHub Enterprise site through the use of a javascript injection extension called [Custom Javascript or CJS](https://chrome.google.com/webstore/detail/custom-javascript-for-web/poakhlngfciodnhlhhgnaaelnpjljija?hl=en) and a slightly modified version of the original Wiki-Search script.

Procedure
----------

 1. Add the CJS extension to your Chrome environment: [chrome store](https://chrome.google.com/webstore/detail/custom-javascript-for-web/poakhlngfciodnhlhhgnaaelnpjljija?hl=en)
 2. Browse to your GitHub Enterprise site location.
 3. Open the modified script file, `github-wiki-search.user.js` and copy the entire script into the clipboard.
 4. Click the 'cjs' icon in chrome to open the extension for this page.
 5. Ensure that the domain in the top left dropdown box is where you desire the script to execute.
 6. Paste the script in the clipbaord to the box in cjs.
 7. Ensure that the checkbox to enable cjs on this site is enabled/checked.
 8. Ensure that the inject dropdown box is set to `--nothing--`.
 9. Click the blue `save` button at the bottom left and refresh the page. You should now have a [Search this wiki...] box next to the green `New Page` button on any wiki at the configured domain.  
