# Dashboard Brasil - Real-Time Data Visualization

A responsive web dashboard that displays real-time data about Brazil, including weather, economic indicators, population statistics, and environmental data.

## Features

- **Real-time Weather Data**: Get current weather information for Brazilian cities
- **Economic Indicators**: 
  - Live Dollar exchange rate
  - SELIC rate
  - IPCA (inflation) data
- **Population Statistics**: Current population data with birth and death rates
- **Economic Evolution**: Historical GDP and inflation trends
- **Environmental Map**: Interactive map showing deforestation data
- **Sector Analysis**:
  - GDP distribution by sector
  - Greenhouse gas emissions by sector
- **City Rankings**: Population data for major cities
- **Cost of Living Index**: Comparative living costs across Brazilian cities

## Technologies Used

- HTML5 & CSS3
- JavaScript (ES6+)
- Chart.js for data visualization
- Leaflet.js for interactive maps
- External APIs:
  - OpenWeatherMap API
  - Brazilian Central Bank API (Banco Central do Brasil)
  - AwesomeAPI (Currency)
  - IBGE API (Brazilian Institute of Geography and Statistics)

## Setup

1. Clone the repository:
```bash
git clone [repository-url]
```

2. Open `index.html` in your web browser or set up a local server.

3. Update the API key in the JavaScript code:
```javascript
const weatherApiKey = "YOUR_API_KEY";
```

## Configuration

The dashboard updates every 10 minutes by default. You can modify the update interval in the JavaScript code:

```javascript
const updateInterval = 10 * 60 * 1000; // 10 minutes in milliseconds
```

## Features

### Weather Widget
- Real-time weather data for any Brazilian city
- Temperature, humidity, and wind speed
- Search functionality for different cities

### Economic Indicators
- Live Dollar/Real exchange rate
- SELIC interest rate
- Monthly IPCA inflation rate

### Interactive Map
- Visualization of deforestation data
- Color-coded regions
- Interactive tooltips with detailed information

### Charts and Graphs
- Line charts for economic trends
- Pie charts for sector distribution
- Animated loading states
- Responsive design

## Styling

The dashboard uses a dark theme with custom CSS variables for easy customization:

```css
:root {
    --bg-color: #0a0a1a;
    --card-bg: #141432;
    --text-color: #ffffff;
    --accent-color-1: #ff4d7c;
    --accent-color-2: #ff8a3d;
    --accent-color-3: #4dc9ff;
    --accent-color-4: #8a56ff;
}
```

## Responsive Design

The dashboard is fully responsive with breakpoints at:
- 1200px (tablet landscape)
- 768px (tablet portrait)
- 480px (mobile)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- OpenWeatherMap for weather data
- Banco Central do Brasil for economic indicators
- IBGE for demographic data
- OpenStreetMap contributors for map data
