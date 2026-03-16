# Risk: Europe Solo Companion

A web-based solo automation tool for the board game **Risk: Europe**. This application manages the logic for non-player adversaries, allowing for a seamless single-player experience without the need for manual chart-flipping or complex decision trees.

## Features

* **Automated Adversary Logic:** Handles the decision-making process for the AI kings, including expansion, recruitment, and taxation.
* **Digital Map State:** Keep track of the board's current state digitally to assist with movement and combat resolution.
* **Persistent State:** (If applicable) Save and load your current game progress to resume your conquest of Europe later.
* **Streamlined Workflow:** Simplifies the administrative overhead of solo play, focusing the experience on your strategic choices.

## Getting Started

### Access the App

The easiest way to use the companion is via the live web version:
**[riskeuropesolo.pages.dev](https://riskeuropesolo.pages.dev)**

### Local Installation

If you prefer to run the application locally:

1. Clone the repository:
```bash
git clone https://github.com/doerrhb/RiskEuropeSolo.git

```


2. Navigate to the project directory:
```bash
cd RiskEuropeSolo

```


3. Open `index.html` in any modern web browser.

## How to Use

1. **Set Up the Physical Game:** Set up your *Risk: Europe* board and components as you would for a standard game, following the solo-specific rules provided in the `solo_rules` folder.
2. **Launch the Companion:** Open the app and follow the prompts to initialize the AI players.
3. **Execute AI Turns:** When it is the AI's turn, the app will generate their orders and movement logic. Update the physical board accordingly.
4. **Win the Crown:** Compete against the automated kings to claim seven Crowns and rule Europe.

## Project Structure

* `index.html`: The main entry point for the web application.
* `solo_rules/`: Contains documentation and logic summaries for the solo variants supported.
* `logo.png`: Assets for the application UI.

## Technical Details

* **Language:** HTML5 / JavaScript
* **Deployment:** Optimized for Cloudflare Pages

## Contributing

Contributions to refine the AI logic or improve the UI are welcome.

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/NewRuleSet`).
3. Commit your Changes (`git commit -m 'Add support for new solo variant'`).
4. Push to the Branch (`git push origin feature/NewRuleSet`).
5. Open a Pull Request.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgments

* **Hasbro/Avalon Hill:** For the original *Risk: Europe* board game.
* **The Solo Gaming Community:** For the inspiration and feedback on automated adversary systems.

---

*Developed by Heath Doerr
