#  MCP Weather Server

A lightweight **TypeScript + Node.js** server built using the [Model Context Protocol (MCP)](https://modelcontextprotocol.org/) to provide **real-time weather alerts** and **forecast data** using the [National Weather Service API](https://www.weather.gov/documentation/services-web-api). 

This is my **first MCP tool**, integrated with **Claude Desktop** and **Cursor**, and designed to demonstrate how AI tools can consume external APIs via tool invocation.

---

## Features

### `get-alerts`
Returns current weather alerts for a given US state code (e.g., `"CA"` for California).

### `get-forecast`
Returns a detailed weather forecast based on geographic coordinates (`latitude`, `longitude`).

---

## 🛠️ Tech Stack

| Technology     | Usage                                |
|----------------|--------------------------------------|
| TypeScript     | Type-safe development                |
| Node.js        | Backend runtime                      |
| MCP SDK        | Tool communication with Claude/Cursor|
| Zod            | Input schema validation              |
| NWS API        | External weather data                |

---
