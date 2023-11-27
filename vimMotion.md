### Normal Mode

| Key Combination                                   | Action                                                                      |
| ------------------------------------------------- | --------------------------------------------------------------------------- |
| `w`                                               | Move forward at the beginning of the word                                   |
| `b`                                               | Move backward at the beginning of the word                                  |
| `e`                                               | Move forward at the end of the word                                         |
| `0`                                               | Move to the beginning of the line                                           |
| `$`                                               | Move to the end of the line                                                 |
| `_`                                               | Move to the first character of the line                                     |
| `r`                                               | Replace a character                                                         |
| `f + {character}`                                 | Move forward to the character                                               |
| `t + {character}`                                 | Move forward to just before the character                                   |
| `F + {character}`                                 | Move backward to the character                                              |
| `T + {character}`                                 | Move backward to the character just before it                               |
| **After `f + {character}` and `t + {character}`** |
| `;`                                               | move forward each character for the search                                  |
| `,`                                               | move backward each character for the search                                 |
| `g + g`                                           | Move to the beginning of the document                                       |
| `shift + g`                                       | Move to the end of the document                                             |
| `ctrl + d`                                        | Scroll down                                                                 |
| `ctrl + u`                                        | Scroll up                                                                   |
| `o`                                               | Insert a new line below and enter insert mode                               |
| `Shift + o`                                       | Insert a new line above and enter insert mode                               |
| `s`                                               | Delete the current character and enter insert mode                          |
| `x`                                               | Delete the current character                                                |
| `d + d`                                           | Cut the line                                                                |
| `z + z`                                           | focus the current line in the center of the screen                          |
| `d + $`                                           | Delete from the current cursor to the end of the line                       |
| `c + $`                                           | Delete from the current cursor to the end of the line and enter insert mode |
| `Shift + a`                                       | Cursor enters insert mode at the end of the line                            |
| `y + y`                                           | Copy the line                                                               |
| `p`                                               | Paste (can paste the copied line and cut line)                              |
| `y + i + w`                                       | copy current word                                                           |
| `space + v`                                       | Open split window vertically                                                |
| `space + s`                                       | Open split window horizontally                                              |
| `space + h`                                       | Focus left window                                                           |
| `space + l`                                       | Focus right window                                                          |
| `space + j`                                       | Focus below window                                                          |
| `space + k`                                       | Focus above window                                                          |
| `*`                                               | Search forward for the current word on the cursor                           |
| `#`                                               | Search backward for the current word on the cursor                          |
| `v + i + {`                                       | Select from `{` to `}` excluding the curly brackets                         |
| `v + a + {`                                       | Select from `{` to `}` excluding the curly brackets                         |
| `y + i + p` | Copy before new line|
| `y + a + p` | Copy till new line |
### Visual Mode

| Key Combination | Action                  |
| --------------- | ----------------------- |
| `v`             | Enter visual mode       |
| `Shift + v`     | Enter visual line mode  |
| `v + i + w`     | Select the current word |
| `o` | Jump back and forth between the selection start and end |

### Other VimVsCommand

| Key Combination                          | Action        |
| ---------------------------------------- | ------------- |
| `Shift + h`                              | Tab switching |
| `Shift + l`                              | Tab switching |
| `Ctrl + e`                               | File explorer |
| In File Explorer (Open with `Ctrl + e`): |
| `n`                                      | New file      |
| `r`                                      | Rename file   |
| `d`                                      | Delete file   |
| `c`                                      | Copy file     |
| `p`                                      | Paste file    |
| `Shift + n`                              | New folder    |

### Integrated Terminal Commands

| Key Combination    | Action                         |
| ------------------ | ------------------------------ |
| `Ctrl + Shift + j` | Show Terminal                  |
| `Ctrl + Shift + w` | Kill Terminal                  |
| `Ctrl + Shift + n` | New Terminal                   |
| `Ctrl + Shift + a` | Focus on the next Terminal     |
| `Ctrl + Shift + b` | Focus on the previous Terminal |
