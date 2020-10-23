# Getting started

This page describes the initial setup, and shares links to materials we are
recommending to get familiar with when joining our team.

## Recommended tools

While your toolset is completely yours, below is the recommended (but not
required) list that will help join our projects:

| Tool name                                                                                            | Download Location                                                                                                    | Description                                                                                                                                                                                                                                                                                                                                            |
|:-----------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Microsoft Teams                                                                                      | ([link](https://www.microsoft.com/en-us/microsoft-365/microsoft-teams/download-app))                                 | Meeting client, collaboration tool                                                                                                                                                                                                                                                                                                                     |
| Git                                                                                                  | ([link](https://git-scm.com/))                                                                                       | Source code management tool.<br/>**Windows users** - we recommend using Cygwin (below) to install git instead of using a separate Windows installer                                                                                                                                                                                                    |
| NodeJS (current)                                                                                     | ([link](https://nodejs.org/))                                                                                        | Our preferred programming platform                                                                                                                                                                                                                                                                                                                     |
| Docker                                                                                               | ([link](https://www.docker.com/get-started))                                                                         | Container runtime<br/>**Windows users** - Docker Desktop is recommended<br/>**Other OS users** - Follow Docker install instructions for your operating system. Additionally, [`podman`](https://podman.io/) will suffice<br/><br/>Please note: this requirement may change when we start using [Kubernetes](https://kubernetes.io/) in our deployments |
| Code editor ([IDE](https://en.wikipedia.org/wiki/Integrated_development_environment)) of your choice | e.g. [Intellij IDEA](https://www.jetbrains.com/idea/) or [Visual Studio Code](https://code.visualstudio.com/)        | It's up to you what you prefer to use, but you'll need something to edit code. If you need a recommendation, VS Code is the most popular tool among Node JS developers. But most of our teammates prefer Intellij IDEA (or WebStorm which is de-facto the same IDE)                                                                                    |
| Cygwin (**Windows users**)                                                                           | ([link](https://cygwin.com/install.html))<br/>([package list](https://github.com/devsecops-learning/cygwin-scripts)) | POSIX shell and GNU tools for Windows.<br/>This is a recommended way to install `git` at Windows                                                                                                                                                                                                                                                       |

## Registration at online services

In our work, we use multiple online platforms, and you may want to ensure you
registered / have an account at:

- [Microsoft live](https://live.com) (to share documents, access Teams and
  Azure)
- [GitHub](https://github.com) (to collaborate on our projects and code)
- [Docker Hub](https://hub.docker.com/) (to access and publish container images)

## Recommended Knowledge

We recommend some reading to ensure we know the basics, and use the same
definitions. Additionally, we do offer deep dive sessions on all topics, and
will be happy assist catching up.

The links proposed below are just for those who don't have time to 'google'. We
recommend 'googling' these topics over just following links we provide.

Note the "Skim through?" column - we value your time, and do understand
that its not always possible to allocate enough time required for reading
technical reference documents. We'd still like to recommend these documents to
you, but all we ask you to do is just skim through, index these documents, so
that you know where to look for this information when you'll need it.

| Title / Name        | Link                                                                                                                        | [Skim through](https://en.wiktionary.org/wiki/skim_through)? | Description                                                                                                                                                                                  |
|:--------------------|:----------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| OSI Model           | ([link](https://en.wikipedia.org/wiki/OSI_model))                                                                           | N/A                                                          | High level overview of how information gets transmitted between two computer systems                                                                                                         |
| HTTP Protocol       | ([link](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview))<br/>([reference](https://tools.ietf.org/html/rfc7230)) | N/A<br/>Yes                                                  | Protocol used for communication between two computer systems. Essential for modern software development                                                                                      |
| REST API            | ([link](https://en.wikipedia.org/wiki/Representational_state_transfer))                                                     | N/A                                                          | An approach simplifying use of HTTP requests for client-server communication and actions                                                                                                     |
| Pro Git book        | ([link](https://git-scm.com/book))                                                                                          | Read sections 1-3, and can skim through the rest             | Git is extremely useful and powerful source code management tool. With our approach 'Everything as Code', its essential to know how to use it                                                |
| JavaScript tutorial | ([link](https://nodejs.dev/learn))                                                                                          | N/A                                                          | Any JavaScript tutorial of your choice. We recommend a couple of books/courses, focused on NodeJS (vs browser)                                                                               |
| NodeJS API          | ([link](https://nodejs.org/docs/latest/api/))                                                                               | Yes                                                          | It is impossible to write software without knowing standard capabilities of the chosen platform. Skim through NodeJS API just to know what functionality is available for you out of the box |
| Markdown language   | ([link](https://guides.github.com/features/mastering-markdown/))                                                            | Yes                                                          | Markup language used by nearly all code collaboration tools, in comments, chat messages, documents etc.                                                                                      |

### Additional resources

Some additional resources and books we highly recommend:

| Title / Name          | Link                                                                                          | [Skim through](https://en.wiktionary.org/wiki/skim_through)? | Description                                                                                                                                                             |
|:----------------------|:----------------------------------------------------------------------------------------------|:-------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Learn Microsoft Azure | ([link](https://docs.microsoft.com/en-us/learn/azure/))                                       | N/A                                                          | Microsoft Azure is our cloud platform of choice. It has great free learning resources.                                                                                  |
| CISSP CBK             | ([link](https://www.amazon.com/Official-ISC-Guide-CISSP-CBK/dp/1119423341))                   | Yes                                                          | That's right, basic security and risk management - essential to create quality solutions. This book is a great single source of everything you need to start in DevOps. |
| The Phoenix Project   | ([link](https://www.amazon.com/Phoenix-Project-DevOps-Helping-Business/dp/0988262592))        | N/A                                                          | The legendary book about DevOps. It's not a technical one. You may even prefer to buy an Audio version, it's great to listen while commuting or working out             |
| War and Peace and IT  | ([link](https://www.amazon.com/War-Peace-Business-Leadership-Technology-ebook/dp/B07JZHCVY9)) | N/A                                                          | Another great book that helps properly set goals of your projects, and understand what value your projects bring. Great in Audio, too!                                  |
