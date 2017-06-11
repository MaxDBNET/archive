# Overview

- [Rules & Punishments](Rules.md#rules-punishments)
    - [Chat Offense](Rules.md#chat-offense)
    - [Gameplay Offense](Rules.md#gameplay-offense)
- [Banning](#banning)
    - [Ban Format](#ban-format)
    - [Ban Time](#ban-time)
- [Ticket](#ticket)
    - [Steps to Handling a Ticket](#steps-to-handling-a-ticket)
    - [Unhandling a Ticket](#unhandling-a-ticket)
    - [View Handled Tickets](#view-handled-ticket)
- [Commands](#commands)
- [Sarah Bot](#sarah-bot)
- [FAQ](#faq)
- [Links](#links)


# Content

## Banning

### Ban Format

This is the format you should follow when banning:

`BanReason | BanTime | Appeal at MaxDB.NET`

To use custom reason, simply go to the next page on the ban menu, accessible via `!admin`.

### Ban Time

Aside from the several fixed length stated in the punishment column, this is really up to the person that's banning. Generally, I base this off on % of players affected by this action.

So team killing, which only affects the minority of the players, will receive two days ban. But for stat boosting, this affects everyone; I'd do a week ban.

## Ticket

We use a custom plugin for handling reports, questions and etc. And we require all staff to handle ticket whenever possible.

### Steps to handling a ticket

 1. Start by checking if there's any ticket available using `!TicketQueue`.
 2. Handle a ticket using `!Handle #`, where `#` is the ticket ID.
 3. View the ticket info using `!ViewTicket #`, where `#` is the ticket ID.
 4. Tag the necessary target player if not already (**for hacker report, mute request, and etc**) `!TagPlayer #`, where `#` is the ticket ID.
 5. Evaluate the ticket and take actions if needed.
 6. Reply to the reporter using `!ReplyTicket # M`, where `#` is the ticket ID and `M` is the message.
 7. After the ticket is **completely** handled, you may close the ticket using `!CloseTicket #`, where `#` is the ticket ID.

### Unhandling a ticket

There are situations where you handled the ticket and later realize you cannot actually resolve this for whatever reason.

Then you may unhandle the ticket using `!UnhandleTicket #`, where `#` is the ticket ID, and it will return to the ticket queue.

### View handled  ticket

Sometimes you lose track what ticket(s) you are currently handling and are not closed.

You may view your handled & unclosed ticket using `!MyQueue #`, where `#` is the page number.

## Commands

Most if not all the admin's command can be accessed using `/admin`.

We also use `Ticketron` for reports, you can learn more about that [here](https://rumblefrog.github.io/Ticketron/).

## Sarah Bot

Sarah-bot is what we created to help optimize our workflow.

If you'd like to opt-in for Steam chat reports from Sarah-bot, please add her [here](http://steamcommunity.com/profiles/76561198258473878/).

Please notify me after you do that and I'll guide you through setting up your notifications.

## FAQ

:question: How can I join MaxDB?

:arrow_right: You can join us by joining our Steam group: <http://steamcommunity.com/gid/103582791457828777>


:question: What is `@Good Ol' Minecraft` group and how can I join it?

:arrow_right: It's a group of people that are currently whitelisted on our Minecraft server (#info), and you can join it by reading and replying to this discussion: <http://steamcommunity.com/groups/MaxDBNET/discussions/0/1291817837629584246>


:question: What are the rules?

:arrow_right: Take a look at #rules


:question: There's a violator in one of your servers, how can I report it?

:arrow_right: You can either use `!Ticket` & `!TagPlayer` combination **OR** you can mention `@Staff` in #support for immediate assistance


:question: I'm having technical difficulties with one of your servers, can you help me?

:arrow_right: Sure, but first use Google to look up the issue, then if that doesn't help, you can mention `@Fishy` for support


:question: I'm getting `Missing Map` on one of your servers, how can I fix this?

:arrow_right: First, make sure you enable custom files to download from the server through in-game setting: `Options -> Multiplayer -> Allow all custom files from server`. And if that didn't work, download the missing map from our FastDL (https://dl.maxdb.net) and drop it off in your maps folder


:question: I'm getting `Your map differs from server's`, how can I fix this?

:arrow_right: Navigate to your downloaded maps (`steamapps\common\Team Fortress 2\tf\download\maps`) folder, delete the mentioned map, and retry.


:question: What's this free hat event I hear about?

:arrow_right: Every Saturday, we host an event on a chosen server, giving away hats for winning the objective (different on each server), and towards the end, we might give away a much higher valued prize


:question: I have a feedback/suggestion! Who can I talk to?

:arrow_right: Awesome! You can inquiry `@Matt` for any feedback/suggestion
## Links

- [General Website](https://maxdb.net)
- [Discord](https://discord.maxdb.net)
- [Forum](https://forum.maxdb.net)
- [Lab](https://lab.maxdb.net)
