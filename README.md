# React from Scratch

Here many basic things are noted.

## 1. What is crossorigin (CORS)

The crossorigin attribute is used in HTML (mainly in <script>, <img>, and <link> elements) to handle cross-origin requests. It controls how browsers handle requests for resources from different origins (domains, protocols, or ports).

## Values of crossorigin

| Value           | Description                                                                     |
| --------------- | ------------------------------------------------------------------------------- |
| anonymous       | Requests the resource without credentials (cookies, HTTP authentication, etc.). |
| use-credentials | Requests the resource with credentials (cookies, authentication, etc.).         |
| (empty)         | Behaves like anonymous by default.                                              |
