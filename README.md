# Vote-application-docker
=========

A simple distributed application running across multiple Docker containers.

Getting started
---------------

Download [Docker Desktop](https://www.docker.com/products/docker-desktop) for Mac or Windows. [Docker Compose](https://docs.docker.com/compose) will be automatically installed. On Linux, make sure you have the latest version of [Compose](https://docs.docker.com/compose/install/). 


* A front-end web app written in Python or ASP.NET Core that allows you to choose between two solutions.\
* A Redis or NATS queue for collecting new votes.
* A Postgres or TiDB database that is supported by a Docker volume
* A.NET Core, Java, and .NET Core 2.1 worker for consuming votes and storing them.
* A Node.js and ASP.NET Core SignalR webapp that displays the vote results in real time
