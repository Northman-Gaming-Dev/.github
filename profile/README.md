# Northman Gaming Dev

Software, services, automation, and tools for Northman Gaming Corporation.

## Table of contents

- [Northman Web v2](#northman-web-v2)
- [Archived v1 services](#archived-v1-services)
- [Applications and tools](#applications-and-tools)
- [Development](#development)

## Northman Web v2

The active TypeScript platform and its supporting services.

### Core platform

- [Monorepo](https://github.com/Northman-Gaming-Dev/northman-web-v2)  
  Main v2 workspace containing shared architecture and deployment resources.
- [Frontend](https://github.com/Northman-Gaming-Dev/northman-web-fe-v2)  
  Next.js user interface for the Northman platform.
- [Backend](https://github.com/Northman-Gaming-Dev/northman-web-be-v2)  
  Fastify API and backend business logic.
- [Gateway](https://github.com/Northman-Gaming-Dev/northman-web-gateway-v2)  
  Public API and realtime gateway boundary.
- [SDK](https://github.com/Northman-Gaming-Dev/northman-web-sdk-v2)  
  Shared TypeScript contracts and client types.
- [Load balancer](https://github.com/Northman-Gaming-Dev/northman-web-lb-v2)  
  Cloudflare edge routing and origin health handling.
- [Attendance app](https://github.com/Northman-Gaming-Dev/northman-attendance-app-v2)  
  Expo Android employee clock application.
- [Database backup](https://github.com/Northman-Gaming-Dev/northman-db-backup-v2)  
  Database backup and retention service.

### Services

- [Audit publisher](https://github.com/Northman-Gaming-Dev/northman-web-audit-publisher-v2)  
  Publishes audit events for downstream consumers.
- [Email](https://github.com/Northman-Gaming-Dev/northman-web-email-v2)  
  Email delivery and notification service.
- [File manager](https://github.com/Northman-Gaming-Dev/northman-web-file-manager-v2)  
  File uploads, downloads, deletes, and replica repair.
- [Fleet](https://github.com/Northman-Gaming-Dev/northman-web-fleet-v2)  
  Fleet and vehicle operations service.
- [Logger](https://github.com/Northman-Gaming-Dev/northman-web-logger-v2)  
  Centralized application logging service.
- [MCP/LSP](https://github.com/Northman-Gaming-Dev/northman-web-mcp-lsp-v2)  
  MCP server and language-server bridge.
- [Queue](https://github.com/Northman-Gaming-Dev/northman-web-queue-v2)  
  Background job and queue processing service.
- [Redis](https://github.com/Northman-Gaming-Dev/northman-web-redis-v2)  
  Redis management and shared cache service.
- [Replica manager](https://github.com/Northman-Gaming-Dev/northman-web-replica-manager-v2)  
  Replica coordination and synchronization service.
- [Socket](https://github.com/Northman-Gaming-Dev/northman-web-socket-v2)  
  Socket.IO realtime transport service.
- [STL manager](https://github.com/Northman-Gaming-Dev/northman-stl-manager-v2)  
  STL asset management service.
- [Supabase](https://github.com/Northman-Gaming-Dev/northman-web-supabase-v2)  
  Supabase integration and write-layer packages.
- [Tampermonkey](https://github.com/Northman-Gaming-Dev/northman-web-tampermonkey-v2)  
  Browser automation and Tampermonkey scripts.
- [Telegram](https://github.com/Northman-Gaming-Dev/northman-web-telegram-v2)  
  Telegram notification and messaging service.
- [Users](https://github.com/Northman-Gaming-Dev/northman-web-users-v2)  
  User, identity, and access-related service functionality.

## Archived v1 services

Legacy repositories retained for reference and compatibility work.

- [Frontend](https://github.com/Northman-Gaming-Dev/northman-web-fe)  
  Archived v1 frontend application.
- [Backend](https://github.com/Northman-Gaming-Dev/northman-web-be-v1)  
  Archived v1 backend API.
- [Child backend](https://github.com/Northman-Gaming-Dev/northman-web-child-be)  
  Archived v1 child-service backend.
- [Gateway](https://github.com/Northman-Gaming-Dev/northman-web-gateway)  
  Archived v1 gateway and routing layer.
- [SDK](https://github.com/Northman-Gaming-Dev/northman-web-sdk)  
  Archived v1 shared SDK.
- [Attendance service](https://github.com/Northman-Gaming-Dev/northman-attendance-service)  
  Archived employee attendance service.
- [Identity service](https://github.com/Northman-Gaming-Dev/northman-identity-service)  
  Archived identity and authentication service.
- [Scraper service](https://github.com/Northman-Gaming-Dev/northman-scraper-service)  
  Archived data scraper service.

## Applications and tools

- [Telegram bot](https://github.com/Northman-Gaming-Dev/northman-telegram-py-bot)  
  Python Telegram bot and operational automation tools.
- [Project 101 APK](https://github.com/Northman-Gaming-Dev/northman-project-101-apk)  
  Project 101 Android application workspace.

## Development

All repositories are private. Active feature development targets v2; v1 repositories are reference-only.
