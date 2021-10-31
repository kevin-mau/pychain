# *PyChain Ledger
---
### Using Python and Steamlit we build a blockchain-based ledger system, complete with a user-friendly web interface.  This ledger allows users to conduct financial transactions and verify the integrity of the data in the ledger. 
### Within the `PyChain` Ledger, we will create a `record` data class that will consist of the transaction's three attributes: the `sender`, the `receiver`, and the `amount`.  These three attributes are stored in the `Block` data class.  We will build input areas for the three attributes to be captured and stored through the Streamlit application.  Finally, we test the `PyChain` Ledger and user interface by running the Streamlit application and test the blockchain validation process by using the `PyChain` ledger.

---
## Installation Guide

Prior to running the application, you will need to install these dependencies:

```python
  pip install pandas
  pip install streamlit
```

## Technologies:

This application utilizes python 3.7 along with the below imports:

```python
  import streamlit as st
  from dataclasses import dataclass
  from typing import Any, List
  import datetime as datetime
  import pandas as pd
  import hashlib
```
---
## Instructions:

In the terminal, navigate to the cloned repo and run the Streamlit application by using `streamlit run pychain.py`.  Then simply enter values for sender, receiver, and amount, 
and then click the Add Block button.  You can verify the block contents and hashes in the Streamlit drop-down menu and also validate the blockchain with the "Validate Chain" 
button.

---
### PyChain Ledger - Streamlit Application Demonstration:
![pychain-·-Streamlit-Google-Chrome-2021-10-30-17-54-23](https://user-images.githubusercontent.com/85687829/139569013-6d2cb0ea-4512-40ee-b325-9055eb2fdfb1.gif)

### Screenshot of "Block Difficulty" slide bar and "Block Inspector" pull-down menu:
![screen_block_inspector](https://user-images.githubusercontent.com/85687829/139568884-4f0fde42-119d-44a5-b2c0-790ddcf0dd38.png)

### Screenshot showing that "Blockchain is Valid" message upon using the "Validate Chain" button:
![blockchain_is_valid](https://user-images.githubusercontent.com/85687829/139568929-d2e61505-252c-4664-95ad-522d08f25e1b.png)

---

## Contributors

kevin-mau

---

## License

MIT
