# Medicore

Medicore is a comprehensive clinical management system designed to streamline the operations of healthcare facilities. This new version is built with Golang for the backend and React.js for the frontend, providing a robust and modern solution for managing patient records, appointments, billing, and more.

## Features

- **Patient Management**: 
  - Register new patients
  - Update patient information
  - View patient history

- **Appointment Scheduling**:
  - Book, reschedule, and cancel appointments
  - Automated reminders for upcoming appointments

- **Billing and Invoicing**:
  - Generate invoices for services rendered
  - Track payments

- **Inventory Management**:
  - Manage medical supplies and equipment
  - Track stock levels and reorder supplies

- **Reporting and Analytics**:
  - Generate reports on patient data
  - Analyze data to improve operational efficiency

- **User Management**:
  - Role-based access control
  - Manage staff profiles and permissions

## Installation

### Backend (Golang)

1. **Clone the repository**:
   ```bash
   git clone https://github.com/SehatForge/medicore.git
   ```

2. **Navigate to the backend directory**:
   ```bash
   cd medicore/backend
   ```

3. **Install dependencies**:
   ```bash
   go mod tidy
   ```

4. **Run the server**:
   ```bash
   go run main.go
   ```

### Frontend (React.js)

1. **Navigate to the frontend directory**:
   ```bash
   cd medicore/frontend
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm start
   ```

## Usage

- Access the application at `http://localhost:3000`
- Log in with your credentials
- Navigate through the dashboard to access different modules

## Contributing

We welcome contributions from the community. Please read our [contribution guidelines](https://github.com/SehatForge/medicore/blob/main/CONTRIBUTING.md) for more information.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/SehatForge/medicore/blob/main/LICENSE) file for details.
