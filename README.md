We have a wiki page

The goal of this is to have links clickable in both vscode and on https://github.com/wolfderby/wiki_test_links/wiki

file://file1.txt (nope in vscode; )

file://./file1.txt (nope in vscode; )

file://../file1.txt (nope in vscode; )

[file1.txt ./ test link](./file1.txt) (yes in vscode; yes on github)

[file1.txt ../ test link](../file1.txt) (no in vscode; no on github)


[[wiki_test_links.wiki/Home.md]]

