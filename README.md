**Real Estate Management System**

**Project Description:**
The Real Estate Management System (REMS) is a Java-based application designed to facilitate property, landlord, tenant, and rental management for real estate agencies. It provides a graphical user interface (GUI) for managing operations such as registering landlords and tenants, recording properties, processing rentals, and persisting data.



**Features**

Landlord Management:

      *Register, amend, and remove landlords.
      *Maintain contact details, status, and unique IDs.

Tenant Management:

     *Register, amend, and remove tenants.
     *Manage tenant status and personal details.

Property Management:

    *Add new properties with attributes like address, number of beds, type, rent amount, and status.
    *List, search, and delete properties.

Rental Management:

    *Process rentals by associating tenants with properties.
    *View and update rental details.

Persistence:

    *Store and retrieve data using serialized files.

Graphical User Interface:

    *User-friendly GUI for managing all operations.



**System Requirements:**

Programming Language: Java 8 or later.

Development Environment: Apache NetBeans IDE.

Dependencies: Swing for GUI.



**Installation and Usage**

1. Clone the Repository
git clone <https://github.com/Nitheeskumar1405/RealEstateManagementSystem.git>
cd RealEstateManagementSystem

3. Build and Run the Project:
Open the project in Apache NetBeans or your preferred Java IDE.
Build and run the Property_Rental to launch the application.



**Team Contributions**

Team Members:

Nitheeskumar Sivakumar(ID-219600710):

*GUI integrations (HomeScreenGUI), overall system architecture, and core functionality.

*Landlord management and GUI components (Landlord.java, RegisterLandlordGUI.java, AmendLandlordGUI.java).

Pranav Maurya(ID-229660590):

*Tenant management and related tests (Tenant.java, RegisterNewTenantGUI.java, AmendTenantGUI.java).

Jama Omer(ID-209611830):

*Property management, including GUIs and persistence (Property.java, RecordNewPropertyGUI.java, PropertyRent.java).

Syed Almann(ID-229682780):

*Rentals and testing utilities (Rental.java, propertySaveTester.java, propertyLoadTester.java).


**License:**

This project is licensed under the MIT License. See the LICENSE file for details.



**Acknowledgments:**

Developed as part of a software engineering course.
Special thanks to our professor for guidance and feedback.



