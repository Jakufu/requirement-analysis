# requirement-analysis

# Requirement Analysis in Software Development.
Welcome to the **Requirement Analysis** repository! 
This repository serves as a central space to document the requirements analysis process in software development projects.  

It includes research, specifications, user stories, and planning materials that guide the design and implementation of effective, user-centered solutions.  

The goal is to ensure clear alignment between project stakeholders, technical teams, and user needs.

## What is Requirement Analysis?
Requirement Analysis is a critical phase in the software development lifecycle (SDLC) where the project team gathers, analyzes, and defines the requirements of the software product to be developed. This process ensures that all stakeholders have a clear and mutual understanding of what the system should do and how it should perform.
### Why is Requirement Analysis Important?
- **Clarity and Understanding**: It helps in understanding what the stakeholders expect from the software, reducing ambiguity.
- **Scope Definition**: Clearly defines the scope of the project, which helps in preventing scope creep.
- **Basis for Design and Development**: Provides a solid foundation for designing and developing the system.
- **Cost and Time Estimation**: Facilitates accurate estimation of project cost, resources, and time.
- **Quality Assurance**: Ensures that the final product meets the specified requirements, leading to higher customer satisfaction.

  ## Key Activities in Requirement Analysis.
1. Requirement Gathering
- Engage with stakeholders to collect initial requirements.
- Use various techniques like interviews, surveys, and workshop
2. Requirement Elicitation
- Refine and elaborate on the gathered requirements.
- Use techniques like brainstorming, focus groups, and prototyping.
3. Requirement Documentation
- Document the requirements in a detailed and structured format.
- Use requirement specification documents, user stories, and use cases.
4. Requirement Analysis and Modeling
- Analyze and prioritize the requirements.
- Create models to visualize and understand the requirements.
5. Requirement Validation.
- Review and validate the requirements with stakeholders.
- Define acceptance criteria and ensure traceability.

 ## Types of Requirements.

### Functional Requirements

Functional requirements define the specific behaviors or functions that the system must perform. They describe *what* the system should do.

**Examples:**

* **Hotel Management Service:**
    * **Add New Hotel:** The system must allow hotel managers to add new hotel listings, including details such as name, address, number of rooms, and available amenities.
    * **Update Hotel Information:** The system must enable hotel managers to modify existing hotel information, such as room availability, pricing, and descriptions.
    * **View Booking Details:** The system must allow hotel managers to view details of all bookings made for their hotel(s).

* **Customer Service (Search + Booking):**
    * **Search Hotels:** The system must allow customers to search for hotels based on criteria such as location, dates, number of guests, and optionally, amenities or price range.
    * **View Hotel Details:** The system must allow customers to view detailed information about a specific hotel, including photos, descriptions, amenities, and reviews.
    * **Book Hotel:** The system must enable authenticated customers to book a selected hotel for specified dates and number of guests.
    * **Process Payment:** The system must integrate with a third-party payment service to securely process booking payments from customers.
    * **Receive Booking Confirmation:** The system must provide customers with a confirmation of their booking details.

* **View Booking Service:**
    * **View Current Bookings:** The system must allow authenticated users (both customers and managers) to view their current and upcoming bookings.
    * **View Past Bookings:** The system must allow authenticated users to view their past booking history.

* **Notifications:**
    * **Send Booking Notification to Manager:** The system must send a notification to the relevant hotel manager when a new booking is made.
    * **Send Booking Confirmation to Customer:** The system must send a booking confirmation notification to the customer after a successful booking.
    * **Send Offer Notifications to Customers:** The system may send notifications to customers about new offers or promotions.

### Non-functional Requirements

Non-functional requirements define the quality attributes of the system. They describe *how* the system should be.

**Examples:**

* **Performance:**
    * **Search Responsiveness:** The system should return hotel search results within a reasonable timeframe (e.g., under 3 seconds) even during peak load.
    * **Booking Processing Time:** The system should process booking requests and generate confirmations within a short period (e.g., under 5 seconds).

* **Scalability:**
    * **Handle High User Traffic:** The system should be able to handle a large number of concurrent users and booking requests without performance degradation, especially during peak travel seasons.
    * **Data Volume Handling:** The system should be able to efficiently manage and query a large volume of hotel and booking data.

* **Reliability:**
    * **High Availability:** The system should be highly available with minimal downtime to ensure continuous service for users.
    * **Data Consistency:** The system should ensure data consistency across all its services and databases (e.g., when a booking is made, inventory is updated accurately).

* **Security:**
    * **Secure Payment Processing:** The system must securely handle payment information through integration with a PCI DSS compliant payment gateway.
    * **User Authentication:** The system must provide secure authentication and authorization mechanisms for both hotel managers and customers.

* **Maintainability:**
    * **Modular Design:** The microservices architecture should contribute to the maintainability of the system by allowing independent updates and deployments of individual services.
    * **Well-Defined APIs:** Clear and well-documented APIs between services will enhance maintainability and integration.

* **Usability:**
    * **Intuitive User Interface:** The customer and manager portals should have user-friendly and intuitive interfaces for easy navigation and task completion.
    * **Responsive Design:** The customer-facing application should be responsive and accessible on various devices (desktops, tablets, and mobile phones).

## Use Case Diagrams.
### What are they?
Use Case Diagrams are a type of UML (Unified Modeling Language) diagram that visually shows:

- Actors (who interacts with the system, e.g., customers, hotel managers, admins)

- Use cases (the main goals or actions, e.g., search hotels, book hotel, make payment)

- They help clarify system scope, user interactions, and key functionalities at a glance.

### Benefits:
-  Clarifies system requirements early.
-  Aligns team understanding of who does what.
-  Simplifies communication with both technical and non-technical stakeholders.
-  Helps identify missing or extra features.

![image alt](https://github.com/Jakufu/requirement-analysis/blob/744fa65a8763a5208d712626f70b316c0a293865/alx-booking-uc.png)
