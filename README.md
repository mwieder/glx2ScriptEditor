# README #

### Release Notes for the GLX2 Script Editor

[Documentation is on the Wiki tab](https://github.com/mwieder/glx2ScriptEditor/wiki)

-----------------------------------------------------------------------
## 2021.11.24 GLX2 4.2.3
-----------------------------------------------------------------------
    Find/Find Again now works like the IDE script editor
    Restored external handler italicization
    Added (and fixed again) the option of custom colorization
    Bernd fixed collapseAll and misquoted literals
    Chalkboard and Alabaster backgrounds are now configurable 
    Custom colorization saved to preferences file
    Fixed OSX toolbar|menubar conflict with 4wdevolution
    Added menu option to upper|lower case control structures
    Custom colorization switch added as suboption of Colorization
-----------------------------------------------------------------------
## 2021.10.21 GLX2 4.2.2
-----------------------------------------------------------------------
    Fixed capitalization of control structures
-----------------------------------------------------------------------
## 2021.09.22 GLX2 4.2.1 (equinox)
-----------------------------------------------------------------------
    Fixed (again) saving font information
-----------------------------------------------------------------------
## 2021.07.10 GLX2 4.2.0
-----------------------------------------------------------------------
    Revived the preference options for italic and/or bold comments
    Time for a major version release.
    Bernd Niggemann has done some amazing work re code folding
    tweaking more speed out of routines
    and cleaning up the visual interface
-----------------------------------------------------------------------
## 2021.05.06 GLX2 4.1.19k
-----------------------------------------------------------------------
    improved gutter clicking speed and effect
    fixed split-screen artifacts
-----------------------------------------------------------------------
## 2021.05.06 GLX2 4.1.19j
-----------------------------------------------------------------------
    removed experimental doResize speed improvements
-----------------------------------------------------------------------
## 2021.05.06 GLX2 4.1.19h
-----------------------------------------------------------------------
    Improved code folding/collapsing
    Rearranged order or colorization and italicization
    Only adjust split window when active
    Bernd Niggemann's experimental doResize speed improvements
    Update check shows available build version and (date)
-----------------------------------------------------------------------
## 2021.04.18 GLX2 4.1.19e
-----------------------------------------------------------------------
    Bernd's additions for faster folding and external handler italicization
 ----------------------------------------------------------------------
## 2021.04.13 GLX2 4.1.19d
-----------------------------------------------------------------------
    Better faster code folding checks
    Fixed: stringified block comment start was causing formatting problems
    Colorization weren't always being triggered
    Right-clicking a constant will set a tooltip to its value
-----------------------------------------------------------------------
## 2021.04.11 GLX2 4.1.19c
-----------------------------------------------------------------------
    Bernd's latest patch for single-line block comments
    Better control over italicized external handler links
    Now forcing evaluation of local handlers on editing a new script
    Speed increase patch to line numbering
    Fixed version number
    Better live colorizing
-----------------------------------------------------------------------
## 2021.04.05 GLX2 4.1.19b
-----------------------------------------------------------------------
      Fixed update check urls (github can't update from folder)
      Unhoused handlers now appear in handler list
-----------------------------------------------------------------------
## 2021.04.03 GLX2 4.1.19
-----------------------------------------------------------------------
      Fixed handler contextual menu
      Refactored a bit for better coexistence with revSETH
      Italicized external references are working again
-----------------------------------------------------------------------
## 2021.03.22 GLX2 4.1.18
-----------------------------------------------------------------------
	  Faster code folding
	  Faster formatting
	  Clairvoyance check no longer triggers compilation
	  fixed problem with errorline of zero
	  adding cr after "next", "exit", "pass" wouldn't add cr
	  also wasn't properly identifying when to add completion text
	  linkText of handlers outside current script wasn't working
	  editing/deleting of folded code sections is disallowed
	  script colorization is controlled by the engine
	  script formatting is controlled locally
	  folded code and breakpoints are adjusted when adding/deleting lines
	  breakpoints are restored with undo actions
	  faster adding and deleting of lines in long scripts
	  fixed collapse.all and expand.all commands
	  handler list updated when adding or deleting script lines

-----------------------------------------------------------------------
## 2021.01.17 GLX2 4.1.16
-----------------------------------------------------------------------
	  Delayed update check until after plugin loading
	  block comment colorization
	  Folding/unfolding of line continuations

-----------------------------------------------------------------------
## 2021.01.15 GLX2 4.1.15
-----------------------------------------------------------------------
	  Bernd fixed code folding

-----------------------------------------------------------------------
## 2021.01.14 GLX2 4.1.14
-----------------------------------------------------------------------
	  Incorporated Bernd Niggeman's fix to colorizing block comments
	  Big speed improvements in initial load when editing

-----------------------------------------------------------------------
## 2021.01.10 GLX2 4.1.13
-----------------------------------------------------------------------
	  User preference for update checking on launch

-----------------------------------------------------------------------
## 2021.01.10 GLX2 4.1.12
-----------------------------------------------------------------------
	  Scripting error text shows up in status bar
	  fixed missing line 1 of block comment at start of script

----------------------------------------------------------------------
## 2020.12.21 GLX2 4.1.11
----------------------------------------------------------------------
    Fixed: pasting and deleting lines with folded code

----------------------------------------------------------------------
## 2020.12.21 GLX2 4.1.10
----------------------------------------------------------------------
	  Fixed code folding visual aspect (too many triangles)
	  Tabkey reformatting speed improvement
	  No collision when setting a ghost breakpoint on a script error line

----------------------------------------------------------------------
## 2020.12.21 GLX2 4.1.8
----------------------------------------------------------------------
	  Fixed live colorization

----------------------------------------------------------------------
## 2020.12.21 GLX2 4.1.6
----------------------------------------------------------------------

	  Now that 4.1.6 is done, a few improvements (thanks to Bernd Niggeman):
	  better code folding with tab indentation
	  Edge case folding fixed
	  Much faster formatting with code folding enabled

----------------------------------------------------------------------
## 2020.12.21 GLX2 4.1.6
----------------------------------------------------------------------

	  Now escaping all five html entities properly
	  Fixed autocompletion of control structures: try, repeat, switch, if
	  Fixed nesting of control structures
	  Fixed autocompletion line numbering
	  Some increase in autocompletion speed
	  Setting the script after compilation

----------------------------------------------------------------------
## 2020.10.27 GLX2 4.1.4k
----------------------------------------------------------------------

	  Tabbed formatting was messed up on several fronts

----------------------------------------------------------------------
## 2020.10.27 GLX2 4.1.4j
----------------------------------------------------------------------

	  Fixed tab folding of nested structures (off by one error)
	  Fixed non-colorized folded structures

----------------------------------------------------------------------
## 2020.10.26 GLX2 4.1.4h
----------------------------------------------------------------------

	  Fixed folding of nested structures

----------------------------------------------------------------------
## 2020.06.29 GLX2 4.1.4g
----------------------------------------------------------------------

	  Serious refactoring
	  Much improved speed for long scripts

----------------------------------------------------------------------
## 2020.06.15 GLX2 4.1.4f
----------------------------------------------------------------------

	  Fixed the initial display of disclosure triangles for foldable text
	  Trapping of editScript fixed on osx (frontscript order)
	  Code folding now applies to handlers
	  Code disclosure triangles moved to the gutter
	  Split screen improved (shift-click a tab to toggle)

----------------------------------------------------------------------
## 2020.05.21 GLX2 4.1
----------------------------------------------------------------------

Thanks to many code and bugfix contributions from the community, the glx2 script editor
is finally reaping the benefits of being open-source (meaning I don't have to do everything)
Special thanks to Bernd Niggeman, Bob Sneidar, and Mattias Rebbe.

Note that the Undo mechanics will no longer allow you to undo the script past the last save.

Improvements to code folding

Errors flagged in red during editing

Lots of bug fixes to

	   Preference settings
	   Clairvoyance
	   Colorization
	   Tabbing
	   Undo/Redo

----------------------------------------------------------------------
## 2020.04.05 GLX2 4.0
----------------------------------------------------------------------

	  Integration of the status bar with Fourth World's devolution
	  (http://fourthworld.com/products/devolution/index.html)
	  Refactored code folding
	  Status bar colors match LiveCode license version colors
	  Fixed block comment folding inside handlers
	  Refactored code folding yet again for speed
	  Renamed stack for ease of editing in Project Browser
	  Fixed "end try" tab formatting
	  Removed most dependence on stack naming convention
	  Some rework for compatibility with Refactor stack

----------------------------------------------------------------------
## 2017.07.24 GLX2 3.0.24
----------------------------------------------------------------------

Some bugfixes:

	OSX problem with toggling GLX2 on and off
	Ghost breakpoints weren't correctly responding to cut/paste
	Refactored for speed

----------------------------------------------------------------------
## 2016.10.05 GLX2 3.0.21
----------------------------------------------------------------------

Mostly a bugfix release

new features:

    Folding block comments.
    Extended pattern matching to "()[]{}"

bugs fixed:

    Ghost breakpoints coexist with code folding.
    Compilation errors weren't highlighting the error line properly.
    Right-clicking the handler panel was only selecting the folders popup.
    Some code folding wasn't working properly. Reformatting could lose code if collapsed.
    Removed lots of unused legacy custom properties (see note about deleting prefs file)
    Command-w (control-w) closes the current tab.

known issues:

     Line wrapping doesn't change the line numbering. If you turn on line wrapping, the line numbers after a line wraps will be wrong. I don't currently know any way of telling when a line is being wrapped.
    Still some problems recognizing that text inside a block comment is not actionable.
    Swapping back and forth between glx2 and the IDE's script editor gets a bit wonky.
    Very little testing has been done on any Windows platform. If it works, it works.
    Spuriously recognizes "the" as a library handler.

----------------------------------------------------------------------
## 2016.09.20 GLX2 3.0.20
----------------------------------------------------------------------

new features:

    control-tab and shift-control tab move among the open script editor tabs.
    Click in line number field to toggle ghost breakpoints on and off.
    Line numbering and ghost breakpoints adjust properly to cut/paste/edit.

bugs fixed:

    Folding case statements inside switch contructs works properly now.
    It was previously collapsing all the way down to the 'end switch' statement.
    Line numbering could get out of sync on opening a new tab.
    Reopening the script editor after closing wasn't properly noticing previously-open tabs.
    Hacked around LC8.1 interaction with reloading/rewriting revTools.

known issues:

    Line wrapping doesn't change the line numbering. If you turn on line wrapping, the line numbers after a line wraps will be wrong. I don't currently know any way of telling when a line is being wrapped.
    Still some problems recognizing that text inside a block comment is not actionable.
    Swapping back and forth between glx2 and the IDE's script editor gets a bit wonky.
    Very little testing has been done on any Windows platform. If it works, it works.
    Sometimes spuriously recognizes "the" as a library handler.
    Ghost breakpoints don't recognize code folding yet.

## 2016.09.10 GLX2 3.0.19

Fraser Gordon and I sat down for half an hour at the LiveCode 16 conference in Edinburgh and figured out what was causing the problem with taking up the CPU cycles. The engine problem still isn't fixed, but that gave me enough knowledge of what's going on to come up with a workaround for it, so I'm bringing this project back on line.
http://quality.livecode.com/show_bug.cgi?id=16880

new features:

    Line numbers. Yes, finally.
    Unit test generation. Click a command declaration, then select from the contextual menu. The tests will be created in a file named "tests.text" in the same directory as the stack file.
    Documentation generation. Inline javadoc-style - select from the contextual menu.
    Pressing enter on a compiled script closes the tab ala the built-in editor. I never thought that was a thing.

bugs fixed:

    Lots of little things I had time to fix up while waiting.
    For one thing, the splitter bar between the handlers and script panels is more accessible now.

known issues:

    Line wrapping doesn't change the line numbering. If you turn on line wrapping, the line numbers after a line wraps will be wrong. I don't currently know any way of telling when a line is being wrapped.
    Still some problems recognizing that text inside a block comment is not actionable.
    Swapping back and forth between glx2 and the IDE's script editor gets a bit wonky.
    Very little testing has been done on any Windows platform. If it works, it works.

## 2016.01.29 GLX2 3.0.19 beta 7

----------------------------------------------------------------------
NOTE: THERE ARE STILL PROBLEMS WITH THIS RELEASE!
----------------------------------------------------------------------
They are problems with the engine/IDE, not with glx2, so I'm holding off an official release for now.
In particular:
On linux with LC7.x or LC8.x when the status bar becomes a palette, the desktop manager takes ~90% of the CPU cycles. This makes the entire desktop sluggish to the point of unusability. This is not a problem on OSX.
On OSX with LC6.7.x, bringing the glx2 preferences editor up hangs the IDE. This is not a problem on linux.
----------------------------------------------------------------------

There is no longer a problem editing a stack previously edited by another editor. There is now a slightly longer delay because the script is loaded each time, but the engine is now fast enough that this shouldn't be noticeable.

There is now a proper license file. GLX2 has always been licensed under the MIT license, but there was no external notice of this, only a custom property (uRIP["EULA"]) of the mainstack.

The default font size preference is now 12 point.

The "red dot" breakpoints are now functional, with or without PowerDebug. This is a Big Deal, because the dot positions are recalculated when you compile so that the actual breakpoints stay in sync with the visual indicators. To toggle a breakpoint for a given line, right-click on the line and select the option from the pop-up menu. Note that the ghost breakpoints are not persistent, i.e., they only exist for the current session.
NOTE: If you use breakpoints without PowerDebug in the system, you will end up launching the IDE's script editor on hitting a breakpoint. The IDE's debugger is intimately intertwined with the IDE's script editor.

bugs fixed:

 The properties were never included in clairvoyance completion
 Fixed miscellaneous problems with glx2 plugin handler code
 Preferences weren't being loaded properly
 Multiple problems solved with handler folders
 Several things that were previously working were fixed until they broke, then refactored until they worked again.
 Repeat until probably no longer broken.

NOTE: the glx2Plugins.txt file should be placed in the same user plugins folder as glx2 itself. If you have an older "glx2 Plugins.txt" file you can get rid of it. I renamed the new file to eliminate the embedded space, and the older naming convention will just be ignored. Current plugin integrations are lcTaskList and PowerDebug.

 Also, it's probably best practice to delete any existing "GLX2 Code Prefs.txt" preference file before installing the new version. Some preferences have changed and the discrepancy may cause some confusion.

## 2015.07.03 GLX2 3.0.18

    Looks like I never got around to uploading v17.
    Some speed increases and minor bug fixes along the way.

## 2014.08.04 GLX2 3.0.17

bugs fixed

    The cursor was being positioned improperly for new commands and functions

## 2013.11.06 GLX2 3.0.16

bugs fixed

    Two folding structures problems fixed
    "else if" was folding in the middle
    the combination of folding structures and block comments could lose text
    Re-enabled live colorization
    Bernd Niggeman contributed live colorization fixes
    Fixed the cursor flickering problem
    Broke and fixed clairvoyance
    Frontscript was interfering with text/icons display in the IDE's dock

known issues

    clicking outside the plugins popup menu blocks mouseMove messages temporarily

## 2013.07.05 GLX2 3.0.15

new features

    The F3 key now acts like command-G as a "Find Again" command
    Disabled the note-to-handler list as causing problems

(still) known issues

    The insertion point cursor would disappear on OSX 5.0.2 (only)
    Double-click to find needs to narrow scope for local vars and parameters
    Sometimes a script tab has a formatted length of 14 (0+14)

bugs fixed

    Block comments now colorize properly
    Settings would open and then immediately close (bad preferences switch)
    Typing "< " would lose text and reposition the insert cursor
    Fixed the disappearing conjuctions thing (thanks to Bernd Niggeman)

## 2013.05.02 GLX2 3.0.14

new features

    Speed: editing and formatting is now *much* faster
    Clairvoyance knows the difference between commands and functions
    Unclosed quoted strings are highlighted in red
    Return key on OSX now compiles script, Enter enters a newline
    Hover tooltip features:
     constants show their values
     color names show their RGB values
    Double-clicking a variable highlights all instances of that variable in the script
    Better PowerDebug integration on script errors:
     error text appears in GLX2 statusbar and as tooltip on line with error
    GLX2 now responds to the LC6 message box "show source" button

known issues

    Double-click to find needs to narrow scope for local vars and parameters
    Sometimes a script tab has a formatted length of 14 (0+14)

bugs fixed

    Structure outlines:
     inserting/deleting a new line wasn't adjusting outline size
    Script info panel was broken: now displays more information
    Message box kept popping up on dual-monitor systems

## 2012.12.07 GLX2 3.0.13

Also, glx2 macro processing has been deprecated. It's also a good idea to remove any "glx2 Macros" folder from your Plugins directory to prevent unforseen repercussions. Macro processing seemed like a good thing to add, but I don't think anyone was making use of it, and it had some annoying and hard to track down side effects.

new features

    Version control can now be disabled on an individual stack basis. This sets the stack's custom property uRIP["glx2VersionControl"] to "never". If you change your mind and want to put a stack under version control after disabling it from control, delete this custom property.
    Quoted strings that aren't properly closed will now highlight the entire line in red.
    The Watched Variables right-click plugin now launches PowerDebug's Watched Variables editor stack to allow for conditional breakpoints.
    Containers are now colorized. Colors are the same as for control keywords for now.

known issues

    Live Colorization doesn't work inside block comments.
    Macro processing was causing some problems, and I'm not sure anyone actually used it, so it's been deprecated.
    Features that have been deprecated/removed from glx2 are now in the "extras" folder.     It's part of the legacy code, so I didn't want to just dump them, but they're in unknown state and not recommended.

bugs fixed

    Inserting the "--> all handlers" line into text incorrectly placed the cursor at the end of that line instead of the end of text.
    ExplicitVars wasn't being picked up properly from the IDE setting. Might not work with MetaCard.
    Formatting a handler's parameters messed up following lines in the handler if a continuation char existed.
    A period would close the clairvoyance popup window.
    Live colorization recognized "--" but not "-- " (with a trailing space).
    Uncommenting a line of text would lose its colorization.
    Formatting issues with "&", "<" and ">" embedded in text being deleted or mangled.
    The outline block wasn't scrolling correctly with the text all the time.
    Multiple split screens are now more stable.
    Tab key wasn't formatting text properly inside a handler.
    Cursor was positioned at start of text after formatting.

Release history:

## 2012.11.01 GLX2 3.0.12 (Go Giants!)

new

    The font selector in the preferences pane was bringing up a hard-coded list instead of grabbing the fontNames, so now it gets the whole list. Adobe's new open-source SourceCode Pro font looks great. Download it from http://sourceforge.net/projects/sourcecodepro.adobe/
    Control+mouseOver the Find button turns it into "Find All", which will bring up a list of the locations of the found phrase anywhere in the stack file scripts (stack, substacks, cards, controls). Clicking on any line in the datagrid will bring that script up in the script editor with the specified line highlighted.
    All the 3.0.11 features below.
    Got the German keyboard AltGr key working now, thanks to Gunter Gaich. 

## 2012.09.19 GLX2 3.0.11

Coming up on the equinox. Never got a chance to announce this, so 3.0.11 is an unofficial release, and all the features here should be considered as being rolled into 3.0.12.

new stuff

    Code folding preference for control structures
    Complete on return preference
    Warning if you try to undo past the last save
    Licensing changed to MIT model
    Removed no-click inspection (attempt to get German keyboard working)
    Code stubbing added to new commands and functions
    Live colorization completely refactored
    Version Control updated:
        more version control features (Branch, Merge, Checkout, Reset To..., Remove)
        lots of bug fixes
        Recreate Object from archived files 

bug fixes

    fixed menubar disappearance on OSX
    fixed (I think) live colorization problems
    'function' wasn't being colorized/capitalized
    fixed link to docs on preferences panel
    fixed crash if close script editor/toggle GLX2 off with stack still in memory
    Refactoring:
        change signature didn't handle split lines
        change signature had problems with function parameters 

known issues

    There's still a preprocessor problem with = signs embedded in block comments
    Still doesn't handle the German keyboard. 

## 2012.08.01 GLX2 3.0.10 About time to release this one.

new stuff

    Refactoring support in the Script menu. Not everything is working yet, but it's a good start, and the parts that aren't there yet will tell you so.
    Unlimited undos! This is a big deal. I got rid of the old undo mechanism that wasn't really working very well and put a FILO stack array in its place. Fast, efficient, and you can undo all the way back to when you first opened the script editing session. 

known issues

    Refactoring to change the signature of a function is still wonky. Commands work ok, but I still need to do some work on the function parameter formatting. 

## 2012.06.20 GLX2 3.0.9

bug fix

    Live colorization again. There was a nasty bug with spaces at the end of a line containing a comment would mangle the text. Getting a bit frantic with bug fixes as we approach conference time.

## 2012.06.18 GLX2 3.0.8

bug fix

    Sigh. Not a good idea to launch a modal dialog from a menubar. Changed the Version     Control substack to a modeless launch to avoid a hung IDE.


## 2012.06.18 GLX2 3.0.7

Faster git

    I found a "do" statement that was slowing down git saves. Practically imperceptible now. It's safe to do the 'Export stack' command.

## 2012.06.17 GLX2 3.0.6

New features:

    lcTaskList compatibility. Right-click on a line in the script editor to insert a task comment.
    Right-click the GLX2 icon in the status bar to invoke the preferences panel.
    More git integration. 

Note: "export stack" takes a LONG time. Do this only once to a stack.

Bugs fixed:

    Closing the last open tab no longer crashes glx2.
    Enabling icons on tabs no longer causes version control crash.
    Live colorization is working better. 

## 2012.06.07 GLX2 3.0.5

    Restores command-G Find Selection/Find Again processing.
    Also, stacks are now tagged for version control. If a stack hasn't been tagged and you have git enabled you will be asked if you want to start tracking the stack. At present you can explicitly prevent stacks from being tracked, but you'll be asked each time you save. 

## 2012.06.05

GLX2 3.0.4 fixes an uninitialized variable problem that prevented some comment colorization if bold folder links wasn't selected. Weird. Also re-enabled live colorization that was accidentally disabled in the previous build.

GLX2 3.0.3 is now ready for downloading. It may still be a bit rough around the edges, but it's a major departure from previous builds. The script editor is now separated from the other parts of the older glx2 builds (the property editor, VAB, utilities) and the other parts are now separate stacks. This makes the code cleaner and easier to maintain. I can't guarantee that the property editor and VAB are working properly at this point, but I'm not sure if anyone uses these. They'll be cobbled together as time permits.

New to this release:

    Split screen viewing has been restored. Shift-click on a tab to open a second screen for viewing. Shift-click it again to close the split pane. Still can only edit the lower pane, but it's a start.
    Compatibility with Bill Vlahos' lcTaskList plugin
    Live colorization of lines as you type. Live colorization has been disabled for comment lines because there's still an issue with that, but it'll get fixed later on.
    A start at git version control integration: new items in the Tools menu. If you have git installed you can enable version control integration from the Tools menu. This will automatically stage text files containing the scripts of edited stacks when you do a save, and create a metadata directory structure to contain them. All other git commands are manual (commit files using the Tools submenus). No explicit diffs yet, but you can launch gitk from the menu.
    A start at refactoring support in the Script menu. Currently supported: converting literal values to constants, converting globals to script- or handler-locals. More to come later. 

So... you can just replace the "GLX2 Code" stack in your plugins folder and have the new version running. Don't need to add the other stacks, but it won't hurt anything if you do. The PowerPlug stack contains some of the utility functions that were previously in the main stack ( hiding/showing the tools stack, etc), so you may want that as well.

The stacks are all saved in 2.7 file format, so they should be compatible back to at least Rev 3.5. Compatibility testing with versions earlier than 4.6.4 has been spotty, though. There may be some issues with earlier prefs files - toss them if in doubt, and they'll be rebuilt.

## 2012.04.30

I made one fix to the uExtensions macro to handle "case" statements. I updated the 1.19 file but put the macro files in their own zip file for a faster download if that's all you need.

2012.04.10 v1.19foss

Fixed the no-click options for OSX. The menubar on OSX no longer disappears and reappears. Closing the stack, either with the closebox or via close-and-remove-from-memory, now triggers the removal of appropriate script editor tabs through a cleaner mechanism than before.

## 2012.04.07 (the Mozambican Women's Day release) v1.18foss

Fixed a couple of major refactoring oversights. Option-control or option-command are now back in service for no-click editing. The status bar now again shows the current mouse object.

## 2012.03.23 (the Equinox release) v1.17foss

This should take care of LC 5.5. I've found some things that don't work in the MetaCard environment, but the majority of things still do.

NB: I'm doing some major refactoring here, so I'll post an experimental version soon. I think I'll branch the code because this will be a major change. What I'm working on is splitting the script editor, property editor, and VAB into separate stacks. This should make maintenance tasks easier and improve the code base as well.

## 2012.03.14 (the Pi Day release!) v1.16foss

Getting ready for the LiveCode 5.5 release, there are a couple of things that need to be changed, so doing a Save As will prompt you with a file version dialog before continuing with the save. The Script Snapshots is also saved in legacy 2.7 format for compatibility between different LiveCode versions. Clairvoyance finally shows handlers from the IDE's builtin external libraries (xml, db, zip) and is now smart enough to show only commands where commands are appropriate and only functions where only functions can be used. Pressing the tab key while in clairvoyance selects the highlighted entry. The File menu was messed up. It's better now, but probably needs more tweaking.

## 2012.03.06 v1.14foss

The mouseDown handler in the GLX2 menu now does an exit to top after a paste to get around a conflict with tmControls that caused a double paste on OSX. And this still just to get past the LC5.x bug.

## 2012.02.24 v1.13foss

Well, that one *almost* fixed it. I have now added command-X and command-V to the commands glx2 is handling rather than handing control over to the engine. Seems to be working now on OSX 10.6.8 and LiveCode 5.0.2.

## 2012.02.23 v1.12foss !!! 
I've finally got a hack that (I think) solves the menubar thing. I'll put the gory details in the issue report, but this seems to be working properly for LC5.x on all platforms.

## 2012.02.20 v1.11foss

<sigh> I have now backed off completely from trying to fix the menubar thing on my own. The menubar now show up properly in all situations on OSX, but if you're using LC 5.x you have to hold down the control key for about 800 milliseconds to get it to register. No problems with LC 4.6.4 and before.

## 2012.02.05 v1.10foss

Thought I had the control- and command-key slowdown fixed, but it looks like it will have to wait for an engine fix from the rev team. At least it only affects OSX now and not linux. The problem is isolated to setting the menubar, and GLX2 needs to set the menubar on OSX.

## 2012.01.18 v1.07foss

New feature added! I've been wanting this for a long time. You can now highlight the outline of control structures by right-clicking on (for instance) an if statement to show where its corresponding end if statement is. Or right-click on the end statement to see the beginning of the control structure. This works with if, repeat, switch, and try structures. If the structure is too long to fit on the current screen you can press control-shift-O (for outline) to keep it highlighted, then scroll the screen, and finally press control-shift-O again to when you're done.

You can also right-click a left parenthesis to highlight text to its matching right parenthesis.

As a result of this, right-clicking on a term no longer brings up the dictionary definition. To see the word in the docs, press the F1 key.

## 2012.01.07 v1.06foss

Two bug fixes here and a lot of refactoring: Comments starting with a double slash ("") weren't being recognized properly. This is now fixed in a few places and refactored where possible. Selecting handlers from the handler list is fixed. Again. Known issue: folders need *one* space as separation, not more: --> handlerName -- works --> handlerName -- doesn't

## 2011.12.05 v1.05foss

Clicking the handler list wasn't always grabbing the correct handler in the script. Combination of filter and wholematches and lineoffset. Got it fixed now. Breakpoints weren't triggering if PowerDebug wasn't in the system. Breakpoints now trigger the builtin debugger if PowerDebug isn't present, PowerDebug otherwise.

## 2011.10.19 v1.04foss

Startup time is much faster - multiple cards now use behavior buttons, so glx2 no longer has to update and save itself on each launch. F1 key does dictionary lookup. Highlight color set to gray

## 2011.08.12

Cleaned up colorization a bit. Added a bit of help to keep you out of trouble: normally invocations of commands and functions will be formatted as links to the handler. But now if you call a command as a function or call a function as a command it won't be formatted as a link as an aid to pointing out what might be wrong in the code. Constants are now formatted in green in the code to differentiate them from variables.

## 2011.06.04

Bug fixes: Switching motif between chalkboard and alabaster wasn't selecting colors properly until after restart. Selecting handlers from the handler pane wasn't working. Formatting with tab key wasn't working properly.

## 2011.04.25

Cleaned up code, refactored a whole bunch, fixed handler linking, got speed increases in the process. Fixed that annoying thing where compile errors would bring up the error dialog instead of highlighting the problem. Breadcrumbs now return you to the line you came from, not just the start of the handler you were working on. Breakpoints show up in red to catch your attention.

Known issues: Linking from the handler list doesn't work if the linked text is later in the script than a subset that's earlier in the script: findMyTextInSomeBox will fail to bring up that handler if there's a findMyText handler earlier in the script.

## 2010.12.04

First official release announcement as an open-source project to the LiveCode developer community. Click the "Follow" icon if you want to be notified when updates are made to the script editor.

## 2010.10.05

Somehow the uRIP custom properties didn't make it into the first release, so I put those in again and re-uploaded it. No other changes.

-- 
-Mark Wieder
 mwieder@ahsoftware.net
