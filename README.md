# Crux Tutorial

Official Crux "Space Adventure" Tutorial

## Quickstart

Read the tutorial: https://nextjournal.com/crux-tutorial/
Try online: https://nextjournal.com/try/crux-tutorial/

## Install Tutorial on Nextjournal

The Quickstart is the easiest way to run the tutorial and you can use the Nextjournal
"Remix" feature to bring the tutorial into your own Nextjournal Clojure notebooks if you
like. However, you can import the Markdown files in this repository directly, if you would
prefer.

1. Create a new account on [Nextjournal](https://nextjournal.com).
2. Download a Markdown file from this repository root.
3. Click "+ NEW" to create a new notebook on the [Nextjournal Dashboard](https://nextjournal.com/dashboard).
4. At the bottom of the page, choose "Import: Select a Markdown file to import" and upload the `.md` file you downloaded in Step 2.
Do not use "Import from a (GitHub) URL" -- it will not work.
5. Once imported, scroll down to the EDN block which begins with `{:deps ...` under "Runtime Setup".
Hover your cursor over this EDN block and an ellipsis ("...") will appear on the lefthand side.
Click the ellipsis.
Choose "Assign Name" and enter `deps.edn`.
6. Open the Clojure Runtime Settings by clicking "Runtimes: Clojure" in the lefthand sidebar.
Scroll down to "Mounts" and click "+ Add mount".
Select `deps.edn`.
Click "Save changes and start" in the dialog that appears at the top.

You can now run the tutorial notebook.


## Copyright & License

The MIT License (MIT)

Copyright © 2019-2021 JUXT LTD.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
