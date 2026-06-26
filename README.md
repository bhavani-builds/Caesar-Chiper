# 🔐 Caesar Cipher - Python

A simple Python implementation of the **Caesar Cipher**, one of the oldest and most well-known encryption techniques. This program allows users to **encrypt** and **decrypt** messages by shifting letters in the alphabet.

## 📌 Features

* Encrypt text using a custom shift value.
* Decrypt encrypted text.
* Supports uppercase and lowercase input (converted to lowercase).
* Preserves spaces, numbers, and special characters.
* Allows multiple encrypt/decrypt operations without restarting the program.
* Uses modulo (`%`) to correctly wrap around the alphabet.

## 🛠️ Technologies Used

* Python 3
* Functions
* Loops
* Conditional Statements
* Lists
* String Manipulation

## 📂 Project Structure

```
Caesar-Cipher/
│── main.py
│── art.py
│── README.md
```

* **main.py** – Contains the Caesar Cipher program.
* **art.py** – Contains the ASCII logo displayed when the program starts.
* **README.md** – Project documentation.

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/Caesar-Cipher.git
```

2. Navigate to the project folder.

```bash
cd Caesar-Cipher
```

3. Run the program.

```bash
python main.py
```

## 💻 Example

```
Type 'encode' to encrypt, type 'decode' to decrypt:
encode

Type your message:
hello world

Type the shift number:
5

Here is the encoded result: mjqqt btwqi
```

### Decryption Example

```
Type 'encode' to encrypt, type 'decode' to decrypt:
decode

Type your message:
mjqqt btwqi

Type the shift number:
5

Here is the decoded result: hello world
```

## 🧠 How It Works

1. The user chooses **encode** or **decode**.
2. The user enters a message and a shift number.
3. Each letter is shifted by the specified amount.
4. The modulo operator (`%`) ensures letters wrap around from **z** back to **a**.
5. The encrypted or decrypted message is displayed.

## 📚 Concepts Practiced

* Python Functions
* While Loops
* For Loops
* Lists
* String Handling
* Modulo Operator
* User Input
* Conditional Logic

## 🚀 Future Improvements

* Support uppercase letters without converting them.
* Add file encryption and decryption.
* Create a graphical user interface (GUI).
* Allow users to save encrypted messages to a file.

## 👨‍💻 Author

**Govind Devaraj**

If you found this project helpful, consider giving it a ⭐ on GitHub!
