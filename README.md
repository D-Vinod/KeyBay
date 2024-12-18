# KeyBay: Online Marketplace Prototype

## Project Overview
KeyBay is a prototype online marketplace designed to connect buyers and sellers, facilitating secure transactions. It provides features such as product browsing, a shopping cart, a rating and review system, and intuitive interfaces for users to post and search for advertisements. This project was developed as part of the CS2833 – Modular Software Development course at the University of Moratuwa.

## Features
- User authentication with secure account creation and login.
- Sellers can create product listings with details such as title, description, category, and price.
- Buyers can browse categorized products, search using keywords, and add items to a shopping cart.
- A checkout system for completing purchases.
- Ratings and reviews for products and sellers.

## Requirements
### Functional Requirements
- Secure user login and account management.
- Detailed product listings by sellers.
- Search functionality for buyers.
- Shopping cart for managing selected items.
- Integrated rating and review system.

### Non-Functional Requirements
- Fast response times with minimal latency.
- Scalability to handle increasing user traffic.
- Intuitive user interface for easy navigation.

### Domain Requirements
- Well-organized product categorization.
- Integration with secure payment gateways.
- Compliance with e-commerce laws and data protection regulations.

## Implementation
KeyBay was developed as a software prototype focusing on the core functionalities. Java was used for development, with Java Swing for graphical user interfaces (GUIs). Team members were responsible for implementing specific features, which were integrated during the final stage.

### High-Level Design
1. **Use Case Diagram**: Captures user interactions, such as browsing, posting ads, and making purchases.
2. **Class Diagram**: Illustrates the system’s object-oriented structure, including key classes like `User`, `Product`, and `Transaction`.
3. **Key User Interfaces**:
   - **Login Page**: Secure login with username and password.
   - **Homepage**: Directs users to either buy or sell products.
   - **Sell Page**: Allows sellers to input product details and post ads.
   - **Explore Page**: Enables buyers to browse products.
   - **Item Page**: Displays product details and allows adding items to the shopping cart.

### Development Highlights
- **Languages and Tools**: Java for logic, Java Swing for GUI.
- **Implementation Flow**:
  - Secure login and authentication.
  - Seamless navigation between buyer and seller workflows.
  - Efficient categorization and filtering for enhanced user experience.

## Future Enhancements
1. **Dynamic Channel Ranking**: Re-evaluate feature rankings iteratively to optimize performance.
2. **Enhanced Testing**: Include larger datasets with labeled testing samples.
3. **User Traffic Handling**: Integrate load balancing for scalability.
4. **Cross-Platform Support**: Extend usability across mobile and web platforms.

## Contributors
- **D.M.D.V. Bandara** (Index No. 200061N)
- **J.J.S.E. Croos** (Index No. 200095V)
- **H.M.E.A.C. Herath** (Index No. 200212F)
- **M.D. Morawaka** (Index No. 200400F)
- **Vishagar A.** (Index No. 200686J)

## Acknowledgments
This project was completed as part of the CS2833 – Modular Software Development course at the University of Moratuwa. The team thanks the faculty for their guidance and support.

## Contact
For inquiries or collaborations, please contact:
- Faculty of Engineering, University of Moratuwa

---

### Appendix
**Codebase**: The implementation includes Java classes for the GUI and logic layers. Key files are:
- `Login.java`
- `Home.java`
- `SellPage.java`
- `ItemPage.java`
- `VehiclePage.java`
