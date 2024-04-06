```markdown
# Tor Proxy Solution

This repository contains a Tor proxy solution implemented using an MVC (Model-View-Controller) architecture. It includes functionality to configure Chrome to use the Tor network as a proxy and a Streamlit dashboard for monitoring and controlling the Tor proxy setup.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/luxxluciano/pytorproxy.git
   ```

2. Navigate to the project directory:
   ```bash
   cd pytorproxy
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit dashboard:
   ```bash
   streamlit run tor_proxy_dashboard.py
   ```

## Components

- **Model (tor_proxy_model.py):** Contains the core logic and data handling for the Tor proxy setup.
- **View (tor_proxy_view.py):** Handles presentation and user interface elements.
- **Controller (tor_proxy_controller.py):** Orchestrates interactions between the model and view components.
- **Streamlit Dashboard (tor_proxy_dashboard.py):** Provides a user-friendly interface for monitoring and controlling the Tor proxy setup.

## Dependencies

- [Streamlit](https://streamlit.io/): For building the interactive dashboard.
- [pychrome](https://pypi.org/project/pychrome/): For controlling Chrome programmatically.
- [Requests](https://docs.python-requests.org/en/latest/): For making HTTP requests.
```

Make sure to replace `yourusername` in the clone command with your actual GitHub username if you plan to host this repository on GitHub. These files provide a clean and organized structure for your Tor proxy solution repository, along with instructions for setting up and running the project.


```

To run the Streamlit dashboard, execute the following command in your terminal:

```
streamlit run tor_proxy_dashboard.py
```

This will launch a local server and open the Tor Proxy Dashboard in your default web browser. You can now monitor and control the Tor proxy setup through the Streamlit interface.
