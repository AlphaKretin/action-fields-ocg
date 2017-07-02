# action-fields-ocg

- fieldlist.txt has a list of all fields in the game, with those completed "commented out".
- generic-action-cards.lua is a snippet for the list of cards I've arbitarily deemed generic enough to use in every field, the 4 official default ones aren't enough imo.
- all-action.cdb has action versions of every field spell, in theory. needs fixing
- gimmick-action.cdb has action versions of field spells that fairly affect both players and change the game in an interesting way, a list arbitrarily decided by me.
- gimmick-list.txt has the above list with IDs
- action-snippet.lua has the code to make a Field Spell and Action Field. Delete the field's existing --Activate block, and you'll have to renumber the other effects the card has. Also replace 95000062 with the right card ID
