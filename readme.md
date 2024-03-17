# QiblaQuest SG

QiblaQuest SG is a web application designed to assist Muslim users in Singapore to find mosques, musollas (prayer rooms), and carparks conveniently. The application aims to address the challenges Muslim users face when searching for prayer facilities and parking spaces, especially in unfamiliar areas or during busy times.

## User Stories

- **As a Muslim resident or visitor in Singapore**, I want to easily find nearby mosques and musollas for prayers, especially when I'm in a new area or traveling.
- **As a driver**, I want to locate available carparks near mosques and musollas to facilitate my parking during prayer times.
- **As a user with visual impairment or limited mobility**, I want a user-friendly interface with accessible features that allow me to navigate the application efficiently.

## Features

- **Interactive Map**: Users can view locations of mosques, musollas, and carparks on an interactive map, making it easy to identify nearby facilities.
- **Search Functionality**: Allows users to search for mosques or musollas by name or location, providing quick access to specific places of worship.
- **Geocoding Control**: Utilizes MapTiler geocoding to convert addresses into geographic coordinates for accurate marker placement on the map.
- **Location Services**: Provides users with their current location on the map, enabling them to easily identify nearby facilities.
- **Routing Control**: Offers routing functionality to find directions between two points, helping users plan their route to mosques or musollas.
- **Custom Icons and Popups**: Utilizes custom icons and popups to display additional information about each location, enhancing the user experience.
- **Clustered Markers**: Groups nearby markers into clusters for improved map visualization, especially in densely populated areas.
- **Responsive Design**: Ensures compatibility and usability across various devices and screen sizes, catering to the needs of a diverse user base.

## Technologies Used

- **HTML**
- **CSS**
- **JavaScript**
- **BootStrap5**
- **Leaflet**: Open-source JavaScript library for interactive maps.
- **Axios**: Promise-based HTTP client for making requests to fetch data.
- **Leaflet MarkerCluster**: Provides clustering functionality for better visualization of markers.
- **Leaflet Routing Machine**: Adds routing capabilities to the map for finding directions.
- **Leaflet Search Control**: Enables search functionality on the map for finding mosques or musollas.
- **Leaflet Control Geocoder**: Geocoding control for converting addresses into geographic coordinates.
- **Leaflet FlyTo**: Adds a control to fly to a specific location on the map.
- **SweetAlert2**: Provides beautiful, responsive, customizable pop-up boxes for user notifications.

## Design and User Experience

### Visual Theme
The design aims for simplicity and accessibility. The color scheme is chosen to be visually appealing yet easy on the eyes. Gold, white, black, and green tones are used to symbolize growth, harmony, and peace, aligning with the theme of spirituality and nature.

### Fonts
Clear and readable fonts are selected to ensure accessibility for all users. Sans-serif fonts are preferred for better legibility, especially on digital screens.

### Layout
The layout is designed to be intuitive and user-friendly, with essential features easily accessible. The map takes center stage, providing the main interface for users to interact with.

### Wireframes and Site Diagrams 
- [Site Diagram](site_diagram.pdf) (*coming soon*)

### Screenshots 

![Desktop View](screenshots/desktop.png) (*coming soon*)

![Mobile View](screenshots/mobile.png) (*coming soon*)

## Testing

### Test Cases
1. Search for a specific mosque by name.
2. Search for musollas in a particular area.
3. Check if the routing feature provides accurate directions.
4. Test the geocoding functionality by entering different addresses.
5. Ensure that markers are clustered correctly on the map.
6. Test the responsiveness of the application on various devices.

### Testing Steps
1. Enter a mosque name in the search bar and verify if the corresponding marker is displayed.
2. Enter a location in the search bar and check if nearby musollas are listed.
3. Input start and end points for routing and verify if the route displayed is accurate.
4. Enter different addresses in the geocoding control and confirm if the markers are placed correctly.
5. Check if markers cluster properly when zooming in and out on the map.
6. Open the application on different devices (desktop, tablet, mobile) to ensure responsiveness.

## Deployment

To deploy the project, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/QiblaQuestSG.git
   ```

2. Navigate to the project directory:

   ```bash
   QiblaQuestSG
   ```

3. Open `index.html` in a web browser to run the application locally.


## License

This project is licensed under the [MIT License](LICENSE).

