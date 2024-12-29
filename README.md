# Uncommon HTML Encoding Bug

This repository demonstrates a subtle HTML encoding error and its solution. The bug arises from improper encoding of HTML special characters, leading to unexpected rendering or parsing errors in the browser.

## Bug Description

The bug is characterized by the incorrect rendering of HTML special characters, such as < and >, which may be misinterpreted as tags instead of plain text.  This can result in broken layout or incorrect behavior.

## Solution

The solution involves proper HTML encoding of special characters using HTML entities: &lt; for < and &gt; for >. This ensures that these characters are displayed as plain text and not interpreted as HTML tags.

## How to reproduce

1. Clone this repository.
2. Open `bug.html` in your browser. Observe the incorrect rendering.
3. Open `solution.html` in your browser. Observe the correct rendering.