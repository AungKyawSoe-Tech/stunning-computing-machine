# Stunning-computing-machine

## Primary Objective

The primary objective of creating this repository is for experimenting by making self-contained development environments for in-soucing by properly managing freelancers and also by providing secure, intellectul property protecting development environment. 

This will be a framework for a web site that will provide Docker Containers for software development.


## Secondary Objective

The secondary objective of this repostry is to see how to do scale up software development by means of AI/LLM Prompt engineering and Context engineering by using custom chatmodes.

### What Is a Custom Chat Mode?
It’s essentially a user-defined configuration file (chatmode.md) that tells Copilot how to think, act, and respond. For example, you can create modes tailored for:


## Development Approach

This project is developed by using AI development team inspired by this article below:

![AI development team workflow](ai_development_team_with_different_chatmodes.png)

[Reference: AI Development team article from dev.to](https://dev.to/this-is-learning/github-copilot-a-persona-based-approach-to-real-world-development-56ee?fbclid=IwY2xjawM8dztleHRuA2FlbQIxMQBicmlkETFJbnB5MllVUlBHRE44T2ttAR6Vo3pcghM2ZIT_lueDkcHrMkhWzQPT9YY1kK7I9FCDCRjqE5BPPvalCbbjUw_aem_DrbIbU_mdkUeC6Ac4H35zw)

The benefit of that approach is that continual flow of prompting by just switching chatmodes as follows:

![AI persona switching](switching_chatmodes.png)

## How custom chatmodes are used

When you load a mode with a Focus section, Copilot interprets it as a high-level directive. For example:

## Focus
- Focus: C++ development with Modern C++ 11/14/17/20/23, STL, Boost, CMake, and performance optimization. Use Non-Boost ASIO for networking and filesystem. Use header-only libraries, Use RAII and smart pointers for memory management. Follow C++ best practices and idioms. Use Cppcheck, Clang-Tidy, and AddressSanitizer for static analysis and runtime checks. Write unit tests with Google Test or Catch2. Adhere to the C++ Core Guidelines.

This tells Github Copilot to use:

- Modern C++ standards
- Boost
- Non-Boost ASIO for Networking and FileSystems
- Use Header Only libraries 
- CMake Built System
- RAII for smart pointers


## $$$$ 

While this AI multiple persona based approach can be useful for you to serve as an AI team there are cost implications for using custom chatmodes especially in
Agent mode and not in Ask mode.

In other words, custom chatmodes could be costly if one were using VS Code and Github Copilot using personal license. See cost below:

![Cost for custom chatmodes](cost_custom_chatmodes.png)

Above cost breakdown info is from the reference below

[Modes of Chatting with GitHub Copilot by John Miller](https://www.codemag.com/Blog/AIPractitioner/GHCPCM)

## MCP Integration
If you're using MCP instruction files, you can reference specific chat modes within those workflows—making it seamless to switch personas mid-task.

[MCP Integrations with custom chatmodes in VS Code](https://www.codemag.com/Blog/AIPractitioner/GHCPCM)

## Links

To understand more about custom chatmodes can be read here
[Custom chatmodes in VS Code](https://code.visualstudio.com/docs/copilot/customization/custom-chat-modes)

Contents of Chatmodes in this repo are adapted from

[Copilot repo for chatmodes](https://github.com/dfinke/awesome-copilot-chatmodes)

