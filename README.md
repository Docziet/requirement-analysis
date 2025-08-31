# Requirement Analysis in Software Development.
This repo is a documentation for the requirement analysis process in the ALX Prodev Program

# Requirement Analysis

## What is Requirement Analysis?
Requirement Analysis is a **critical phase in the Software Development Lifecycle (SDLC)** where the project team gathers, analyzes, and defines the requirements of the system to be developed.  
It ensures that all stakeholders have a clear and shared understanding of what the system should do and how it should perform.

### Importance in SDLC
- Provides clarity and reduces ambiguity between developers and stakeholders.
- Defines project scope, preventing scope creep.
- Serves as a foundation for system design, development, and testing.
- Enables accurate cost, resource, and time estimation.
- Improves quality assurance and customer satisfaction.

---

## Why is Requirement Analysis Important?
Requirement Analysis is critical because it:
1. **Brings Clarity and Understanding** – Ensures that stakeholder expectations are understood and agreed upon.  
2. **Defines Scope** – Prevents uncontrolled changes by setting clear project boundaries.  
3. **Provides a Basis for Design and Development** – Creates a roadmap for developers and testers to follow.  
4. **Enables Better Estimation** – Helps estimate cost, resources, and project timelines more accurately.  
5. **Assures Quality** – Ensures the final product meets specified requirements.  

---

## Key Activities in Requirement Analysis
The Requirement Analysis process typically involves five key activities:

- **Requirement Gathering** 🗂️  
  - Interviews, surveys, workshops, observations, document reviews.  

- **Requirement Elicitation** ✍️  
  - Brainstorming, focus groups, prototyping.  

- **Requirement Documentation** 📚  
  - Requirement specifications, user stories, use cases.  

- **Requirement Analysis and Modeling** 📊  
  - Prioritization, feasibility analysis, modeling with DFDs or ER diagrams.  

- **Requirement Validation** ✅  
  - Reviews, stakeholder approval, defining acceptance criteria, traceability.  

---

## Types of Requirements

### Functional Requirements ⚙️
Describe **what the system should do**.  
**Examples for Booking Management Project:**
- **Search Properties**: Users can search by location, price, and availability.  
- **User Registration**: Users can create accounts with personal details.  
- **Property Listings**: Display property details with images.  
- **Booking System**: Users can book properties, view, and manage bookings.  
- **User Authentication**: Secure login and registration.  

### Non-functional Requirements 🛡️
Describe **how the system should perform**.  
**Examples for Booking Management Project:**
- **Performance**: Load pages within 2 seconds; support 1000 concurrent users.  
- **Security**: Data encryption, secure login, protection against vulnerabilities.  
- **Scalability**: System can scale to handle more users.  
- **Usability**: Simple, intuitive UI/UX for easy navigation.  
- **Reliability**: 99.9% uptime and quick recovery from failures.  

---

## Use Case Diagrams 📊
Use Case Diagrams visually represent **interactions between users (actors) and the system (use cases).**

### Benefits
- Provide a clear overview of system functionality.  
- Help organize and identify requirements.  
- Improve communication among stakeholders and developers.  

### Booking System Use Case Diagram
Actors:  
- **Guest User** – searches for properties.  
- **Registered User** – registers, books properties, manages bookings.  
- **Admin** – manages property listings, oversees bookings.  

![Booking System Use Case Diagram](./alx-booking-uc.png)  

---

## Acceptance Criteria ✅
**Acceptance Criteria** are measurable conditions a feature must meet to be accepted by stakeholders.  

### Importance
- Define *what success looks like* for each feature.  
- Ensure alignment between stakeholders, developers, and testers.  
- Provide a basis for validation and quality checks.  

### Example: Checkout Feature (Booking System)
- User selects available property and dates.  
- User confirms booking and proceeds to payment.  
- System processes payment securely.  
- User receives confirmation email within 2 minutes.  

---

✍️ **Author:** OKereke David Chidozie  
📂 **Repo:** requirement-analysis

