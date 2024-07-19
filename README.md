Main Components
Imports:
Various javax.swing components for creating the GUI.
java.awt components for layout management.
java.awt.event for handling events.

Class Declaration:
RegistrationForm extends JFrame to create a main application window.

Constructor:
Sets up the GUI components and layout.
Initializes the form fields, labels, and buttons.

GUI Components:
Labels (JLabel): Display text for each input field (e.g., Name, Mobile, ID No, Gender, DOB, Address).
Text Fields (JTextField): Input fields for user data.
Radio Buttons (JRadioButton): Options for selecting gender.
Date Picker (JDateChooser): Input for selecting date of birth.
Text Area (JTextArea): Input for address.
Checkbox (JCheckBox): Checkbox for accepting terms and conditions.
Buttons (JButton): Register button to submit the form.
Table (JTable): Displays the registered user details.
Table Model (DefaultTableModel): Manages the data displayed in the table.

Action listener for the Register button:
Validates input fields.
Displays error messages if inputs are missing or terms are not accepted.
Adds data to the table upon successful validation.
Clears input fields after successful registration.

Main Method:
Creates an instance of the RegistrationForm class, displaying the registration form.
Key Functionality

Form Validation:
Ensures all required fields are filled and terms are accepted.

Data Addition:
Upon successful validation, user data is added to the table.

Clearing Fields:
Clears input fields automatically after successful registration.
