# Configuration files

This is a repository containing configuration files I wrote during the usage of some tools. Most of the tools are already described in howto's a hundred times therefore I didn't tried to reproduce such an already existing howto but giving you a view of the features I combined.

Feel free to adopt, change and create issues or pull requests for them

## mutt

For my mail client I am using mutt a command line mail program. My mail folders are of the mail dir format. Those folders are encrypted using encfs to a dropbox account. That way I always have a backup of my mails and I can access them from everywhere.

I pull my mail using fetchmail and the pop3 adapter. I know IMAP exists but I'm getting used to pop for several years by now.

For sending mails msmtp is what I use with different profiles for different accounts or locations.

Some additional software I use in combination with my mutt setup are:

* collectmail, a bash script which checks if my encfs volume is mounted and then uses some fetchmail commands to get my mail. It's also configured in a cronjob to get mails automatticaly
* urlview, a tool which lists all url's from a text file (https://github.com/sigpipe/urlview)
* mutt-sidebar, a nice feature to get an overview of your folders next to the common mutt view (http://lunar-linux.org/mutt-sidebar)
* mupdf, a clean and simple pdfviewer (http://www.mupdf.com)
* w3m, a tool which I use to convert html based mails into plain text (w3m.sourceforge.net)
* vdirsyncer, which synchronizes my calendars and contacts (https://github.com/pimutils/vdirsyncer)
* khard, a console carddav client which integrates with mutt too (https://github.com/scheibler/khard)
* khal, the cli calendar application I use (https://github.com/pimutils/khal)
