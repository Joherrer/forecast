# GOLD COAST SURF FORECAST

## Description:

Gold Coast Surf Forecast is a web application designed with Python and Flask to offer real-time updates on surf conditions across all the prominent spots along the Gold Coast. This platform is built to provide surfers with accurate and timely surf forecasts to enhance their surfing experience.

Front End Development
The front-end interface of Gold Coast Surf Forecast is crafted using HTML and CSS, combined with Jinja for template rendering. This combination ensures a visually appealing, seamless, and responsive user experience across all devices, including desktops, tablets, and mobile phones. The design prioritizes user-friendliness, making it easy for surfers to navigate through the application and find the information they need quickly.

Back End Development
On the back end, the application leverages the power of SQL and SQLAlchemy to manage a robust database system. This setup efficiently handles and stores critical data, including user profiles, surf spot details, and real-time surf conditions. SQLAlchemy, being an ORM (Object-Relational Mapping) tool, ensures smooth interactions between the database and the application, allowing for complex queries and data manipulation with ease.

User Functionality
Users can create personalized accounts on Gold Coast Surf Forecast, which unlocks a range of features designed to enhance their experience. Upon logging in, users can save their favorite surf spots to a dedicated favorites page, allowing quick and easy access to detailed surf conditions specific to their preferences. This feature ensures that users can stay informed about their chosen locations without having to sift through data for other spots.

Real-Time Data and User Interaction
The application is designed to provide real-time updates on surf conditions, including wave height, wind speed, tide times, and other critical metrics essential for surfers. By delivering up-to-the-minute information, Gold Coast Surf Forecast helps users make informed decisions about when and where to surf, ensuring they catch the best waves under the safest conditions.

Conclusion
Gold Coast Surf Forecast stands out as a comprehensive and reliable resource for surfers on the Gold Coast. Its blend of modern web technologies and user-focused features makes it an indispensable tool for anyone looking to stay ahead of the waves and make the most of their surfing adventures. Whether you are a local surfer or a visitor to the Gold Coast, this application provides everything you need to plan your next surf session with confidence and convenience.

## Features
- Real-time surf condition updates
- User authentication and account management
- Save and manage favorite surf spots
- Responsive and user-friendly design

## Getting Started

### Prerequisites
- Python 3.x
- Flask
- SQLAlchemy

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Joherrer/forecast.git
    ```
2. Navigate to the project directory:
    ```bash
    cd forecast
    ```
3. Create a virtual environment:
    ```bash
    python3 -m venv venv
    ```
4. Activate the virtual environment:
    ```bash
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
5. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Database Setup
1. Set up the database:
    ```bash
    flask db init
    flask db migrate -m "Initial migration."
    flask db upgrade
    ```

### Running the Application
1. Start the Flask application:
    ```bash
    flask run
    ```
2. Open your browser and go to `http://127.0.0.1:5000`.

## Usage
1. Register for a new account or log in if you already have one.
2. Browse surf spots and save your favorites.
3. View detailed surf conditions for your favorite spots from your personalized favorites page.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any features, bug fixes, or enhancements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.