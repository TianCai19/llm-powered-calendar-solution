
# LLM-Powered Calendar Solution
[简体中文](README.zh.md) | [English](README.md)
## Project Overview

The **LLM-Powered Calendar Solution** leverages the capabilities of large language models (LLMs) to create an intelligent and user-friendly calendar management tool. It allows users to generate `.ics` files effortlessly by describing events in natural language or uploading event details (e.g., timetables or meeting invites). These `.ics` files are fully compatible with Google Calendar, Apple Calendar, and other major platforms.

### Key Features:
- **AI-Driven Schedule Parsing**: Understands text and images to extract key event details.
- **Easy File Generation**: Produces ready-to-import `.ics` files without any coding.
- **Time-Saving Automation**: Eliminates manual entry for complex scheduling scenarios like course timetables or recurring meetings.

👉 **[Try the Calendar Assistant](https://chatgpt.com/g/g-674207a394048191a9816f7be35153e6-ri-li-chuang-jian-zhu-shou)**

---

## Key Use Cases

1. **Course Timetable Integration**: Automatically convert class schedules into calendar events.
2. **Event Invitations**: Generate `.ics` files for meetings or events from email text or PDFs.
3. **Travel Itineraries**: Quickly add multi-stop travel plans into your calendar.
4. **Recurring Meetings**: Set up recurring appointments with ease, including custom reminders.

---

## How It Works

1. **Provide Event Information**: Describe events via text or upload screenshots of schedules or invitations.
2. **AI Processing**: The LLM parses the input, identifies key details, and creates a `.ics` file.
3. **Calendar Import**: Import the `.ics` file into your preferred calendar app:
   - **iPhone Users**: Use the [shortcut](https://routinehub.co/shortcut/7005/) for quick integration.
   - **Other Users**: Open the `.ics` file to add events to your calendar.

---

## What is an ICS File?

An ICS file is a universal calendar format used for sharing and storing events. It supports details such as:
- **Event Name**: Title of the event.
- **Start and End Time**: Dates and times in a standard format.
- **Location**: Venue or online meeting link.
- **Description**: Additional event details.

### Example ICS Syntax

```plaintext
BEGIN:VCALENDAR
VERSION:2.0
CALSCALE:GREGORIAN
BEGIN:VEVENT
SUMMARY:Class: Introduction to AI
DTSTART:20241130T090000Z
DTEND:20241130T103000Z
LOCATION:Room 203, Science Building
DESCRIPTION:Lecture on AI fundamentals.
END:VEVENT
END:VCALENDAR
```

This standard format ensures compatibility across platforms, making it easy to share and import event data.

---

## Why Use the LLM-Powered Calendar Solution?

- **No Coding Required**: Perfect for non-technical users.
- **Cross-Platform**: Compatible with all major calendar applications.
- **High Efficiency**: Save time and avoid manual entry errors.
- **Powerful Parsing**: Works with both text descriptions and images.

---

## Contributing

Contributions are welcome! Submit Issues or Pull Requests to help improve the solution.

---

## License

This project is licensed under the MIT License.
