# HelloPaw

HelloPaw is a web-based application designed to streamline the operations of pet service businesses. Built using the Django framework, it offers a suite of tools to manage clients, pets, services, orders, billing, and more, providing an integrated solution for pet care providers.  
![Alt Text](https://github.com/Marjan18101013/HelloPaw/blob/master/media/home/base.jpg?raw=true)

## Features

- **Client Management**: Maintain detailed records of clients, including contact information and associated pets.
- **Pet Profiles**: Store comprehensive information about each pet, such as breed, age, medical history, and service preferences.
- **Service Catalog**: Define and manage various pet services offered, including grooming, boarding, training, and veterinary care.
- **Order Processing**: Facilitate the scheduling and tracking of service orders, ensuring timely and organized service delivery.
- **Billing System**: Generate invoices, process payments, and maintain financial records for transparency and accountability.
- **User Authentication**: Secure the application with user login and role-based access controls to protect sensitive information.
- **Document Management**: Upload and manage important documents related to pets and services, such as vaccination records and service agreements.
- **Homepage and Navigation**: Provide a user-friendly interface with intuitive navigation to access various features of the application.

## Technologies Used

- **Backend**: Python, Django
- **Frontend**: HTML, CSS
- **Database**: SQLite (default for Django projects)
- **Media Handling**: Django's media management for uploading and serving files


### Use Case Diagram

The following UML use case diagram illustrates the primary interactions between system actors and functionalities in **HelloPaw**:

![Alt Text](https://github.com/Marjan18101013/HelloPaw/blob/master/media/images/DP/uml.png?raw=true)

**Description:**

- **Customer** can:
  - Buy **Products** or **Services**
  - Make **Payments**
  - Log into the system
- **Admin** has access to **Manage the System**
- Product and Service selection actions extend to more specific use cases like `choose product` and `choose service`.
- Payment actions extend to `pay product` and `pay service`, both of which require card validation from a **Bank** actor.

## Project Structure

The project is organized into several Django apps, each responsible for specific functionalities:

- `HelloPaw/`: Main project configuration and settings.
- `Client/`: Manages client-related data and interactions.
- `PetService/`: Handles the definition and management of pet services.
- `PetShop/`: Manages products and inventory for pet-related retail.
- `ServiceOrder/`: Processes service orders and scheduling.
- `User/`: Manages user authentication and profiles.
- `Document/`: Handles document uploads and management.
- `Home/`: Provides the homepage and general navigation.
- `Bill/`: Manages billing and invoicing functionalities.
- `media/`: Stores uploaded media files.
- `templates/`: Contains HTML templates for rendering views.



## Contact

For questions or feedback, please contact [Marjan18101013](https://github.com/Marjan18101013).
