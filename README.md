# Stock-Price-Prediction-Using-Genetic Programming (GP)

## Overview
This project is a Java-based implementation of **Stock Price Prediction** using **Genetic Programming (GP)**. It leverages the ECJ library for evolutionary computation to analyze stock market trends and predict future prices.

## Features
- Implements **Genetic Programming (GP)** for financial forecasting.
- Uses **historical stock data** for training and evaluation.
- Includes multiple indicators such as **Moving Averages, Highs, Lows, and Adjusted Close Prices**.
- Built with **Java** and managed using **Maven**.

## Project Structure
```
Stock-Price-Prediction-Using-GP/
├── pom.xml  # Maven configuration
├── ecj.23.jar  # ECJ evolutionary computation library
├── .gitignore  # Git ignore rules
├── src/
│   ├── main/java/StockPredictor/
│   │   ├── Main.java  # Main execution file
│   │   ├── Stock.java  # Stock data structure
│   ├── main/java/terminal/
│   │   ├── Low.java, High.java, AdjustedClose.java  # Terminal nodes
│   ├── main/resources/
│   │   ├── simple.params, ec.params, stock.params  # Parameter files
```

## Installation & Setup
### **Prerequisites**
- Java **8+** installed
- Maven installed (`brew install maven` on Mac)

### **Steps to Run the Project**
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/Stock-Price-Prediction-Using-GP.git
   cd Stock-Price-Prediction-Using-GP
   ```
2. Compile and run using Maven:
   ```sh
   mvn clean install
   mvn exec:java -Dexec.mainClass="StockPredictor.Main"
   ```

## Usage
- Modify `stock.params` to change the dataset and prediction settings.
- Customize GP parameters in `ec.params`.

## Contributing
Contributions are welcome! Feel free to open **issues** or **pull requests**.

## License
This project is licensed under the **MIT License**.

## Acknowledgments

The ECJ library for genetic programming and evolutionary computation.

Open-source contributors for improvements and enhancements.



