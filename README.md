# jsx-renamer
rename JSX files that have the .js extension to .jsx, and fix imports throughout the project

## What it's for

Suppose you have a project with a bunch of JSX files, but you've named them with the .js extension instead
of the .jsx extension.

Perhaps you don't want this.  Perhaps you would like to enable the `react/jsx-filename-extension` rule in your .eslintrc

Now you want a tool that will find the files with JSX in them, and do all the
renaming for you, and also fix imports in other files referencing the renamed files.

This does that.

## Usage
Open up [the script](./jsx-renamer) and read the comments for instructions.

You will need to make changes to the script before it will do anything.

## An apology

It's written in ruby, not js, and doesn't leverage any of the js/es6 tooling out there that deals with packaging
and importing.  This is kind of silly, and also inconvenient for js programmers who haven't seen ruby before.
For this I apologize.
