# Markdown Cheatsheet (GitHub-Flavored Markdown)

## Basic text
# H1
## H2
### H3

*italic* or _italic_
**bold** or __bold__
***bold italic***
~~strikethrough~~

## Line breaks and paragraphs
Paragraphs: separate by a blank line.

Line break (soft): end a line with two spaces then press Enter.  
Hard break: use HTML `<br>` if needed.

## Lists
Unordered:
- item
* item
+ item

Ordered:
1. First
2. Second

Nested:
1. Parent
   - Child
     1. Sub-child

## Task lists (useful for TODOs/runbooks)
- [x] Done
- [ ] Not done

Example:
- [ ] Install OS
- [x] Configure network

## Code
Inline: `inline code`

Fenced blocks (syntax highlighting):
```bash
# example shell
sudo apt update && sudo apt upgrade -y