# AutoHotKey

A nice place to start is [this][tutorial_send].

[tutorial_send]: https://www.autohotkey.com/docs/Tutorial.htm#Send

## 1. First script

### 1.1. Simple Hotkey

```autohotkey
#j::
Send, nuclear launch codes
return
```

The `#` means the <kbd>Windows</kbd> key. The `^` would mean the <kbd>Ctrl</kbd> key. So, in the example above, we would have <kbd>Windows</kbd> + <kbd>j</kbd> *typing* the text *nuclear launch test codes*. The `return` on the third line is necessary to avoid syntactical problems in general.

### 1.2. Simple Hotstring

When you press a hotkey combination, after the release, something will happen. The difference to a hotstring is that something will happen after you type the string, which might even get completely transformed into another string.

```autohotkey
::ftw::Free the whales
```

For example, the code code above will transform the hotstring *ftw* into *Free the whales* after you type it.

## 2. Making it work

To make it work, after having AutoHotKey installed in your machine:

1. Create a new file, either with:
    - <kbd>right-click</kbd> + <kbd>New</kbd> + <kbd>AutoHotKey Script</kbd>
    - Simply create a new text file and have its extension as `.ahk`.
1. Type your code inside it.
1. Double click your `.ahk` file to run it.

Now, everything should be working.