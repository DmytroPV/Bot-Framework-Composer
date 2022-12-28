## An example of a simple bot (Bot Framework Composer) 

The bot was created using the Bot Framework Composer (the application allows you to build bots using the schematic construction of logical blocks, that is, without writing code in practice). It has several logical branches of the conversation with the user. The essence of the conversation is to perform a simple mathematical operation depending on the mood and age of the user. The final two branches are divided into simple (for younger users) and more complex (for teenagers).

The process of publishing a bot is described in the official documentation  **[guided tutorial](https://docs.microsoft.com/en-us/composer/tutorial/tutorial-introduction)**. The bot must be published in the corresponding application (service) Azure which can also be a server, then the bot assembly can be connected to the desired messenger.

- This bot project was created using the Empty Bot template, and contains a minimal set of files necessary to have a working bot.
![Bot1](https://user-images.githubusercontent.com/119622477/209830196-acaf332b-8f87-4ab2-b089-b352036450d3.png)
![Bot2](https://user-images.githubusercontent.com/119622477/209830188-59d9af41-da29-4284-b763-071ed8a39795.png)
![Bot3](https://user-images.githubusercontent.com/119622477/209830184-53399775-b738-4f98-a8d2-abba7275c2c0.png)
![Bot4](https://user-images.githubusercontent.com/119622477/209830173-be94171e-f5d7-497d-913b-9e73b97f10ab.png)

### Next steps

#### Start building your bot

Composer can help guide you through getting started building your bot. From your bot settings page (the wrench icon on the left navigation rail), click on the rocket-ship icon on the top right for some quick navigation links.

Another great resource if you're just getting started is the **[guided tutorial](https://docs.microsoft.com/en-us/composer/tutorial/tutorial-introduction)** in our documentation.

#### Connect with your users

Your bot comes pre-configured to connect to our Web Chat and DirectLine channels, but there are many more places you can connect your bot to - including Microsoft Teams, Telephony, DirectLine Speech, Slack, Facebook, Outlook and more. Check out all of the places you can connect to on the bot settings page.

#### Publish your bot to Azure from Composer

Composer can help you provision the Azure resources necessary for your bot, and publish your bot to them. To get started, create a publishing profile from your bot settings page in Composer (the wrench icon on the left navigation rail). Make sure you only provision the optional Azure resources you need!

#### Extend your bot with packages

From Package Manager in Composer you can find useful packages to help add additional pre-built functionality you can add to your bot - everything from simple dialogs & custom actions for working with specific scenarios to custom adapters for connecting your bot to users on clients like Facebook or Slack.

#### Extend your bot with code

You can also extend your bot with code - simply open up the folder that was generated for you in the location you chose during the creation process with your favorite IDE (like Visual Studio). You can do things like create custom actions that can be used during dialog flows, create custom middleware to pre-process (or post-process) messages, and more. See [our documentation](https://aka.ms/bf-extend-with-code) for more information.
## Bot_Composer
