# Types of Testing

Software testing can be broadly categorized into two major types: **Functional Testing** and **Non-Functional Testing**.

These testing types help ensure that an application not only works according to business requirements but also meets expectations related to performance, security, usability, reliability, and compatibility.

---

## 1. Functional Testing

**Functional Testing** verifies whether the application behaves according to the defined business and functional requirements.

It is performed using functional specifications provided by the client, business requirements, use cases, or design specifications prepared by the development and design teams.

### Includes:

* **Unit Testing**
  Verifies individual components or units of the application in isolation.

* **Integration Testing**
  Verifies whether different modules or components work correctly when integrated.

* **Smoke Testing**
  Performs a preliminary check to confirm that the build is stable enough for further testing.

* **Regression Testing**
  Ensures that existing functionality continues to work after changes, enhancements, or bug fixes.

* **Sanity Testing**
  Performs focused testing to verify that specific changes or fixes are working as expected.

* **User Acceptance Testing (UAT)**
  Validates whether the application meets business requirements and is acceptable to the end users or client.

* **System Testing**
  Tests the complete and integrated application as a whole against its specified requirements.

* **Black Box Testing**
  Tests application functionality without considering the internal code or implementation details.

* **White Box Testing**
  Tests the internal structure, logic, code paths, and implementation of the application.

---

## 2. Non-Functional Testing

**Non-Functional Testing** evaluates how well an application performs rather than what the application does.

It focuses on quality attributes and verifies whether the application meets requirements related to performance, security, usability, reliability, compatibility, and other non-functional expectations.

### Includes:

* **Performance Testing**
  Evaluates the application's responsiveness, speed, stability, and resource utilization under expected conditions.

* **Load Testing**
  Determines how the application performs under expected user or system load.

* **Stress Testing**
  Evaluates application behavior beyond normal operating limits to identify its breaking point and recovery capabilities.

* **Security Testing**
  Identifies vulnerabilities and verifies that the application protects data, users, and system resources.

* **Usability Testing**
  Evaluates how easy, intuitive, and user-friendly the application is for its intended users.

* **Compatibility Testing**
  Verifies that the application works correctly across different browsers, operating systems, devices, screen sizes, and environments.

* **Reliability Testing**
  Evaluates whether the application can consistently perform its intended functions over a specified period without failure.

---

## Functional vs. Non-Functional Testing

| Functional Testing                                | Non-Functional Testing                                  |
| ------------------------------------------------- | ------------------------------------------------------- |
| Verifies what the system does                     | Verifies how well the system performs                   |
| Focuses on business and functional requirements   | Focuses on quality attributes                           |
| Validates features and functionality              | Validates performance, security, usability, etc.        |
| Example: Login should work with valid credentials | Example: Login should respond within an acceptable time |
| Includes functional behavior validation           | Includes performance and quality validation             |

---

> **In simple terms:**
> **Functional Testing asks:** *"Does the application do what it is supposed to do?"*
> **Non-Functional Testing asks:** *"How well does the application do it?"*
