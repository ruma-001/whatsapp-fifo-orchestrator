# WhatsApp FIFO Order Orchestrator 🚀

An intelligent "wrapper" for small-scale Indian businesses (Textiles, Agri, Social Commerce) that converts chaotic WhatsApp LIFO (Last-In-First-Out) chats into a structured, fair FIFO queue.

## 📦 The Problem
Small businesses in India taking orders during Instagram/YouTube Lives face a "Message Avalanche." WhatsApp naturally pushes the latest message to the top (LIFO). This rewards the last person to message and buries the first customers who inquired.

## ✨ The Solution
This app provides a headless orchestration layer that:
1. **Strict FIFO Queue:** Prioritizes customers based on their *first* inquiry timestamp.
2. **Live Inventory Sync:** Notifies the entire queue when an item is sold out.
3. **Auto-Confirmation:** Uses UPI Virtual Accounts to verify payments via webhooks.
4. **Live Analytics:** Real-time revenue and wait-time tracking for the vendor.

## 🛠 Tech Stack
- **Frontend:** React Native (Mobile-First)
- **Backend:** Node.js (Express) with PostgreSQL
- **Integration:** Meta WhatsApp Cloud API
- **Payments:** UPI Deep-linking & Webhook confirmation

## 🚀 Quick Start

### 1. Backend Setup
