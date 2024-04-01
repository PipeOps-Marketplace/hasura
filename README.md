---
title: hasura
description: A hasura instance with a PostgreSQL database
tags:
  - postgresql
  - hasura
---

# hasura on PipeOps

This example sets up a [hasura](https://hasura.io/opensource/) instance with a [PostgreSQL](https://www.postgresql.org/) database.

[![Deploy on PipeOps](https://railway.app/button.svg)](https://railway.app/new/template/hasura)

## ✨ Features

- Postgres
- hasura

## 💁‍♀️ How to use

- Click the `Deploy on pipeops` button
- Set up a `HASURA_GRAPHQL_ADMIN_SECRET` to secure your endpoints and console.
- Visit your console after the deployment is complete

## 📝 Notes

- This starter automagically provisions a PostgreSQL database for you when you click the `Deploy on pipeops`. The `DATABASE_URL` enviroment variable used in the `Dockerfile` is picked up from there.
- The hasura console and dev mode are enabled by default for a better development experience. You may want to read the [production checklist](https://hasura.io/docs/latest/graphql/core/deployment/production-checklist.html) before going live with your app.
