# 🏷️Label Printing Automation

A robust solution for automating label printing by linking zones with branches and specific printers. This project integrates with the PrintNode API to ensure that whenever a customer creates a new order, the system automatically assigns the correct branch and printer based on user-defined settings, and sends a print request with complete order details.

## 📝Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Architecture](#architecture)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [API Integration](#api-integration)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🔍Overview

This project was built to meet the requirement of automating the label printing process for orders. The key objectives include:
- Linking zones with branches and specific printers.
- Automatically assigning a branch and printer information to new orders.
- Integrating with the PrintNode API to send print requests.
- Enhancing the printed PDF with additional order information.

The system is designed to save all branch and printer selections by the user, ensuring a seamless and error-free order processing workflow.

## 🔥Features

- **Automatic Branch Assignment:** When a new order is created, the system assigns the appropriate branch based on the customer's selected zone.
- **Printer Selection:** Each zone is linked to a specific printer, with the printer ID saved in the order meta.
- **PrintNode API Integration:** Automatically sends print requests to PrintNode API for real-time printing.
- **Enhanced PDF Generation:** Generates detailed PDF labels with complete order and printer information.

## 🪨Architecture

The application is designed with scalability and maintainability in mind. Key components include:

- **Zone-Branch Mapping Module:** Associates zones with branches and specific printers.
- **Order Processing Service:** Monitors new orders, assigns branch and printer information, and triggers print requests.
- **Print Request Handler:** Integrates with the PrintNode API to send print jobs.
- **PDF Generation Module:** Enriches the label PDF with additional information before printing.

## 🚀Installation

