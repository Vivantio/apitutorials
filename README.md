# Vivantio Pro / ITSM API Tutorials

This is the home for API tutorials for Vivantio Pro / ITSM. We'll e expanding these tutorials over time so please do let us know what you would like to see here.

We also have a complementary GitHub repo of API samples [here](https://github.com/Vivantio/apisamples) and documentation about the APIs [here](https://github.com/Vivantio/apisamples/wiki).

## API Collections with Postman

Postman is a popular tool for working with APIs, and caters for those who are consumers of APIs as well as those creating them. Consumers of APIs can call an API from Postman and get to understand how it works in terms of inputs, authorization and so on.

One of the useful things you can do with Postman is create **collections** of API calls that can be exported for others to import and use. This is what we're doing with the Vivantio Pro / ITSM APIs, along with documentation to help you understand how to use the collections.

## Getting Started with Postman

If you are new to Postman these resources will help you get up to speed:

- [New to Postman? First 5 things to try](https://www.youtube.com/playlist?list=PLM-7VG-sgbtBsenu0CM-UF3NZj3hQFs7E)
- [Postman Learning Center](https://learning.postman.com/docs/postman/launching-postman/introduction/)

You can download the Postman application from [here](https://www.postman.com/downloads/) and once installed you will need to create an account and be logged in.

## Configuring Postman for use with Vivantio API Collections

The general detail of everything you need to configure is covered in the **New to Postman?** video series we've linked to above. Specifically you will need to:

1. Download or clone this repo to your local machine.
1. In Vivantio Pro or ITSM navigate to **Admin** > **Integrations & API** > **Downloads** so you have access to your **API Credentials**.
1. Create a new Postman environment called (for example) **Vivantio**.
1. In the Postman Vivantio environment create three variables and populate **INITIAL VALUE** and **CURRENT VALUE** with values from **API Credentials**:
   1. `base_url` = *Platform Url* plus `/api/`
   1. `username` = *Username*
   1. `password` = *Password*
1. Navigate to **File** > **Import** and choose the collection file from our repo that you would like to import.

## Working with Vivantio Pro / ITSM API Collections

Please see the following pages for guidance on using specific API collections:

- [Custom Forms Using the Entity APIs](working-with-custom-forms-using-entity-apis.md)
