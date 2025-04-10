# the_blocklist

I get a lot of spam, often by scammy tech vendors and fake startups that cull public information or leaked systems.

The BlockList is an idea to combat them.

The BlockList is focused on ENTIRE DOMAINS - not specific email addresses.  All mail from entries in The BlockList should be refused by all subscribers.

## Version 1

This is version 1.  A github repo to list the spam domains in a TXT file.  PRs by trusted contacts will be reviewed for inclusion.

Tools will be published to convert the text into rules or API actions for various email systems.

## Version 2

I'd like to use trusted networks and GPG keys, so people can run their own blocklists and subscribe/share with their own networks for automatic updating.  Everything is verified via GPG.

### Concept A - Block Only

The list would only include addresses to block.  Inclusion on the list is hard fail.

### Concept B - Network Voting

Participants can blocklist and allowlist; personal networks decide what percentage of blocks vs allows are required to fail.

### Concept C - GPG Privacy

Lists are public, but encrypted with a GPG keyring.  Participants maintain their own keyrings.


