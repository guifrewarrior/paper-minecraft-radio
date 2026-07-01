How it works
What the plugin does
Builds a radio system in Minecraft Paper.
When a player left-clicks the antenna block structure, it opens a radio GUI.
Players can set a frequency and chat on that radio channel.
The plugin creates and manages radio channels automatically.
Main components
Starts the plugin.
Registers event listeners and the /radio command.
detects the antenna structure and left-clicks.
Opens the radio GUI when the correct block is clicked.

Builds the inventory GUI shown to the player.
Shows channel info, connect/disconnect, and frequency controls.

Handles GUI clicks.
Runs actions like joining/leaving channels or changing frequency.
RadioCommand.java
Provides chat commands:
/radio join
/radio leave
/radio say
/radio list
/radio frequency

Tracks active channels and players.
Sends messages to everyone on the same radio frequency.

Represents one radio channel and its state.
