# Recaal

**Step-by-step guides for every coding process that matters.**

![License](https://img.shields.io/badge/license-MIT-blue)
![Azure](https://img.shields.io/badge/Azure-Enabled-blue)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-8.0-blue)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Enabled-blue)

## Table of Contents

1. [Description](#description)
2. [Problem](#problem)
3. [Solution](#solution)
4. [Personas](#personas)
5. [Use Cases](#use-cases)
6. [Full Feature Set](#full-feature-set)
   - [Guide Creation](#1-guide-creation)
   - [Personal Notes and Comments](#2-personal-notes-and-comments)
   - [Forking/Versioning](#3-forkingversioning)
   - [Search & Navigation](#4-search--navigation)
   - [Authentication & Security](#5-authentication--security)
   - [Responsive Design](#6-responsive-design)
   - [AI Integration](#7-ai-integration)
7. [MVP Features](#mvp-features)
8. [Technical Requirements](#technical-requirements)
9. [Potential Solutions for Page Creation, Display, and Storage](#potential-solutions-for-page-creation-display-and-storage)
   - [Page Creation and Display](#page-creation-and-display)
   - [Data Storage and Retrieval](#data-storage-and-retrieval)
10. [Validation Plan](#validation-plan)
11. [Setup Instructions](#setup-instructions)
12. [Project Milestones](#project-milestones)

## Description

Recaal makes it easy to create, share, and revisit step-by-step guides for any task—whether it’s a coding demo, a software workflow, or a DIY project. With screenshots, detailed explanations, and the ability to add personal notes as comments, Recaal helps you organize and recall processes effortlessly, anytime you need them.

## Problem

Students often struggle to remember all the commands and steps demonstrated during live coding sessions. It’s challenging to recall everything and take effective notes for later reference.

## Solution

Build a web application that allows instructors to document step-by-step processes for their demos. These documents can include screenshots, commands, and explanations. Students can revisit these step-by-step guides anytime, leave comments, and even add their own notes.

## Personas

1. **Coding Student**: Needs a reliable reference to revisit class demonstrations and commands.
2. **Instructor**: Wants to provide students with clear, step-by-step documentation for coding demos.
3. **Developer**: Wants to build a project to showcase software design and development skills.

## Use Cases

1. Students revisit previous lessons to recall commands and processes.
2. Instructors create and share step-by-step guides with students before or after live demos.
3. Developers build the application using their preferred tech stack and Azure services.

## Full Feature Set

| Feature                     | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| **Guide Creation**          | Instructors can create step-by-step documentation.                         |
|                             | Upload images/screenshots to illustrate steps.                             |
|                             | Add code blocks with syntax highlighting.                                  |
| **Personal Notes and Comments** | Students can add their own notes to guides.                                |
|                             | Comment on specific sections for clarification.                            |
| **Forking/Versioning**      | Students can fork guides and customize them.                               |
|                             | Track changes or revert to the original guide.                             |
| **Search & Navigation**     | Search guides and specific keywords.                                       |
|                             | Use an intuitive sidebar/menu for easy navigation.                         |
| **Authentication & Security** | Secure user login with Azure Active Directory B2C.                        |
|                             | Role-based access (Instructors vs. Students).                              |
| **Responsive Design**       | Fully functional on desktops, tablets, and mobile devices.                 |
| **AI Integration**          | Automatically convert PDFs/slides into editable guides.                    |
|                             | Suggest step-by-step plans based on a brief topic description.             |

## MVP Features

| Feature              | Description                                                      |
|----------------------|------------------------------------------------------------------|
| **Guide Creation**   | Basic step-by-step creation with text, code snippets, and images. |
| **User Authentication** | Secure login and user roles (Instructor/Student).                |
| **Guide Viewing**    | Students can view guides shared by instructors.                  |
| **Commenting**       | Ability to add basic comments on guides.                         |

## Technical Requirements

1. **Frontend**: Build with a modern JavaScript framework like React or Angular.
2. **Backend**: Develop with C# and ASP.NET Core.
3. **Database**: Use a relational database like SQL Server to store documentation and user comments.
4. **Azure Services**: Host the application using Azure App Service. Use Azure Blob Storage for storing images/screenshots.
5. **Authentication**: Implement user authentication using Azure Active Directory B2C.

## Validation Plan

1. **Interview Students**: Ask if they struggle to remember coding commands and demo steps.
2. **Interview Instructors**: Ask if they find it challenging to provide comprehensive notes or documentation for live demos.
3. **Survey Students**: Ask how they currently take notes during coding demos and if they would use a tool that provides step-by-step documentation.
4. **Survey Instructors**: Determine if they would find value in a tool that simplifies creating and sharing demo documentation.

## Setup Instructions

Provide detailed steps to clone the repository, set up the environment, and run the project locally:

1. Clone the repository.
2. Install dependencies.
3. Set up Azure configurations.
4. Start the development server.

## Production

1. Deploy application for user to use the application for free (limited page creation to ensure we don't inquire cost for the running application)
2. Make it open source and a quite on how to set up the application on private infrustracture and use the app for free in your organization
3. Ask for sponsorship to keep the project open source

## Project Milestones

### MVP Completion
- Guide creation and viewing.
- User authentication.
- Commenting system.

### Phase Two
- AI for converting PDFs/slides.
- Forking/versioning features.
- Enhanced search and navigation.
