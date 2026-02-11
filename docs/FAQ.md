# Frequently Asked Questions (FAQ)

## General

**Q: Why is the bot a single file?**
A: Streamer.bot actions are easiest to share as a single C# script. Splitting it into multiple files would make importing
difficult for end-users.

**Q: Can I use C# 10 features?**
A: No. Streamer.bot runs on .NET Framework 4.8 which supports C# 7.3. Using newer features will cause compilation errors
for users.

## Troubleshooting

**Q: I get "Script unavailable" error.**
A: Ensure you have compiled the code in Streamer.bot. Click the "Compile" button in the Execute C# Code sub-action.
