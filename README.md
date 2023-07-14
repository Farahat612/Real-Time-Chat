# Real-Time Chat Web App

A simple real-time chat web application built using Python, Django, and Ajax. This project was developed as part of a learning journey to practice web development skills.

## Project Overview

The Real-Time Chat Web App is a simple yet powerful web application that allows users to communicate with each other in real-time. The app utilizes the Django web framework.
You can watch a demo here if interested: https://tinyurl.com/RTC-app

## Features

- **Real-time Messaging**: Users can send and receive messages instantly without needing to refresh the page.
- **Multiple Chat Rooms**: Users can join and participate in different chat rooms, creating separate conversations.
- **User Authentication**: The app provides a user authentication system, ensuring that only authenticated users can access and participate in chat rooms.
- **Responsive Design**: The app is designed to be responsive and adaptable to different screen sizes, providing a seamless experience across devices.

## Project Structure

The project follows the standard Django project structure, with the following key directories and files:
```
- djangochat/          # Project root directory
  - asgi.py
  - settings.py
  - urls.py
  - wsgi.py
- chat/                # App directory
  - admin.py
  - apps.py
  - models.py
  - tests.py
  - urls.py
  - views.py
- templates/           # HTML templates directory
  - home.html
  - room.html
- manage.py            # Django management script
```

## Getting Started

To get started with the Real-Time Chat Web App, follow these steps:

1. Clone the repository to your local machine using the following command:
`git clone https://github.com/Farahat612/Real-Time-Chat.git`
2. Navigate to the project root directory:
`cd djangochat`
3. Install the required dependencies by running:
`pip install django`
4. Apply database migrations using the following command:
`python manage.py migrate`
5. Start the development server:
`python manage.py runserver`


6. Open your web browser and visit `http://localhost:8000` to access the Real-Time Chat Web App.

## Usage

1. On the home page, enter a desired chat room name and your username.

2. Click the "Enter Room" button to join the chat room.

3. Once inside the chat room, you can start sending and receiving real-time messages with other participants.

4. To create additional chat rooms, simply enter a new room name on the home page and click "Enter Room" again.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please feel free to open an issue or submit a pull request.

## License

The Real-Time Chat Web App is released under the [MIT License](https://opensource.org/licenses/MIT).


## Known Issues or Limitations

Currently, there are no known issues or limitations with this project.
