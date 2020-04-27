# deno_search

A CLI utility to search for deno packages.

## Installation

```bash
$ deno install --allow-net ds https://github.com/etopiei/deno_search/master/main.ts
```

## Usage

This is quite a naive search, no fuzzy matching yet, it simply looks for all search terms in the package description.

e.g.

```bash
$ ds "web"
abc - A better Deno framework to create web application
alosaur - Alosaur - Deno web framework 🦖.
bwt - Better Web Token,  a web token format, generation, and verification scheme
denotrain - An easy to use webserver engine like express in nodejs fully written in Typescript.
espresso - deno minimal web framework
fen - A simple web framework for deno.
i18next_http_middleware - A simple i18next middleware to be used with Node.js web frameworks like express or Fastify and also for Deno.
pogo - Pogo is an easy to use, safe, and expressive framework for writing web servers and applications. It is inspired by hapi.
saur - Deno Saur is a full-stack web application framework with a focus on rapid development, similar to Django or Ruby on Rails.
webview - Deno bindings for webview, a tiny library for creating web-based desktop GUIs
```
