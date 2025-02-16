# Bus Reservation System

This repository hosts an interactive Bus Reservation System web application developed using HTML, CSS, and JavaScript. It features a modern, responsive design powered by Materialize CSS and provides a user-friendly interface for managing bus schedules and seat reservations.

## Features

- **Add Bus:** Create new bus entries by specifying details such as bus number, driver name, departure and arrival times, and route information.
- **Reserve Seat:** Book a seat by selecting the bus number, seat number (from 1 to 32), and entering the passenger's name.
- **Cancel Reservation:** Easily cancel a seat reservation if plans change.
- **View Buses:** Quickly view all bus details, including the number of total and available seats.
- **Delete Bus:** Remove a bus from the system with a simple form submission.
- **Available Seats:** Dynamically display a seating grid for each bus with visual cues—available seats are highlighted in green and occupied ones in red. Hover effects reveal additional passenger details for occupied seats.

## Technologies Used

- **HTML5:** Structure and semantic markup.
- **CSS3:** Custom styling with a background overlay effect and grid layout for seat arrangement.
- **JavaScript:** Application logic, event handling, and DOM manipulation to drive interactivity.
- **Materialize CSS:** A modern front-end framework for responsive design and pre-styled components.

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, etc.)
- No server setup is required as the application uses the browser's localStorage for data persistence.

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/bus-reservation-system.git
   ```

2. **Open the Application:**
   - Navigate to the project folder and open the `index.html` file in your browser.

## Usage

- Use the navigation tabs at the top of the page to switch between functionalities:
  - **Add Bus:** Fill out the form to add a new bus.
  - **Reserve Seat:** Enter the bus number, seat number, and passenger name to reserve a seat.
  - **Cancel Reservation:** Cancel an existing seat reservation using the provided form.
  - **View Buses:** See a list of all buses with current seat availability.
  - **Delete Bus:** Remove a bus entry from the system.
  - **Available Seats:** Visualize seat arrangements with an interactive grid.

- The application provides real-time feedback using custom toast notifications, enhancing the user experience.

## Contributing

Contributions are welcome! If you have ideas for improvements, bug fixes, or additional features, please feel free to fork the repository and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to explore, experiment, and help enhance this Bus Reservation System. Happy coding!
