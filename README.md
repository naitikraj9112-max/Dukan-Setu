# DukanSetu
### AI-Powered Multilingual Voice-First Business Communication & Order Management Platform

## Project Overview

**DukanSetu** is a smart, WhatsApp-inspired, AI-powered business communication platform designed to transform how local Kirana stores manage customer orders and daily operations.

In India, many small businesses rely heavily on WhatsApp messages, voice notes and handwritten records to receive orders, communicate with customers and track transactions. While convenient, this approach often leads to missed orders, communication errors, duplicated requests and inefficient inventory management.

DukanSetu addresses these challenges by combining a familiar chat interface with **multilingual voice AI, automated order processing, inventory management and real-time business tracking**.

Unlike traditional messaging applications, DukanSetu doesn't just enable conversations — it converts unstructured voice messages into **structured, actionable and trackable business operations**.

## Problem Statement

Small retailers frequently manage orders through WhatsApp chats and voice messages. As the number of customers increases, important information gets buried in conversations, making order tracking, modifications and inventory management difficult.

Additionally, many customers prefer communicating through voice notes in their regional languages rather than typing lengthy messages.

There is a need for a voice-first system that preserves the simplicity of messaging while providing the reliability of a dedicated business management platform.

## Our Solution

DukanSetu provides a WhatsApp-like messaging experience where customers can place and modify grocery orders using voice notes in supported languages such as Hindi, Kannada and English.

The system uses speech recognition and AI-powered natural language understanding to extract products, quantities and customer instructions from conversations. These details are converted into structured orders, verified with the customer and managed through a centralized shopkeeper dashboard.

Orders are stored in a database, enabling tracking, notifications, customer history, inventory monitoring and business analytics.

## Key Features

1. **WhatsApp-Inspired Chat Interface:** A familiar and responsive messaging experience for customers and shopkeepers.
2. **Multilingual Voice Ordering:** Customers can place orders using voice notes in their preferred supported language.
3. **AI-Powered Order Extraction:** Automatically extracts product names, quantities and units from spoken messages.
4. **AI Clarification Assistant:** Requests clarification when voice instructions are incomplete or ambiguous.
5. **Voice-Based Order Modification:** Allows customers to update, add or remove items through speech.
6. **Smart Inventory Management:** Checks stock availability and helps maintain product inventory.
7. **AI Product Substitution:** Suggests available alternatives for out-of-stock items.
8. **Duplicate Order Detection:** Identifies potentially repeated orders.
9. **Voice-Based Repeat Ordering:** Allows customers to request previous orders through voice commands.
10. **Real-Time Order Tracking:** Displays the current processing status of customer orders.
11. **Centralized Shopkeeper Dashboard:** Provides an interface for managing orders, customers and inventory.
12. **Business Analytics:** Visualizes order trends, popular products and store activity.
13. **Demand Forecasting:** Estimates future product requirements using historical order data.
14. **Voice-Based Order Confirmation:** Enables customers to confirm orders through spoken responses.
15. **Confidence-Based Error Detection:** Flags uncertain information and requests verification.
16. **Customer Order History:** Maintains searchable records of previous purchases.
17. **Automatic In-App Notifications:** Updates customers about changes in order status.
18. **Digital Order Records:** Stores structured orders and their processing history.

## Proposed Tech Stack

| Component | Technology |
|---|---|
| Frontend | React, Vite, Tailwind CSS |
| Backend | Python, FastAPI |
| Database | Neon PostgreSQL |
| Speech Processing | Multilingual Speech-to-Text |
| AI Processing | LLM-based Intent and Entity Extraction |
| Analytics | Recharts, Python |
| Version Control | Git, GitHub |
| Deployment | Vercel and compatible Python hosting |

*The technology stack may change based on the final implementation.*

## How It Works

1. A customer opens the DukanSetu web application.
2. The customer records a voice message in a supported language.
3. Speech recognition converts the audio into text.
4. AI identifies the customer's intent, products and quantities.
5. The system checks inventory and asks for clarification when necessary.
6. The customer confirms the order through voice.
7. The backend validates and stores the confirmed order.
8. The shopkeeper receives the order on a centralized dashboard.
9. The shopkeeper processes the order and updates its status.
10. The customer receives order updates within the application.

## What Makes DukanSetu Different?

Traditional messaging platforms are designed primarily for communication, not structured business operations.

DukanSetu bridges that gap by combining the ease of conversational messaging with intelligent automation and business management tools.

Its core innovation is **Voice-to-Action AI** — converting multilingual spoken instructions into verified business transactions rather than simply transcribing audio.

## Expected Impact

- Reduce missed and duplicated grocery orders.
- Minimize manual recordkeeping.
- Improve communication between customers and shopkeepers.
- Make digital ordering more accessible to voice-first and regional-language users.
- Enable faster order processing and improved inventory visibility.
- Help small businesses make decisions using structured operational data.

## Hackathon Context

Developed for **REWIRED Hackathon — A: ECHO**, addressing the challenge of redesigning real-world workflows that currently depend on WhatsApp voice notes and informal messaging.

The project focuses on making voice communication actionable without forcing users to abandon their preferred way of interacting.

## Project Vision

**DukanSetu — From Voice Notes to Real Actions.**

Our vision is to create an accessible, intelligent and scalable communication platform that helps small businesses move beyond informal WhatsApp-based workflows toward reliable, voice-first digital operations.
