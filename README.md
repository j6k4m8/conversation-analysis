# conversation-analysis
Some Python notebooks to play around with chat-message analytics.

Some scripts to draw interesting analyses from text chats. Makes the following assumptions about your data formatting:
- Your data have been run through `minify`, and thus are a JSON file with `author`, `body`, and `timestamp` fields
- Timestamp is in millis

You can get a JSON of Facebook messages using [this code](https://github.com/RaghavSood/FBMessageScraper/issues/3#issuecomment-168302782). You can also download from Google Hangouts using [Google Takeout](https://takeout.google.com/settings/takeout/custom/chat), though I have not tested this system.
