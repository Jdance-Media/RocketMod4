# RocketMod4 Events

Events can be useful for logging things or blacklisting certain actions. Some events are not actually events in some cases but can be used as one.

  - U.Events.OnPlayerConnected(UnturnedPlayer player) - This is invoked when a player connects to the server
  - U.Events.OnBeforePlayerConnected(UnturnedPlayer player) - This is invoked before a player connects to the server
  - U.Events.OnPlayerDisconnected(UnturnedPlayer player) - This is invoked when a player disconnects from the server
  - ChatManager.onChatted(SteamPlayer player, EChatMode mode, ref Color chatted, ref bool isRich, string text, ref bool isVisible) - This is invoked when a player sends a chat message
  - Provider.onCommenceShutdown() - This is invoked when the server is shutting down. Useful for saving things before shutdown
