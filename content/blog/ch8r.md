---
id: 9
title: 'Ch8r - An AI Powered Customer Support Agent'
slug: 'ch8r'
description: 'In this blog, we’ll discuss Ch8r - an open-source customer support agent with a chat widget and API access and its features.'
published: true
posted: 2025-10-13
authorSlug: 'anish-ghimire'
banner: ''
bannerAlt: 'Ch8r - An AI Powered Customer Support Agent'
tags: ['CH8R', 'Customer Support']
featured: true
---

## Introduction to Ch8r
[Ch8r](https://github.com/Sarva-Tech/ch8r) is an open source smart customer support agent that provides chat widget and 
API access. It works by allowing users to upload their documents as knowledge base files and then processes them in a way
AI can search and provide information to users.

## Ch8r - Features

Ch8r comes with features such as a project-wise organized knowledge base, chat APIs, smart escalation, and project
management integrations.

### Application based data separation
  Each application being created has its own knowledge base, chats, and other configurations. Each application 
  may represent a separate site, web app or a custom use case.
  
  You can create a new application by clicking on the application switcher at the top-left of the screen, and
  then selecting 'Create New Application'.
  
  ![Ch8r - Create Application](/img/ch8r/ch8r-create-app.png)

  While creating a new application, you can provide its name and also upload knowledge base documents.
    
### Knowledge base
  AI does not have accurate information, troubleshooting steps, guidelines about your specific product. That’s 
  where Ch8r comes in: upload your product specific documents and Ch8r does the rest for you. Internally, 
  it processes the documents you provide in a way that AI can respond to queries related to your product.

  ![Ch8r - Knowledge Base](/img/ch8r/ch8r-knowledge-base.png)

  You can add files such as PDFs, Word documents, text files, or Markdown files, or simply paste text to 
  upload your product-specific documents.

### Widget integration

  You can integrate AI-powered chat support, built on top of your knowledge base, into your site. This allows 
  your users to submit their queries via the chat widget available on your site.
  
  ![Ch8r - Widget Integration](/img/ch8r/ch8r-widget-integration.png)

  To enable widget integration, visit the API Keys & Widget page and turn on the widget integration. 
  You will then be provided with code snippets to include in your website’s code to display the chat 
  support on your site

### Chat API access

  If you want to fully customize your chat experience and take it to the next level, we provide API access
  to our chat endpoints. By integrating these APIs, you can build the chat experience you want - 
  while we handle everything else, like knowledge base processing and conversation insights.

  ![Ch8r - API Keys](/img/ch8r/ch8r-api-keys.png)

  You can also create a new API key from the API Keys & Widget page.

### Conversation insights

  Monitor, review, or jump into the conversation happening between your site users and AI 
  via the chat widget or API access in real time from Ch8r’s dashboard.


  ![Ch8r - Conversation Insights](/img/ch8r/ch8r-conversation-insights.png)

### Smart human escalation

  **There can be times when AI is unable to process certain user queries. This can happen when the issue is 
  new, unusually complex, or sensitive enough to require human assistance. 
  
  In such cases, we smartly escalate those requests to the support team or ask the user whether they want to escalate 
  the request. We send a notification to the configured channel about the need to escalate.
  
  ![Ch8r Human Escalation](/img/ch8r/ch8r-human-escalation.png)

### Notification profiles

  Configure notification profiles so that important notifications such as human escalation immediately
  arrive in your Mail, Slack, or Discord.

![Ch8r Notification Profiles](/img/ch8r/ch8r-notification-profiles.png)

### Project management integrations

  Knowledge base documents are helpful, but do they capture the full picture of your product? Ch8r supports
  integrating project management systems such as GitHub Projects.

  ![Ch8r Project Management Integration](/img/ch8r/ch8r-project-management-integration.png)  

  These integrations allow the AI to provide more contextually accurate responses.

  ![Ch8r Project Management Tools Configuration](/img/ch8r/ch8r-project-management-tools-configuration.png)

  For example, if a user asks about a feature, Ch8r can check whether it's already planned, in progress,
  or resolved and respond with the most up-to-date information. Or file a support ticket on the user’s behalf.

## Roadmap

The MVP of this project is complete and has been open-sourced for the community. At this point, 
I’ve paused active development to focus on other projects.

That said, the repository remains open for anyone who’d like to:

- Explore or use the existing features

- Contribute new functionality or improvements

- Fork it and build upon it for their own use cases

While the MVP is complete and functional, there are several features and improvements that could make 
this project more robust and production-ready. If someone sponsors or contributes to further development,
here are some ideas to work on:

- Automated knowledge base processing.
- Support for additional knowledge base sources such as URLs, Discord, and Slack.
- Bring and use your own vector databases.
- Additional project management integrations such as Jira and Linear.
- CRMs integration.
- Custom tool integration to perform product specific actions.
- Support for creating Discord, Slack, and WhatsApp chatbots.

If you or your team are interested in continuing its development, sponsoring further work, 
collaborating, or hiring us, feel free to reach out to me via 
[LinkedIn](https://www.linkedin.com/in/anishghimire862/), [X](https://x.com/anishghimire862) or 
[email](mailto:anishghimire862@gmail.com).

You can find the repository [here](https://github.com/Sarva-Tech/ch8r). The README.md contains instructions to run and self-host the project.
