# 🌟 **Naming Conventions**

## 1. 🖋️ **CamelCase** for Components or Screens

### 1.1. **Description**
- Use **PascalCase** (capitalize the first letter of each word) for component or screen files.

### 1.2. **Examples:**
  - `LoginScreen.js`
  - `UserProfileCard.js`

## 2. 🛠️ **Kebab-case** for Utility Files

### 2.1. **Description**
- Use **kebab-case** (lowercase words separated by hyphens) for utility or module files.

### 2.2. **Examples:**
  - `date-utils.js`
  - `api-client.js`

---

# 🗂️ **Expo File-based Routing**

## 3.1. **Overview**
Expo uses **file-based routing**, where the file structure determines the URL routing of the app. This simplifies navigation by automatically generating routes based on your file hierarchy.

### 3.2. **Further Reading:**
For more details, check out the [📖 official Expo documentation on file-based routing](https://docs.expo.dev/develop/file-based-routing/).

---

# 🚀 **Git Workflow Guidelines**

## 4. **Branch Naming Convention**

### 4.1. **Format**
- Use a prefix to indicate the type of work, followed by a brief, descriptive name.
- **Format:** `{type}/{description}`
  - `{type}`: Nature of the branch (e.g., feature, bug, hotfix, etc.).
  - `{description}`: A concise description of the task or issue.

### 4.2. **Examples:**

```bash
📂 git checkout -b feature/add-login-button
🐛 git checkout -b bug/fix-header-overlap
⚡ git checkout -b hotfix/critical-issue-123
```

---

## 5. 📝 **Commit Message Convention**

### 5.1. **Format:**

```bash
{type}: {subject}
```

- **`type`**: Purpose of the commit (see the table below for types).
- **`subject`**: A brief, imperative description of what the commit does.

### 5.2. **Pre-commit Workflow:**

1. ✅ Ensure linting and formatting checks pass (set up pre-commit hooks for automatic validation).
2. 🖊️ Write clear, meaningful commit messages.

### 5.3. **Examples:**

```bash
✨ git commit -m "feat: add login button"
🐛 git commit -m "fix: resolve header overlap issue"
📚 git commit -m "docs: update README with contributing guidelines"
```

### 5.4. **Commit Types:**

| **Type**     | **Description**                                                                     |
| ------------ | ----------------------------------------------------------------------------------- |
| **feat** ✨    | Introduces a new feature or functionality.                                          |
| **fix** 🐛     | Fixes a bug in the application.                                                     |
| **docs** 📚   | Documentation updates or improvements (e.g., README, comments, etc.).               |
| **style** 🎨  | Code changes that do not affect functionality (e.g., formatting, lint fixes).       |
| **refactor** 🔄| Code changes that neither add functionality nor fix bugs.                           |
| **perf** ⚡    | Improves performance without changing functionality.                                |
| **test** 🧪   | Adds new tests or fixes existing ones.                                              |
| **build** 🏗️  | Changes to the build process or dependencies (e.g., npm, Webpack).                  |
| **ci** 🔧     | Changes to CI/CD configurations and scripts.                                        |
| **chore** 🧹  | Routine tasks or updates that don't affect the codebase (e.g., dependency updates). |
| **revert** ⏪  | Reverts a previous commit.                                                          |
| **hotfix** 🚑 | Critical fixes that need to be deployed immediately.                                |

---

## 6. 🌿 **Branch Management**

### 6.1. **Workflow:**

1. Always work on a new branch based on the task or feature.
2. Regularly pull updates from the main branch to avoid merge conflicts.
3. Use pull requests (PRs) for code reviews before merging.

---

## 7. 📤 **Push Workflow**

### 7.1. **Steps:**

1. Create a branch based on the feature or issue you're working on:
   ```bash
   🌱 git checkout -b {type}/{description}
   ```
2. Make and stage your changes:
   ```bash
   ➕ git add .
   ```
3. Commit your changes with a meaningful message:
   ```bash
   🖋️ git commit -m "{type}: {subject}"
   ```
4. Push your branch to the remote repository:
   ```bash
   🚀 git push origin {type}/{description}
   ```

### 7.2. **Example:**

```bash
🌱 git checkout -b feature/user-authentication
➕ git add .
🖋️ git commit -m "feat: implement user authentication flow"
🚀 git push origin feature/user-authentication
```

---

## 8. 📌 **Branch Type Reference**

| **Branch Type** | **Purpose**                                                 |
| --------------- | ----------------------------------------------------------- |
| **feature** ✨   | For adding new features or functionality.                   |
| **bug** 🐛       | For fixing bugs or issues.                                  |
| **hotfix** 🚑    | For critical fixes that must be resolved immediately.       |
| **release** 🚀   | For preparing a release with tested and finalized features. |
| **chore** 🧹     | For maintenance tasks such as dependency updates.           |

---


