==============================================================================
Installation Instructions
==============================================================================

If you have the .NET framework 4.0 then you can just start the application.
If not then install the .NET framework 4.0 from here:
http://www.microsoft.com/download/en/details.aspx?id=17851


Requires administrative privileges. If you are not logged in as an
administrator then right click the program executable and click "Run as
Administrator". If you do not have those privileges you will get the error:
"System.ServiceModel.CommunicationObjectFaultedException: The communication
object, System.ServiceModel.ServiceHost, cannot be used for communication
because it is in the Faulted state."

==============================================================================
About G19 - League of Legends
==============================================================================

Shows custom timers on the logitech G19 keyboard. The timers as well as their
locations are configurable in the XML file.
It uses about 20kb RAM and (rounded to whole numbers) 0% CPU on low end
systems (using default settings).

Features:
- Fully customizable timers, profiles, backgrounds and sound effects.
- Costs almost no resources.
- Open Source, so no spyware or anything.

==============================================================================
Manual
==============================================================================

- See "Help.pdf" or "Help.odt". Those documents also explain how to bind the
  G-keys.

==============================================================================
Version History
==============================================================================

Version 1.0.6 (June 18 2013)
  - Updates default jungle timers for the 3.8 patch. See:
    http://euw.leagueoflegends.com/news/patch-38-notes
  - On request: The G19 can now bind a key to reset all timers at once
   (code 00).
  - Updated the help file accordingly.
  - When an invalid message is parsed the original message will not be
    displayed in the error code.

Version 1.0.5 (March 30 2013)
  - Added Help.chm and removed the pdf & odt help files.
  - Added a LCD Menu. Use the [Menu] button on the G19 to open the menu.
  - Added a credits section to this file.

Version 1.0.4 (November 28 2012)
  - Increased the selection border thickness from 1f to 2f.
  - Added the new Twisted Treeline (the '2012 Beta') map.
  - Added the option to change your WCF Service port.
  - Enhanced the Config menu a bit.
  - Also included the .pdb file in the release. This makes it easier to
    debug exceptions raised by end-users.
  - The timers background- and text colors can now be configured by editing
    the Timers.xml.
  - Refactored the custom timer code.
  - Paused timers are now colored orange by default (this can be overruled)

Version 1.0.3 (October 21 2012)
  - Added the option to add custom sounds to the timers.
  - Renamed the "Assign G-Keys" documents to "Help" and expanded it.

Version 1.0.2b (September 18 2012)
  - Fixed the default respawn times on Summoners Rift.

Version 1.0.2a (September 7 2012)
  - The SendMessage.exe no longer starts a Windows Form when no error occured.
  - Only one instance of the G19LoL main application can be run at a time.
  - Slightly improved background images.
  - The main window is no longer (shortly) shown on the taskbar after the
    application was just started.

Version 1.0.2 (September 6 2012)
  - The application's main window no longer shows after pressing [Alt]+[Tab].
  - Added the option to bind the G-Keys (or any other application) to this
    application (see the manuals).

Version 1.0.1 (April 14 2012)
  - Fixed a small memory leak.
  - Synched the countdown sound with the time.
  - Switched from WAV to MP3.
  - Can now handle multiple sounds simultaneously.

Version 1.0.0 (April 1 2012)
  - First release.


==============================================================================
Credits
==============================================================================
Menu Background Image : www.OpenGameArt.org (CC0 license)