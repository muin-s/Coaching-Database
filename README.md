## Prerequisites
Ensure you have the following installed:
- MySQL Server
- Python 3.x
- Required Python packages (see installation steps below)

## Installation & Setup

**Step 1: Initialize the Database**
```bash
mysql -u [your_username] -p < COACHING.sql
```

**Step 2: Launch the Application**
```bash
python3 coaching.py
```

**Important:** If you encounter a missing dependency error for `tabulate`, install it using:
```bash
pip3 install tabulate
```
