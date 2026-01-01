# FastAPI Real-Time WebSocket Chat Demo

This is a **mini real-time chat application** built with **FastAPI** using **WebSockets**.  
It demonstrates instant messaging between multiple clients without refreshing the page.

## Features

- Real-time chat using WebSockets
- Personal messages (`You wrote: ...`)
- Broadcast messages to all other connected clients
- Disconnect notifications
- Simple front-end with HTML + Bootstrap

## Tech Stack

- **Backend:** FastAPI
- **Server:** Uvicorn (ASGI)
- **Frontend:** HTML + Bootstrap + JavaScript (WebSocket)
- **Python Version:** 3.11+

## Installation

1. Clone this repository:

```bash
git clone https://github.com/zhandev07/fastapi-realtime-chat
cd fastapi-realtime-chat
