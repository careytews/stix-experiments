# stix-experiments
Let's turn STIX into something useful, shall we?

## TA18-149A HIDDEN COBRA

The script `xmlToJSON.js` comes from https://github.com/metatribal/xmlToJSON.

The STIX source was downloaded from https://www.us-cert.gov/ncas/alerts/TA18-149A.

Using VSCode:

1. Join the lines of the `xml` file, so it's one *really* big string.
2. Escape all of the single quotes.
3. Turn the string into a variable, and change the file extension to `js`.
4. Plug the javascript files into the `html` file.
5. Open the web page in your browser, copy and paste the resulting text and save as a `json` file.
6. Fix the JSON, using [the Fix JSON Code plug-in](https://marketplace.visualstudio.com/items?itemName=oliversturm.fix-json).
7. Et voilà!

```
Dear colleagues,

I am sure that I can write code to do this, 
but it would take longer than the above. 

When I repeat it, I'll automate it.

Love, Carey :-)
```
