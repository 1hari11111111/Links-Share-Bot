<p align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />
</p>

## What is LinkShareBot?

**LinkShareBot** is a modern Telegram bot that allows you to share and manage unlimited Telegram channel links with automatic invite link generation and management. 

Powered by **Pyrogram**, it provides a seamless experience for users to join channels through secure, auto-expiring links. The bot includes advanced features like force subscription, bulk link generation, and request link management.

## 🚀 Features

<table>
<tr>
<td>
  <img src="https://telegra.ph/file/6478c4b60d9164beb39d2-14a358dcdc0a18b5a5.jpg" width="300" />
</td>
<td>

| 🌟 Feature                | 🔎 Description                              |
| ------------------------- | ------------------------------------------- |
| 📺 Unlimited Channels     | Add and manage unlimited Telegram channels  |
| 🔗 Auto Invite Links      | Generate secure, auto-expiring invite links |
| ⏱️ Auto Revoke            | Links automatically revoke after 5 minutes  |
| 📦 Bulk Generation        | Generate links for multiple channels at once |
| 📋 Pagination Support     | Navigate through large channel lists easily |
| 🔄 Request Links          | Support for join request links              |
| 🛡️ Force Subscription     | Require users to join specific channels     |
| 📊 Bot Statistics         | Monitor bot usage and user statistics       |

</td>
</tr>
</table>

## 🛠️ Commands

### Channel & Link Management (Owner/Admins)
- <b>`/addch <channel_id>`</b> — Add a channel to the bot (admin only)
- <b>`/delch <channel_id>`</b> — Remove a channel from the bot (admin only)
- <b>`/channels`</b> — Show all connected channels as buttons (paginated)
- <b>`/reqlink`</b> — Show all request links for channels (paginated)
- <b>`/links`</b> — Show all channel links as text (paginated)
- <b>`/bulklink <id1> <id2> ...`</b> — Generate links for multiple channel IDs at once
- <b>`/channels`</b> — Show all connected channel IDs and names (paginated, with next/prev buttons and auto-deleting "please wait..." status)

- <b>`/reqtime`</b> — Set the auto-approve request timer duration.
- <b>`/reqmode`</b> — Toggle auto request approval mode (ON/OFF).
- <b>`/approveon`</b> — Enable auto request approval for a specific channel.
- <b>`/approveoff`</b> — Disable auto request approval for a specific channel.
- <b>`/approveall`</b> — Approve all pending join requests in a channel using userbot (make sure to fill your session string in `approve.py`).

### Admin Commands
- <b>`/stats`</b> — Show bot stats (owner only)
- <b>`/status`</b> — Show bot status (admins)
- <b>`/broadcast`</b> — Broadcast a message to all users (admins)
- <b>`/cleanup`</b> — Remove inactive users from database (admins)

## 🔑 Environment Variables

Below are the required and optional environment variables for deployment.

```env
API_ID=              # Required - Get from https://my.telegram.org
API_HASH=            # Required - From https://my.telegram.org
TG_BOT_TOKEN=        # Required - Get from @BotFather
OWNER_ID=            # Required - Your Telegram user ID
ADMINS=              # Required - Admin user IDs (space separated)
DB_URL=              # Required - MongoDB connection string
DB_NAME=             # Optional - MongoDB database name (default: LinkShareBot)
DATABASE_CHANNEL=    # Required - Private channel ID for link storage
```

⚠️ **Never expose raw credentials or tokens in public repos.** Use safe paste services like [Pastebin](https://pastebin.com) or [Batbin](https://batbin.me).

## 

# 🔖 Credits

* <b> ᴄʀᴀғᴛᴇᴅ ᴡɪᴛʜ ᴘᴀssɪᴏɴ ʙʏ HARI </b>

