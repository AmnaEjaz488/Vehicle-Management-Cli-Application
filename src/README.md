# Vehicle Management CLI Application

## User Story

AS a developer  
I WANT to update an existing application to include additional vehicle types  
SO THAT I am able to comprehend and work with existing code bases.

## Acceptance Criteria

GIVEN a command-line application that accepts user input  
WHEN I am prompted to create a new vehicle or select an existing vehicle  
THEN I can choose between the two options  

WHEN I am prompted to choose the vehicle type during creation  
THEN I can choose between car, truck, and motorbike  

WHEN I am prompted for details about the vehicle  
THEN I can enter the vehicle information  

WHEN I have entered all the vehicle information  
THEN I can use the created vehicle  

WHEN I select an existing vehicle  
THEN I can use the selected existing vehicle  

WHEN I have created a new vehicle or selected an existing vehicle  
THEN I can perform actions with that vehicle  

WHEN I perform an action with a vehicle  
THEN I see the result of the action in the command-line  

WHEN I complete the process of performing an action  
THEN I can perform additional actions until I choose to exit  

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/vehicle-management-cli.git
    ```
2. Navigate to the project directory:
    ```sh
    cd vehicle-management-cli
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

## Usage

1. Start the application:
    ```sh
    npm start
    ```
2. Follow the prompts to create a new vehicle or select an existing vehicle.
3. Enter the required details for the vehicle.
4. Perform actions with the created or selected vehicle.
5. Continue performing actions until you choose to exit.

## Features

- Create new vehicles (car, truck, motorbike)
- Select existing vehicles
- Perform various actions with the vehicles
- View the result of each action in the command-line

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
