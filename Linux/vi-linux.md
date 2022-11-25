### vi

#### ESC command mode
| Combination | Usage                         |
|-------------|-------------------------------|
| ESC         | enter command mode            |
| i           | insert before cursor          |
| I           | insert before line            |
| a           | append after cursor           |
| A           | append before cursor          |
| o           | open blank line before cursor |
| O           | open blank line above cursor  |

#### Quitting Vi
| Combination | Usage                                  |
|-------------|----------------------------------------|
| :x          | Exit, saving changes                   |
| ZZ          | Exit, saving changes                   |
| :wq!        | Exit, saving changes                   |
| :q!         | Wipe out your edits and quit           |
| :e!         | Return to the last version of the file |

#### Moving
| Combination | Usage      |
|-------------|------------|
| h           | Move left  |
| j           | Move down  |
| k           | Move up    |
| l           | Move right |

#### Moving Complex
| Combination | Usage                                                      |
|-------------|------------------------------------------------------------|
| w           | Move to the beginning of the next word                     |
| W           | Move to the beginning of the next blank delimited word     |
| b           | Move to the beginning of the previous word                 |
| B           | Move to the beginning of the previous blank delimited word |
| e           | Move to the end of the next word                           |
| E           | Move to the end of the next blank delimited word           |
| 0           | Move to the begining of the line                           |
| $           | Move to the end of the line                                |

#### Changing text
| Combination | Usage                                                     |
|-------------|-----------------------------------------------------------|
| cw          | To the end of a word                                      |
| c2b         | Back two words                                            |
| c$          | To the end of the line                                    |
| C           | To the end of the line                                    |
| c0          | To the beginning of the line                              |
| cc          | The whole line                                            |
| S           | The whole line                                            |
| r           | Replace one character                                     |
| 4s          | Substitute 4 characters with new text until you press ESC |
| 4r          | Replace the next 4 characters with the same character     |
| 4s          | Replace the next 4 characters with different characters   |
| R           | Replace until you ESC                                     |

#### Deleting text
| Combination | Usage                                   |
|-------------|-----------------------------------------|
| dw          | Delete a word                           |
| x           | Delete character to the right of cursor |
| X           | Delete character to the left of cursor  |
| D           | Delete to the end of the line           |
| dd :d       | Delete current line                     |
