docker # .github

# GenAI Logic - the future of software lifecycle development using AI 

 docker # .github

# About

This is the **development site** for API Logic Server.  This is used by the **development team**; the first link below is intended for users.

|   Site    | For   | Notes   |
:-------|:------------|:-----------------|
| [User Documentation](https://apilogicserver.github.io/Docs/) | **Users** | Creating projects |
| [demo](https://github.com/ApiLogicServer/genai_demo) | **Users** | Review a Sample Project from the [homepage](https://www.genai-logic.com/) (try Shift + ".") |
| &nbsp; | | |
| [MySQL creation and deployment](https://github.com/ApiLogicServer/docker-compose-mysql-classicmodels) | **Users** | **Creating and deploying MySQL** example with docker and docker-compose |
| [Postgres deployment](https://github.com/ApiLogicServer/docker-compose-nw-postgres) | **Users** | **Deploying existing Postgres** example with docker and docker-compose |
| &nbsp; | | |
| [SQLAlchemy](https://docs.sqlalchemy.org/en/20/) | All | ORM |
| [SAFRS](https://github.com/thomaxxl/safrs/wiki) | All | API |
| [Flask](https://flask.palletsprojects.com/en/2.3.x/) | All | Server |
| &nbsp; | | |
| [API Logic Server Source](https://github.com/ApiLogicServer/ApiLogicServer-src) | Developers | [Dev Install - source and docs](https://apilogicserver.github.io/Docs/Architecture-Internals/)  |
| [Docs Source ](https://github.com/ApiLogicServer/Docs) | Developers | Uses mkdocs |
| &nbsp; | | |
| [Donate](https://www.paypal.com/donate/?hosted_button_id=YRVDR6Q59AT5G)| | Support for [WebGenAI](https://apifabric.ai) from [GenAI Logic](https://www.genai-logic.com) |

&nbsp;

# What is API Logic Server
API Logic Server is an open source Python project to make it faster and easier to create __database web applications.__  It provides a CLI to create customizable projects with a single command, that you can then run / customize / debug in your IDE.  

Created projects provide an API, an Admin Web App, and spreadsheet-like business rules to enforce database integrity. They can be containerized to simplify deployment. 

Additional background is provided in the next section, below.  Extensive [documentation is available here](https://apilogicserver.github.io/Docs/) - checkout the [FAQs]([https://valhuber.github.io/ApiLogicServer/FAQ-Frameworks/](https://apilogicserver.github.io/Docs/FAQ-Low-Code/)).

You can use this page in several ways:

* __Tutorial:__ [Click here](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=593459232) to open codespaces to see a created project, explore it, and learn how to create it

* __Learning Center:__ [Click here](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=641207071) to use an _API Fiddle_ to learn key concepts of JSON:API, Flask and SQLAlchemy

&nbsp;

# Why: Partial Automation, Proprietary IDEs

We saw __shortfalls in current approaches__ for building database systems:

* __Frameworks: too slow -__ _multi-endpoint APIs_ and _multi-page apps_ would require _weeks_ in frameworks such as Flask or Django, since it's all code -- no automation

* __Low Code Tools: no backend automation, proprietary IDEs__ - good UI automation, but none for backend business logic (nearly half the effort), and often do not leverage existing IDEs (VSCode, PyCharm, etc).

&nbsp;

# Instant, Full System Automation, Leverage Existing Tools
So, we created API Logic Server: with a single command, create __executable / customizable database projects__, providing an __Admin App__, an __API__, and __spreadsheet-like rules__ for business logic.

API Logic Server is an __open source__ Python project: a __CLI__ for project creation, and a set of __execution runtimes.__  Install with a standard Python (`pip`) install or Docker.<br/><br/>

## Project Creation is Instant: Single Command
 
&nbsp;&nbsp;&nbsp;&nbsp;
`ApiLogicServer create --project_name=ApiLogicProject --db_url=`<br/><br/>


## Projects are Highly Functional: Admin UI and API
API Logic Server reads your schema, and creates an  __executable__ project:

* __API__ - an endpoint for each table, with filtering, sorting, pagination and related data access

* __Admin UI__ - multi-page / multi-table apps, with page navigations and automatic joins<br/><br/>

## Projects are Customizable: Using _Your_ IDE

Customize projects in __your IDE__ (VSCode, PyCharm, etc.) for edit, debug and code management.<br/> <br/>


## Business Logic is Automated: Unique Rules :trophy: 

Declare business logic with spreadsheet-like rules (40x more concise than code), extensible with Python.

&nbsp;

