# Building a message

First, we'll need to install the libraries we'll use. In the terminal, run:

`pip install slackclient`

Let's create a Python file that will connect to our Slack and post a simple message. In the terminal, type `touch slack_bot.py` and then bring it up in the editor so you can edit it.

At the top of the file, let's add the following:

```
import os
from slack import WebClient
from slack.errors import SlackApiError

token = os.environ.get('SLACK_API_TOKEN')
```


---

**Next section: [03 - Responding to Slack events](03-responding-to-slack-events.md).**

**Previous section: [01 - Creating the Slack app](01-creating-the-slack-app.md).**

**Back to the [Table of contents](README.md#table-of-contents).**
