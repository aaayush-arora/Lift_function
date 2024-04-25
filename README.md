1.⁠ ⁠Lift Class Definition
   - Defines the Lift class with private member variables (⁠ currentFloor ⁠, ⁠ direction ⁠, ⁠ doorOpen ⁠, ⁠ emergencyStop ⁠, ⁠ overloaded ⁠).
   - Initializes these variables in the constructor (⁠ Lift() ⁠).

2.⁠ ⁠goToFloor Method
   - Handles the functionality of moving the lift to a specified floor.
   - Checks for emergency stop or overload conditions before proceeding.
   - Determines the direction of movement and updates the current floor until reaching the target floor.
   - Notifies floor arrival and opens/closes the door accordingly.


5. ReportOverload and removeOverload Methods
   - Manages the detection and removal of overload conditions.
   - Updates the overloaded variable to halt or resume lift operations.

4. Activate EmergencyStop and deactivateEmergencyStop Methods
   - Controls the activation and deactivation of the emergency stop feature.
   - Updates the emergencyStop variable accordingly.
   
6. Communicate With Emergency Services Method
   - Simulates communication with emergency services when required.
