nPOPuk v3.04                                     readme.txt
                                            2 November 2017
-----------------------------------------------------------


Contents
--------
1. Introduction
2. Installing the Fix
3. What's New
4. What's Planned
5. Upgrading from an earlier version of nPOP


-----------------------------------------------------------
1. Introduction

Thank you for downloading this release of nPOPuk.  Versions
for each of the supported platforms, significanly enhanced
from the source code of nPOP originally written by Tomoaki
Nakashima, have been created by English speaking users of
the program.

The latest public release of the "UK versions" of nPOP,
both source and executable code, are available at
http://www.npopuk.org.uk/downloads.htm.
Pre-release versions are available to subscribers of the
npopsupport mail list at:
http://groups.yahoo.com/groups/npopsupport/files


Thanks must go to programmers Geoffrey Coram, Bruce
Jackson, and Amy Millenson, as well as the other members
of the development/test team.

Greg Chapman
Webmaster
http://www.npopuk.org.uk


-----------------------------------------------------------
2. Installing nPOPuk

nPOPuk needs no special installation procedure.  Simply
copy the nPOPuk.exe file to a suitable location and run the
program.

NOTES:
------

*  If you need help configuring nPOP see:
   http://www.npopuk.org.uk/install.htm 

*  If upgrading from an earlier version of nPOP, either
   a "UK" version or one from Tomoaki's site, then see
   the notes in Section 5 of this file.


-----------------------------------------------------------
3. What's New

This version extends the original nPOP v1.0.9 version to
include the following features:

* A box to filter the displayed messages for quick
  searching.

* Highlighting links and making them active in received
  messages (RichEdit functionality). 

* A message-preview pane.

* Ability to supply your own icons.

* Better support for Unicode.

