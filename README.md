# Fantasy Football AI

A Python-based project designed to help optimize fantasy football drafting and weekly lineup decisions using machine learning and data from the **Sleeper API**.

## 🚀 Project Plan

This project aims to create an intelligent system that assists in fantasy football by:
1. **Draft Optimization** - Developing an algorithm to suggest the best players during the draft.
2. **Weekly Lineup Optimization** - Analyzing your current roster and suggesting the optimal lineup based on available players and matchups.
3. **Machine Learning** - Using statistical modeling and machine learning to improve player predictions and optimize strategies.

## 📊 Current Stage

### 1. **Data Collection** (In Progress)
We are currently in the **data collection phase**, where we are:
- Connecting to the **Sleeper API** to retrieve player data, league settings, and other relevant information.
- Building the **data-fetching module** (`data_fetcher.py`) to regularly pull data from the API and save it for processing.

### 2. **Data Processing** (Planned)
Once we have the raw data, the next step will be to clean and format it into usable datasets. This step will involve:
- Filtering relevant player stats.
- Handling missing or incomplete data.
- Organizing the data into structures that will be used in the draft and lineup algorithms.

### 3. **Drafting Algorithm** (Planned)
After data processing, we will focus on building the algorithm that can:
- Suggest the best possible picks during a draft, based on player stats, position, and historical performance.

### 4. **Lineup Optimization** (Planned)
Lastly, we will implement an **optimization algorithm** that analyzes your current roster and suggests the best lineup for each week, based on matchups, player form, and other factors.

## 🛠️ Technologies

- **Python** (for all development)
- **Pandas** (data manipulation and analysis)
- **Requests** (to interact with the Sleeper API)
- **Scikit-learn** (for machine learning algorithms, when we move to predictive modeling)
- **Jupyter Notebooks** (for initial data analysis and experimentation)

## 📂 Project Structure

- `src/` - Contains all the Python code for fetching, processing, and analyzing data, as well as the algorithms for draft and lineup optimization.
- `data/` - Stores raw and processed data pulled from the Sleeper API.
- `models/` - Saved models after training for optimization purposes.
- `notebooks/` - Jupyter notebooks for experimentation and data exploration.
- `tests/` - Unit tests to verify that all the functions and algorithms work correctly.

## 🚧 What’s Next?

- Completing the **data fetching and processing** modules.
- Implementing the **draft optimization algorithm** to make intelligent draft picks.
- Building the **lineup optimization system** to automatically suggest the best weekly lineup.

## 📝 How to Contribute

Feel free to fork this project and submit issues or pull requests. Whether you want to help with coding, testing, or improving the documentation, your contributions are welcome!

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

For any questions or suggestions, feel free to open an issue or reach out!
