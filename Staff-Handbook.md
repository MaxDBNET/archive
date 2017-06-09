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

## Links

- [General Website](https://maxdb.net)
- [Discord](https://discord.maxdb.net)
- [Forum](https://forum.maxdb.net)
- [Lab](https://lab.maxdb.net)
