# Meetings

We meet weekly to discuss progress on Open UI initiatives. Topics of
conversation are determined beforehand, and listed in
[telecon agenda documents](https://github.com/openui/open-ui/tree/main/meetings/telecon).

Meetings are held on Thursdays from [11:00 AM US/Pacific to 11:45 AM US/Pacific](https://www.worldtimebuddy.com/).

## Minutes

The [`telecon/` directory](https://github.com/openui/open-ui/tree/main/meetings/telecon) contains meeting minutes. If you'd like to stay up to date on upcoming
meetings, their agenda's and call in information please join the Open UI community group on the [W3C's Open UI community site](https://www.w3.org/community/open-ui/).

## Discord

Telecon agendas are announced in the #telecon-agendas channel in [our Discord
server](https://discord.com/invite/DEWjhSw). If you join Discord, be sure to introduce
yourself in the #introductions channel.

## IRC

We use IRC during the weekly telecon meetings. To join, #openui on
[irc.w3.org](http://irc.w3.org/). If you are unfamiliar with IRC, here is a
[quickstart guide](https://opensource.com/article/16/6/irc-quickstart-guide).

### Commands

We use the following commands to help run our meetings:

- `q+`/`q-`: Add or remove a question from the queue. This helps the person
running the meeting ensure nobody is overlooked who has a question.
- `present+`/`present-`: Add or remove yourself from the presentation queue.
- This signals to the person running the meeting that you have a presentation
    you would like to give, as well as marking it completed or no longer
    necessary.

### Note-taking

We have someone volunteer to take meeting notes every meeting (the scribe). Notes help us
keep a record of what was discussed. To take notes, post in #openui using the following format:

```
who: said what
```

An example of this is:

```
 gregwhitworth: I would not want to put that on authors to have every primitive, mix and match etc.
```

The chair (or scribe) can also set the topic (which generates a heading in the published notes): 

```
topic: <name of the topic>
```

If there is a GitHub issue for this topic, this command can be used to set the topic (to that issue's name) and post the discussion as a comment to the relevant issue:

```
/me github-bot, topic <GitHub issue url>
```

(This only works if the issue's GitHub organisation is in the [bot's config](https://github.com/dbaron/wgmeeting-github-ircbot/blob/main/src/config.toml) and `github-bot` is in the IRC channel)

### Setting up and running a meeting

Please refer to [`chair-meeting.md`](https://github.com/openui/open-ui/blob/main/meetings/telecon/chair-meeting.md).
