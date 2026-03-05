# Slack

## Avoid back-and-forth, provide all the info in fewer messages

❌ DON'T: "hey, do you have a minute?"

✅ DO: "hey, quick question about the deploy pipeline — is X expected behavior?"

- Don't ask "can I ask you a question?" — just ask it.
- Don't send "hey" and wait for a response.
- Include all the context upfront so the other person can answer in one go.
- Add additional context and messages in a thread, if needed.

And the timeless classic
[No Hello: Please don't say just 'hello' in chat](https://nohello.net/).

## Show, don't tell: provide context upfront (links, screenshots, CLI output)

❌ DON'T: "hey, I ran the command to get offers, and I'm receiving an error.
Does it happen to you too?"

✅ DO: "Hi, I ran the command `abc.sh --flag param1 param2` and it's failing
with `some meaningful error`. Full output and logs in the thread."

- Don't give incomplete information
- Give something that can be reproduced to confirm or deny the error
- URLs let people jump straight to the source
- Screenshots help when the UI is hard to navigate or the state might change
- CLI output helps when the other person can't reproduce the issue

## Use bullets points instead of long paragraphs

- Bullets are faster to scan and easier to read.
- Long paragraphs and walls of text get skipped.
- When asking questions, use numbered bullets, so it's easier for the
  interlocutor to answer.

## Display content previews

- When pasting URLs of posts, code, Jira tickets, please keep the preview.
  - This saves the reader a click, open a browser tab, wait for the page to
    load, switch back to Slack, etc.
- To display previews, you must install the Slack apps for GitHub, Jira,
  PagerDuty, etc.

## Don't link URLs to short words like "here" or "this"

❌ DON'T: `"See the docs [here](https://example.com)"`

✅ DO: "See [Deployment docs](https://example.com)"

Short link text is hard to skim and loses context when copy-pasted.
