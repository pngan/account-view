# Quickstart

This document describes how to test the API using `curl`.

## Prerequisites

- The application running locally.

## Get Transactions

```bash
curl -X GET http://localhost:5000/api/transactions -H "Authorization: Bearer <YOUR_JWT_TOKEN>"
```

## Get Categories

```bash
curl -X GET http://localhost:5000/api/categories -H "Authorization: Bearer <YOUR_JWT_TOKEN>"
```
