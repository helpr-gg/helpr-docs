# Add Command 

## Usage
`/custom commands add` `<name>` `<description>` `<response>`
:::info[`Manage Guild`]
:::

## Details
Creates a custom slash command in your server
+ `<name>` Must be less than or equal to 32 characters and can only be one word, you can not use numbers. To use more than one word split it with a `-` or an `_`. So `/help me` would become `/help-me` or `/help_me`. Also you can't use uppercase letters they will be auto changed to lowercase. The name can not be the same as one of Helpr's commands or be the same as a custom command you have already made. These are all limitations imposed by Discord so I can not change them
+ `<description>` Must be less than or equal to 50 characters. You can use things like emojis or numbers in this and can use as many words as you want.
+ `<response>` Must be less than or equal to 2000 characters. You can use anything that you could send in a normal message, please note custom emojis might not work if Helpr is not in the same server as the emoji or if you do not use the emoji's id (`<name:id>`)

## Limits
+ You can only have 25 custom commands per server. (To request an increase in this amount please create a ticket in the support server [here](https://helpr.gg/server). Please tell us why you need more commands, and we will aprove/deny based on your needs.)
+ You can only create 200 commands per day, so if you create and delete a bunch of commands over and over then it will stop working after 200 creations. This is a limit imposed by Discord so I can not change it.
