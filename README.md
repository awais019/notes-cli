# NOTES CLI

## Description

This is a CLI tool that allows you to take notes in the terminal. You can add, remove, list, and read notes.

## Commands

- `note new <note>` Create a new note
- `note all` get all notes
- `note find <filter>` get matching notes
- `note remove <id>` remove a note by id
- `note web [port]` launch website to see notes. Default port is 5000
- `note clean` remove all notes

## Flags:

- `--tags, -t` add tags to a new note

## Running the CLI

- Clone the repo
- Run `npm install`
- Run `npm link`
- Run `note --help` to see all available commands

## Example

- `note new "This is a new note"` will create a new note with the content "This is a new note"
- `note all` will list all notes
- `note find "new"` will list all notes that contain the word "new"
- `note remove 1` will remove the note with id 1
- `note web` will launch a website to see all notes
- `note clean` will remove all notes
- `note new "This is a new note" -t "tag1, tag2"` will create a new note with the content "This is a new note" and tags "tag1" and "tag2"
- `note new "This is a new note" -t "tag1, tag2" -t "tag3"` will create a new note with the content "This is a new note" and tags "tag1", "tag2", and "tag3"

## Technologies

- Node.js
