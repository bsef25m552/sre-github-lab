# sre-github-lab
Requirement Documentation

# Food Delivery System

## Overview

The Food Delivery System is developed to simplify food ordering within hostel premises. It provides a digital platform where students can browse food items, submit orders, and receive deliveries at their rooms. The canteen manager can control menu availability, process incoming orders, and distribute delivery tasks among servers. The system replaces the existing phone-based and manual ordering process with a centralized solution.

## Scope

- In scope: Creating student accounts and managing login.
- In scope: Displaying food items, prices, and availability.
- In scope: Placing orders with selected items and quantities.
- In scope: Storing customer, order, and payment details.
- In scope: Managing incoming orders and assigning delivery staff.
- Out of scope: Deliveries beyond the selected hostel area.
- Out of scope: Third-party restaurants and external delivery services.
- Out of scope: GPS-based real-time location tracking.
- Out of scope: Direct online payment gateway processing.

## Stakeholders

- Students: Browse the menu, order food, provide delivery information, select payment methods, and receive their orders.
- Canteen Manager: Maintains food listings, handles customer orders, and distributes deliveries among available servers.
- Delivery Servers: Receive delivery assignments, access customer information, deliver orders, and update their progress.
- Project Maintainer: Maintains project documentation, handles requirement changes, and ensures consistency throughout development.

## Functional requirements

- FR-01: The system shall provide student registration and login facilities.
- FR-02: The system shall allow the manager to maintain food items, prices, and availability.
- FR-03: The system shall display the current food menu to students.
- FR-04: The system shall allow students to build and submit orders by selecting items and quantities.
- FR-05: The system shall save complete order information, including customer details, food items, total cost, and payment method.
- FR-06: The system shall provide the manager with facilities to review and confirm incoming orders.
- FR-07: The system shall allow the manager to distribute confirmed orders among available servers.

## Nonfunctional requirements

- NFR-01: The complete menu browsing and order placement process should take no longer than 3 minutes.
- NFR-02: Assigning an order to an available server should take no longer than 1 minute.
- NFR-03: The application should have a simple interface that allows all three user types to perform their tasks with minimal assistance.
- NFR-04: All completed orders must be stored with their associated customer, delivery, and payment information.
- NFR-05: The application should be accessible whenever the required network connection and canteen services are available.

## Acceptance criteria

- FR-01: When a student enters valid registration information, the system creates an account and allows subsequent login.
- FR-02: When the manager modifies a food item's price or availability, the updated information is reflected in the menu.
- FR-03: When a student opens the menu, all currently available food items and their prices are displayed.
- FR-04: When a student selects food items and quantities, the system displays the calculated total price before allowing the student to confirm the order.
- FR-05: After an order is submitted, its customer information, selected items, quantities, total price, delivery address, and payment method are saved.
- FR-06: When a new order is received, the manager can access its details and change its status to confirmed.
- FR-07: When the manager assigns an order to an available server, the assignment appears in that server's account within 5 seconds.
- FR-08: When a server opens their assigned orders, the system displays the relevant customer, room, food, and payment details.
- FR-09: When a server marks an order as Delivered, the system saves the updated status and displays it in the student's order history.
- FR-10: When an order status changes, the student can see the latest status within 5 seconds.
- FR-11: When submitting an order, the student can choose either cash or online banking.
- FR-12: When an order is marked as delivered, its customer, order, delivery, and payment information remains stored in the system.

## Assumptions and open questions

Assumptions

- A-01: The application will serve one selected hostel area and its centralized canteen.
- A-02: Students, managers, and servers will have suitable devices to access the application.
- A-03: Delivery staff will operate within walking distance of the canteen.
- A-04: Students will enter accurate room and hostel information.
- A-05: The canteen will continue supporting cash and online banking payments.
- A-06: Internet connectivity will be available during normal system usage.

Open Questions

- Q-01: Should students be able to modify or cancel orders after submission?
- Q-02: How will server availability be maintained and updated?
- Q-03: Should students receive notifications when their order status changes?
- Q-04: What specific online banking methods should be supported?
- Q-05: Should completed orders remain accessible indefinitely or only for a defined period?

## Project status and viewing

The project is currently in the requirements documentation phase. The system vision and initial requirements have been defined. Implementation and testing have not yet started.