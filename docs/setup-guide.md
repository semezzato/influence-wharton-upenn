# Installation Guide

## Prerequisites
- Python 3.10 or higher
- pip (Python package manager)
- Git

## Quick Start

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo.git
cd your-repo

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Verifying Installation

Run the test suite to make sure everything is working:

```bash
python -m pytest tests/
```

If all tests pass, you are ready to go!
