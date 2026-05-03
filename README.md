🔐 Diffie-Hellman Key Exchange Simulator

A simple and interactive web-based application that demonstrates the **Diffie-Hellman Key Exchange Algorithm**, allowing two users to securely generate a shared secret over an insecure channel.

## 📌 Project Overview

This project simulates how two parties (**Alice and Bob**) can securely exchange keys without directly transmitting the secret key. It provides a visual and interactive way to understand the working of the Diffie-Hellman algorithm.

## 🎯 Objectives

* Demonstrate secure key exchange using Diffie-Hellman
* Provide an interactive UI for better understanding
* Show how both parties derive the same shared secret
* Help beginners understand cryptographic concepts easily

## 🧠 Concepts Used

* Diffie-Hellman Key Exchange
* Public and Private Keys
* Modular Exponentiation
* Discrete Logarithm Problem

## ⚙️ How It Works

1. User enters:

   * Prime number (p)
   * Generator (g)

2. Alice and Bob choose private keys:

   * Alice → a
   * Bob → b

3. Public keys are generated:

   * A = g^a mod p
   * B = g^b mod p

4. Shared secret is computed:

   * Alice: S = B^a mod p
   * Bob: S = A^b mod p

5. Both obtain the same shared secret:

   * S = g^(ab) mod p

## 💻 Tech Stack

* HTML
* CSS
* JavaScript

## 🚀 Features

* Interactive UI with modern design
* Input fields for custom values
* Random key generation
* Real-time calculation of:

  * Public keys
  * Shared secret
* Beginner-friendly visualization

## ▶️ How to Run

1. Download or clone the repository
2. Open `index.html` in any browser
3. Enter values or use random generator
4. Click **Generate Keys**

## 📸 Output

* Displays:

  * Alice’s Public Key
  * Bob’s Public Key
  * Shared Secret Key

## ⚠️ Limitations

* Vulnerable to **Man-in-the-Middle attack** (no authentication)
* Uses small numbers for demonstration purposes
* Not suitable for real-world secure communication

## 🌍 Real-World Applications

* HTTPS (TLS handshake)
* VPN connections
* Secure messaging systems

## 🔥 Future Improvements

* Add AES encryption using shared key
* Step-by-step animation of algorithm
* Real-time chat simulation
* Improved UI/UX

## 👨‍💻 Author

* Tupakula Timothi


## ⭐ Note

This project is built for **learning and demonstration purposes** to understand the fundamentals of cryptography.

---

If you want next:
👉 I can give **resume bullet points for this project (very important for placements)**
👉 Or **viva questions + answers based on this project 🔥**
