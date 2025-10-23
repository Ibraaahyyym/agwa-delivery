# 🛵 Picka Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)
[![Repo Size](https://img.shields.io/github/repo-size/<your-username>/picka-platform.svg)]()
[![Issues](https://img.shields.io/github/issues/<your-username>/picka-platform.svg)]()
[![Contributors](https://img.shields.io/github/contributors/<your-username>/picka-platform.svg)]()

**Picka Platform** — *Your delivery, your guy.*  
A full-stack delivery & logistics platform powering Picka, a community-first service starting in **Agwa, Chikun LGA, Kaduna State (Nigeria)**. Built to coordinate customers, riders, and local businesses with real-time tracking, payments, and rider management.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Architecture & Folder Structure](#architecture--folder-structure)
- [Tech Stack](#tech-stack)
- [Getting Started (Local Development)](#getting-started-local-development)
  - [Prerequisites](#prerequisites)
  - [Quickstart (clone & setup)](#quickstart-clone--setup)
  - [Environment Variables](#environment-variables)
  - [Run Backend](#run-backend)
  - [Run Frontend](#run-frontend)
  - [Run Mobile (optional)](#run-mobile-optional)
- [API & WebSocket Endpoints (Examples)](#api--websocket-endpoints-examples)
- [Testing](#testing)
- [Linting & Formatting](#linting--formatting)
- [CI / CD](#ci--cd)
- [Deployment Tips](#deployment-tips)
- [Security](#security)
- [Contributing](#contributing)
- [Roadmap](#roadmap)
- [Code of Conduct](#code-of-conduct)
- [License](#license)
- [Contacts & Support](#contacts--support)
- [Acknowledgements](#acknowledgements)

---

## Project Overview
Picka Platform is the central codebase for Picka’s web and backend systems:
- Customer-facing ordering UI (web/mobile)
- Business/vendor dashboard
- Rider app / dashboard & routing
- Admin & analytics panel
- Real-time order coordination & tracking

This repo aims to house the unified full-stack codebase for the MVP and later production systems.

---

## Features
- ✅ User registration & authentication (customers, riders, vendors, admins)  
- ✅ Browse shops & place orders (menu/catalog)  
- ✅ Order lifecycle: requested → accepted → picked-up → delivered  
- ✅ Real-time tracking via WebSocket / Socket.IO  
- ✅ Rider assignment & basic route optimization (MVP)  
- ✅ Payments: cash-on-delivery + provider integration (placeholder)  
- ✅ Vendor dashboard for order management  
- ✅ Admin dashboard for operations and analytics

---

## Architecture & Folder Structure