* The code necessary for SSL connections is built in;
  you no longer need to find the OpenSSL DLLs.
  This product includes software developed by the OpenSSL
  Project for use in the OpenSSL Toolkit.
  (http://www.openssl.org/)
  This product includes cryptographic software written by
  Eric Young (eay@cryptsoft.com).
  Please read LICENSE_openssl.txt
  The Windows CE versions of this program also include
  software from http://www.essemer.com.au/
  Please read LICENSE_wcecompat.txt

* Option to set receive options (eg, number of lines to
  download on check) on a per-account basis, instead of
  globally.

* Option to receive messages in reverse order (newest first).

* Ability to delete all messages from the server
  (without downloading anything first).

* For Windows Mobile and WindowsCE devices, the ability
  to automatically activate the Wi-Fi connection to
  check mail.

* Ability to ignore "Re:" or "Fwd:" when sorting the
  main window's list of messages by subject.

* Ability to sort by the bare e-mail address when sorting
  the main window's list of messages by the 'From' column.

* Navigation buttons to move forward/backward between
  sent messages in the Outbox.

* An advanced options editor, to modify the global options
  by editing in a text window.

* Ability to import Internet Setup files (*.ins) to
  configure accounts.  Templates for popular mail services
  (GMail, Yahoo! Mail, etc.) are available.

* Clickable text in message body indicating partially
  downloaded messages (click to initiate full download)
  and listing attachments (click to open).

* Ability to redirect messages (conditional on your ISP
  supporting this function)

* An optional second pane in the main window to list the
  accounts (for easier access than the drop-down list).

* A progress bar to graphically show the percentage of a
  message being downloaded or sent.

* Search and Replace, with wildcards.

* Reflow selection - to correct bad linebreaks, especially
  in quoted text.

* Ability to Flag messages for follow-up.

* Changes to the toolbars to add additional icons and
  replace grayed icons with ones that are applicable for
  the current mailbox.

* Global filters - applied to all accounts.

* Scrambling (ROT-13) to obscure mail data from prying eyes

* Ability to handle embedded images when opening text/html
  messages in a web browser.

* Auto-complete of addresses.

* Indication of unsent mail (in the status bar).

* Filter improvements: new filter actions to forward to
  a specified address or change the priority of a message;
  filter conditions for any address in the address book
  or one in a particular group, or for checking relative
  dates (N days ago).

* Ability to salvage mail data already received if the
  connection is lost (wifi, dialup, or otherwise).

* Ability to open attached messages in nPOPuk itself,
  including an ability to parse MIME-digests into
  separate messages.

* Option to re-filter messages on full download.

* Improvements to the address book, including resizing
  the dialog and sort by column.

* Support for PocketContacts on additional handheld
  platforms (WinCE), and the ability to add entries
  to PocketContacts.

* Command-line options to send a message and quit, or to
  check mail and quit, or to close a running session.

* Ability to suppress text in the forwarding and reply
  headers, if the corresponding header in the orignal
  message is blank.

* Menu item to paste as quotation.

* Ability to Find in the OutBox.

* New options for navigating between messages.

* Multiple saveboxes.

* Support for MBOX-format mail files, including importing
  of mailboxes from other clients.

* Menu item for backing up files.

* Icon in the main mail list window to indicate messages
  that are multipart/alternative, generally meaning the
  only attachment is an HTML version of the message.

* Rudimentary parsing of html-only messages to make them
  readable.

* Ability to group addresses in the address book, and 
  show addresses based on their group membership; further
  improved in 2.08 so one can set a group that is shown
  by default.

* Overlays in the main mail list window to indicate whether
  messages have been forwarded and/or replied to.

* Improvements to word-wrapping for English text as well as
  text in most European character sets (the original nPOP
  is for Japanese Unicode).  Linebreaks no longer happen
  at punctuation or non-English characters, extra spaces at
  the beginning of lines are removed, and quoted lines are
  broken before having the quotation mark ("> ") added.

* Correct indication of whether a message has been fully
  downloaded, even if nPOP is set to download only the
  first N lines.  (Previously, nPOP would indicate partial
  download when set to download only N lines, even if
  the message was in fact shorter than N lines.)

* The size column in the OutBox includes the attachments,
  so one can better estimate the upload time.

* The message composition (Edit) window now has separate
  icons and menu items for "Send now", "Save to Outbox",
  and "Save and Mark" to send later (on the next update
  account); this replaces the AutoMarkSend global option
  found in previous UK versions of nPOP.

* One may quote only portions of a message when replying
  or forwarding by selecting the desired text in the Mail
  View window before initiating the reply/forward.

* Dates now display correctly, regardless of the time zone
  of the sender and recipient.  The date and time format
  can be set in the Global Options dialog "Other" tab.

* When the Global Option "Include header lines" is checked,
  the View source option is used to view the header lines.
  (Previously, in text-only messages, the headers intruded
  into the message body.)

* Sent mail can no longer be edited.

* The Reply-To address can be selected from a drop-down
  list.

* Filters are now correctly moved with accounts when
  reordering (Move up/down).

* Messages that include lines starting with "from"
  (regardless of case) are handled correctly.

* The Help/About dialogue now includes a reference to the
  nPOP UK Support web site.

* New icons and toolbar button images.

* A Mail Forwarding facility
  (Further improved over nPOPw v1.0.1.4 Beta 2, with
  the ability to forward the message as an attachment
  or in-line, with or without attachments, as well as
  additional Global Option settings, such as different
  headers for Reply and Forward, and whether to add the
  signature to forwarded mail.)

* Global Options to allow:
    Disabling of Warning Popup Boxes
    Control of Mail List Sorting

* An option to Save all working files without exiting. 

* Support for mail priorities (High, Normal and Low). 

* Support for read and delivery receipts.

* In new installations, the quotation string for replies
  and forwarded mail is "> " rather than ">".

* Many revised translations and corrected spellings in
  menus and dialogues throughout the program.  (See also
  Section 5.)


-----------------------------------------------------------
4. What's Planned

A small group of programmers are working to improve nPOP.
If you have programming skills and wish to help you may
contact them through the npopsupport mail list.
(See: http://groups.yahoo.com/groups/npopsupport/)


-----------------------------------------------------------
5. Upgrading from an earlier version of nPOP

When first starting nPOPuk, the program looks for its
settings in a file nPOPuk.ini in the same directory as the
executable.  If no such file is found, nPOPuk will then
look for nPOP.ini, created by a Tomoaki Nakashima version
of nPOP or an earlier "nPOP-uk" version.  If the file is
found, you will be prompted whether to import those 
settings or not.

If you choose to import them, then SaveBox.dat will be
copied into a new "savebox-type" mailbox.  nPOPuk does not
use SaveBox.dat after this point, and you may delete the
file if you do not intend to return to a previous version
of the program.  Note that nPOPuk and nPOP both use the
MailBox?.dat files to store incoming messages and
SendBox.dat to store outgoing.  If you create a new
account/mailbox in either program, the other program will
be unaware, and data may be lost.

One of the features of nPOPuk is that it corrects the
spelling of four entries that appear in the nPOP.ini file
created by versions of the program obtained from Tomoaki
Nakashima's site.  If you import nPOP.ini, the misspelled
versions are automatically replaced by the correct settings
in nPOPuk.ini.

  Original entry        Replaced by
  --------------------------------------------
  StertPass             StartPass
  MstchCase             MatchCase
  ShowNewMailMessgae    ShowNewMailMessage
  ActiveNewMailMessgae  ActiveNewMailMessage

Additionally, the unused entries sBura and sOida (believed
to be related to word-wrapping for Japanese text) are
automatically deleted from nPOPuk.ini.

nPOPuk also changes the way messages are stored on disk,
saving some disk space and adding some functionality at the
cost of making the mailbox files incompatible Tomoaki's
releases.  (The message text will still be readable, but
information about whether the message was downloaded
or marked for downloading/deletion/sending will not be
correct.)

Compared with Tomoaki's nPOP, nPOPuk incorporates a new,
more sophisticated, date handling routine that enables
the correct sorting of mail from across different time
zones.

However, depending on the date format used (a setting found
in the nPOPuk.ini file) and the settings for Mail List
Sorting (Found on the Other tab of the Global Options
dialogue), on initial upgrade dates may not, initially,
display correctly in the main window.

To correct any problem, simply open the Mailbox Menu and
select "Initialise".  On the dialogue that appears, under
the section "When checking mail download:" set the radio
button to "Mail from item number:" and in the associated
box enter the value "1" (without quotes).

When you next check you mail, all mail will be read again
and the list re-populated, now showing in the desired
format and correct order.

Finally, some previous versions of nPOP set the TimeZone
entry in nPOP.ini to "+0000" (GMT).  Generally, the entry
should be blank, i.e.:
TimeZone=
so that nPOP uses the time zone set by the Windows
operating system (and tracks changes if you travel with
your laptop and change the time zone).  If you import
nPOP.ini, you may want to check nPOPuk.ini for this
setting.

-----------------------------------------------------------
EOF
