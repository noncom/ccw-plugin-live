# ccw-plugin-live
#CounterClockWise IDE plugin enabling more live-coding features

(all this text is alpha version and a subject to change)

##Currently the following goals are known:

1. Change namespace from within repl - probably press a hotkey and get an autocomplete prompt on all available namespace files to navigate quickly
2. A hotkey to clear all console and repl output at once
3. Open an editor in the ns that is currently open in the repl: if the editor is already opened, switch to it, if the editor is not open then open at the beginning of the file, if the input cursor is on a symbol, open the editor at that symbols definition.. in any of these cases - put the focus into the editor and let type at the caret
4. a hotkey to move focus from the editor to the repl without any changes anywhere
5. a hotkey to move focus from repl to the currently opened editor(last focused)..

the 4) and 5) can be 1 hotkey, depending on the current state