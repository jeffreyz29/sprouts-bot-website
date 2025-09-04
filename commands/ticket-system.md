---
description: Comprehensive ticket management system for apm managers
---

# Ticket System

<table data-full-width="true"><thead><tr><th width="211.68359375">Command</th><th>Example Usage</th><th>Description</th></tr></thead><tbody><tr><td><code>s.new</code></td><td><code>s.new [reason]</code></td><td>Creates a new ticket with optional reasoning</td></tr><tr><td><code>s.add</code></td><td><code>s.add @johnathan</code> <br><code>s.add 1234567890</code></td><td>Adds a new member to a ticket channel</td></tr><tr><td><code>s.claim</code></td><td><code>s.claim</code></td><td>Claim Ownership of a ticket</td></tr><tr><td><code>s.close</code></td><td><code>s.close [reason]</code></td><td>Close an active ticket</td></tr><tr><td><code>s.forceclose</code></td><td><code>s.forceclose</code></td><td>Force close a ticket </td></tr><tr><td><code>s.move</code></td><td><code>s.move &#x3C;CategoryID></code></td><td>Moves a ticket to a new category</td></tr><tr><td><code>s.priority</code></td><td><code>s.priority high|medium|low></code><br><br>high - mark as urgent<br>medium - standard priority<br>low - non-urgent</td><td>Sets the priority level of the ticket</td></tr><tr><td><code>s.release</code></td><td><code>s.release</code></td><td>Release a active claimed ticket </td></tr><tr><td><code>s.remove</code></td><td><code>s.remove @johnathan</code><br><code>s.remove 1234567890</code></td><td>Removes the user from the ticket</td></tr><tr><td><code>s.listtickets</code></td><td><code>s.activetickets</code></td><td>Shows a list of active tickets in the guild </td></tr><tr><td><code>s.topic</code></td><td><code>s.topic new mass please</code></td><td>Changes a ticket topic </td></tr><tr><td><code>s.transfer</code></td><td><code>s.transfer @staff</code><br><code>s.transfer 1234567890</code></td><td>Transfer an active ticket to another staff</td></tr><tr><td><code>s.rename</code></td><td><code>s.rename &#x3C;new_name></code></td><td>Renames an active ticket channel </td></tr><tr><td><code>s.createpanel</code></td><td><code>s.createpanel</code></td><td>Creates multiple ticket panels </td></tr><tr><td><code>s.listpanels</code></td><td><code>s.listpanels</code></td><td>List all of the current active ticket panels </td></tr><tr><td><code>s.delpanel</code></td><td><code>s.delpanel &#x3C;panel_id></code></td><td>Deletes a ticket panel</td></tr><tr><td><code>s.ticketsetup</code></td><td><code>s.ticketsetup</code></td><td>Sets up the ticket system with a dropdown menu</td></tr><tr><td><code>s.ticketlimit</code></td><td><code>s.ticketlimit &#x3C;number></code></td><td>Sets a ticket limit, by default is 10</td></tr><tr><td><code>s.ticketuseembed</code></td><td><code>s.ticketuseembed &#x3C;embed_name></code></td><td>Uses a custom embed as the ticket message</td></tr></tbody></table>

{% hint style="info" %}
Discord will automatically sync its category permissions when new channels are created. If Discord does not sync its perms, you must go to the channel settings, press "sync perms" to sync them manually.
{% endhint %}









