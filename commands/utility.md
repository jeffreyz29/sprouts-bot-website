---
description: >-
  Essential utility commands for information gathering and basic server
  management.
---

# Utility

### Information Commands

#### User Information

```
s.userinfo [user]
```

Get comprehensive information about a user.

**What it shows:**

* User ID and mention
* Account creation date
* Server join date
* Roles and permissions
* Avatar and status
* Boost information (if applicable)

**Examples:**

```
s.userinfo @john
s.userinfo 123456789012345678
s.userinfo
```

#### Server Information

```
s.serverinfo
```

Get detailed information about the current server.

**What it shows:**

* Server ID and owner
* Creation date and member count
* Boost level and features
* Channel and role counts
* Server icon and banner

#### Channel Information

```
s.channelinfo [channel]
```

Get information about a specific channel.

**What it shows:**

* Channel ID and type
* Creation date
* Topic and permissions
* Member count (for voice channels)

**Examples:**&#x20;

```
s.channelinfo <#channelID>
s.channelinfo 21371947144014
```

#### Role Information

```
s.roleinfo <role>
```

Get information about a server role.

**What it shows:**

* Role ID and permissions
* Creation date and color
* Member count
* Mentionable status

**Examples:**&#x20;

```
s.roleinfo @role
s.roleinfo 12379123
```

### Avatar & Media

#### User Avatar

```
s.avatar [user]
```

Get a user's avatar in high resolution.

**Features:**

* Shows server-specific avatar if available
* Falls back to global avatar
* Provides direct image link
* Works with user mentions or IDs

### Bot & Server Management

#### Latency Check

```
s.ping
```

Check the bot's response time and API latency.

**Shows:**

* Message latency
* WebSocket latency
* Bot uptime

#### Prefix Management

```
s.prefix
```

Check the current server prefix.

```
s.setprefix <new_prefix>
```

Set a custom prefix for your server.

**Requirements:**

* Manage Server permission
* Prefix can be 1-5 characters
* Cannot be only spaces

**Examples:**

```
s.setprefix !
s.setprefix >>
s.setprefix sprouts
```

#### Invite Information

```
s.inviteinfo <invite_link>
```

Get information about a Discord invite.

**What it shows:**

* Server name and member count
* Invite creator and expiration
* Channel information
* Verification level

**Examples:**

```
s.inviteinfo https://discord.gg/abc123
s.inviteinfo abc123
```

### Usage Tips

#### Permission Requirements

Most utility commands require no special permissions, but some server management commands need:

* `setprefix`: Manage Server permission
* Server information may be limited based on your permissions

#### Error Handling

If a command fails:

* Check the command syntax with `s.help <command name>` .
* Ensure you have necessary permissions.
* Verify the target (user/channel/role) exists and is accessible.
