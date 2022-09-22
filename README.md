# Synaze API Documentation

We wrote the documentation for Synaze Cloud in Insomnia HTTP client which is free and open source client available for Windows, Linux and macOS. API Documentation in Insomnia client will bring you flexible and interactive experience while you are working on your own application with SynazeCloud API.

## Contents 

- [Installation](#installation)
- [Environment Setup](#environment-setup)
- [Interface Explanation](#interface-explanation)

## Installation

1. Download and install [Insomnia HTTP client](https://insomnia.rest/download).
2. Open Insomnia client and create new project via Git Clone button.
3. Paste url address https://github.com/synazecloud/synaze-api.git into URL input and confirm the popup.
4. Open newly created document and switch at center of the top navigation into Debug tab.
5. That's all.

## Environment Setup

To properly run all documented endpoints you have to set environment variables.

In the top left corner you will see **Config** dropdown menu, click on it and select **Manage Environments**. In Config environment you will see two variables which you have to edit on your own.

1. `base_url` - The base url of your running server with SynazeCloud (for Business)
2. `token` - The authentication token generated in the SynazeCloud app or obtained via `/api/login` login route.

## Interface Explanation:
Interface is divided into three parts:

#### Left Sidebar
All SynazeCloud API endpoints sorted into multiple categories

#### Middle part
Contains URL address bar with 5 Tabs:
1. Body of the request
2. Request authorization with bearer token for all secured endpoints
3. Queries for your request
4. Header setup for sending requests
5. Docs where you find explanations for current endpoint

#### Right Sidebar
The original response of the request which was sent


