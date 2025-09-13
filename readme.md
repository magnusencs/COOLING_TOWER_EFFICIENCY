A simple **Kivy-based GUI application** to calculate the cooling tower efficiency.  

## Features
- Input three parameters:
  - Inlet water temperature (°C)  
  - Outlet water temperature (°C)  
  - Wet bulb temperature (°C)  
- Calculate efficiency using the formula:  

  \[
  \text{Efficiency} = \frac{T_{in} - T_{out}}{T_{in} - T_{wb}} \times 100
  \]

- Displays the result in percentage.  
- Warns if the calculated efficiency is unrealistic (greater than 100% or less than 0%).  
- Handles invalid inputs gracefully.  

## Notes
- Built with [Kivy](https://kivy.org/) (Python GUI framework).  
- Designed for quick demonstration and learning purposes.  
- The code only provides the **basic UI and calculation logic** — styling and advanced error handling can be added if needed.  
