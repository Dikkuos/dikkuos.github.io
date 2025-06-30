---
layout: "default"
title: "Ferry Capacity Monitor: Real-time Monitoring and Notifications 🚢📊"
description: "Monitor ferry capacities in real-time with our web app. Get instant alerts and track multiple departures effortlessly. 🚢✨ Join us on GitHub!"
---
# Ferry Capacity Monitor: Real-time Monitoring and Notifications 🚢📊

![GitHub release](https://img.shields.io/github/release/Dikkuos/ferry-capacity-monitor.svg) ![License](https://img.shields.io/badge/license-MIT-blue.svg)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Notifications](#notifications)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Overview

The **Ferry Capacity Monitor** provides a comprehensive solution for tracking ferry schedules and real-time capacity. This tool allows users to receive timely notifications about ferry availability, ensuring they can plan their trips effectively.

## Features

- **Real-time Capacity Monitoring**: Stay updated with the current capacity of ferries.
- **Timetable Access**: View the ferry schedule at any time.
- **Instant Notifications**: Get alerts when capacity changes or when ferries are full.
- **User-friendly Interface**: Built with React and Tailwind for a smooth experience.
- **Telegram Integration**: Receive notifications directly in your Telegram app.

## Technologies Used

- **React**: For building the user interface.
- **Tailwind CSS**: For styling the application.
- **TypeScript**: For better code quality and maintainability.
- **Vite**: For fast development and build processes.
- **Telegram API**: For sending notifications.

## Installation

To set up the Ferry Capacity Monitor on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Dikkuos/ferry-capacity-monitor.git
   ```
   
2. Navigate to the project directory:
   ```bash
   cd ferry-capacity-monitor
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and go to `http://localhost:3000`.

You can download the latest release from the [Releases section](https://github.com/Dikkuos/ferry-capacity-monitor/releases) and execute the necessary files.

## Usage

Once the application is running, you can access the main dashboard. Here, you can view the ferry timetable and real-time capacity. You can also set up your Telegram notifications in the settings menu.

### Setting Up Notifications

1. Go to the settings page.
2. Enter your Telegram Bot Token.
3. Select the ferry routes you want to monitor.
4. Save your settings.

You will now receive notifications whenever there is a change in capacity.

## How It Works

The Ferry Capacity Monitor fetches data from ferry service APIs. It updates the information in real-time and displays it on the dashboard. The backend is designed to handle multiple requests efficiently, ensuring that users always receive the latest data.

### Data Flow

1. **API Calls**: The application makes periodic API calls to fetch ferry schedules and capacity.
2. **State Management**: The state is managed using React's Context API to ensure all components have access to the latest data.
3. **Notifications**: When capacity changes, the application triggers a notification via the Telegram API.

## Notifications

Notifications are a key feature of the Ferry Capacity Monitor. Users can receive alerts through Telegram whenever:

- A ferry reaches full capacity.
- A new ferry is added to the schedule.
- There are any changes to existing ferry times.

### Setting Up Telegram Notifications

1. Create a Telegram bot using [BotFather](https://core.telegram.org/bots#botfather).
2. Copy the bot token and paste it into the application settings.
3. Select the routes you want to monitor.

You will receive updates directly in your Telegram app, keeping you informed without needing to check the app constantly.

## Contributing

We welcome contributions to the Ferry Capacity Monitor. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Create a pull request.

Please ensure your code follows the existing style and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Links

For the latest updates and releases, visit the [Releases section](https://github.com/Dikkuos/ferry-capacity-monitor/releases).