### Some Microsoft bot tests ###
- app1 - runs the botapi, test with bot framework emulator locally
- app2 - take a name, change name - command line version
- app3 - bot framework version, no id/password yet
- app4 - LUIS test
- app5 - 

#### Plans
- finish dialogue, clear name and data
- show summary list, who involved
- complex conversation with data
- firebase memory of personal info ?
- LUIS version

#### Terms
- `userData` stores information globally for the user across all conversations.
- `conversationData` stores information globally for a single conversation. This data is visible to everyone within the conversation so care should be used to what’s stored there. It’s disabled by default and needs to be enabled using the bots persistConversationData setting.
- `privateConversationData` stores information globally for a single conversation but it's private data for the current user. This data spans all dialogs so it’s useful for storing temporary state that you want cleaned up when the conversation ends.
- `dialogData` persists information for a single dialog instance. This is essential for storing temporary information in between the steps of a waterfall.


