# Send-Gmail-by-Python
Pythonを使ったGmailの自動送信を実装してみる。

参考先： https://qiita.com/muuuuuwa/items/822c6cffedb9b3c27e21

--------------------------------------------------------------------------

list Gmail Inbox.

Usage:
    listmail.py <query> <tag> <count>
    listmail.py -h | --help
    listmail.py --version

Options:
    -h --help     Show this screen.
    --version     Show version.

--------------------------------------------------------------------------

Send E-Mail with GMail.

Usage:
    sendmail.py <sender> <to> <subject> <message_text_file_path> [--attach_file_path=<file_path>] [--cc=<cc>]
    sendmail.py -h | --help
    sendmail.py --version

Options:
    -h --help     Show this screen.
    --version     Show version.
    --attach_file_path=<file_path>     Path of file attached to message.
    --cc=<cc>     cc email address list(separated by '.').Default None.