
# Internshala Automation

A backend project that automates interactions with the [Internshala](https://internshala.com/) website using Puppeteer. This project enables automated login, job/internship searches, and data extraction, making it easier to manage tasks on Internshala through an automated backend service.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The **Internshala Automation** project is designed to streamline interactions with the Internshala website. By leveraging **Puppeteer**, this project automates tasks such as logging in, searching for specific internships or jobs, and extracting relevant data.

## Features

- Automated login to Internshala with user-provided credentials
- Programmatic search for internships and jobs based on filters
- Extraction of internship/job details, such as title, company, location, and stipend
- Saves results in a structured format (e.g., JSON or CSV)
- Configurable to meet specific data extraction needs

## Tech Stack

- **Node.js**: Runtime environment for backend
- **Puppeteer**: Headless browser automation library

## Setup and Installation

### Prerequisites

- [Node.js](https://nodejs.org/en/) (version 14.x or later)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/internshala-automation.git
   cd internshala-automation
   ```
````

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory with the following:

   ```plaintext
   INTERNSHALA_USERNAME=your_email@example.com
   INTERNSHALA_PASSWORD=your_password
   ```

4. **Run the project**
   ```bash
   node index.js
   ```

## Usage

1. Run the automation script using:
   ```bash
   node index.js
   ```
2. The script will:

   - Log in to your Internshala account
   - Perform searches or data extraction as configured
   - Save data to a specified output file (e.g., `output.json`)

3. **Customization**: Modify `config.js` to adjust search parameters, output format, or data extraction options.

## Folder Structure

```plaintext
internshala-automation/
├── cover.js              # Put your customised cover letter here
├── scripts/              # Puppeteer scripts for specific tasks
├── .env                  # Environment variables (username/password)
├── index.js              # Main entry point of the project
└── README.md             # Project documentation
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the project
2. Create a new branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
