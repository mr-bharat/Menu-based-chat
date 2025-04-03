# Menu-based Chat Widget

A menu-based chat widget, developed using pure JavaScript, HTML, CSS, and TailwindCSS, with Webpack used for the build process.

## Architecture
[User's Website] --> [JavaScript Initiator] --> Creates an iFrame and loads the widget --> [Chat Widget] --> Communicates via WebSocket/REST API --> [Backend Server] --> [Database]


## Features:
### 1. **Conversation History Storage**
   - Saves chat history in local storage for easy access and continuity.

### 2. **Mute/Unmute**
   - Allows users to mute or unmute the chat notifications.

### 3. **API Integration**
   - Fetches data from a server via API to enhance the chat experience.

### 4. **Download Chat History**
   - Users can download their chat history in `.txt` format.

## Tabs:
The widget is organized into three tabs:
- **Home Tab**: Displays the most recent conversation, frequently viewed support blogs, and featured articles.
- **Chat Tab**: Shows the chat conversation history stored in local storage by default. It also features a **Start Chat** button for users to initiate a new conversation.
- **Help Tab**: Displays support articles to assist with common issues.

## Upcoming Features:
### 1. **Live Chat**
   - The widget currently supports initiating live chat functionality, but WebSocket integration has not yet been implemented. Once WebSocket support is added, live chat will enable real-time communication with support agents for a more interactive and responsive user experience.
### 2. **AI Chat Agent**
   - A smart AI-based chat agent will be trained on support articles and FAQs. It will provide instant assistance and suggestions based on user queries, effectively streamlining the support experience. The AI will help handle common issues and guide users through troubleshooting steps, improving response times and user satisfaction.
### 3. **Push Notification**
   - A push notification will be sent to the user to alert them about new messages if they are away from the screen.

## Demo:
https://youtu.be/Qt4obg7tvp4
