# A widont plugin for Jekyll

## Installation

Create a _plugins directory in your Jekyll site. Put the widont.rb file in the _plugins folder and restart your Jekyll process.

## Usage

The plugin works like any other standard Liquid filters. Simply pass the text you want to process through the widont keyword using a pipe character.

    <h1>{{ page.title | widont }}</h1>

## Version History

1.0 Initial release for Jekyll 0.11

## Feedback and Bugs

Please report bugs or other feedback at https://github.com/scottboms/jekyll-widont