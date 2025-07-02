### **Standard Commit Message Format:**

```
<type>: <short summary>

```

### **Common Commit Types (Prefixes):**

| Type       | Description                                                   |
| ---------- | ------------------------------------------------------------- |
| `feat`     | A new feature                                                 |
| `fix`      | A bug fix                                                     |
| `docs`     | Documentation only changes                                    |
| `style`    | Code style changes (formatting, missing semi-colons, etc)     |
| `refactor` | Code change that neither fixes a bug nor adds a feature       |
| `perf`     | A code change that improves performance                       |
| `test`     | Adding or updating tests                                      |
| `build`    | Changes that affect the build system or external dependencies |
| `ci`       | Changes to CI configuration files and scripts                 |
| `chore`    | Miscellaneous changes that don’t modify src or test files     |
| `revert`   | Reverts a previous commit                                     |

---

### ✍️ **Examples:**

1. `feat: add social login with Google`
2. `fix: handle null wallet address in transaction`
3. `docs: update installation guide for Windows`
4. `style: reformat file to match ESLint rules`
5. `refactor: extract mediaService from controller`
6. `perf: optimize token swap algorithm for speed`
7. `test: add unit tests for transfer module`
8. `chore: bump web3.js from 1.7.1 to 1.8.0`
9. `revert: feat: add phantom wallet support`

---

### 🧠 **Commit Body (Optional):**

Use when:

* Explaining **why** the change was made
* Describing **breaking changes**
* Referencing issues/tickets (e.g. `Closes #42`)

**Example:**

```
fix(token): correct token balance formatting

The frontend was receiving raw values instead of formatted decimals,
which caused display issues for users.

Closes #123
```

---

### 🛠️ Good Practice:

* Keep the summary line under **50 characters**
* Use body if change is **non-trivial**
* Group commits logically (e.g., don’t mix fix + feature in same commit)
