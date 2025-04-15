# Brevity Engineering Method Repository

This repository contains engineering calculation methods developed by Brevity Ltd for structural and building physics analysis. These methods are implemented as Jupyter notebooks that can be run in Google Colab or locally.

## Purpose

The engineering methods in this repository:

1. Implement structural and building physics calculations according to relevant standards
2. Provide transparent, reviewable calculation methods for engineering design
3. Support Brevity's engineering design processes with standardised calculation approaches

## Getting Started

### For Non-GitHub Users

If you're not familiar with GitHub but need to review or run these notebooks:

1. **View notebooks online**: You can view any notebook by clicking on its filename in the repository
2. **Run in Google Colab**: 
   - Click on the notebook you want to run
   - Click the "Open in Colab" button at the top of the file (if available)
   - Alternatively, go to [Google Colab](https://colab.research.google.com/), select "GitHub" in the open dialog, and paste the URL of this repository

### For GitHub Users

1. **Clone the repository**:
   ```
   git clone https://github.com/Team-Brevity/engineering-methods.git
   ```

2. **Fork the repository**:
   - Click the "Fork" button at the top right of this page
   - This creates your own copy of the repository that you can modify

## Running Notebooks Locally

To run these notebooks on your local machine:

1. Install Python 3.8 or higher
2. Install Jupyter:
   ```
   pip install jupyter
   ```
3. Install required dependencies:
   ```
   pip install numpy pandas matplotlib
   ```
4. Install the Brevity standards package:
   ```
   pip install git+https://github.com/Team-Brevity/standards.git
   ```
5. Launch Jupyter:
   ```
   jupyter notebook
   ```

## Repository Structure

- `/`: Root directory containing engineering method notebooks
- Each notebook is a self-contained calculation method for a specific engineering problem

## Standards and Dependencies

These notebooks rely on the Brevity standards repository, which contains implementations of engineering standards and common calculation methods. The standards repository is available at [Team-Brevity/standards](https://github.com/Team-Brevity/standards).

## Peer Review Process

For engineers reviewing these notebooks:

1. Review the calculation methodology against relevant standards
2. Execute the notebook to verify calculations
3. Check input assumptions and output interpretations
4. Provide feedback via GitHub issues or pull requests

### How to Raise Issues During Peer Review

When you identify concerns or have suggestions during your review:

1. **Navigate to the Issues tab**: Click on the "Issues" tab at the top of the repository page
2. **Create a new issue**: Click the green "New issue" button
3. **Use a descriptive title**: Clearly state the nature of the issue (e.g., "Incorrect formula in seismic load calculation")
4. **Provide detailed information**:
   - Specify which notebook and section contains the issue
   - Explain what the problem is and why it's a concern
   - Include references to relevant standards or literature
   - Add screenshots if helpful
   - Suggest a solution if possible
5. **Add labels**: Use appropriate labels such as "bug", "enhancement", or "question"
6. **Link to specific code**: You can reference specific lines of code by:
   - Opening the notebook file in GitHub
   - Clicking on the line number to highlight it
   - Clicking the "..." menu and selecting "Copy permalink"
   - Pasting this link in your issue

### Reviewing Pull Requests

If you're reviewing someone else's changes:

1. Go to the "Pull requests" tab
2. Select the pull request to review
3. Click on "Files changed" to see the modifications
4. Add comments by hovering over specific lines and clicking the "+" icon
5. When finished, click "Review changes" to approve, request changes, or comment

## License

See the [LICENSE](LICENSE) file for details.

## Contact

For questions or support, contact info@teambrevity.com. 