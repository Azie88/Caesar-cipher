# Caesar Cipher 🔐

A beginner-friendly Python project that lets you hide and reveal messages using a classic encryption technique, with a modern keyword-based twist.

---

## 🧐 What is a Caesar Cipher?

The Caesar Cipher is one of the oldest and simplest forms of encryption. Traditionally, it works by shifting each letter in the alphabet by a fixed number of positions.

**Example (Shift = 3):**
- `A` → `D`
- `B` → `E`
- `C` → `F`
- `Z` → `C`

So the word **HELLO** becomes **KHOOR**.

### 🛠️ How This Version Works
Instead of a simple number, this program uses a **Keyword** (e.g., `SECRET`).

1. **Input:** You enter a message and a keyword.
2. **Behind the Scenes:** The program converts the keyword into a numerical shift value.
3. **Consistency:** The same keyword always produces the same shift, making it easier to remember than a random number.
4. **Security:** While still a "learning" cipher, the keyword adds a layer of personalization.

> [!IMPORTANT]
> This project is for **educational purposes only**. Caesar ciphers are not secure for real-world sensitive data.

---

## ✨ Features

*   **🔑 Keyword-based Encryption:** No need to remember shift numbers.
*   **🧠 Smart Handling:** Preserves capitalization (`A` vs `a`) and ignores symbols/numbers (`!`, `@`, `123`).
*   **🔄 Two-way Process:** Encrypts and decrypts automatically within the notebook.
*   **🐍 Clean Code:** Written in beginner-friendly Python with clear comments.

---

## 🚀 How to Run This Project

Follow these steps to get the project running on your local machine:

### 1. Clone the Repository
```bash
git clone https://github.com/Azie88/Caesar-cipher.git
cd Caesar-cipher
```

### 2. Set Up a Virtual Environment (Recommended)
This keeps your global Python installation clean.

**Create the environment:**
```bash
python -m venv .venv
```

**Activate it:**
- **Windows (PowerShell):**
  ```powershell
  .venv\Scripts\Activate.ps1
  ```
- **Windows (CMD):**
  ```cmd
  .venv\Scripts\activate
  ```

### 3. Install Dependencies
```bash
pip install jupyter ipykernel
```

**Register the kernel:**
```bash
python -m ipykernel install --user --name=.venv --display-name "Python (.venv)"
```

### 4. Open the Notebook
You can use the classic Jupyter interface or VS Code:

- **VS Code (Recommended):**
    1. Open the project folder.
    2. Open `Cipher.ipynb`.
    3. Select the kernel **Python (.venv)** in the top-right corner.
    4. Run the cells sequentially.

- **Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

---

## 📖 Usage Example

Once the notebook is running, follow the prompts:

1. **Enter Message:** `Hello World`
2. **Enter Keyword:** `SECRET`

**Output:**
```text
Encrypted: Tqxxa Iadxp
Decrypted: Hello World
```

---

## Contributions :handshake:

Open an issue, submit a pull request or contact me for any contributions.

## Author :writing_hand:

Andrew Obando

<a href="https://www.linkedin.com/in/andrewobando/"><img align="left" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="Andrew Obando | LinkedIn"/></a>
<a href="https://medium.com/@obandoandrew8">
![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)
</a>

---

Feel free to star ⭐ this repository if you find it helpful!
