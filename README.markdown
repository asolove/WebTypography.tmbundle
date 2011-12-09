# Web Typography TextMate Bundle

This bundle aims to make it easy to mark up plain text into beautifully-typeset HTML. 

## Features

- *Snippets for real punctuation:* when your cursor is right after a plain ', ", or -, press tab to get a list of html entities for real quotation marks and dashes.

## Coming soon

- *Markup*: More entities, soft hyphens, unicode symbol lookup.
- *CSS helpers*: unclear how this will work.
- *Standard spaces* for optically spacing display text or poor kerning pairs.

## Installation

At a console, execute the following commands:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles

    cd ~/Library/Application\ Support/TextMate/Bundles

    git clone git://github.com/asolove/WebTypography.tmbundle

    osascript -e 'tell app "TextMate" to reload bundles'

And now TextMate should know all about how to create beautiful html typography.
