---
layout: default
category: Open-Source
title: aws-lambda-goodreads-airtable
badges: Ruby
description: |
  AWS Lambda function to fetch books from Goodreads, serialize, and push to Airtable. Modified from original repo: Adapt to lambda function and replace harcoded keys with env variables; Specify ruby version; Add Makefile for convenience; General refactoring; Don't override all records by default (optimize for specific updates, such as unread to read); Cache activerecord calls to .all (since these trigger API calls); etc.
---

Github: [https://github.com/jasantunes/aws-lambda-goodreads-airtable](https://github.com/jasantunes/aws-lambda-goodreads-airtable)
