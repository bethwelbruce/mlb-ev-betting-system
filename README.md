# mlb-ev-betting-system
An AI-driven sports betting system that predicts +EV bets for MLB games and player props.

# MLB +EV Sports Betting System

## Description

The **MLB +EV Sports Betting System** is an AI-driven solution designed to help sports bettors make informed decisions when betting on Major League Baseball (MLB) games. The system leverages historical game data, player statistics, and advanced machine learning models to predict **+EV** (positive expected value) bets for both **game outcomes** (moneyline, totals) and **player props** (e.g., home runs). It then compares the model's predictions to sportsbook odds (FanDuel and DraftKings) to identify profitable betting opportunities.

### Key Features:
- **Game Prediction Model**: Predicts the outcomes of MLB games (moneyline and totals).
- **Player Prop Prediction Model**: Predicts the probability of players hitting home runs.
- **+EV Calculation**: Detects positive expected value betting opportunities.
- **Automated Daily Updates**: The system fetches new data and predictions daily.
- **Front-End Viewer**: A user-friendly interface to view predictions and betting recommendations.

## Technologies Used:
- **Backend**: Python (with libraries such as pandas, scikit-learn, xgboost)
- **APIs**: FanDuel, DraftKings (for odds data)
- **Frontend**: Streamlit, Flask, or HTML (simple viewer)
- **Other Tools**: GitHub Actions (for automation), CSV/JSON for data output

## How to Use:
### Setup Instructions:
1. Clone the repository:
    ```bash
    git clone https://github.com/bethwelbruce/mlb-ev-betting-system.git
    ```
2. Navigate to the project folder:
    ```bash
    cd mlb-ev-betting-system
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Model:
1. Fetch new data, run predictions, and calculate +EV bets by executing the script:
    ```bash
    python run_betting_model.py
    ```
2. The results will be saved as a **CSV** or **JSON** file in the project directory. You can also view the results through the **Streamlit** or **Flask** frontend.

### Front-End Viewer:
1. To launch the front-end viewer (if you're using Streamlit):
    ```bash
    streamlit run betting_dashboard.py
    ```
   The front-end will display game predictions, player prop predictions, and +EV bets in an easy-to-use interface.

## Contributing:
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Contributions are always welcome!

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact:
For any questions or support, feel free to reach out to https://github.com/bethwelbruce).

