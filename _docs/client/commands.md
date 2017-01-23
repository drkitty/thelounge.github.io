---
layout: documentation
title: Commands
description: Add your description here
category: Client
order: 3.1
---

# Commands

The Lounge implements most of the IRC commands you may be familiar with. Here's a list of commands you can use:

## /away [\<message>]

Mark yourself as away and set your away message. If you omit the message, an empty one is used.

Example: `/away Making quiche`

## /back

Remove your away status (after `/away [<message>]`).

## /clear

Clear the current screen.

## /close

Close the current window.

Aliases:

- [/leave](#leave)
- [/part](#part)

## /connect \<hostname>

Connect to a new network.

Example: `/connect irc.freenode.org`

Aliases:

- [/server](#server-hostname)

## /deop \<nick>

Remove op (-o) from a user in the current channel.

Example: `/deop john`

## /devoice \<nick>

Remove voice (-v) from a user in the current channel.

Example: `/devoice john`

## /disconnect

Disconnect from the current network.

## /invite \<nick> \<channel>

Invite a user to the specified channel.

Example: `/invite john #chan`

## /join \<channel>

Join a channel.

Example: `/join #chan`

## /kick \<nick>

Kick a user from the specified channel.

Example: `/kick john`

## /leave

Leave the current channel or query.

Aliases:

- [/close](#close)
- [/part](#part)

## /me \<message>

Send an `ACTION` message to the current channel.

Example: `/me likes chocolate`

## /mode \<modes> \<nick>

Set the user mode in the current channel.

Example: `/mode +o john`

## /msg \<channel> \<message>

Send a message to the specified channel.

Example: `/msg #chan Hello!`

## /nick \<new-nick>

Change your nickname on the current network.

Example: `/nick john`

## /notice \<nick> \<message>

Sends a notice message to the specified user.

Example: `/notice john Hello!`

## /op \<nick>

Make user op (+o) in the current channel.

Example: `/op john`

## /part [\<message>]

Leave the current channel.

## /query \<nick> \<message>

Send a private message to the specified user.

Example: `/query john Hello!`

## /quit

Disconnect from the current network.

## /quote \<raw-message>

See `/raw`.

Example: `/quote AWAY :Eating quiche`

Aliases:

- [/raw](#raw)
- [/send](#send)

## /raw \<raw-message>

Send a raw message to the current IRC network.

Example: `/raw AWAY :Cleaning dishes`

Aliases:

- [/quote](#quote)
- [/send](#send)

## /say \<message>

Send a message to the current channel.

Example: `/say Hello!`

## /send \<raw-message>

Example: `/send BACK`

Aliases:

- [/quote](#quote)
- [/raw](#raw)

## /server \<hostname>

Connect to a new network.

Example: `/server irc.freenode.org`

Aliases:

- [/connect](#connect)

## /slap \<nick>

Slap someone in the current channel. With a trout!

Example: `/slap john`

## /topic \<topic>

Set the topic in the current channel.

Example: `/topic Hello!`

## /voice \<nick>

Give a user voice (+v) in the current channel.

Example: `/voice john`

## /whois \<nick>

Whois a user on the current network.

Example: `/whois john`
