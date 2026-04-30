# Flint Project

## Overview
Flint is a multi-faceted project that includes desktop and web applications, backend services, and machine learning components. It is designed to provide robust solutions for data analysis, forecasting, and trading environments.

## Project Structure

### Applications
- **Desktop**: Built with Electron and Vite, the desktop application includes components for charting, terminal integration, and user interface elements.
- **Web**: A Next.js-based web application with styled components and pages for user interaction.

### Backend Services
- **API**: Python-based API with routes for candles, contracts, forecasts, ICT, and volume. Includes data handling and service logic.
- **Market State**: Services for managing market data and states.
- **Trading**: Engines for ICT and volume trading.
- **ML Engine**: Machine learning components for forecasting and data analysis.

### Packages
- **Config**: Shared configuration files and presets.
- **UI**: Reusable UI components.

### Data
- **ES Futures**: Historical data files for futures trading.

## Getting Started

### Prerequisites
- Node.js
- Python 3.8+
- npm or yarn
- Conda (optional for Python environment management)

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd flint
   ```
3. Install dependencies:
   - For the desktop application:
     ```bash
     cd apps/desktop
     npm install
     ```
   - For the web application:
     ```bash
     cd apps/web
     npm install
     ```
   - For backend services:
     ```bash
     cd services
     pip install -r requirements.txt
     ```

### Running the Project
- **Desktop Application**:
  ```bash
  start_flint.bat
  ```
- **Web Application**:
  ```bash
  start_web.bat
  ```
- **Backend Services**:
  ```bash
  python -m services.api.main
  ```

## Contributing
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For questions or support, please contact the project maintainers.