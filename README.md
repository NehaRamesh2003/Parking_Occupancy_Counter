Sure, here it is formatted for easy copy-pasting:

---

# Parking Occupancy Project

This project aims to monitor and display the occupancy status of parking spaces in a given parking lot using image processing techniques.

## Features

- Select and manage parking spaces.
- Display the number of empty and occupied parking lots.
- Visual representation with occupied spots in green and empty spots in red.

## Getting Started

### Prerequisites

- Python 3.x
- Required Python libraries (listed in `requirements.txt`)

### Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/NehaRamesh2003/Parking_Occupancy_Counter.git
    cd Parking_Occupancy_Counter

    cd parking-occupancy-project
    ```

2. Install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. **Select Parking Spaces**

    Run the `ParkingSpacePicker.py` script to select parking spaces on the image:

    ```bash
    python ParkingSpacePicker.py
    ```

    - Left-click on the spot in the image to select a parking space.
    - Right-click on the rectangle to delete a parking space.

2. **Run the Main Script**

    Once all the required spots are selected, run the `main.py` file to monitor and display the parking occupancy status:

    ```bash
    python main.py
    ```

    You will see:
    - The number of empty parking lots out of the total number of parking lots.
    - Occupied spots will be highlighted in green.
    - Empty spots will be highlighted in red.

### Directory Structure

```plaintext
parking-occupancy-project/
│
├── images/
│   └── parking_lot_image.jpg  # Sample image of the parking lot
├── parking_spaces.json        # JSON file to store selected parking spaces
├── ParkingSpacePicker.py      # Script to select parking spaces
├── main.py                    # Main script to monitor and display parking occupancy
├── requirements.txt           # List of required Python libraries
└── README.md                  # This README file
```

### Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

Feel free to modify any sections as per your requirements!
