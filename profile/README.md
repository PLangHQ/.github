


# Plang Programming Language

![Plang Logo](https://plang.is/android-chrome-192x192.png)

***Plang is a modern programming language written in natural language.***

Join our community on [Discord](https://discord.gg/A8kYUymsDD) | Follow us on [Twitter](https://twitter.com/planghq)


## Introduction

Plang is a programming language written in natural language.

Plang is a new type of programming language that provides various features over other operation programming languages. It has built in Identity, built in database, built in messaging, solves syncing between device, and more. 

Plang provides the developer with features that he already is familiar with such as variables, condition and for statements as well as powerfull standard library, and language is easily extendable.

Plang provides increased security and privacy to both developer and users of their application, for free as in beer.

## Hello plang world
This is an example of a hello world app written in plang

```plang
Start
- write out 'Hello plang world'
```

Then you build & run it
```bash
$ plang exec
```

## Installation

Set up Plang on your system. Download Plang from [the download page](https://github.com/PLangHQ/plang/releases) and follow our [Installation Guide](https://github.com/PLangHQ/plang/blob/main/Documentation/Install.md).

## Getting Started

Explore plang's capabilities and start building today. For initial steps and guidance, see [Getting Started with plang](https://github.com/PLangHQ/plang/blob/main/Documentation/GetStarted.md).

## Usage

Explore plang's features and capabilities:

- **Basics for everybody**
    - **[Development Environment (IDE)](https://github.com/PLangHQ/plang/blob/main/Documentation/IDE.md)**: This is where you write your code. Makes sure to setup your development environment.
    - **[Rules](https://github.com/PLangHQ/plang/blob/main/Documentation/Rules.md)**: The basic rules to follow when writing plang code.
- **Basics for beginners**
    - **[Variables](https://github.com/PLangHQ/plang/blob/main/Documentation/Variables.md)**: Learn about `%variables%` in plang and how to use them.
    - **[Conditions](https://github.com/PLangHQ/plang/blob/main/Documentation/Conditions.md)**: Understanding `if` statements and conditional logic in plang.
    - **[Loops](https://github.com/PLangHQ/plang/blob/main/Documentation/Loop.md)**: Explore how to go through a list of data
    - **[Date & Time](https://github.com/PLangHQ/plang/blob/main/Documentation/Time.md)**: How you work with `%Now%`, the date and time of the system
- **For everybody**
    - **[Debugging](https://github.com/PLangHQ/plang/blob/main/Documentation/Debug.md)**: Learn how to debug when programming in the plang language
    - **[Examples](https://github.com/PLangHQ/plang/tree/main/Tests)**: See list of plang code examples, it can help you get started    
    - **[Apps](https://github.com/PLangHQ/apps/)**: See list of available apps, written in plang. Great for learning.
- **Advanced**
    - **[Identity](https://github.com/PLangHQ/plang/blob/main/Documentation/Identity.md)**: What is Identity and why is it so important
    - **[Private keys](https://github.com/PLangHQ/plang/blob/main/Documentation/PrivateKeys.md)**: What private keys are in the system and where are they stored.
    - **[Settings](https://github.com/PLangHQ/plang/blob/main/Documentation/Settings.md)**: How to store and use settings in your app such as API keys and other sensitive data.
    - **[Runtime Lifecycle](https://github.com/PLangHQ/plang/blob/main/Documentation/RuntimeLifcycle.md)**: Sequence of operations when running plang
    - **[Runtime Events](https://github.com/PLangHQ/plang/blob/main/Documentation/Events.md)**: Learn about event-driven programming in plang.
    - **[Builder Lifecycle & Events](https://github.com/PLangHQ/plang/blob/main/Documentation/BuilderLifcycle.md)**: Sequence of operations when building plang and build events
    - **[Modules](https://github.com/PLangHQ/plang/blob/main/Documentation/modules/README.md)**: Learn how to extend the language. Discover the different modules available in plang and their capabilities. 
    - **[Services](https://github.com/PLangHQ/plang/blob/main/Documentation/Services.md)**: Learn how flexible the plang language is, e.g. using the db engine of your choice, your own caching service and more.
        - **[Use OpenAI directly](https://github.com/PLangHQ/plang/blob/main/Documentation/PlangOrOpenAI.md)**: Shows how to use OpenAI API directly instead of PLang LLM service
    - **[Reserved keywords](https://github.com/PLangHQ/plang/blob/main/PLang/Utils/ReservedKeywords.cs)**: See list of reserved keywords in the language
- **Developing the plang language**
    - **[Help create PLang](https://github.com/PLangHQ/plang/blob/main/Documentation/PLangDevelopment.md)**: Information on how to help with development of plang programming language.
- **Examples of actual apps**
    - List of apps at https://github.com/PLangHQ/apps
    - **Doc builder** - This doc is built with plang
        - [Setup](https://github.com/PLangHQ/plang/blob/main/Documentation/Setup.goal)
        - [Start](https://github.com/PLangHQ/plang/blob/main/Documentation/Start.goal)
        - [Modules](https://github.com/PLangHQ/plang/blob/main/Documentation/Modules.goal)
    - **Static content generator** - plang.is website is built using plang
        - [Start](https://github.com/PLangHQ/plang.is/blob/main/Start.goal)

## Features

Plang comes with a wide range of features including:

- Intuitive syntax (just natural language, with some rules)
- Powerful standard library
- [Built-in Identity](https://github.com/PLangHQ/plang/blob/main/Documentation/Identity.md)
- [Efficient error handling](https://github.com/PLangHQ/plang/blob/main/Documentation/modules/plang.Modules.FileModule.md#caching-retries-error-handling--run-and-forget)
- [Efficient cache handling](https://github.com/PLangHQ/plang/blob/main/Documentation/modules/plang.Modules.CachingModule.md#caching)
- [Built-in Messaging system](https://github.com/PLangHQ/plang/blob/main/Documentation/paper/README.md#messages)
- [Built-in Database](https://github.com/PLangHQ/plang/blob/main/Documentation/paper/README.md#dbmodule)
- [Dependency injection](Services.md)
- [User privacy](https://github.com/PLangHQ/plang/blob/main/Documentation/paper/README.md#security--privacy)
- [Verifiable code](https://github.com/PLangHQ/plang/blob/main/Documentation/paper/README.md#verifiable-code---possible)
- [Local storage of your data](https://github.com/PLangHQ/plang/blob/main/Documentation/paper/README.md#event-sourcing)
- [Sync between devices](https://github.com/PLangHQ/plang/blob/main/Documentation/paper/README.md#event-sourcing)
- [User is in control the UX](https://github.com/PLangHQ/plang/blob/main/Documentation/paper/README.md#user-interface)
- [Programing in your native tongue](https://github.com/PLangHQ/plang/blob/main/Documentation/paper/README.md#natural-language-neutral)
- [Security at another level, eliminating most problems we have today](https://github.com/PLangHQ/documentation/tree/main/blob/main/Security.md)

## Paper

You can read the ["paper" I wrote](https://github.com/PLangHQ/plang/blob/main/Documentation/paper/README.md) while developing plang. 
It goes into detail about the language and thoughts.

## Contributing

Join our community of contributors! Learn how you can contribute on [GitHub](https://github.com/PLangHQ).

## Versioning

At version 0.1. 

## Authors and Acknowledgment

- Creator: [@ingig](https://twitter.com/ingig)
- Contributors: [See the list of contributors](https://github.com/PLangHQ/plang/blob/main/Documentation/contributors.md)

Special thanks to everyone who has developed an open source project that plang uses. ❤️

## License

plang is available under LGPL version 2.1. Details are in our [LICENSE](https://github.com/PLangHQ/LICENSE).

## Contact Information

Go to the [discussion board](https://github.com/orgs/PLangHQ/discussions), 
find us on [Discord](https://discord.gg/A8kYUymsDD)
or follow us on [Twitter](https://twitter.com/planghq)
or email [plang@plang.is](mailto:plang@plang.is)


