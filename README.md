# ![Bot Framework SDK](./docs/media/FrameWorkSDK.png)

# Bot Framework SDK 

The Bot Framework SDK v4, part of the [Bot Framework](https://github.com/microsoft/botframework), provides the most comprehensive experience for building conversation applications. With the Bot Framework SDK, developers can easily model and build sophisticated conversation using their favorite programming languages. With the Bot Framework SDK, you can build bots that converse free-form or your bot can also have more guided interactions where it provides the user choices or possible actions. The conversation can use simple text or more complex rich cards that contain text, images, and action buttons. You can add natural language interactions and questions and answers, which let your users interact with your bots in a natural way.

## Bot Framework SDK v4
The Bot Framework SDK v4 includes SDKs that enable developers to model and build sophisticated conversation using their favorite programming language.

|   | C#  | JS  | Python |  Java | 
|---|:---:|:---:|:------:|:-----:|
|Stable Release |[4.4.3][1] | [4.4.0][2] | [4.4.0b1 (preview 2)][3] | [4.0.0.a6 (preview)](https://github.com/Microsoft/botbuilder-java#packages) |
|Docs | [docs][5] |[docs][5] | | |
|Samples |[.NET Core][6], [WebAPI][10] |[JavaScript][7] , [TypeScript][8], [es6][9]  | | | 

[1]:https://github.com/Microsoft/botbuilder-dotnet/#packages
[2]:https://github.com/Microsoft/botbuilder-js#packages
[3]:https://github.com/Microsoft/botbuilder-python#packages
[4]:https://github.com/Microsoft/botbuilder-java#packages
[5]:https://docs.microsoft.com/en-us/azure/bot-service/?view=azure-bot-service-4.0
[6]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/csharp_dotnetcore
[7]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/javascript_nodejs
[8]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/typescript_nodejs
[9]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/javascript_es6
[10]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/csharp_webapi

### Bot Framework SDK v4 - (New! - version 4.5 preview)
The Bot Framework SDK v4 - Version 4.5 new capabilites in preview. 

- [Adaptive Dialog][47] | [docs][48] | [C# samples][49] :: The new **Adaptive dialog** and the event model simplify sophisticated conversation modelling primitives, eliminate much of the boiler plate code and helps you **focus on the model of the conversation** rather than the mechanics of conversation and dialog management. This new way to model conversations that takes the best of waterfall dialogs and prompts and simplifies sophisticated conversation modelling primitives like building a dialog dispatcher and ability to handle interruptions elegantly.  Adaptive dialog, ground up is built to be [declaratively configurable][50].

- [Language Generation][43] | [docs][44] | [C# samples][45] :: Language generation is the umbrella term for generating appropriate output to the user. In some sense, language generation is reverse of language understanding. While language understanding goes from user input to extracting meaningful information such as intent and entities, language generation helps construct meaningful, variable and grammatically correct responses that a bot can send back to the user.

- [Common Expression Language][40] | [api][41] :: Both Adaptive dialogs and Language Generation rely on and use a common expression language to power bot conversations.

[40]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/common-expression-language
[41]:https://github.com/Microsoft/BotBuilder-Samples/blob/master/experimental/common-expression-language/api-reference.md
[43]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/language-generation
[44]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/language-generation/docs
[45]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/language-generation/csharp_dotnetcore
[46]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/language-generation/javascript_nodejs/13.core-bot
[47]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/adaptive-dialog
[48]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/adaptive-dialog/docs
[49]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/adaptive-dialog/csharp_dotnetcore
[50]:https://github.com/Microsoft/BotBuilder-Samples/tree/master/experimental/adaptive-dialog/declarative


## Questions and Help 
If you have questions about Bot Framework SDK or using Azure Bot Service, we encourage you to reach out to the community and Azure Bot Service dev team for help.
- For questions which fit the Stack Overflow format ("how does this work?"), we monitor the both [Azure Bot Service](https://stackoverflow.com/questions/tagged/azure-bot-service) and [Bot Framework](https://stackoverflow.com/questions/tagged/botframework) tags (search [both](https://stackoverflow.com/questions/tagged/azure-bot-service+or+botframework))
- You can also tweet/follow [@msbotframework](https://twitter.com/msbotframework) 

Join the conversation on **[Gitter](https://gitter.im/Microsoft/BotBuilder)**.

See all the support options **[here](https://docs.microsoft.com/en-us/bot-framework/resources-support)**.


## Issues and feature requests 
We track functional issues and features asks for and Bot Builder and Azure Bot Service in a variety of locations. If you have found an issue or have a feature request, please submit an issue to the below repositories.

|Item&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|Description|Link&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
|----|:-----|---------|
|SDK v4 .NET| core bot runtime for .NET, connectors, middleware, dialogs, prompts, LUIS and QnA| [File an issue](https://github.com/Microsoft/botbuilder-dotnet/issues) |
|SDK v4 JS| core bot runtime for Typescript/Javascript, connectors, middleware, dialogs, prompts, LUIS and QnA | [File an issue](https://github.com/Microsoft/botbuilder-js/issues) |
|SDK v4 Python| core bot runtime for Python, connectors, middleware, dialogs, prompts, LUIS and QnA | [File an issue](https://github.com/Microsoft/botbuilder-python/issues) |
|SDK v4 Java| core bot runtime for Java, connectors, middleware, dialogs, prompts, LUIS and QnA | [File an issue]( https://github.com/Microsoft/botbuilder-java/issues)|


## Prior releases

- Bot Builder v3 SDK has been migrated to the [Bot Framework SDK V3](https://github.com/microsoft/botbuilder-v3) repository.


## Prior releases
- Bot Builder V3 SDK has been migrated to the [Bot Framework SDK v3](https://github.com/microsoft/botbuilder-v3) repository.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Reporting Security Issues
Security issues and bugs should be reported privately, via email, to the Microsoft Security Response Center (MSRC) at [secure@microsoft.com](mailto:secure@microsoft.com). You should receive a response within 24 hours. If for some reason you do not, please follow up via email to ensure we received your original message. Further information, including the [MSRC PGP](https://technet.microsoft.com/en-us/security/dn606155) key, can be found in the [Security TechCenter](https://technet.microsoft.com/en-us/security/default).

## License

Copyright (c) Microsoft Corporation. All rights reserved.

Licensed under the [MIT](LICENSE) License.
