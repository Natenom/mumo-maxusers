mumo-maxusers
=============
NOTE: This module is going to become obsolete because in the near future this will be implemented into the Mumble-Server itself, see at https://wiki.natenom.com/w/Mumble_Moderator/MaxUsers.

This is a mumo module to provide an administrator the capability of enforcing granular user limits by channel in mumble.

Features:
- Can set a limit to every channel (global config)
- Can specify limits to unlimited individual channels, overriding the global configuration
- Automatically move users back to their previous channel when attempting to join a full channel, while letting them know why they were moved.
- Allow for groups to be exempted from enforcement on channels based on the group/acl applied to the channel. Can override the exception on each channel if you wish.

This module should be considered beta for the moment, but is currently being actively used/tested. 

Some documentation about this module can be found at https://wiki.natenom.com/w/Mumble_Moderator/MaxUsers
