


# 🚀 Python Hybrid API Automation Framework

This repository contains a **custom-built Hybrid API Automation Framework** designed using **Python**, following industry best practices such as modular architecture, scalability, reusability, and maintainability.
The framework is suitable for **real-world API testing**, supporting advanced validations, parallel execution, and rich reporting.

---

## 📁 Framework Architecture & Folder Structure

The framework follows a **well-organized folder structure** to clearly separate concerns such as test cases, test data, utilities, configuration, and reports.
This structure helps improve **readability, maintainability, and scalability** of the automation suite.

📸 **Reference Folder Structure**
![Framework Structure](https://github.com/user-attachments/assets/3c7d5fe5-207a-42e7-84fe-f4d53354d987)

---

## 🧰 Tech Stack & Tools Used

| Category             | Tools / Libraries                       |
| -------------------- | --------------------------------------- |
| Programming Language | **Python 3.12**                         |
| HTTP Client          | **Requests**                            |
| Test Framework       | **PyTest**                              |
| Reporting            | **Allure Reports**, **PyTest HTML**     |
| Test Data Management | **CSV**, **Excel**, **JSON**, **Faker** |
| API Validation       | **jsonschema**                          |
| Parallel Execution   | **pytest-xdist**                        |

---

## ✅ Key Features of the Framework

* 🔹 Modular & scalable **hybrid framework design**
* 🔹 Supports **CRUD API operations**
* 🔹 Advanced **response validation using JSON Schema**
* 🔹 Dynamic **test data generation using Faker**
* 🔹 Multiple test data formats (CSV, Excel, JSON)
* 🔹 Parallel execution for **faster test runs**
* 🔹 Rich and interactive **Allure Reports**
* 🔹 PyTest markers for selective execution
* 🔹 CI/CD friendly structure

---

## 📦 Package Installation

Install all required dependencies using the command below:

```bash
pip install requests pytest pytest-html faker allure-pytest jsonschema
```

---

## ⚡ Enable Parallel Execution

Install **pytest-xdist** to execute test cases in parallel:

```bash
pip install pytest-xdist
```

Example (run tests in parallel):

```bash
pytest -n auto
```

---

## 🧪 Execute Test Cases with Allure Report

Run a **basic CRUD test case** and generate Allure results:

```bash
pytest tests/tests/crud/test_create_booking.py --alluredir=allure_result -s
```

After execution, generate and open the Allure report:

```bash
allure serve allure_result
```

---

## 📊 Reporting

* **Allure Report**

  * Interactive dashboard
  * Test trends & execution history
  * Request/response logs
  * Screenshots & attachments support

* **PyTest HTML Report**

  * Lightweight and quick execution summary

---

## 🎯 Ideal Use Cases

* API automation for **enterprise-level projects**
* Regression & smoke API testing
* CI/CD pipeline execution
* Interview & portfolio demonstration
* Scalable test automation setups

---

## 🏁 Conclusion

This **Python Hybrid API Automation Framework** provides a robust foundation for building **maintainable, scalable, and efficient API automation suites**, aligning with modern testing standards and best practices.

---
