# 🛡️ Tayo Language (v1.1)

**Tayo** is a high-performance, security-focused domain-specific language (**DSL**) written in **Rust**. It is specifically designed for banking operations, secure data processing, and seamless system integration.

---

## 🌟 Key Philosophy

Tayo provides a human-readable syntax to handle sensitive operations like **OTP** generation, data encryption, and transaction limits without the complexity of general-purpose languages.

---

## 🛠️ Installation

Install Tayo directly from Crates.io:

```bash cargo install tayo Once installed, you can use the tayo command in your terminal.

📖 Language Guide & Keywords ## Variables & Math (get) Perform arithmetic operations (plus, minus, times, divide, percent) and store them in variables.

Code snippet get balance = **5000** plus **2500** get tax = balance percent 5 ## Output (view) Print strings or variable values to the console.

Code snippet view *Current Balance:* view balance ## Security & Banking otp: Generates a 6-digit secure code.

secure: Basic encryption of stored data.

limit: Checks an amount against a cap. If exceeded, the operation blocks.

log: Saves an audit trail to audit.log with a Unix timestamp.

Code snippet otp my_code limit **6000** **5000**   -- This will trigger a **SECURITY** **ALERT** log balance ## Interoperability (link & call) link: Connects and reads data from external files.

call: Executes external system commands (Python, Node.js, Shell, etc.).

Code snippet link *data.txt* call *python3 notify_user.py* ## Input & Logic (ask & check) ask: Request user input from the terminal.

check: Simple conditional branching (more / less).

Code snippet
ask username
check balance more **1000**
    view ***VIP** Account*
🖥️ Interactive Shell (**REPL**)
Simply type tayo without arguments to enter the interactive shell:

Bash $ tayo --- 🛡️ Tayo Bank OS Shell v1.1 --- tayo> get x = 10 plus 20 tayo> view x 📺 x: 30 📝 Example Script (test.tayo) Code snippet -- Tayo Banking Script Example view *Starting Secure Session...* ask user_account otp session_id get deposit = **5000** limit deposit **10000** log deposit view *Transaction Logged Successfully.* 🤝 Contributing Contributions are welcome! Since Tayo is built in Rust, ensure you have the latest stable version of Rust installed to build from source.

Bash git clone [https://github.com/yourusername/tayo](https://github.com/yourusername/tayo) cd tayo cargo build --release 📜 License Licensed under the **MIT** License. See **LICENSE** for more information.

Created with ❤️ by a Myanmar Developer.

---

### အကြံပြုချက် - 

၁။ **Repository Link:** အပေါ်ကကုဒ်ထဲက `[https://github.com/yourusername/tayo`](https://github.com/yourusername/tayo`) နေရာမှာ သင့်ရဲ့ တကယ့် GitHub link ကို အစားထိုးပေးပါ။ (မရှိသေးရင် ဒီစာကြောင်းကို ခဏဖြုတ်ထားလို့ရပါတယ်)။

၂။ **Versioning:** သင် `Cargo.toml` မှာ version ကို `1.1.0` လို့ ပေးထားရင် ဒီ `**README**` ထဲမှာလည်း version ညှိထားပေးပါ။
