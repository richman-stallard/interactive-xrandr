# interactive-xrandr
Interactive CLI frontend for xrandr with limited functionality.

Auto-disables disconnected display outputs, lets user choose which of the connected outputs are enabled (default: all of them) and where to place them.

# Installation
File "ixr" is a Python2 script, simply download and place in path.

# Command line args
- ixr [-h,--help]

Show available command line args.

- ixr [-d,--defaults]

Apply default settings: all connected outputs are enabled, all disconnected outputs are disabled. Connected outputs are sorted 
left-to-right in the order that xrandr lists them in.

- ixr

Interactive session.
  
# Interactive commands
- h

  Explain available commands.
  
- l

  List all outputs, their enable state and position.

- m

Modify output enable state and position. User is queried for one of the connected outputs.

- q

Finish modifying outputs. User is asked for confirmation to apply the changes.
